# 如何运行代码
由于作者太菜没什么使用GitHub的经验以及visual studio配置中使用了很多绝对路径，现在还不太会以能直接的形式分享代码。但是开源仍然是必须要做的事情，因此如果你想运行猫咪的代码，可能会需要麻烦你做下面的事情：

1、在vs中直接以代码创建工程，其中使用的三个项目已经被分装到不同文件夹，BongoCatMver是猫咪本体，C++项目。BongoCatMverUI是wpf的UI界面的C#类库。CatUILauncher是UI界面的底层，是C++项目。其中CatUILauncher需要修改输出文件名。当然可以本体的项目不依赖其他项目也可运行。

2、搭建SFML环境https://www.sfml-dev.org/tutorials/2.5/start-vc.php

如果不需要live2d部分可以把live2d有关的代码删掉而不需要做以下几步\n
如果需要live2d请继续以下步骤

3、下载live2d的SDK for native

4、参考教程为猫咪搭建live2d的环境https://docs.live2d.com/cubism-sdk-tutorials/sample-build-opengl/

5、猫咪有借用live2d opengl demo的部分代码，这部分代码没有直接放在库里，需要自行copy，根据本体代码中的头文件copy即可。
