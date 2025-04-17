# Installation 

[Follow documentaion](https://docs.ros.org/en/humble/Installation/Alternatives/Ubuntu-Development-Setup.html)

## Fix url of VCS import 
```bash
vcs import --input https://raw.githubusercontent.com/ros2/ros2/humble/ros2.repos src
```
TO

```bash
vcs import --input https://raw.githubusercontent.com/zygn/ros2/refs/heads/rolling/ros2.repos src
```
