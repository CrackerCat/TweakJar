TweakJar

TweakJar是一个轻量级的运行时Jar包修改框架，它主要面向Android正向开发者（当然，逆向开发者也同样适用）。
他的主要功能是：在运行时hook任意的java方法，动态调整其方法逻辑。
框架专为希望微调或增强jar包中某些方法的功能又没有jar包源码的场景而设计。
你可以认为他是一个微缩版本的xposed，又没有它的笨重、需要root权限等限制，主打一个极简与方便集成。
此框架从我的另一个开源逆向框架TweakMe裁剪而来，剥离出其中的java拦截部分功能。
因为TweakMe是一个相对较重的逆向框架，而java拦截部分实际上可以单独提取以让其正逆两用，极大的方便使用者在自己的项目中集成开发。
目前TweakJar框架在5.0到14.0的android手机上测试通过。