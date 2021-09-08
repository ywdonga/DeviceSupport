# DeviceSupport iOS 15.0 真机调试文件

[github地址](https://github.com/ywdonga/DeviceSupport)
[简书地址](https://www.jianshu.com/p/660c5135bb08)

> 在开发时经常因为手痒，把手机升级到了最新的版本，导致Xcode无法真机调试。
> 错误提示 `This iPhone 8 (Model A1863, A1905, A1906, A1907) is running iOS 12.3 (16F5117h), which may not be supported by this version of Xcode.`这种`This xxx is running iOS xxx, which may not be supported by this version of Xcode.`意思是你的手机系版本太高了，当前Xcode无法支持。
![image.png](https://upload-images.jianshu.io/upload_images/1760826-59a676a2ad56d270.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
> 此时不需要大费周章的去下载最新的Xcode(毕竟那么大)只需要下载与手机对应的系统支持文件放入Xcode的真机调试支持文件目录后，重启Xcode即可。

目录地址：
`/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport`

图文演示：
1.找到`Xcode`图标，右键，点击`显示包内容`,或者复制上面的目录地址，按下`shift+command+G`直接跳转到该目录

![image.png](https://upload-images.jianshu.io/upload_images/1760826-78b529f37c49251f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


2.将下在好的文件放入`DeviceSupport`目录
![Jietu20190401-103059.jpg](https://upload-images.jianshu.io/upload_images/1760826-6e4f9b79f9e6e716.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### iOS真机调试支持文件 
下载地址如下，后面会持续更新
> [15.0.zip](https://github.com/ywdonga/DeviceSupport/blob/master/15.0.zip?raw=true)
> [14.7.1.zip](https://github.com/ywdonga/DeviceSupport/blob/master/14.7.1.zip?raw=true)
> [14.7.zip](https://github.com/ywdonga/DeviceSupport/blob/master/14.7.zip?raw=true)
> [14.6.zip](https://github.com/ywdonga/DeviceSupport/blob/master/14.6.zip?raw=true)
> [14.5.zip](https://github.com/ywdonga/DeviceSupport/blob/master/14.5.zip?raw=true)
> [14.4.zip](https://github.com/ywdonga/DeviceSupport/blob/master/14.4.zip?raw=true)
> [14.3.zip](https://github.com/ywdonga/DeviceSupport/blob/master/14.3.zip?raw=true)
> [14.2.zip](https://github.com/ywdonga/DeviceSupport/blob/master/14.2.zip?raw=true)
> [14.1.zip](https://github.com/ywdonga/DeviceSupport/blob/master/14.1.zip?raw=true)
> [14.0.zip](https://github.com/ywdonga/DeviceSupport/blob/master/14.0.zip?raw=true)
> [13.6.zip](https://github.com/ywdonga/DeviceSupport/blob/master/13.6.zip?raw=true)
> [13.5.zip](https://github.com/ywdonga/DeviceSupport/blob/master/13.5.zip?raw=true)
> [13.4.zip](https://github.com/ywdonga/DeviceSupport/blob/master/13.4.zip?raw=true)
> [13.3.zip](https://github.com/ywdonga/DeviceSupport/blob/master/13.3.zip?raw=true)
> [13.2.zip](https://github.com/ywdonga/DeviceSupport/blob/master/13.2.zip?raw=true)
> [13.1.zip](https://github.com/ywdonga/DeviceSupport/blob/master/13.1.zip?raw=true)
> [13.0.zip](https://github.com/ywdonga/DeviceSupport/blob/master/13.0.zip?raw=true)
> [12.4.zip](https://github.com/ywdonga/DeviceSupport/blob/master/12.4.zip?raw=true)
> [12.3.zip](https://github.com/ywdonga/DeviceSupport/blob/master/12.3.zip?raw=true)
> [12.2.zip](https://github.com/ywdonga/DeviceSupport/blob/master/12.2.zip?raw=true)
> [12.1.zip](https://github.com/ywdonga/DeviceSupport/blob/master/12.1.zip?raw=true)
> [12.0.zip](https://github.com/ywdonga/DeviceSupport/blob/master/12.0.zip?raw=true)
> [11.4.zip](https://github.com/ywdonga/DeviceSupport/blob/master/11.4.zip?raw=true)
> [11.3.zip](https://github.com/ywdonga/DeviceSupport/raw/master/11.3.zip?raw=true)
> [11.2.zip](https://github.com/ywdonga/DeviceSupport/blob/master/11.2.zip?raw=true)
> [11.1.zip](https://github.com/ywdonga/DeviceSupport/blob/master/11.1.zip?raw=true)
> [11.0.zip](https://github.com/ywdonga/DeviceSupport/blob/master/11.0.zip?raw=true)
> [10.3.zip](https://github.com/ywdonga/DeviceSupport/blob/master/10.3.zip?raw=true)
> [10.2.zip](https://github.com/ywdonga/DeviceSupport/blob/master/10.2.zip?raw=true)
> [10.1.zip](https://github.com/ywdonga/DeviceSupport/blob/master/10.1.zip?raw=true)
> [10.0.zip](https://github.com/ywdonga/DeviceSupport/blob/master/10.0.zip?raw=true)
> [9.3.zip](https://github.com/ywdonga/DeviceSupport/blob/master/9.3.zip?raw=true)
> [9.2.zip](https://github.com/ywdonga/DeviceSupport/blob/master/9.2.zip?raw=true)
> [9.1.zip](https://github.com/ywdonga/DeviceSupport/blob/master/9.1.zip?raw=true)
> [9.0.zip](https://github.com/ywdonga/DeviceSupport/blob/master/9.0.zip?raw=true)
> [8.4.zip](https://github.com/ywdonga/DeviceSupport/blob/master/8.4.zip?raw=true)
> [8.3.zip](https://github.com/ywdonga/DeviceSupport/blob/master/8.3.zip?raw=true)
> [8.2.zip](https://github.com/ywdonga/DeviceSupport/blob/master/8.2.zip?raw=true)
> [8.1.zip](https://github.com/ywdonga/DeviceSupport/blob/master/8.1.zip?raw=true)
> [8.0.zip](https://github.com/ywdonga/DeviceSupport/blob/master/8.0.zip?raw=true)
