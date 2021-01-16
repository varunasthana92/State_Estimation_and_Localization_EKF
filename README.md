## Implementation of Extended Kalman Filter for state estimation

### Motion Model
The vehicle motion model recieves linear and angular velocity odometry readings as inputs, and outputs the state (i.e., the 2D pose) of the vehicle.

### Measurement Model
The measurement model relates the current pose of the vehicle to the __LIDAR__ range and bearing measurements

__Note__ Refer the jupyter notebook for more details

### Ground Truth for result comparision
<p align="center">
<img src="https://github.com/varunasthana92/Trajectory_Tracing_EKF/blob/master/data/gtruth.png" width = 400>
<img src="https://github.com/varunasthana92/Trajectory_Tracing_EKF/blob/master/data/gtruth2.png" width = 400>
</p>

### State Estimation
<p align="center">
<img src="https://github.com/varunasthana92/Trajectory_Tracing_EKF/blob/master/output/ekf.png" width = 400>
<img src="https://github.com/varunasthana92/Trajectory_Tracing_EKF/blob/master/output/ekf_orientation.png" width = 400>
</p>



