# 简介 #

**语如意 识知音**
人机语音交互项目：
  * 人说话：**语如意**  ->  机识别：**识知音**    机器语音识别
  * 机器语义识别
  * 机器自然语言处理
  * 机合成：**语如意**  ->  人听懂：**识知音**    机器语音合成

# 详情 #

**语如意子项目，做为整个项目基础，我们需要先收集大量人们讲话、交谈录音，并且把录音整理成对应文本、标注语音：**
  * CMU Sphinx wiki 建议非特定人语音识别至少要搜集200人份共计50小时语音。考虑到汉语方言众多，南腔北调，我们需要成倍增加语音收集数量。
  * 类似项目 http://www.voxforge.org/ 搜集语音 http://librivox.org/ 有声书籍
  * 这是开源项目。在不违反项目许可协议前提下，确保人们可以任意使用是项目原则。包含在项目语音数据库中的任何一份录音及对应文本、语音标注可以有自己的许可协议。项目不歧视任何人，不歧视任何用途，包括商业使用。所以声明为禁止商业使用的数据，项目不能收录。

**对于任何一份录音及对应文本、语音标注的许可协议，项目语音数据库可以接受的为：**
  * 署名-相同方式共享 2.0 通用 (CC BY-SA 2.0)
  * 署名 2.0 通用 (CC BY 2.0)
  * 署名-相同方式共享 3.0 未本地化版本 (CC BY-SA 3.0)
  * 署名 3.0 未本地化版本 (CC BY 3.0)
  * 署名-相同方式共享 3.0 中国大陆 (CC BY-SA 3.0 CN)
  * 署名-相同方式共享 2.5 中国大陆 (CC BY-SA 2.5 CN)
  * GFDL 1.3
  * LGPL
  * GPLv2 or later
  * 公共域 (public domain)

**一份录音及对应文本、语音标注，要求为：**
  * 汉语语音：清晰，可分辨，当前主要搜集汉语通用语语音。带方言味道语音以只会讲普通话者能听懂为准。在此基础上，欢迎额外提供纯正汉语方言语音，请说明方言名，所在地区。
  * 正常语速：约240~360字/分钟，约4~6字/秒。
  * 录音时长：20分钟左右，不宜超过30分钟。
  * 录音人数：不宜超过3人。
  * 采样频率：16kHz整数倍，16kHz、48kHz、96kHz、192kHz，不接受44.1kHz。
  * 采样精度：24bit。
  * 录音格式：无损格式，如.flac、.wav，不接受有损格式如.mp3、.ogg。注意好多录音笔提供的.wav属于有损格式。
  * 对应文本：按句分隔，句句间换行分隔。保留标点符号。建议词语间空格分隔。
  * 语音标注：暂不作要求。
  * 法律状态：清楚。项目对侵范著作权持零容忍态度。建议原创，讲自己知道的、感兴趣的，如家乡美景、吃喝玩乐、穿的、用的，讲公众知道的，如神话、传说、故事、历史，可以和朋友侃大山，可以拿出地图按任意顺序念地名，甚至可以词语接龙。请注意保护好自己和他人隐私，人名建议用化名，地址建议新造一个不存在的。并以录音和文本两种形式声明版权(署名、许可协议)。

**一份录音及对应文本、语音标注，如何提交到"语如意"子项目：**
  * 发邮件到： yuruyi-shizhiyin@googlegroups.com
  * 邮件主题：“[语如意][标签]” (不包括引号，标签选择能代表录音内容的关键词，可添加多个[标签])
  * 邮件正文：分段列出录音设备、录音环境、录音人、版权声明、录音内容简介、录音及对应文本下载地址
  * 邮件附件：录音对应的文本

```
-----BEGIN PGP SIGNED MESSAGE-----
Hash: SHA256

项目名称： 语如意 识知音
Project Name: yuruyi shizhiyin

密钥指纹：
key fingerprint:

pub   4096R/E165CF27 2013-06-10
      Key fingerprint = 95E4 6C36 9FBB E38F 633A  4890 A61F CA16 E165 CF27
uid                  yuruyi shizhiyin <yuruyi.shizhiyin@gmail.com>
sub   4096R/CD20FB24 2013-06-10 [expires: 2015-05-01]
sub   4096R/FDD1E17E 2013-06-10 [expires: 2015-05-01]

https://code.google.com/p/yuruyi-shizhiyin/
https://groups.google.com/group/yuruyi-shizhiyin

当前，本项目目标是收集汉语语音资源，包括通用语和各地方言。
Currently, the project goal is to collect Chinese speech resources,
including the common language and local dialects.
-----BEGIN PGP SIGNATURE-----
Version: GnuPG v1.4.12 (GNU/Linux)

iQIcBAEBCAAGBQJR0CJxAAoJELjrz9H90eF+hXAP/0adLzFHHxgg8y9EELVjm04w
268zT4n/NcRtsdH2WSIWia4ccG54Ob/RUIWDezbJ2kcbNsCVcrN33XTmT4H09/9M
R+5he0fi5w/KkprvAAhqbqWSsTiGJCKg0zCdZzWgzRQtzKGMv997MVYE/wLh+yFn
OqTnca1YhdiiAhn0br79Rlbml4xUCRL6EAem3+mF200HbGGpI1YKF1CUHVixOX67
Odou5Vtc+XUaoTzyIOAY2QdQaOXlS9WXifvIDP3MB01/QJnpvhiiieQ1WDkoMj4n
HWPWzXR5YO16CTpxVsjpP3bYf3PkEwjkQLOVGpN+NpK5U+myOm6fpUv+aEZ9KYrE
MWQwdS/aRm3F2qSleTrL9DUdUcWTvGm8bX+fxPIR8VsT4e3lN5IAQ2Bzow+alTc7
oyq3m34BknT3HaCJepaJXPBpGymfI+MbjTcKMPEJonuVSbZXowVB0dw19L8ZKF+1
Xwn7hu3a9ZWn4rr4tnr23bRtDKcCbGDOXmiZ4Eqir2JH4DkrIIro5Z8iMM5T3wR5
vIFGBg0mY4L8OAfmeraSJD3sq4Xyz1f1F9NpWeSvDGI2DIBAZajkyNoLtkc3ut0O
CxdM8nsUB+/Ki1jhuxfVR5ZTBB3ejaWvpMsD5rs8yh3aoKl7+NwZ6PQuJR7NOsub
aPAJI+lh3mg+PtE+1ZNn
=qEt8
-----END PGP SIGNATURE-----
```