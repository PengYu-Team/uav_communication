# uav_communication

写一个ROS节点：

- 可配置IP，无人机话题前缀等

- 订阅指定ROS话题
- 发布指定ROS话题
- 将订阅得到的消息发送给其他IP
- 将从其他IP收到的消息变为ROS消息发布
