## 编译
由于ros2 gazebo ros没有支持/gazebo/set_model_state，故需要使用本工程下的gazebo ros pkg
```sh
colcon build
```

## 运行
```sh
cd <work_space>/src/td3/scripts
ros2 launch td3 training_simulation.launch.py 
```
