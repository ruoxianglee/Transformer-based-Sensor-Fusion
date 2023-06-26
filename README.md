# Transformer-based-Sensor-Fusion

| - |      Type                                  |
|---------|--------------------------------------------|
|     1.1   | Two-stage                                  |
| 1.2      | Single-stage                               |
| 2.1       | Early fusion, a.k.a, point-level           |
| 2.2       | Deep fusion, a.k.a, proposal-level |
| 2.3       | Late fusion, a.k.a, detection-level        |


## Survey
[Apoorv Singh. 2023] Transformer-Based Sensor Fusion for Autonomous Driving: A Survey
<img width="400" alt="截屏2023-06-23 13 53 05" src="https://github.com/ruoxianglee/Transformer-based-Sensor-Fusion/assets/36948139/6f118cfb-d96d-44fd-9856-9d06e91d7c2b">

[Apoorv Singh. 2023] Vision-RADAR fusion for Robotics BEV Detections: A Survey

## Benchmark
[CARLA Leaderboard](https://leaderboard.carla.org/leaderboard/)

[nuScenes Leaderboard](https://paperswithcode.com/sota/3d-object-detection-on-nuscenes)

## Lidar+Camera
[Aditya Prakash. 2021 CVPR] Multi-Modal Fusion Transformer for End-to-End Autonomous Driving

[Kashyap Chitta. 2022 ] TransFuser: Imitation with Transformer-Based Sensor Fusion for Autonomous Driving ([Code](https://github.com/autonomousvision/transfuser))

Note:
- Type: Proposal-level fusion
- Dataset: CARLA
<img width="400" alt="截屏2023-06-23 13 55 01" src="https://github.com/ruoxianglee/Transformer-based-Sensor-Fusion/assets/36948139/3d482ac0-8a35-4a78-b333-ae106ccd3e72">

[Xuyang Bai. 2022 CVPR] TransFusion: Robust LiDAR-Camera Fusion for 3D Object Detection with Transformers ([Code](https://github.com/XuyangBai/TransFusion/))

Note:
- Type: Deep fusion
- Dataset: nuScenes
<img width="400" alt="截屏2023-06-23 14 11 33" src="https://github.com/ruoxianglee/Transformer-based-Sensor-Fusion/assets/36948139/a7a26693-4dcf-43fd-941f-5aaab41e6baa">

[Hao Shao. 2022 CoRL] InterFuser: Safety-Enhanced Autonomous Driving Using Interpretable Sensor Fusion Transformer ([Code](https://github.com/opendilab/InterFuser))

Note:
- Type: Deep fusion
- Dataset: CARLA
<img width="400" alt="截屏2023-06-23 13 53 26" src="https://github.com/ruoxianglee/Transformer-based-Sensor-Fusion/assets/36948139/d242abb6-3a5f-42f3-b9af-fd1cd156e1a6">

[Hao Shao. 2023 CVPR] ReasonNet: End-to-End Driving with Temporal and Global Reasoning

Note:
- Type: Deep fusion?
- Dataset: CARLA
<img width="400" alt="截屏2023-06-23 14 20 10" src="https://github.com/ruoxianglee/Transformer-based-Sensor-Fusion/assets/36948139/bda8755a-4ddb-4c0f-8315-c5d2b58d3bb3">

[Zehui Chen. 2022 IJCAI] Autoalign: Pixel-instance feature aggregation for multi-modal 3d object detection

Note:
- Type: 
- Dataset: KITTI, nuScenes
<img width="400" alt="截屏2023-06-26 17 15 39" src="https://github.com/ruoxianglee/Transformer-based-Sensor-Fusion/assets/36948139/e3bba931-af30-4aec-a686-02b208c14bbe">

[Zehui Chen. 2022 ECCV] AutoAlignV2: Deformable Feature Aggregation for Dynamic Multi-Modal 3D Object Detection ([Code](https://github.com/zehuichen123/AutoAlignV2))

Note:
- Type: 
- Dataset: nuScenes

<img width="300" alt="截屏2023-06-26 17 31 41" src="https://github.com/ruoxianglee/Transformer-based-Sensor-Fusion/assets/36948139/031f33f7-1e89-4eb9-a74a-4639e7a15e10">
<img width="400" alt="截屏2023-06-26 17 31 13" src="https://github.com/ruoxianglee/Transformer-based-Sensor-Fusion/assets/36948139/65e6d811-c8fa-422e-9b41-df2314149642">

[Junjie Yan. 2023] Cross Modal Transformer: Towards Fast and Robust 3D Object Detection ([Code](https://github.com/junjie18/CMT))

Note:
- Type: 
- Dataset: nuScenes
<img width="400" alt="截屏2023-06-26 17 43 33" src="https://github.com/ruoxianglee/Transformer-based-Sensor-Fusion/assets/36948139/d406169d-87fe-4dc2-997b-44ec4483f38a">

## Unified Framework (LiDAR, Camera, Radar)
[Xuanyao Chen. 2023 CVPR] FUTR3D: A Unified Sensor Fusion Framework for 3D Detection ([Code](https://github.com/Tsinghua-MARS-Lab/futr3d))

Note:
- Type: Deep fusion
- Dataset: nuScenes
<img width="400" alt="截屏2023-06-26 15 59 48" src="https://github.com/ruoxianglee/Transformer-based-Sensor-Fusion/assets/36948139/68462514-a775-40ce-9bff-dc7ff56ed293">
<img width="400" alt="截屏2023-06-26 16 00 02" src="https://github.com/ruoxianglee/Transformer-based-Sensor-Fusion/assets/36948139/e2e437e2-cfc1-4e48-93d4-282b1b8e4440">

## Other DL-based fusion
### Survey

[Literature summary for e2e AD](https://github.com/opendilab/awesome-end-to-end-autonomous-driving)

[Danni Wu. 2022] Deep learning for LiDAR-only and LIDAR-fusion 3D perception: a survey
<img width="400" alt="截屏2023-06-24 17 17 14" src="https://github.com/ruoxianglee/Transformer-based-Sensor-Fusion/assets/36948139/81c573f7-200b-46af-8635-95336d85216c">
<img width="400" alt="截屏2023-06-24 17 17 44" src="https://github.com/ruoxianglee/Transformer-based-Sensor-Fusion/assets/36948139/3022da24-0617-4900-ac93-19a3ca181896">
