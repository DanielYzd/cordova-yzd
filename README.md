#安卓app打包工具cordova环境搭建和使用教程
![image](https://user-images.githubusercontent.com/18028533/27120577-b9a728d0-5116-11e7-94a2-8cd55266ba04.png)  

> [浅谈Cordova框架的理解](https://www.cnblogs.com/cr330326/p/7082821.html)  
> [cordova打包教程](https://www.jianshu.com/p/60e98587ae89)  
##安装cordova cli
###1.下载安装nodejs
###2.下载安装git（配置环境变量）
###3.下载安装jdk sdk
[sdk下载](http://tools.android-studio.org/index.php/sdk/)
###对应平台环境搭建
- [android](http://cordova.apache.org/docs/en/latest/guide/platforms/android/index.html#requirements-and-support)
+ [ios](http://cordova.apache.org/docs/en/latest/guide/platforms/ios/index.html#requirements-and-support)
+ [windows](http://cordova.apache.org/docs/en/latest/guide/platforms/windows/index.html#requirements-and-support)
###4.使用npm安装cordova
	npm install -g cordova
##创建App
	cordova create CordovaProject io.cordova.hellocordova CordovaApp
##添加平台
	cordova platform add android
	cordova platform add ios(可选)
##构建和运行##
	cordova build android
> Could not find an installed version of Gradle wrapper  
> > [下载地址](http://services.gradle.org/distributions/)  
> > 环境变量配置  




