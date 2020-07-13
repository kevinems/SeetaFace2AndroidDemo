# SeetaFace2AndroidDemo
这是中科视拓开源项目[SeetaFace2](https://github.com/seetafaceengine/SeetaFace2)的android示例

由于模型文件较大，需要用户自己去下载然后放到app模块的assets目录下，或者/sdcard/seeta/model目录下。
记得修改一些环境变量为你自己的配置环境，如ndk、cmake等，祝好运。

====================================================
kevinems:
在原作者的基础上，修改如下，具体可以查看修改记录：
1. Android Studio 4.0 上编译通过。
2. 使用重新编译的 seetaface2 的库，并支持 arm64。（原项目没有提供 arm64 库，所以在目前的主流手机上都跑不了）
3. demo 修改为使用后置摄像头。

有问题可以到这里找我 www.kevinems.com