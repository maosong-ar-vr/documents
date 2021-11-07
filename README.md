# AR/VR 相关资料

## 统一SDK版本

- Unity3D 2020.3.xxx LTS
- Vuforia 10.2

## 图像、对象识别方案

- Image Targets 简单、平面的图像目标、圆柱形形式的卷曲目标，或组合框的多目标。
https://library.vuforia.com/objects/best-practices-designing-and-developing-image-based-targets

- Cylinder Targets 圆柱目标使您能够检测和跟踪包裹成圆柱和圆锥形状的图像，如酒瓶、易拉罐、药瓶等
https://library.vuforia.com/cylinder-targets/recommendations-designing-cylinder-targets

- Multi Targets 立方体识别
https://library.vuforia.com/objects/recommendations-designing-multi-targets

- Object Targets 玩具、产品、复杂的几何形状 
https://library.vuforia.com/objects/object-targets

- ❗️Model Targets 从家用电器和玩具到车辆，再到大型工业设备，甚至是建筑地标。 
https://library.vuforia.com/model-targets/model-targets-supported-objects-cad-model-best-practices
  - 创建 Model Targets(MTG)
  https://library.vuforia.com/model-targets/how-create-model-target
  - MTG 使用说明
  https://library.vuforia.com/objects/model-target-generator-user-guide
  - 官方推荐硬件 Structure Sensor (Mark II)
    - https://library.vuforia.com/model-targets/how-create-model-targets-3d-scans
    - https://structure.io/structure-sensor-pro

## 空间扫描方案

- 最佳实践
https://library.vuforia.com/area-targets/best-practices-scanning-environment

- 10 到 50 平米 或 500 平方英尺，最好使用 Vuforia Area Target Creator 应用程序（支持 LiDAR Scanner 的 iPhone/iPad）。
- 100 到 1000 平米 或 10,000 平方英尺的中等室内空间最好使用 Matterport Pro2 和 Leica scanners。
- 超过 30.000 平米 或大约 30 万平方英尺推荐 NavVis scanners 和 Leica RTC360。如此大的空间要分割并单独处理，以方便处理并得到更好的性能。


## 教程

- ❗️Model Target 上传3D模型并识别
https://www.youtube.com/watch?v=OiVCDcYqNYw

- How to Use LiDAR on iPhone & iPad -- What Can It Do?
https://www.youtube.com/watch?v=UzLzLQQJC30

- MetaHuman Creator 所有功能试用
https://www.bilibili.com/video/BV1iK411F7w8/?spm_id_from=333.788.recommend_more_video.-1

- Vuforia Model Targets Tutorial（Vuforia模型识别教程）
https://b23.tv/SrNpD5

- Model Targets - Vuforia's latest object recognition technology
https://b23.tv/bApHAt

## 案例

- 汽车说明书APP演示
https://www.36kr.com/video/1409768433534337

- ❗️Model Target 机械原理演示
https://www.youtube.com/watch?v=xnl5qxv8ot0

- 44470 Hyundai Virtual Guide Overview
https://www.youtube.com/watch?v=3MdRhROQcKE

- 基于Unity AR的数字营销
https://blog.unity.com/manufacturing/embedding-real-time-3d-in-your-digital-marketing-strategy

- Hyundai's wild augmented reality owner's manual — CES 2016
https://www.youtube.com/watch?v=qOMvl6-cP7o

- Unity 技术开放日 | 绝对干货 - 揭秘最新数字人制作流程
https://developer.unity.cn/projects/611cda59edbc2a0020a4a09b

- 国内首个超写实数字人 AYAYI 来了！
https://socialbeta.com/c/7595

- Mapbox做的室内导航
https://www.bilibili.com/video/av19172854

- HoloLens 汽车维修 demo
https://www.bilibili.com/s/video/BV1iv411P76B

- 【数字孪生+AR】赋能工业设备远程维修
https://www.bilibili.com/video/BV1pv411P7r9

- SenseAR提供平面检测、运动追踪、云锚点、手势识别等多种AI+AR基础能力，通过赋能移动端开发，构建增强现实体验平台。
https://openar.sensetime.com/

- AR工业远程维修
https://www.bilibili.com/video/BV1yZ4y1w7Mf/

- 在工业4.0和建筑领域的增强现实技术应用
https://www.bilibili.com/video/BV145411s7g3/

## 会议资料

- Unity线上技术大会-工业专场｜基于 Unity 的数字孪生
https://open.163.com/newview/movie/free?pid=KG8PQ24O1&mid=AG8PQ24OQ

- Unity线上技术大会-工业专场｜Unity MARS ：一站式无代码AR和MR开发
https://c.m.163.com/news/v/VV8PP7VPL.html

- Unity线上技术大会-工业专场｜绘数据 见未来
城市数据运营
https://www.163.com/v/video/VV8PPB8G3.html

- Unity线上技术大会-工业专场｜沃尔沃汽车如何联手 Unity 探索上限
https://open.163.com/newview/movie/free?pid=YG8PSHOK3&mid=SG8PSHOKT

- 2020年Unity线上技术大会的相关视频
https://open.163.com/newview/search/Unity%E7%BA%BF%E4%B8%8A%E6%8A%80%E6%9C%AF%E5%A4%A7%E4%BC%9A%20%E5%B7%A5%E4%B8%9A%E4%B8%93%E5%9C%BA

## 招聘

- 请教大厂的大佬们ue4游戏开发，蓝图重要一些 还是c++ 一般招聘更倾向那个？
https://www.zhihu.com/question/268297447/answer/646396096

## 其它文档/资源

- 3D模型搜索网站（需要注册）
https://www.turbosquid.com
  - [易拉罐模型文件](./files/beverage-can.fbx)
  - [玫瑰花模型文件](./files/rose.fbx)
  - [iPhone 13 Pro 模型文件](./files/iphone-13-pro.blend)

- [AR装配 Automatic generation of augmented reality guided assembly instructions using expert demonstration](./files/automatic-generation-of-augmented-reality-guided-assembly-instruc.pdf)

- [案例整理 - 胡林红](./files/case-linhong-hu.pptx)

- [案例整理 - 朱要良](./files/case-yaoliang-zhu.pptx)
