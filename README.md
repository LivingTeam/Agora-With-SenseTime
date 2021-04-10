# 声网互动直播+商汤美颜
> [官方文档](https://docs.agora.io/cn/Interactive%20Broadcast/landing-page?platform=Android)

## Android 
 
 ### 1.注意事项
 - 需匹配美颜 sdk 版本 ([查看使用版本](/Agora-Video-With-SenseTime-Android/sensetime/src/main/jni/prebuilt/lib/VERSION))，否则有 jni 方法找不到。
 - 镜像可以在 `PreprocessorSenseTime` 中加标识，在其中的 `onPreProcessFrame` 方法中直接返回
