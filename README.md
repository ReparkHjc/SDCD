# SDCD: A Synthetic Digital City Dataset for Robustness and Generalisation of Depth Estimation Models

## Overview
SDCD, as a monocular depth driving dataset, is collected under 6 different weather driving conditions, and 6 common adverse perturbations caused by the data transmission. It provides a total of 930K high-resolution RGB images and corresponding perfect observed depth maps. The technical validation results shows that depth estimation models which are trained on SDCD provide a clearer, smoother, and more precise long-range depth estimation compared to those trained on one of the best-known driving datasets KITTI. [Youtube Video link](https://www.youtube.com/watch?v=hO2XO5Py_1A) 
## Key Features
- **Large-Scale, High-Resolution**: SDCD contains 920K high-resolution (1080*720) RGB images and corresponding dense depth maps with a total of 427.5 kilometers of vehicle driving mileage
- **Multiple adverse driving conditions**: SDCD provides adequate data collected under 6 different weather driving conditions and 6 common perturbations from the data transmission. It covers common adverse conditions in the real world to investigate the robustness of the depth estimation models
- **The immense potential of synthetic datasets**: The validation results indicate that depth estimation models trained on the SDCD (Synthetic Driving Dataset) exhibit superior performance, with clearer, smoother, and more precise depth estimation in long-range compared to those trained on the KITTI (Real-world Driving Dataset), it also showcases the immense potential of synthetic datasets and the vision algorithms trained on them, particularly in autonomous driving

## Dataset Description

The dataset is organized as follows:

- **RGB images**: High-resolution RGB images collected under different adverse driving conditions.
- **Depth maps**: Long range (540m) and dense depth maps.

## Data Collection

The SDCD was collected over various driving conditions and driving scenarios including urban and highway. Data was collected during different times of day and varying weather conditions to ensure a diverse set of examples.

## Use Cases

The SDCD is intended for:

- Developing and testing depth estimation algorithms.
- Investigating for robustness and generalisation of depth estimation models.
- Proving the immense potential of synthetic datasets and the vision algorithms trained on them.

## Download

You can download the dataset from our [official website](https://www.scidb.cn/en/detail?dataSetId=822a5a9cb0454658911eb625e0c9f213). Please refer to our usage terms and licensing information before using the dataset.
