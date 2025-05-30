# 🚗 复杂场景下智能网联车辆协同智能增强
**本文对比了在完全自动驾驶和人车混合驾驶两种环境下，单车智能PPO算法与协同增强PPO-OK算法的表现。**

视频左侧展示的是采用单车智能算法的自动驾驶车辆，右侧展示的是采用协同增强算法的自动驾驶车辆。绿色代表协同增强车辆，黄色代表单车智能车辆，蓝色代表人类驾驶车辆。通过这种方式，我们可以清晰地对比两种算法在三种典型场景（四车直行、四车左转、四车混合通行）中的差异，直观感受它们在不同驾驶环境下的表现。

在此基础上，我们在人机混合驾驶场景中进一步引入了三个视频，均来自同济大学测试场的仿真环境。视频中展示了三种代表性人类驾驶风格（分别为激进、中性和保守），对应**HV**依次为第1辆、第3辆和第4辆车的通过交叉口的车辆。通过这些视频，可以更全面地观察协同增强算法在面对不同类型人类驾驶员时的适应性与表现差异。

## 1. 完全自动驾驶环境

### 1.1 场景一：四车直行通行

<div align="center">
  <video src="./videos/full_autonomous/individual_intelligence/straight.mp4" controls width="480" loop autoplay></video>
  <video src="./videos/full_autonomous/collaborative_intelligence/straight.mp4" controls width="480" loop autoplay></video>
</div>
### 1.2 场景二：四车左转通行

<div align="center">
  <video src="./videos/full_autonomous/individual_intelligence/left.mp4" controls width="480" loop autoplay></video>
  <video src="./videos/full_autonomous/collaborative_intelligence/left.mp4" controls width="480" loop autoplay></video>
</div>
### 1.3 场景三：四车混合通行

<div align="center">
  <video src="./videos/full_autonomous/individual_intelligence/mixed.mp4" controls width="480" loop autoplay></video>
  <video src="./videos/full_autonomous/collaborative_intelligence/mixed.mp4" controls width="480" loop autoplay></video>
</div>
## 2. 人机混驾环境

### 2.1 场景一：四车直行通行

<div align="center">
  <video src="./videos/human_vehicle_mixed/individual_intelligence/straight.mp4" controls width="480" loop autoplay></video>
  <video src="./videos/human_vehicle_mixed/collaborative_intelligence/straight.mp4" controls width="480" loop autoplay></video>
</div>
### 2.2 场景二：四车左转通行

<div align="center">
  <video src="./videos/human_vehicle_mixed/individual_intelligence/left.mp4" controls width="480" loop autoplay></video>
  <video src="./videos/human_vehicle_mixed/collaborative_intelligence/left.mp4" controls width="480" loop autoplay></video>
</div>
### 2.3 场景三：四车混合通行

<div align="center">
  <video src="./videos/human_vehicle_mixed/individual_intelligence/mixed.mp4" controls width="480" loop autoplay></video>
  <video src="./videos/human_vehicle_mixed/collaborative_intelligence/mixed.mp4" controls width="480" loop autoplay></video>
</div>
## 3. 同济大学测试场仿真环境

### 3.1 场景一：HV为第一辆通过交叉口的车辆（激进驾驶员）

  <video src="./videos/carla/levelkPPO_HV_1st_processed.mp4" controls width="480" loop autoplay></video>

### 3.2 场景二：HV为第三辆通过交叉口的车辆（中性驾驶员）

  <video src="./videos/carla/levelkPPO_HV_3rd_processed.mp4" controls width="480" loop autoplay></video>

### 3.3 场景三：HV为第四辆通过交叉口的车辆（保守驾驶员）

  <video src="./videos/carla/levelkPPO_HV_4th_processed.mp4" controls width="480 * 2" loop autoplay></video>
