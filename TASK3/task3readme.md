使用具有泛化能力的 NeRF 模型，自己构建物体数据集（如手机拍摄），对物体进行三维重建 

一次步骤

1、参考教程（https://zhuanlan.zhihu.com/p/576416530）
2、制作数据集
3、根据数据集使用COLMAP获取相机位姿
4、使用LLFF脚本对位姿数据进行格式转化，把数据集转换成LLFF格式数据集
5、把处理好的数据集配置到Nerf代码目录下
