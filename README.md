# Depth-Based Elevator Dispatch System

## Overview
This project implements a depth-only, privacy-preserving elevator demand estimation system
using LiDAR-style depth data. Instead of counting people or tracking movement, the system
computes waiting-area density to optimize elevator dispatch and positioning.

## Key Ideas
- Depth sensing instead of cameras or IR beams
- Density-based demand estimation
- Waiting-zone filtering to avoid loitering noise
- Time-adaptive behavior for peak periods
- Multi-lift positioning for faster response

## System Pipeline
Depth Sensor → Zone Filter → Density Score → Time Adaptation → Lift Dispatch

## Features
- Works with stationary people
- Low data rate (no images)
- Scales to multi-floor buildings
- Suitable for embedded deployment

## Status
Prototype implemented using simulated depth data.
