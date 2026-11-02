# TokyoFlowAI

Spatio-temporal people flow forecasting and visualization for Tokyo using large-scale mobility data from WorldMove.

## Overview

TokyoFlowAI is a research and portfolio project focused on analyzing and forecasting urban human mobility in Tokyo.

The project explores how large-scale mobility trajectories can be transformed into spatio-temporal representations and used to predict future people-flow patterns.

The project is related to research on:

- Cyber-Physical Systems (CPS)
- Big Data Computing
- Urban Mobility
- Spatio-Temporal Forecasting
- Machine Learning
- Geospatial Visualization

## Project Goals

1. Process large-scale Tokyo mobility trajectory data.
2. Visualize people-flow patterns across Tokyo.
3. Convert mobility trajectories into spatial-temporal grid data.
4. Predict future people density and movement.
5. Compare multiple forecasting approaches.
6. Build an interactive visualization dashboard.

## Planned Pipeline

WorldMove Mobility Data

→ Data Cleaning

→ Spatial / Temporal Aggregation

→ People-Flow Visualization

→ Forecasting Models

→ Model Evaluation

→ Interactive Tokyo Mobility Dashboard

## Dataset

This project uses the WorldMove mobility dataset.

Raw dataset files are not stored in this repository due to their size.

Dataset:
WorldMove — Global Synthetic Human Mobility Dataset

## Current Status

### Phase 1 — Data Exploration

- [x] Project repository setup
- [ ] Download WorldMove dataset
- [ ] Extract Tokyo data
- [ ] Inspect trajectory structure
- [ ] Analyze dataset statistics
- [ ] Create first Tokyo mobility visualization

### Phase 2 — Data Processing

- [ ] Define Tokyo spatial grid
- [ ] Aggregate trajectories by time and location
- [ ] Generate forecasting dataset

### Phase 3 — Forecasting

- [ ] Persistence baseline
- [ ] Machine learning baseline
- [ ] LSTM / GRU
- [ ] Spatio-temporal model
- [ ] UrbanGPT experiment

### Phase 4 — Visualization

- [ ] Interactive Tokyo map
- [ ] People-density heatmap
- [ ] Actual vs predicted flow
- [ ] Time animation

## Technologies

- Python
- Pandas / NumPy
- GeoPandas
- PyTorch
- Scikit-learn
- Folium / Plotly
- FastAPI
- Gradio

## Research Direction

The main research question is:

> Can large-scale mobility trajectories be used to forecast short-term urban people flow in Tokyo?

The project also investigates the application of big-data computing and machine learning to urban Cyber-Physical Systems.