# Running Data Summary
This project leverages [MATLAB Mobile™](https://www.mathworks.com/products/matlab-mobile.html) to automatically collect phone raw sensor data (enable `position` option which including latitude, longitude, altitude, etc.). The data is then uploaded to MATLAB Drive (e.g., the default 'MobileSensorData' directory). An automated script then quantitatively analyzes the running data, generates visualizations, and pushes the results to a GitHub repository to showcase the latest running data. **All of this is seamlessly accomplished using MATLAB Mobile™**.
> [!NOTE]
> If you're interested in contributing to this project MATLAB automation script, please [open an issue](https://github.com/cuixing158/RunningLog-Analyzer/issues) or contact me at cuixingxing150@gmail.com. If you find my work helpful, I'd gratefully accept a small tip via [Buy Me a Coffee](https://raw.githubusercontent.com/cuixing158/OpticalFlow-Visualization/refs/heads/main/README_media/sponsors.jpg) — thank you!
| Date | Distance (km) | Duration | Elevation Gain (m) | Elevation Loss (m) | Avg Speed (km/h) | Trajectory Map | Altitude-Speed Plot | Speed Histogram |
|------|---------------|----------|--------------------|--------------------|------------------|----------------|---------------------|-----------------|
| 2025-09-18 | 7.78 | 01:07:50 | 338 | 377 | 6.88 | <details><summary>点击预览</summary><img src="./images/2025-09-18_gps_trajectory.jpg" alt="Trajectory" width="600" /></details> | <details><summary>点击预览</summary><img src="./images/2025-09-18_altitude_speed.jpg" alt="Altitude-Speed" width="600" /></details> | <details><summary>点击预览</summary><img src="./images/2025-09-18_speed_histogram.jpg" alt="Speed Histogram" width="600" /></details> |
| 2025-09-25 | 4.53 | 00:42:26 | 188 | 235 | 6.41 | <details><summary>点击预览</summary><img src="./images/2025-09-25_gps_trajectory.jpg" alt="Trajectory" width="600" /></details> | <details><summary>点击预览</summary><img src="./images/2025-09-25_altitude_speed.jpg" alt="Altitude-Speed" width="600" /></details> | <details><summary>点击预览</summary><img src="./images/2025-09-25_speed_histogram.jpg" alt="Speed Histogram" width="600" /></details> |
| 2025-09-28 | 4.52 | 00:38:55 | 172 | 205 | 6.97 | <details><summary>点击预览</summary><img src="./images/2025-09-28_gps_trajectory.jpg" alt="Trajectory" width="600" /></details> | <details><summary>点击预览</summary><img src="./images/2025-09-28_altitude_speed.jpg" alt="Altitude-Speed" width="600" /></details> | <details><summary>点击预览</summary><img src="./images/2025-09-28_speed_histogram.jpg" alt="Speed Histogram" width="600" /></details> |
| 2025-09-30 | 4.48 | 00:30:46 | 183 | 397 | 8.73 | <details><summary>点击预览</summary><img src="./images/2025-09-30_gps_trajectory.jpg" alt="Trajectory" width="600" /></details> | <details><summary>点击预览</summary><img src="./images/2025-09-30_altitude_speed.jpg" alt="Altitude-Speed" width="600" /></details> | <details><summary>点击预览</summary><img src="./images/2025-09-30_speed_histogram.jpg" alt="Speed Histogram" width="600" /></details> |


## References
1. [Matlab Mobile高逼格实时记录GPS运动轨迹（各项参数统计计算）——无第三方包依赖](https://zhuanlan.zhihu.com/p/126242819)
2. [Log Sensor Data Locally](https://www.mathworks.com/help/matlabmobile/ug/log-sensor-data-locally.html)
3. [geoplot](https://www.mathworks.com/help/matlab/ref/geoplot.html)
4. [Set Up Git Source Control](https://www.mathworks.com/help/matlab/matlab_prog/set-up-git-source-control.html)

