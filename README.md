# RM-computer-vision


# 环境说明
    opencv３以上

# 内容说明

# PlanA
    main.cpp是传坐标差版本，现场调个阈值就行了，关键部分写了些注释。
　
# PlanB

    VersionAnger.cpp是传移动角度的版本
    carmera文件夹是采集标定图像的代码。
    camera_calib是获得相机内参calib.xml的代码。
    自己要标定相机获得calib.xml
    注意：传角度代码存在理论误差，坐标差版本无理论误差。传角度版本比较开环，传坐标差版本比较闭环。
    
# PlanC
    using_network.py是神经网络版本。
    對比赛没啥价值，有兴趣可以玩下。
    训练自己的卷积神经网络模型参数参照本文https://www.52cv.net/?p=470
    
