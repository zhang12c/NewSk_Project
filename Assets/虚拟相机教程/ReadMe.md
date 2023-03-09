##总结##

虚拟相机(CinemachineVirtualCamera)
1. Follow 跟随的物体 Body可以修改虚拟相机与物体的距离
2. LookAt 看着一个物体 Aim可以修改看着物体的位置

主相机 CinemachineBrain 组件 
1. 设置不同虚拟相机切换模式，渐入渐出等
2. 自定义切换模式

TimeLine
1. 创建一个空物体
2. 打开TimeLine的窗口
3. 点击空物体，在timeLine窗口点击Create
4. 创建Cinemachine Track
5. 填入主相机。并将不同的虚拟相机拖入时间轴。类似animator

TimeLine的物体 Playable Director
1. Wrap Mode 设置TimeLine播放的顺序