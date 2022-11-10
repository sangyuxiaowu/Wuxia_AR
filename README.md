# Wuxia_AR
天涯明月刀OL 游戏角色 AR

需要安装有 ffmpeg 软件，Windows 电脑需要配置好环境变量。

# 食用教程

1. 克隆或下载存储库 [https://github.com/sangyuxiaowu/Wuxia_AR/](https://github.com/sangyuxiaowu/Wuxia_AR/)
2. VsCode 打开该存储库文件夹，访问 `main.ipynb`
3. 下载或生成 `video.mov` 录制的角色视频，放到这个文件夹中
4. 执行 `main.ipynb` 中的代码块
5. 打开或部署 `index.html` 文件

网页视频的图片预览可替换 `1000000.png` 文件。

### 注意

需要注意的是，经过测试，因为摄像头调用和视频播放没有适配 IOS设备，另外是透明背景视频 webm 的视频编码 VP9 是一个由 Google 开发的开放格式，只有在 webkit 内核的浏览器才可以播放，所以这个网页仅有安卓用户可以正常访问，在微信中或是手机版的 Chrome，Edge 浏览器访问即可看到效果。
