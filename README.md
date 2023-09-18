# SF_TRT_62


## 本项目为开源项目, 欢迎对本项目提出issues,或者pr
### 因第一次正式使用github,不是很了解github的操作, 需要一定时间去适应
### 代码提交需要符合以下规则
* 不得包含侵入式的代码，如非法注入，非法HOOK，非法加载驱动等
* 代码尽量保持规范，使用面向对象编程方法
* 如使用他人的代码需要遵守其开源协议, 并在提交的代码头注释来源。
    

## ->编译文档

### 1. 安装Visual Studio 2022
- vs2022负载选择 **使用c++的桌面开发**
- 安装完成后才能进入下一步骤

### 2. 安装CUDA,cudann,TensorRt, [安装视频](https://www.bilibili.com/video/BV1pG411h743/?spm_id_from=333.999.0.0&vd_source=48769c3445e4933d438612c7cb69d59c)

### 3. 安装[opencv](https://github.com/opencv/opencv/releases)
- 双击安装后,在exe同级目录下解压出一个opencv文件夹,记住他
  
### 4. 安装[cmake](https://github.com/Kitware/CMake/releases)
 - 版本要求>3.18

### 5.修改SF_TRT_62源码下的CMakeLists.txt
- 打开CMakeLists.txt
- 修改opencv的路径,就是上面记住的路径
- 路径定位到build,即能看到include文件夹
- 检查分隔符是不是2个  **\\\\**
- ctrl + s 保存

### 6. 打开cmake,按照[视频](https://www.bilibili.com/video/BV1pG411h743?p=3&vd_source=48769c3445e4933d438612c7cb69d59c)编译
- 记得将Debug改为Release
- 运行库选择MT

## [作者: Bilibili:随风而息](https://space.bilibili.com/120366874)
## 如果你觉得很酷,请给个赞+投币!
### [其他]
- [python-dll教程](https://www.bilibili.com/video/BV1Pe4y1p7Ds/?share_source=copy_web&vd_source=1ab4c859f1ebd918903f472636409e44)
- [依赖yolov5项目写一个自己的项目](https://www.bilibili.com/video/BV1Da4y1G7B2/?share_source=copy_web&vd_source=1ab4c859f1ebd918903f472636409e44)