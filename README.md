# Sugar-Voice-Change 甜女声转换
使用星梦基础模型和浅扩散模型转换歌声，转换文本，也可以用于变声器等 <br>
基于 <a href="https://github.com/svc-develop-team/so-vits-svc">So-Vits-Svc</a> 项目，模型由兰酱训练，数据集不公开且模型已经完成训练<br>
至少需要6GB以上显存的显卡，且推荐12GB显存或以上，so-vits-svc自带切片功能，显存少请减少切片时间避免爆显存！（如果你是转换一首歌的话）
# 开始使用
<b>整合包下载 <a href="https://drive.xmlans.com/s/GkSL">https://drive.xmlans.com/s/GkSL</a> </b>
由于太多小白，兰酱直接打包一个整合包并内置Suger-Voice-Change模型，使用Suger-Voice-Change模型则证明您已同意EULA协议（见存储库）<br>
点击启动webui.bat在你的本地浏览器运行可交互界面，所有模型请勾选带suger-voice-change模型（在下拉菜单选中） <br>
虽然so-vits-svc是歌声转换，但自然可以用于实时变声，充分训练的so-vits-svc模型兰酱认为强于RVC变声器模型，请一并下载 <a href="https://github.com/w-okada/voice-changer">实时变声器，supported该库模型</a> 并使用suger-voice-change进行实时变声 <br>
# 开发初衷
视频创作者平时用剪辑软件的人机字幕配音太没有情感了，虽然这个model无法实现很好的男声转女声，但是可以很好把难听的女声转成目标女声，而且你自己说话有自己的那一个调子，还能实现隐藏自己原声的目的 <br>
# 免责声明
本模型的本意不是冒犯任何人，适用于任何对自然人的声音保护，下载此项目后任何的再训练，转换等与本项目及参与者无关 <br>
在结合实时变声器的使用时会与您当前运行的程序抢占系统资源，导致卡顿和掉帧（转换时对GPU开销大），且CS2游戏内转换在第三方平台时有极小概率被封禁！(其他python变声器有前车之鉴)
