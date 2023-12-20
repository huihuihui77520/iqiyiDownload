# iqiyiDownload

# 1.通过谷歌浏览器F12 查看可以知道，M3U8地址通过get dash接口获取在返回参数的m3u8获取，所以需要组装该接口的参数就可以获取到。

#记录iqiyi视频抓取记录
### 视频请求接口
# 2.https://cache.video.iqiyi.com/dash? ### 视频请求接口
### 视频ID
tvid=8140078211660600 ### 视频ID
&bid=800&
vid=1d08d31a203c2132c4167c66148afc66&
src=03020031010000000000&
### 用户id
uid=**** ### 用户id 
&k_uid=1e5745129f086ea338fe23c1e1ebb998&
pt=0&
lid=&
cf=&
ct=&
dfp=a0930a1a71f24e4d9b873db754a71715a924bd0aca09c6b39bfc5a4a4d4e289155@1703931395378@1702635396378&
pck=b5fsVsin3D1I4T0KnFhjcet8STax5IVzEWXO1F51zyVqO87eZbjWm3cWPr5tj7m3BbVb94&
qd_v=5& 
### unix时间戳
tm=1702971055674&  ### unix时间戳
k_ft2=8191&
### 加密值
vf=ebc5384474db97adaf501c2d93f516d8  ### 加密值

# 3.除加密值以外的其他值都可以通过请求页面和登录的cookie可以获取到。

# 4. VF加密参数的获取。
## 4.1 通过F12的 search vf= 可以查询到vf 生成的所在文件，

![image](https://github.com/huihuihui77520/iqiyiDownload/assets/145181908/706b4b29-c36f-4ed5-a98e-6510d2b65226)

在该位置，打断点，追踪参数 i 的来源。获取i参数的组装方式，谁知道的怎么操作指导我一下。。。。


