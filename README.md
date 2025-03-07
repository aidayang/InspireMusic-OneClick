# InspireMusic-OneClick
InspireMusic文本转音乐软件免安装一键启动整合包
![](https://raw.githubusercontent.com/FunAudioLLM/InspireMusic/main/asset/logo.png)

## InspireMusic介绍
InspireMusic 是阿里团队推出的一个基本的 AIGC 工具包和模型，旨在使用 PyTorch 生成音乐、歌曲和音频。

亮点：

InspireMusic专注于音乐生成、歌曲生成和音频生成。

音乐、歌曲、音频生成的统一框架。可通过文本提示、音乐流派、音乐结构等进行控制。

支持高音质音乐生成任务，可提供24kHz、48kHz的采样率。

支持长格式音频生成。

便捷的微调和推理。支持混合精度训练（BF16、FP16、FP32）。提供便捷的微调和推理脚本和策略，让用户可以轻松微调自己的音乐生成模型。

## InspireMusic整合包使用说明
首先将网盘内的压缩包软件下载到本地电脑并解压。然后双击【启动软件.exe】，稍等一会会打开webUI界面。
![](https://raw.githubusercontent.com/aidayang/InspireMusic-OneClick/refs/heads/main/jietu.webp)

软件主要有两个功能，1、文本转音乐。2、音乐续写

1、文本转音乐

在Input Text输入框中输入想要合成音乐的文本描述词，用英文输入。然后点击下方Start Text-to-Music Task按钮开始生成音乐。

2、音乐续写

在右侧Input Audio Prompt (For Music Continuation Task)里上传一段音频样本，然后点击下方按钮Start Music Continuation Task，就会根据音频素材旋律风格继续生成音乐。用于帮助理解音乐结构和创作技巧，为音乐创作者寻找灵感或扩展思路。

软件顶部有4个参数可以设置。Select Model Name为模型选择，默认使用的是InspireMusic-1.5B-Long，使用其它模型的话需要额外下载模型文件。

Chorus Mode里可以选择音乐段落

1. Intro（引子）

含义：音乐的开头部分，通常用于引入主题或营造氛围。


2. Verse（主歌）

含义：音乐的主要叙述部分，通常包含歌词的主体内容。


3. Chorus（副歌）

含义：音乐的高潮部分，通常是整首歌曲中最具记忆点的段落。


4. Outro（结尾）

含义：音乐的结束部分，用于收尾或逐渐淡出。


Output Audio Sample Rate为音频采样率，默认即可。

Generate Audio Length生成音频的时长，最长300秒，即5分钟。

视频教程及演示：[youtube>>](https://www.youtube.com/watch?v=222mZiXD0NA)

## 注意事项
软件只支持英伟达30或40系列显卡电脑

只支持windows10或11系统

软件运行路径中不要有非英文字符和空格

## 文字转音乐软件InspireMusic整合包下载链接
https://pan.quark.cn/s/f8fa6c688046

## InspireMusic项目地址
https://github.com/FunAudioLLM/InspireMusic
