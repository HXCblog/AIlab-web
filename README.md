# AIlab-web
Recordmp3js+腾讯AIlab语音识别接口开发的流式语音识别web版
该项目实现的大体流程：使用Recordmp3js在web浏览器中进行录音，定时切片，然后转换为MP3音频切片文件，将切片文件上传到腾讯AIlab语音识别接进行识别，将放回结果渲染在页面上。


*Recordmp3js开源地址：  https://github.com/Audior/Recordmp3js


*腾讯AIlab语音识别接口参考手册：https://ai.qq.com/doc/aaiasr.shtml


预览地址：https://www.huxinchun.com/public/ailab/

## 部署方法


1.将项目上传到php web环境下


2.修改upload.php 中的 腾讯AI平台语音识别信息 AppID和AppKey


3.全站配置开启HTTPS访问协议


4.访问地址：www.域名.com/index.html
