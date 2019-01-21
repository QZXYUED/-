# 清泽心雨UED改版主页 --2019
_清泽心雨网站是太原理工大学学生工作的门户网站_ &emsp;详情请见太原理工大学官网（http://www2017.tyut.edu.cn/）&emsp;清泽心雨官网（http://qzxy.tyut.edu.cn/）<br>
项目负责 清泽心雨UED（技术开发部）
# 工作说明
  * 改版工作前请详细阅读此文档
  * 站员创建GitHub账号申请加入GIT--QZXYUED团队(地址：https://github.com/QZXYUED) 项目地址（https://github.com/QZXYUED/-）
  * 每次上传自己所负责的模块
#手机测试地址
  模块测试地址为[测试](101.7.159.134/template)
# 站点
  网站站点为 [太原理工大学清泽心雨](http://qzxy.tyut.edu.cn/portal.html)
  <br>

  站员测试站点[测试站点](http://101.7.159.134/) （测试需要连接校园网）
  ***
## 目录结构
* enroll &emsp;&emsp;&emsp;//面试查询模块
* error &emsp;&emsp;&emsp;//错误模块
* home__site__template &emsp;&emsp;&emsp;//主站模块
* portal__template &emsp;&emsp;&emsp;//子站模块
* search &emsp;&emsp;&emsp;//搜索模块
* srt &emsp;&emsp;&emsp;//轻应用模块
* static &emsp;&emsp;&emsp;//静态文件

# 目录详细介绍
> enroll
>>enroll.html &emsp;//*面试查询模块*
***
>error
>>400.html &emsp;//*400错误页面*  
>>401.html &emsp;//*401错误页面*  
>>404.html &emsp;//*404错误页面*  
>>500.html &emsp;//*500错误页面*  
>>503.html &emsp;//*503错误页面*  
>>debug.html &emsp;//*系统错误页面*
***
>home__site__template  
>>banner.html &emsp;//*轮播图模块*  
>>footer.html &emsp;//*公共尾模块*  
>>header.html &emsp;//*公共头模块*  
>>main.html &emsp;//*公共内容展示模块*  
>>qzSlghts.html &emsp;//*公共校园风光模块*  
>>qznews.html &emsp;//*公共要闻模块*
***
>portal__template  
>>ctwh__article &emsp;//*子站---传统文化文章模块*
>>>common.html &emsp;//*公共文章模块*
***
>>ctwh__home_page &emsp;//*子站---传统文化公共模块*  
>>>banner_nav.html&emsp;//*轮播图模块*   
>>>gxCulture.html&emsp;//*国学宝典模块*  
>>>gxHistory.html&emsp;//*国学入门模块*  
>>>gxNetResource.html&emsp;//*百家争鸣模块*  
>>>gxNews.html&emsp;//*国学新闻模块*
***
>>paxy__home_page &emsp;//*子站---平安校园模块*
>>>banner_nav.html&emsp;//*轮播图导航模块*  
>>>paEat__Trans.html&emsp;//*饮食卫生模块*  
>>>paSlider.html&emsp;//*安全动态模块*  
***
>>rdnm__article &emsp;//*子站---热点凝眸文章模块*
>>>common.html &emsp;//*公共文章模块*
***
>>rdnm__home_page &emsp;//*子站---热点凝眸公共模块*
>>>morePage.html &emsp;//*公共模块*
***
>>sxkj__home_page &emsp;//*子站---学术科技模块*
>>>banner_nav.html&emsp;//*轮播图导航栏模块*  
>>>xsAchievements.html&emsp;//*科技成果模块*  
>>>xsBaseConstruction.html&emsp;//*基地建设模块*  
>>>xsCompetiton.html&emsp;//*科技竞赛模块*  
>>>xsPeople.html&emsp;//*风云人物模块*  
>>>xsSlider.html&emsp;//*通知公告模块*  
>>>xsTeacher.html&emsp;//*师资队伍模块*  
***
>>sxkj__substation &emsp;//*子站---学术科技---科技竞赛模块*
>>>common.html &emsp;//*公共模块*
***
>>sztd &emsp;//*子站---思政天地模块*
>>>banner_nav.html&emsp;//*轮播图导航栏模块*  
>>>main_szEraModel.html&emsp;//*时代楷模模块*  
>>>main_szSlider.html&emsp;//*时政公共模块*  
***
>>xygj__article &emsp;//*子站---校园广角文章模块*
>>>common.html&emsp;//*公共模块*
***
>>xygj__home_page &emsp;//*子站---校园广角模块*
>>>banner_nav.html&emsp;//*轮播图导航栏模块*  
>>>xylntroduct.html&emsp;//*学院揽胜模块*  
>>>xyPoineer.html&emsp;//*校园先锋模块*  
>>>xySlider.html&emsp;//*学风建设模块*  
>>>xyTeacher.html&emsp;//*教师风采模块*  
***
>search
>>search.html&emsp;//*搜索模块*
***
>srt
>>join&emsp;//*清泽心雨招新报名模块*
>>>index.html&emsp;//*报名主页模块*  
>>>assets&emsp;//*静态文件*
>>>>css  
>>>>fonts  
>>>>img  
>>>>js  
***
>>quesbank&emsp;//*马原题库模块*
>>>index.html&emsp;//*题库模块*  
>>>assets&emsp;//*静态文件*
>>>>css  
>>>>js
***
>static
>>css&emsp;//*静态资源*  
>>fonts&emsp;//*静态资源*  
>>img&emsp;//*静态资源*  
>>js&emsp;//*静态资源*  
>>lib&emsp;//*静态资源*  
# 测试服务器使用说明
* 测试服务器ip 地址101.7.159.134
* 站员登陆账户ued 密码tyutqzxy
* [kod登陆地址](http://101.7.159.134/kodexplorer/) 
* kod登陆账号ued 昵称ued 密码tyutqzxy
* 测试文件上传目录/var/www/html/
* ![kod管理加载中](http://tyutjohn.com/kod/kod.png)

# 连接服务器说明
* 需要连接校园网
* 需安装xshell
* [vpn下载地址](https://www.forticlient.com/downloads)
* vpn配置详情见群公告

# 负责人联系邮箱 <br>
tyutjohnwang@163.com <br>
公共邮箱 tyutued@163.com <br>

2019-1-13 by qzxy-ued-johnwang
