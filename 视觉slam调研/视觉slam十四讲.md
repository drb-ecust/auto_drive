#### 参考内容

视觉slam十四讲

Visual SLAM algorithms: a survey from 2010 to 2016



视觉slam特点：

 In general,the technical difficulty of vSLAM is higher than that of

other sensor-based SLAMs because cameras can acquire

less visual input from a limited field of views compared

to 360° laser sensing which is typically used in robotics.

视觉slam方法类型：

feature-based，direct，RGB-D camera-based 



basic module：

initialization：构建世界坐标系，建立周围环境

tracking：连续估计相机位姿

mapping：估计相机在地图中的位姿