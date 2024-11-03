# Data Directory

This directory stores all data used by the TradingRobotPlug project, organized by type and processing stage. The `data` directory is essential for ensuring a clean, efficient data workflow.

## Structure
- `raw/`: Contains raw, unprocessed data directly from data sources.
- `processed/`: Stores cleaned, transformed data ready for model training and analysis.
- `data_fetchers/`: Includes scripts and tools to retrieve data from external sources.

## Guidelines
1. Avoid modifying files in the `raw` directory; make all transformations in code and save to `processed`.
2. Use consistent naming conventions to make it easy to locate specific datasets.