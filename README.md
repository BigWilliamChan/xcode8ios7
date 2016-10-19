# xcode8ios7
支持xcode8编译ios7 Support xcode8 compiler ios7

 - **首先下载支持ios7的device**
在我github工程里下载
https://github.com/chenwei910101/xcode8ios7.git
解压文件后得到7.0和7.1文件夹

 - 打开DeviceSupport 打开xcode的包文件，最好直接用命令行找到DeviceSupport文件夹

```
open /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport
```

 - **将7.0和7.1文件拷贝进去**

如图
![这里写图片描述](http://img.blog.csdn.net/20161019115851693)

 - **命令行打开文件夹**

```
open /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS.sdk/
```

![这里写图片描述](http://img.blog.csdn.net/20161019120025448)

 - **找到SDKSettings.plist文件 用xcode打开**
   在`DEPLOYMENT_TARGET_SUGGESTED_VALUES`里面添加
   7.0 
   7.1

![这里写图片描述](http://img.blog.csdn.net/20161019120236074)

 - **然后就可以设置Deployment Target为7.0啦**

![这里写图片描述](http://img.blog.csdn.net/20161019120330215)