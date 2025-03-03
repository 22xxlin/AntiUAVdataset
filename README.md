# AntiUAV-Dataset Collection
Provide a visual perception data set collation platform for Anti-UAV
# 反制无人机数据集 / Anti-UAV Datasets

| 数据集名称 <br> Dataset Name       | 年份 <br> Year | 模态 <br> Modality | 分辨率 <br> Resolution        | 数据量 <br> Size (k) | 无人机类别 <br> Classes | 6D姿态 <br> 6D Pose | 特点与应用场景 <br> Key Features & Usage Scenarios | 参考文献 <br> Reference |
|------------------------------------|-------|----------|------------------------------|------------|------------|---------|--------------------------------------------------|------------|
| **Anti-UAV**                       | 2021  | RGB+IR   | 640×512~1920×1080            | 585.9      | 4          | ✗       | 最大规模多模态数据集，支持全天候检测与跟踪 <br> Largest multi-modal dataset for all-weather UAV detection and tracking |     |
| **Anti-UAV410**                    | 2023  | IR       | 640×512                      | 438.0      | -          | ✗       | 纯红外热成像数据，夜间反制任务优化 <br> Pure infrared thermal imaging for night counter-UAV tasks |        |
| **MAV6D***                         | 2024  | RGB      | 640×512                      | 57.1       | 2          | ✓       | 含无人机6D位姿，精准干扰算法开发 <br> 6D pose (position + rotation) for trajectory prediction |       |
| **ARD-MAV***                       | 2023  | RGB      | 1920×1080                    | 107.5      | 1          | ✗       | 极小目标检测（平均0.02%面积占比） <br> Extreme small object detection (avg. 0.02% area) |       |
| **Drone-vs-Bird**                  | 2021  | RGB      | 720×576~3840×2160            | 104.8      | 8          | ✗       | 区分无人机与鸟类，减少误报 <br> UAV vs bird discrimination (8 classes) |      |
| **M3D***                           | 2024  | RGB      | 1920×1080                    | 84.0       | 22+10      | ✗       | 多领域无人机变体，增强泛化能力 <br> 22-class MAVs + 10-class variants |      |
| **DUT Anti-UAV**                   | 2022  | RGB      | 160×240~3744×5616            | 10.1       | 1          | ✗       | 极端尺度变化（0.00019%~70%目标占比） <br> Extreme scale variation for edge computing |        |
| **Real-World**                     | 2020  | RGB      | 640×480                      | 56.8       | 3          | ✗       | 真实场景静态图像，快速原型验证 <br> Real-world images for rapid prototyping |       |
| **NPS-Drones**                     | 2016  | RGB      | 1920×1080, 1280×760          | 70.3       | 1          | ✗       | 多分辨率视频跟踪基准 <br> Multi-resolution video tracking benchmark |       |
| **FL-Drones**                      | 2016  | RGB      | 640×480, 752×480             | 38.9       | 1          | ✗       | 早期检测基准（光照变化与遮挡） <br> Early benchmark with occlusion scenarios |       |
| **MIDGARD**                        | 2020  | RGB      | 752×480                      | 8.8        | 1          | ✗       | 微型无人机视觉定位数据集 <br> Visual localization for micro-UAVs |       |



- ## References

1. **Pawelczyk, M., & Wojtyra, M.**  
   "Real-World Object Detection Dataset for Quadcopter Unmanned Aerial Vehicle Detection."  
   *IEEE Access*, 8, 174394–174409 (2020).  
   DOI: [10.1109/ACCESS.2020.3025077](https://doi.org/10.1109/ACCESS.2020.3025077)

2. **Walter, V., Vrba, M., & Saska, M.**  
   "On Training Datasets for Machine Learning-Based Visual Relative Localization of Micro-Scale UAVs."  
   *IEEE International Conference on Robotics and Automation (ICRA)*, 10674–10680 (2020).  
   DOI: [10.1109/ICRA40945.2020.9197510](https://doi.org/10.1109/ICRA40945.2020.9197510)

3. **Zheng, Y., et al.**  
   "Air-to-Air Visual Detection of Micro-UAVs: An Experimental Evaluation of Deep Learning."  
   *IEEE Robotics and Automation Letters (RAL)*, 6(2), 1020–1027 (2021).  
   DOI: [10.1109/LRA.2021.3056351](https://doi.org/10.1109/LRA.2021.3056351)

4. **Zhang, Y., et al.**  
   "Domain Adaptive Detection of MAVs: A Benchmark and Noise Suppression Network."  
   *IEEE Transactions on Automation Science and Engineering (TASE)*, 1–16 (2024).  
   DOI: [10.1109/TASE.2024.3370147](https://doi.org/10.1109/TASE.2024.3370147)

5. **Li, J., et al.**  
   "Multi-Target Detection and Tracking from a Single Camera in Unmanned Aerial Vehicles (UAVs)."  
   *IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)*, 4992–4997 (2016).  
   DOI: [10.1109/IROS.2016.7759737](https://doi.org/10.1109/IROS.2016.7759737)

6. **Rozantsev, A., Lepetit, V., & Fua, P.**  
   "Detecting Flying Objects Using a Single Moving Camera."  
   *IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)*, 39(5), 879–892 (2017).  
   DOI: [10.1109/TPAMI.2016.2551248](https://doi.org/10.1109/TPAMI.2016.2551248)

7. **Coluccia, A., et al.**  
   "Drone-vs-Bird Detection Challenge at IEEE AVSS 2021."  
   *IEEE International Conference on Advanced Video and Signal-Based Surveillance (AVSS)*, 1–8 (2021).  
   DOI: [10.1109/AVSS52988.2021.9663800](https://doi.org/10.1109/AVSS52988.2021.9663800)

8. **Jiang, N., et al.**  
   "Anti-UAV: A Large-Scale Benchmark for Vision-Based UAV Tracking."  
   *IEEE Transactions on Multimedia (TMM)*, 25, 486–500 (2021).  
   DOI: [10.1109/TMM.2021.3128047](https://doi.org/10.1109/TMM.2021.3128047)

9. **Jiang, N., et al.**  
   "Anti-UAV: A Large-Scale Benchmark for Vision-Based UAV Tracking."  
   *IEEE Transactions on Intelligent Transportation Systems (TITS)* (2023).  
   DOI: [10.1109/TITS.2022.3226043](https://doi.org/10.1109/TITS.2022.3226043)

10. **Guo, H., et al.**  
    "Global-Local MAV Detection Under Challenging Conditions Based on Appearance and Motion."  
    *IEEE Transactions on Intelligent Transportation Systems (TITS)* (2024).  
    DOI: [10.1109/TITS.2023.3331667](https://doi.org/10.1109/TITS.2023.3331667)

11. **Huang, B., et al.**  
    "Anti-UAV410: A Thermal Infrared Benchmark and Customized Scheme for Tracking Drones in the Wild."  
    *IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)* (2023).  
    DOI: [10.1109/TPAMI.2023.3347289](https://doi.org/10.1109/TPAMI.2023.3347289)
