输入：接受 uint8/double 任意尺度(lbp仅仅比大小)
输入：接受单通道图像，三通道将三图片横排列连接 没有太大意义
输出：支持 密度图/hist/normalized hist
输出：边界按照valid模式
输出：编码的code可以可按需要后处理解码

code book：支持旋转不变 uniform 不压缩
邻点采样：支持任意邻点数 半径可调 邻点严格按照圆圈排列 邻点采样使用线性插值

