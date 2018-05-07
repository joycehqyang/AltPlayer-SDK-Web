# VRVIU-AltPlayerSDK (web)

[![](https://img.shields.io/badge/Powered%20by-vrviu.com-brightgreen.svg)](https://vrviu.com)

## 版本
V1.0.0

## 功能说明
支持FLV格式普通视频点播以及直播功能，其中直播是网络主播实时推送的视频流，用户能够及时看到主播的画面。点播是播放云端或者本地的文件。

* **播放器格式支持**：播放器格式支持：目前只能支持FLV格式的视频或者HTTP-FLV视频流格式。

* **直播视频秒开**：通过优化播放器缓冲策略、网络加载等，该SDK可以实现秒开。

* **多协议支持**：支持HTTP-FLV协议，以及本地文件的播放。

* **接口简单全面**：实现播放接口简单，可快速实现播放。

* **兼容性**：目前主要支持PC上chrome，firefox，edge等主流浏览器,移动端只有android chrome支持。

* **渲染类型**：支持普通2D视频点播直播。



## 快速体验播放效果 (https://rs1-pv.vrviu.com/h5/v1.3/index.html) 


## 导入SDK
### 1. 开发准备
下载最新的VRVIUPlayer2D.min.js以及VRVIUPlayer2D.min.css

### 2. 导入SDK
##### 2.1 新建Html文件导入js-sdk以及css文件
```html
<!DOCTYPE html>
<html lang="en">
<head>
        <meta charset="utf-8">
        <title></title>
        <meta name="description">
        <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
        <meta name="apple-touch-fullscreen" content="yes">
        <meta name="x5-fullscreen" content="true">
        <meta name="x5-page-mode" content="app">  
        <meta name="full-screen" content="yes">
        <meta name="format-detection" content="telephone=no">
        <meta name="apple-mobile-web-app-capable" content="yes">
        <meta name="apple-mobile-web-app-status-bar-style" content="black-translucent" />
        <title></title>
        <link rel="stylesheet" href="./dest/ready/css/VRVIUPlayer2D.min.css">
        <script src="./dest/ready/js/VRVIUPlayer2D.min.js"></script>
</head>
<body>

</body>
</html>
```

##### 2.2 配置工程权限
引入新建js文件配置相关权限

```javascript
......
<script src="./dest/ready/js/encript2d.min.js"></script>
......

encript2d.min.js

new VRVIUPlayer2D({
        url:"https://img.vrviu.com/static/media/vrviu_level_2_e13_noSEI.flv",
        AppId :'vrviu_test_user',
        AccessKeyId :'vrviu_test_access_key_id',
        BizId :'vrviu_test_bizid',
        AccessKeySecret:"vrviu_test_access_key@1234",
        isLive:false
})
```




## 账号鉴权参数表
 |参数|说明|是否必填|类型|
 |:---|:---|:---|:---|
 |AppId|分配给用户的ID，可通过 www.vrviu.com 填写表单或者联系客服申请|必填|String|
 |AccessKeyId|分配给用户的ID，可通过 www.vrviu.com 填写表单或者联系客服申请|必填|String|
 |BizId|分配给用户的ID，可通过 www.vrviu.com 填写表单或者联系客服申请|必填|String|
 |AccessKeySecret|分配给用户的ID，可通过 www.vrviu.com 填写表单或者联系客服申请|必填|String

## 商务合作
电话：0755-86960615

邮箱：business@vrviu.com
