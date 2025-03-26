## 编译
由于ros2 gazebo ros没有支持/gazebo/set_model_state，故需要使用本工程下的gazebo ros pkg
```sh
colcon build
```

## 运行
```sh
ros2 launch td3 training_simulation.launch.py 
```
注意：
训练结果存储于 install/td3/share/td3/scripts/pytorch_models中
训练过程数据存储于 install/td3/share/td3/scripts/runs中
