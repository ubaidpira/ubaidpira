Hi, I’m Ubaid

I’m a Robotics Engineering student at the University of Michigan, graduating in December 2026. I work with robot software, sensors, and simulation, with experience testing systems on humanoid and mobile robots.


Experience

STMicroelectronics | Applications Engineer Intern, Robotics & MEMS

I built a lab validation setup for evaluating ST IMUs on the Unitree G1, using motion capture as a ground-truth reference. I established a repeatable testing and data-collection methodology, wrote robot-control and recording software, and synchronized acquisition across the sensor hardware, NVIDIA Jetson Orin, and Windows motion-capture system. I also developed data-processing and visualization tools to align recordings and compare sensor measurements across trials.

I developed an Isaac Sim workflow to generate repeatable push and fall tests, reducing the need to expose physical hardware to potentially damaging falls while collecting data for ST Machine Learning Core (MLC) models. I compared locomotion-policy behavior in simulation and on the real robot, and built a replay tool that synchronizes robot motion, sensor readings, and labels to help validate the training data. By using IMU measurements and simulation physics to detect ground contact and stabilization, I automated labeling and trimming, eliminating manual segmentation of each simulated recording and making larger test datasets practical to produce.

The planned next phase is to explore using MLC outputs as an additional input to a robot safety pipeline built around NVIDIA HALOS.

Stellar Industries, a TRUMPF Company | Process Automation Intern

I developed a PyTorch-based system for detecting surface defects in ceramic components and a camera-calibration and tray-mapping routine for robotic pick-and-place, achieving approximately 1–2 mm localization accuracy.


Projects

OdorBot | Autonomous odor localization

Research using an MBot Omni with gas and airflow sensors to locate an odor source. My work includes a state machine that combines odor and wind measurements, sensor integration, and repeated physical testing.

MBot | Navigation and state estimation

A mobile robotics project involving occupancy-grid mapping, particle-filter localization, EKF sensor fusion, A* and RRT planning, and PID control.

Tools I use

Python, C++, C, ROS 2, Linux, NVIDIA Isaac Sim, PyTorch, MATLAB, RViz, and rosbag.

Some research and coursework repositories are private. Public repositories here contain selected work.
