# Simple-navigation-system-2020

基于C++的简易校园导航系统(以SUT为例)

需要学校地图图像、以及地点坐标

算法部分，利用数据结构专业课关于“图”的知识，把关键地点设为图的“顶点”，关键点之间的路径设为图的“边”，路径长度设为图的“权值”，利用书上的**迪杰斯特拉(Dijkstra)**算法计算出最短路径。

为了使系统生成更易懂、可视化的路线图，运用了大一C语言画图的知识。设置工大地图的背景，画出每条路径。

![image-20210901084230637](C:\Users\lance\AppData\Roaming\Typora\typora-user-images\image-20210901084230637.png)

![image-20210901084247144](C:\Users\lance\AppData\Roaming\Typora\typora-user-images\image-20210901084247144.png)

参考 https://www.write-bug.com/article/2150.html

https://blog.csdn.net/ZHUO_SIR/article/details/80628663?tdsourcetag=s_pctim_aiomsg

https://blog.csdn.net/weixin_42718701/article/details/107616125

https://download.csdn.net/download/u014534533/8584393?utm_source=iteye

https://docs.easyx.cn/zh-cn/loadimage