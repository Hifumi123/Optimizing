# 性能优化

引擎原理课第十四次作业。

优化了一个以前制作的游戏项目，原项目地址：https://github.com/Hifumi123/Race。

在未优化时，运行的性能情况如图：

![优化前](/README_IMG/001.PNG)

通过场景物件合批、烘培优化、遮挡面剔除等方式进行优化，优化后的性能情况如图：

![优化后](/README_IMG/002.PNG)

可以看到，经过优化，帧数从837.2提升到925.9，Batches由85下降到16，Tris由50.6k下降到
14.4k，Verts由45.1k下降到15.4k。

开发环境为Unity 2019.4，需要Cinemachine插件。

可执行文件在Build目录下，主场景在Assets\Scenes目录下。