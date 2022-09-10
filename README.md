# 0 Info
## 1 [weekly](https://github.com/ruanyf/weekly)
科技爱好者周刊
记录每周值得分享的科技内容，周五发布。

# 1 算法
## 1 [IMU_Attitude_Estimator](https://github.com/beichu2020/IMU_Attitude_Estimator)

This project is aimed at estimating the attitude of Attitude Heading and Reference System(AHRS). And the project contains three popular attitude estimator algorithms.
- Mahony's algorithm
- Extend Kalman Filter(EKF)
- Error State Kalman Filter(ESKF)

## 2 [经典卡尔曼算法对比](https://github.com/beichu2020/3_state_filter)

来自大师 priseborough，包括EKF,GSF_EKF,IMMEKF,PF,UKF滤波融合算法实现，非常适合入门学习分析。

## 3 [Ardupilot的EKF算法](https://github.com/beichu2020/InertialNav)
来自大师 priseborough，深入飞控滤波算法这个非常有价值。

## 4 [矩阵运算库C++实现](https://github.com/PX4/PX4-Autopilot/tree/4a3d64f1d76856d22323d1061ac6e560efda0a05/src/lib/matrix)

# 2 GUI
## 1 [LVGL在STM32F405RG上的尝试，效果惊艳](https://github.com/beichu2020/LVGL-STM32F405RG)

# 3 AI
## 1 [Stable Diffusion](https://github.com/CompVis/stable-diffusion)
从草图生成高清的细节图像，非常Nice.
Stable Diffusion is a latent text-to-image diffusion model. Thanks to a generous compute donation from Stability AI and support from LAION, we were able to train a Latent Diffusion Model on 512x512 images from a subset of the LAION-5B database. Similar to Google's Imagen, this model uses a frozen CLIP ViT-L/14 text encoder to condition the model on text prompts. With its 860M UNet and 123M text encoder, the model is relatively lightweight and runs on a GPU with at least 10GB VRAM. See this section below and the model card.

[这里是一个学习本项目的一个collection](https://github.com/Maks-s/sd-akashic)
This repository is a collection of studies, art styles, prompts and other useful tools you can use throughout your exploration of the latent space.
As Stable Diffusion is still in beta and subject to lots of changes, the Records will often change to reflect new information.

[这里是一个简单的教程](https://andys.page/posts/how-to-draw/)
Watching a vibrant Seattle sunset the other day, my imagination started running. The otherworldly hue of the sky evoked something from science fiction. The hazy orange-purple was mesmerizing.

# 4 数字货币|加密货币|数字钱包
## 1 [数字钱包](https://github.com/OneKeyHQ/firmware)
OneKey
🔑 OneKey is the smartest way to secure, buy, exchange and grow your crypto assets. Learn more here.

make something people want

🗳️ Your crypto, in your hands
OneKey will not store your private keys or recovery seed, all our hardware and software are open source.

👶 Simple yet secure
Use the OneKey App by itself or with the hardware, keeping it simple for beginners without compromising on security.

👁️ Truly open source
Open source means that we don't hide any code and are open to inspection by everyone, which takes courage and commitment.

🔐 End-to-end encryption
OneKey uses industry-leading encryption technology to store your information locally. Only you can decrypt that information.

#5 相角摄像机 | IPC
## 1 [openmiko](https://github.com/openmiko/openmiko)
OpenMiko is custom opensource firmware for cameras that use the Ingenic T20 chip. These cameras include the Wyzecam V2 and Xiaomi Xiaofang.

The firmware aims to provide an an alternative to the closed source out of box firmwares which can often be riddled with bugs and security holes. Privacy is also a concern as it is difficult to tell if out of box firmware reaches out to other servers or is broadcasting metadata.
支持方案Ingenic T20X (128Mb DDR)：Wyze Cam V2 | Xiaomi Dafang | Wyze Cam Pan
君正T20全高清智能视频应用处理器是一款智能视频应用处理器，针对像移动相机、安全调查、视频通话、视频分析等视频设备。这种SOC引入了一种创新的architec。确保满足高性能计算和高质量的图像和视频编码要求。提供T20高速CPU计算能力，出色的图像信号处理，FLUENT 2048x1536分辨率录像。

CPU核心，配备32KB指令和32KB数据级1高速缓存，128KB二级高速缓存，工作频率为1GHz，全功能MMU功能执行操作系统相关任务 在CPU核心的核心是XBurst处理器引擎。XBurst是业界领先的微处理器内核，可提供卓越的高性能和一流的低功耗。此外，还包括与IEEE 754兼容的浮点单元。MXU2.0(SIMD 128)指令集由XBurst Engine实现，是CPU的一部分。

有了强大的cpu，t20支持各种计算机视觉应用，如人脸检测、人体检测、手势识别等，人们也可以开发新的计算机视觉应用。离子使用MXU2.0加速它。

VPU(视频处理单元)核心由另一个XBurst处理器引擎驱动。T20与片上视频加速引擎和后处理单元一起提供高视频性能。编码支持最大分辨率为2048x1536的H.264格式。同时支持1080 p@30 fps和d1@30 fps，具有最大的性能。

为了更快、更容易地使用T20，集成了一个512 Mbit DDR2。

片内模块(如音频编解码器、多通道SAR-ADC控制器和摄像头接口)为设计人员提供了一套经济实用的用于视频应用的外设。WLAN、蓝牙和扩展选项 通过高速spi和MMC/SD/SDIO主机控制器支持离子。其他外设，例如USBOTG、UART和SPI以及通用系统资源提供了足够的计算和连接 适用于许多应用程序。

下面是另一个君正方案IPC固件
If you have a device with a Ingenic T10 SOC, consider using for now https://github.com/EliasKotlyar/Xiaomi-Dafang-Hacks

