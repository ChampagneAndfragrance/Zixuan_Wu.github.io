---
title: 'Trajectory Servoing: Image-Based Trajectory Tracking without Absolute Positioning'
authors:
- Zixuan Wu
date: 2021-05-15
publishDate: '2021-01-01'
publication_types:
- manuscript
abstract: Navigation systems with real-time needs often employ hierarchical schemes
  that decompose navigation across multiple spatial and temporal scales. Doing so
  permits the navigation solution to respond in real-time to novel information gained
  from sensors, while being guided by the more slowly evolving global path. At the
  lowest level of the hierarchy lies trajectory tracking to realize the planned paths
  or synthesized trajectories. In the absence of an absolute reference (such as GPS)
  and of an accurate map of the environment, there are no external mechanisms to support
  trajectory tracking. Onboard mechanisms include odometry through proprioceptive
  sensors (wheel encoders, IMUs, etc.) or visual sensors. Pose estimation from proprioceptive
  sensors is not observable, thus visual sensors provide the best mechanism to anchor
  the robot’s pose estimate to external, static position references.Indeed visual
  odometry (VO) or visual SLAM (V-SLAM) solutions are essential in these circumstances.
  However, they too experience drift, mostly due to the integrated effects of measurement
  noise and system latency. Specificly, the feedback rate from multiple sensor (IMU,
  Camera, etc.) and control loops are impossible to be perfectly matched since each
  latency varies, therefore, raw IMU data uncorrected by VO may be directily sent
  to controller and cause tracking deviation [1]. Additionally, the accumulation of
  noise (eg IMU bias, camera noise, calibration error, etc.) will cause the VO drift
  [2] and further undermine the trajectory tracking. From the limitation of cost,
  cameras that are compatible with small robots are easily be affected by Johnson-Nyquist
  thermal …
---
