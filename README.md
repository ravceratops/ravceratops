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
  
  **Research hook:** A 3-D point can have low reprojection error and still be wrong. UMVT-V2 frames landmark reliability as selective prediction: robust N-view triangulation, pixel-noise-scaled covariance, and leave-one-view-out validation produce both an interpretable acceptance gate and a continuous score, allowing a perception system to trade coverage for expected reliability. On frozen DTU final tests, it reaches mean scene-level AURC of 0.572 mm for SIFT and 0.902 mm for SuperPoint+LightGlue, beating reprojection-only ranking on 4/5 and 5/5 scenes respectively; ETH3D results are mixed, keeping the claim deliberately bounded.

- **A Sensor-Only Hybrid Physics-Machine-Learning Architecture for Motorcycle Stability Control under Synthetic-Only Validation**
  
  **Research hook:** The controller sees 15 sensor channels—not privileged road-bank truth—and must forecast instability before a deterministic allocator limits throttle and brake commands. The architecture combines a temporal neural predictor with a friction observer and physics-based control, then separates prediction quality, warning lead, intervention burden, and closed-loop outcome instead of collapsing them into one safety number. In a prevalence-matched out-of-distribution subset, warnings cover 48.1% of unsafe onsets within 500 ms with 0.400 s mean lead; the paired 500-scenario comparison crosses zero, so the manuscript presents a bounded synthetic evaluation framework—not a real-road safety claim.

- **Distance-Only Inside/Outside Determination under Geometric and Motion Constraints** — conditional decidability for localization without direct position reconstruction.

## 03 — Ranked independent projects

Ranked by technical distinctiveness and admissions-facing impact; manuscript experiments are described only in the private manuscript copies.

1. **Auto-Annotation Tool (Python)** — YOLO-compatible image labeling with custom class mapping, class merging or renaming, optional GPU acceleration, and YOLO-format output.
2. **Vision-Based Automatic ORVM Adjustment** — facial landmarks, head-pose estimation, 3-D eye-point geometry, mirror reflection, and deterministic setpoint generation.
3. **Search and Rescue Robot** — Arduino robotics proof of concept with obstacle detection, camera feedback, autonomous movement, and target alerts.
4. **Motorcycle Stability Control Unit (Python)** — physics-based braking, traction, and lean-angle simulation for cornering and emergency-braking scenarios.
5. **Kalman Filter vs Particle Filter** — motion prediction, sensor fusion, RMSE/MAE comparison, and uncertainty visualisation.
6. **Adaptive Cruise and Lane Change Assist (Python)** — simulated traffic environment with speed adjustment, safety margins, lane availability checks, and automatic lane-change decisions.
7. **Lane Change Assist Prototype (Arduino)** — five ultrasonic sensors, warning indicators, LCD feedback, and servo-based lane-switching control.

## Contact

For research or engineering collaboration, connect with me on [LinkedIn](https://www.linkedin.com/in/raviramananv) or email [ravi.psln2003@gmail.com](mailto:ravi.psln2003@gmail.com).
