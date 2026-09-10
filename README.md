# Raviramanan V

Applied researcher and engineer working on computer vision, multi-view geometry, sensor fusion, and autonomous systems.

My work focuses on reliable perception and decision-making under uncertainty, with projects spanning sparse 3-D reconstruction, visual correspondence, Bayesian state estimation, and vehicle stability control.

[LinkedIn](https://www.linkedin.com/in/raviramananv) · [Research portfolio](https://github.com/ravceratops/research-portfolio)

## Research interests

- Computer vision and multi-view geometry
- Sparse 3-D reconstruction and predictive uncertainty
- Sensor fusion and Bayesian state estimation
- Autonomous systems, ADAS, and robotics
- Physics-informed machine learning

## 01 — Publication

### Coordinated-Turn EKF for Multi-Sensor Tracking

Simulation-based study of a Coordinated Turn Model inside an Extended Kalman Filter for nonlinear target motion and heterogeneous sensor measurements.

**Publication:** [Evaluating Coordinated Turn Model-Based EKF for Multi-Sensor Target Tracking in Curved Maneuvers](https://doi.org/10.1109/RAEEUCCI67649.2026.11504758) · RAEEUCCI 2026 · Best Paper Award

## 02 — Manuscripts

Manuscripts are private. For access, email [ravi.psln2003@gmail.com](mailto:ravi.psln2003@gmail.com) and request access to the [private manuscript archive](https://github.com/ravceratops/research-portfolio-private).

- **Selective Multi-View Triangulation with Predictive Uncertainty for Reliable Sparse 3-D Reconstruction**
  
  Multi-view pipelines can accept geometrically plausible tracks even when they are weakly constrained or matcher-ambiguous. UMVT-V2 addresses this with a matcher-agnostic selective sparse-reconstruction pipeline that combines robust N-view triangulation, pixel-noise-scaled first-order covariance, and leave-one-view-out predictive validation. The method produces an interpretable acceptance gate and continuous reliability score, enabling a coverage–reliability trade-off. On frozen DTU final tests, mean scene-level AURC is 0.572 mm for SIFT and 0.902 mm for SuperPoint+LightGlue, with reprojection-only ranking improved in 4/5 and 5/5 scenes, respectively. Evaluation on ETH3D shows that performance varies with the matcher and scene distribution.

- **A Sensor-Only Hybrid Physics-Machine-Learning Architecture for Motorcycle Stability Control under Synthetic-Only Validation**
  
  Motorcycle stability control is studied using a sensor-only hybrid physics–machine-learning architecture under synthetic-only validation. The controller receives 15 vehicle-facing sensor channels while road bank remains hidden, and combines a temporal neural predictor, a friction observer, and deterministic throttle/brake allocation. Prediction, warning lead, intervention burden, and closed-loop outcomes are reported separately. In a prevalence-matched out-of-distribution subset, warnings cover 48.1% of unsafe onsets within 500 ms with a mean lead of 0.400 s. Across the paired 500-scenario Plant-B bank, the combined controller changes unsafe fraction by −0.000105 relative to physics-only control, with a 95% interval of [−0.000275, 0.000000].

- **Distance-Only Inside/Outside Determination under Geometric and Motion Constraints** — conditional decidability for localization without direct position reconstruction.

## Projects

1. **Auto-Annotation Tool (Python)** — YOLO-compatible image labeling with custom class mapping, class merging or renaming, optional GPU acceleration, and YOLO-format output.
2. **Vision-Based Automatic ORVM Adjustment** — facial landmarks, head-pose estimation, 3-D eye-point geometry, mirror reflection, and deterministic setpoint generation.
3. **Search and Rescue Robot** — Arduino robotics proof of concept with obstacle detection, camera feedback, autonomous movement, and target alerts.
4. **Motorcycle Stability Control Unit (Python)** — physics-based braking, traction, and lean-angle simulation for cornering and emergency-braking scenarios.
5. **Kalman Filter vs Particle Filter** — motion prediction, sensor fusion, RMSE/MAE comparison, and uncertainty visualisation.
6. **Adaptive Cruise and Lane Change Assist (Python)** — simulated traffic environment with speed adjustment, safety margins, lane availability checks, and automatic lane-change decisions.
7. **Lane Change Assist Prototype (Arduino)** — five ultrasonic sensors, warning indicators, LCD feedback, and servo-based lane-switching control.

## Contact

For research or engineering collaboration, connect with me on [LinkedIn](https://www.linkedin.com/in/raviramananv) or email [ravi.psln2003@gmail.com](mailto:ravi.psln2003@gmail.com).
