# 垃圾分类小程序
## 小程序使用到的云开发内容
> 不了解小程序云开发请访问[文档](https://developers.weixin.qq.com/miniprogram/dev/wxcloud/basis/getting-started.html)

---
## 截图
<div >
    <img src='https://raw.githubusercontent.com/zhangliwen1101/Images/master/img/garbage/01.png' style='max-width:100px!important;width:100px!important;'>
    <img src='https://raw.githubusercontent.com/zhangliwen1101/Images/master/img/garbage/02.png' style='style='max-width:100px!important;width:100px!important;'>
    <img src='https://raw.githubusercontent.com/zhangliwen1101/Images/master/img/garbage/03.png' style='style='max-width:100px!important;width:100px!important;'>
    <img src='https://raw.githubusercontent.com/zhangliwen1101/Images/master/img/garbage/04.png' style='style='max-width:100px!important;width:100px!important;'>
    <img src='https://raw.githubusercontent.com/zhangliwen1101/Images/master/img/garbage/05.png' style='style='max-width:100px!important;width:100px!important;'>
    <img src='https://raw.githubusercontent.com/zhangliwen1101/Images/master/img/garbage/06.png' style='style='max-width:100px!important;width:100px!important;'>
</div>

---

云函数，云数据库：
- 数据库：存储四种垃圾分类的相关垃圾数据， 创建表commit,sort，product。把sort.json 和product.csv 导入云数据库即可
- 云函数：获取百度识别库的accessToken
[百度AI识别库地址](http://ai.baidu.com/docs#/ImageClassify-API/ebc492b1)
[QQ AI地址](https://ai.qq.com/)

## 需要修改为自己的key 
1. 小程序key 在文件project.config.json->appid 记住创建小程序的时候选择云开发
2. 百度key 主要做拍照识别的cloudfunctions->baiduAccessToken->index->apiKey和secretKey
此处替换为：API Key 和 Secret Key

## 常见错误
1. 没有自己部署云函数
2. 数据库没有给与相应的权限，最好给最大权限
3. 需要的key 配置错误。
4. 没有创建数据库名称

## 直接扫码体验
![标准垃圾分类](https://raw.githubusercontent.com/zhangliwen1101/Images/master/img/garbage/erweima01.jpg)
## 其他小程序
![婚礼邀请函love](https://raw.githubusercontent.com/zhangliwen1101/Images/master/img/marry/自制婚礼请柬1.jpg)
[QQ AI地址](https://github.com/zhangliwen1101/wedding)

## 打赏
码砖不易，如果您需要，随意打赏，从零开始搭建此项目，直到发版 ->后期运营~
> * QQ: 383755537
> * WX: bjawenfd

### 支付宝

<img src="https://raw.githubusercontent.com/zhangliwen1101/Images/master/img/zhifubaoshou.png" width="300" /> <img src="https://raw.githubusercontent.com/zhangliwen1101/Images/master/img/zhifubaohong.png" width="300" />

### 微信

<img src="https://raw.githubusercontent.com/zhangliwen1101/Images/master/img/weixinshou.png" width="300" />

## License

[MIT](http://opensource.org/licenses/MIT)

Copyright (c) 2019-present, developed by jack.zhang

 