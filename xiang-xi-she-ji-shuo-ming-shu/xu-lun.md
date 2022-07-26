# 绪论

### 1.1 项目背景

遥感是20世纪60年代兴起并迅速发展起来的一门综合性探测技术，它利用非接触传感器使人们能离开地球来获取有关地球的时空信息，不仅着眼于解决传统目标的几何定位，更为重要的是对利用外层空间传感器获取的影像和非影像信息进行语义和非语义解译，提取客观世界中各种目标对象的物理特征和信息，从而为人们认识自然和改造自然提供科学的技术和方法。

遥感数据具有覆盖范围及时域广、获取迅速、动态信息强等特点，已广泛应用于城市规划、气象预测、环境保护、防灾减灾、农林业监测等领域并取得了良好的经济和社会效益。近年来，随着遥感技术的进一步发展和新一代高分辨率卫星系统相继投入应用，我国遥感领域已步入了高分辨率影像的快车道，对遥感数据的分析应用服务需求与日俱增。传统方式对高分辨率卫星遥感图像的特征刻画能力差且人工成本高。随着人工智能及深度学习技术快速发展，通过应用深度学习技术可以加速遥感领域智能化应用，促进遥感数据处理走向智能化，使遥感事业更好地服务国计民生。

基于深度学习的遥感图像自动分析和智能解译，是智慧城市、气象预测、环境保护和防灾减灾、农林业监测等场景的重要研究领域，一套科学的遥感图像分析系统，对于城市规划、重点用地监控、环境保护有着重要意义。

### **1.2 国内外研究现状** <a href="#12-guo-nei-wai-yan-jiu-xian-zhuang" id="12-guo-nei-wai-yan-jiu-xian-zhuang"></a>

目前市面上已经有诸如阿里巴巴ai earth，商汤sense earth比较成熟的商业化平台，针对各个来源的遥感图像以及在各个领域的使用都提出的十分完善的解决方案，我们本次项目的主要设计出发点便是吸取市面上已有遥感开发平台的在我们项目所需要用到的功能的优势，打造出一个小而精细的遥感图像解译平台。

### **1.3 项目的主要工作** <a href="#13-xiang-mu-de-zhu-yao-gong-zuo" id="13-xiang-mu-de-zhu-yao-gong-zuo"></a>

项目最终需要开发一个web平台，完成对用户上传的遥感图像进行目标提取，目标检测，地物分类，变化检测四种推理操作。而支持实现这四个功能的模型也需要项目组成员自己编写和训练，并且需要模型F1 score满足一定的指标，所以项目除了web开发之外，另外一个主要工作量就是模型训练和调优。
