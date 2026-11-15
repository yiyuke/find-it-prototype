# 找东西原型

手机网页原型：用摄像头认出水杯等物品，用语音说出方向，并预览眼镜小屏和 VR 盒子两种显示方式。

- 识别：[MediaPipe Tasks Vision](https://github.com/google-ai-edge/mediapipe) 0.10.14 + EfficientDet-Lite0 模型（Apache License 2.0），文件放在 `lib/` 和 `models/`，不依赖外部 CDN。
- 说话：浏览器自带的语音合成；语音指令依赖浏览器是否支持语音识别。
