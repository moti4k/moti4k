# Satellite-derived bathymetry

**Research and applied ML · Depth-map prediction**

I developed a system to estimate water depth from satellite imagery. The project began with a client task and continued as independent research, with development grant support at the Vybirai forum in 2024.

## Model and training

- A U-Net predicting depth at each pixel, with **Swin Transformer and residual blocks** in the downsampling path and bottleneck.
- Multiscale supervision on downsampled depth maps at intermediate decoder levels, weighted by distance from the final output.
- Loss normalisation using per-loss exponential moving averages.
- Bottom-type-conditioned normalisation: an auxiliary bottom-type model informed grouping for mean/variance estimation.

## Evaluation

The held-out evaluation included entire water bodies and separate areas. At inference, normalisation statistics could be recalculated using imagery and predicted bottom types, without ground-truth depths. This is a test-time adaptation step and should be considered when comparing results with a fixed-statistics model.

## Related public material

- [Early 3D lake visualisation assets](https://github.com/moti4k/bathymetry_creation) — USDZ outputs, not the training implementation.
- [Satellite image segmentation](https://github.com/moti4k/segmentation-TPSH) — a separate public PyTorch project with U-Net notebooks and a Flask interface.

The training data and full bathymetry implementation remain private; the public repositories provide related implementation examples and visualisation assets.

[Back to profile](../README.md)
