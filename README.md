# qa-webview-camera

#### 项目介绍
快应用中webview调用系统能力的demo

#### 使用快应用调试器扫码预览
<img src="/qrcode/qr.png" alt="Qr code" style="width: 50%">

## Start

``` bash
npm install hap-toolkit -g
npm install
```

## Build
``` bash
npm run build
```

## 真机预览
- 手机安装调试器
- 手机安装平台预览版
- 打开调试器，使用本地安装安装Build生成的rpk包（位于dist文件夹下）
  
下载调试器APK和平台预览版APK详见详见[资源下载](https://www.quickapp.cn/docCenter/post/69)

## 如果遇到 npm run build 报错 “Cannot find module '/***/webpack.config.js'”:
- 新建一个快应用项目
- 拷贝本项目中的src替换默认生成的src文件夹
- 在新生成的项目下运行 install 和 build 等操作

## Thanks
For detailed explanation & more functions, checkout the [quickapp](https://www.quickapp.cn/) and [quickapp官方文档](https://doc.quickapp.cn/tutorial/).
