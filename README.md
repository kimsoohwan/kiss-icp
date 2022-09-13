# KISS-ICP: In Defense of Point-to-Point ICP – Simple, Accurate, and Robust Registration If Done in the Right Way

## Abstract
Robust and accurate pose estimation of a robotic platform, so-called sensor-based odometry, is an essential part of many robotic applications. While many sensor odometry systems made progress by adding more complexity to the ego-motion estimation process, we move in the opposite direction. By removing a majority of parts and focusing on the core elements, we obtain a surprisingly effective system that is simple to realize and can operate under various environmental conditions using different LiDAR sensors. Our odometry estimation approach relies on point-to-point ICP combined with adaptive thresholding for correspondence matching, a robust kernel, a simple but widely applicable motion compensation approach, and a specific point cloud subsampling. This yields a system with only a few hyperparameters that do not even have to be tuned to a specific LiDAR sensor in most cases. Our system using the same hyperparameters performs on par with state-of-the-art methods under various operating conditions using different platforms: automotive platforms, UAV-based
operation, vehicles like segways, or handheld LiDARs. We do not require integrating IMU information and solely rely on 3D point cloud data obtained from a wide range of 3D LiDAR sensors, thus, enabling a broad spectrum of different applications and operating conditions. Our open-source system
operates at sensor frame rate in all presented datasets and is designed for real-world scenarios.

## Open-source Release: 01.10.2022
 
https://user-images.githubusercontent.com/38326482/189950820-030fd9e4-406b-4d14-8171-43b134344223.mp4

