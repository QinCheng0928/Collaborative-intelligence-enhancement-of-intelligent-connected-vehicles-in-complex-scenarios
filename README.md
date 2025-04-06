# 🚗 复杂场景下智能网联车辆协同智能增强
**本文对比了在完全自动驾驶和人车混合驾驶两种环境下，单车智能PPO算法与协同增强PPO-OK算法的表现。**  

视频左侧展示的是单车智能车辆的表现，右侧展示协同增强车辆的表现。绿色代表协同增强车辆，黄色代表单车智能车辆，而蓝色代表人类驾驶车辆。通过这种方式，我们能够清晰地对比这两种算法在三种典型场景（四车直行、四车左转、四车混合通过）中的差异，直观地感受不同算法在不同驾驶环境下的表现。

## 1. 完全自动驾驶环境

### 1.1 🛣️ 场景一：四车直行通行

<div align="center">
  <video src="./videos/full_autonomous/individual_intelligence/straight.mp4" controls width="480"></video>
  <video src="./videos/full_autonomous/collaborative_intelligence/straight.mp4" controls width="480"></video>
</div>

### 1.2 ↩️ 场景二：四车左转通行

<div align="center">
  <video src="./videos/full_autonomous/individual_intelligence/left.mp4" controls width="480"></video>
  <video src="./videos/full_autonomous/collaborative_intelligence/left.mp4" controls width="480"></video>
</div>

### 1.3 🔀 场景三：四车混合通行

<div align="center">
  <video src="./videos/full_autonomous/individual_intelligence/mixed.mp4" controls width="480"></video>
  <video src="./videos/full_autonomous/collaborative_intelligence/mixed.mp4" controls width="480"></video>
</div>

## 2. 人机混驾环境

### 2.1 🛣️ 场景一：四车直行通行

<div align="center">
  <video src="./videos/human_vehicle_mixed/individual_intelligence/straight.mp4" controls width="480"></video>
  <video src="./videos/human_vehicle_mixed/collaborative_intelligence/straight.mp4" controls width="480"></video>
</div>

### 2.2 ↩️ 场景二：四车左转通行

<div align="center">
  <video src="./videos/human_vehicle_mixed/individual_intelligence/left.mp4" controls width="480"></video>
  <video src="./videos/human_vehicle_mixed/collaborative_intelligence/left.mp4" controls width="480"></video>
</div>

### 2.3 🔀 场景三：四车混合通行

<div align="center">
  <video src="./videos/human_vehicle_mixed/individual_intelligence/mixed.mp4" controls width="480"></video>
  <video src="./videos/human_vehicle_mixed/collaborative_intelligence/mixed.mp4" controls width="480"></video>
</div>
