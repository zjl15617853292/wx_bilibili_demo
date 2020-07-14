# wx_bilibili_demo
项目名：微信小程序的B站项目demo
成品来自于：https://www.bilibili.com/video/BV1Ct411p7bj?t=27&p=22

注意事项：
  API（来自用户：78763697824_bili ）：
    首页导航：http://mock-api.com/mnEe4VnJ.mock/navList
    轮播图：http://mock-api.com/mnEe4VnJ.mock/swiperList
    视频列表：http://mock-api.com/mnEe4VnJ.mock/videoList
    视频详情：http://mock-api.com/mnEe4VnJ.mock/videoDetail
    推荐视频：http://mock-api.com/mnEe4VnJ.mock/otherList
    评论列表：http://mock-api.com/mnEe4VnJ.mock/commentList
   
  font-awesome（来自用户：果儿贪吃糖）:
    font-awesome下载地址http://fontawesome.dashgame.com/ 下载后解压css文件后缀改名wxss
    播放图标矢量图库亲测可用http://www.staticfile.org/ 搜索font-awesome 里面有链接
    将放在styles中的font-awesome.wxss中的代码修改为以下：
      @font-face {
      font-family: 'FontAwesome';
      src: url('https://cdn.staticfile.org/font-awesome/4.7.0/css/font-awesome.css');
      src:
      url('https://cdn.staticfile.org/font-awesome/4.7.0/fonts/fontawesome-webfont.woff2') format('woff2'),
      url('https://cdn.staticfile.org/font-awesome/4.7.0/fonts/fontawesome-webfont.woff') format('woff'),
      url('https://cdn.staticfile.org/font-awesome/4.7.0/fonts/fontawesome-webfont.svg') format('svg'),
      url('https://cdn.staticfile.org/font-awesome/4.7.0/fonts/fontawesome-webfont.eot') format('eot'),
      url('https://cdn.staticfile.org/font-awesome/4.7.0/fonts/fontawesome-webfont.ttf') format('ttf');
      font-weight: normal;
      font-style: normal;
      }
