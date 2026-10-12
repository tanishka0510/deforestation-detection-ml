# Deforestation Detection from Satellite Images

A machine learning project for mapping forest cover and detecting
potential forest loss using Sentinel-2 satellite imagery.

## Planned workflow

1. Collect Sentinel-2 imagery and Dynamic World labels.
2. Preprocess imagery and create image tiles.
3. Establish an NDVI baseline.
4. Train a U-Net segmentation model.
5. Evaluate on geographically held-out areas.
6. Compare forest masks across dates.
7. Visualize potential forest loss on an interactive map.

## Tech stack

- Python
- Google Earth Engine
- NumPy and Rasterio
- PyTorch and segmentation-models-pytorch
- Folium

## Evaluation

IoU and F1 will be reported for the forest class, alongside the
NDVI baseline and the limitations of the dataset.

## Project status

Initial project structure created. Data collection, training,
evaluation and mapping are pending.
