# auto_driving
https://zhuanlan.zhihu.com/p/105512661

接收传感器信息，供算法分析使用，在运算完成后将结果发送出去

基础框架：接收模块、发送模块、与算法对接的接口
接收模块：具体包括接收bag文件中GNSS信息、IMU信息、雷达点云信息和各传感器之间的标定信息。
发送模块：具体包括发送当前点云、全局地图、局部地图、里程计信息、载体运动轨迹等。
接口：具体就是要设计合理的数据结构，能够把算法需要的输入信息和算法的输出信息条例合理地规划好，以使输入输出更清晰方便。
