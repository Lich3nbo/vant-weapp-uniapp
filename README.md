# VantUI  Uniapp 示例

本示例原本是从vant官方发布的微信演示示例转换而来,支持H5/微信小程序。 vant-weapp版本为1.2.1.

vant weapp的框架源码，都在工程的wxcomponents目录下。pages目录下是各个示例页面。

官方组件库UNIappH5编译报错，需要手动格式化icon/inde.wxss文件。 参考： https://ext.dcloud.net.cn/plugin?id=302 

## 图片上传服务
提供了图片Nodejs服务 ，代码路径为\src\node-image-upload-server

安装npm包

```
npm install
```
运行服务
```
node app
```


## 感谢
本示例参考了 https://ext.dcloud.net.cn/plugin?id=302 ，依据官网增加了新控件的使用示例。

 

## 更新日志

### 1.1.0(2020-04-30)

升级版本至1.2.1，增加新功能示例，优化原有功能。

### 1.0.0(2020-02-19)

支持H5模式编译。
