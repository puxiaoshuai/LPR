### Demo运行说明

Demo地址： **[LPR](https://github.com/AleynP/LPR)**
参考地址：[https://www.jianshu.com/p/94784c3bf2c1]
打开项目肯定会报编译错误，要做以下修改：
1. 用AS打开项目
2. 下载NDK-r14b,设置项目,在Projcet Strutrue 中设置 NDK位置
3. 先修改 CMakeLists.txt 文件， 把第19行修改成你本地的 OpenCV SDK 的对应路径。
4. 跟据自己的开发平台，设置 ocr 下的build.gradle  第 18 行代码 是否要注释。目前是注释了的。
完成以上步骤后再运行项目，就没有问题了。


