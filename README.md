# Lidar Obstacle Detection Project

This project revolves around the implementation of a Lidar obstacle detection system. The primary focus is to detect obstacles in a 3D space using lidar sensor data. Below is an overview of the project structure, setup, and functionalities based on the provided information.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Installation](#installation)
3. [Dependencies](#dependencies)
4. [Build and Compile](#build-and-compile)
5. [Implementation Details](#implementation-details)
   - [Bounding Box](#bounding-box)
   - [Point Cloud Filtering](#point-cloud-filtering)
   - [Segmentation and Clustering](#segmentation-and-clustering)
6. [Code Efficiency](#code-efficiency)
7. [Project Rubric Points](#project-rubric-points)
8. [Conclusion](#conclusion)

## Project Overview

This project aims to create a lidar-based obstacle detection system. It includes functionalities such as point cloud filtering, segmentation, clustering, and bounding box generation to identify and highlight obstacles in the 3D space.

## Installation

To get started with this project, you need to clone this repository and ensure that all dependencies are installed.

```bash
git clone https://github.com/KatoStevenMubiru/Lidar-Object-Detection
```

## Dependencies

- PCL (Point Cloud Library)
- Eigen
- CMake
- Make

Ensure that you have installed the above dependencies to compile and run the project successfully.

## Build and Compile

Once all dependencies are installed, navigate to the project directory and run the following commands:

```bash
mkdir build
cd build
cmake ..
make
```

These commands will generate the required makefiles and binaries to run the project.

## Implementation Details

### Bounding Box

The bounding box functionality is crucial for identifying and highlighting obstacles in the 3D space. Each detected object should be enclosed within a bounding box.

### Point Cloud Filtering

This project includes a point cloud filtering implementation. This is essential for removing noise and irrelevant points from the lidar data, ensuring that only relevant obstacle information is processed.

### Segmentation and Clustering

The project implements segmentation and clustering algorithms. The segmentation is used to separate the point cloud data into different objects or regions, while the clustering helps group these points into identifiable obstacles.

## Code Efficiency

The project aims to maintain a balance between code readability, stability, and efficiency. Unnecessary calculations, complex data structures, and redundant control flow checks are avoided to ensure efficient execution.

## Project Rubric Points

The project aligns with the provided rubric points as follows:

### Compiling and Testing

- The project code must compile without errors using cmake and make.

### Obstacle Detection

- Bounding boxes appropriately enclose detected objects.
- Objects are consistently detected across frames.
- Segmentation and clustering are implemented and utilized for obstacle detection.

### Code Efficiency

- The code avoids unnecessary calculations, overly complex data structures, and redundant control flow checks.

## Conclusion

This Lidar Obstacle Detection project is a comprehensive implementation of obstacle detection in 3D space using lidar sensor data. By following the installation guide and ensuring all dependencies are properly installed, you should be able to compile, run, and explore the functionalities of this obstacle detection system. Enjoy detecting obstacles in your 3D space!