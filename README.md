QA周刊分类整理-201508<br />
一些领域分类可能不准确，请见谅!  


##索引

[业界动态](#NEWS)<br />
[测试思维](#TEST)<br />
[基础知识](#BASIC)<br />
[测试工具](#TESTTOOLS)<br />
[自动化测试](#AUTOTEST)<br />
[持续集成](#CI)<br />
[WEB测试](#WEBTEST)<br />
[移动测试](#MOBILETEST)<br />
[性能测试](#PERFORMANCETEST)<br />
[安全测试](#SECURITYTEST)<br />
[实用教程](#COURSE)<br />
[话题](#TOPICS)<br />

<a name="NEWS"></a>
##业界动态
[Go1.5 发布说明](https://github.com/meilihao/TranslateProject/blob/master/201507%20Go%201.5%20Release%20Notes.md)  
[2015Qcon大会资料汇总](http://doc.hz.netease.com/pages/viewpage.action?pageId=45191251)  
[16th 武汉BQConf ppt汇总](http://doc.hz.netease.com/pages/viewpage.action?pageId=45203055)  
[2015TID大会PPT汇总](http://doc.hz.netease.com/pages/viewpage.action?pageId=46890503)  
[2015苹果全球开发者大会（WWDC 2015）](http://tech.163.com/special/wwdc2015/)      
[Google I/O 2015 主题发布会图文直播](http://www.cnbeta.com/articles/397909.htm)  
[PWorld 软件架构 & 平台创新大会](http://pworld.qclub.io/index.html)  
[2015第一届中国移动测试大会PPT](http://doc.hz.netease.com/pages/viewpage.action?pageId=47974520)  
[2015年需要了解的前端框架和语言](http://www.oschina.net/news/64218/2015-frameworkds-need-to-learn)  
[在敏捷中，我们需要思考型的测试人员（Thinking Tester）。](http://www.infoq.com/cn/news/2015/03/creativity-agile-testing)  
[敏捷测试2015新看点](http://www.infoq.com/cn/news/2015/03/new-developments-agile-testing)  
[51testing测试天地之四月刊](http://download.51testing.com/magazine/51Testing_magazine37.pdf)  
[互联网产品测试的宏观性和广义性](http://doc.hz.netease.com/download/attachments/45198556/%E4%BA%92%E8%81%94%E7%BD%91%E4%BA%A7%E5%93%81%E6%B5%8B%E8%AF%95%E7%9A%84%E5%AE%8F%E8%A7%82%E6%80%A7%E5%92%8C%E5%B9%BF%E4%B9%89%E6%80%A7_15725.pdf)  
[告别第三方，Visual Studio 引入新的网络诊断工具](http://blog.jobbole.com/86787/)  
[书评 - 《展望敏捷软件测试》](http://www.infoq.com/cn/articles/agile-software-testing)  
[“互联网女皇报告”中文版_腾讯科技](http://doc.hz.netease.com/download/attachments/46012706/%E2%80%9C%E4%BA%92%E8%81%94%E7%BD%91%E5%A5%B3%E7%9A%87%E6%8A%A5%E5%91%8A%E2%80%9D%E4%B8%AD%E6%96%87%E7%89%88_%E8%85%BE%E8%AE%AF%E7%A7%91%E6%8A%80.pdf)  
[从携程网的故障中我们应该反思什么？](http://www.infoq.com/cn/news/2015/05/rethink-ctrip-offline)  
[那些没在Goggle I/O上展示的Brillo和Weave细节，全都在这儿了](http://36kr.com/p/533402.html?utm_source=site_search)    
[百度众测-基于众包的O2O服务质量保证](http://www.infoq.com/cn/presentations/o2o-service-quality-assurance-based-on-crowdsourcing)  
[2014年第八届中国软件测试现状调查报告](http://download.51testing.com/ddimg/uploadsoft/20150623/2014_tester_report.pdf)  
[为何docker还未一统天下 ](http://sirupsen.com/production-docker/)  
[从360手机卫士的开发历程看如何实施大型移动应用开发 ](http://www.infoq.com/cn/presentations/from-360-development-see-big-mobile-application-development)  
[Git 2.5增加了工作树、改进了三角工作流、性能等诸多方面 ](http://www.infoq.com/cn/news/2015/08/git-25-released)  
[Facebook开源静态代码检查工具Infer](https://code.facebook.com/posts/1648953042007882/open-sourcing-facebook-infer-identify-bugs-before-you-ship/)  
[特殊字符的威力：分分钟搞瘫iOS message & Skype](http://blog.utest.com/2015/06/05/skype-and-iphone-messages-are-having-a-bad-week//)  
[Appium中国行分享总结：当测试遇上机器人](http://www.infoq.com/cn/news/2015/07/mtsc-appium)   
[移动安全顶级峰会揭露主流智能手机系统重大安全隐患： 小小输入法升级？6亿Galaxy 智能手机却可能沦为肉鸡](http://blog.utest.com/2015/06/19/worst-week-ever-major-security-flaws-hit-iphone-and-galaxy-smartphones/)  
[比葫芦娃还可怕的百度全系APP SDK漏洞 - WormHole虫洞漏洞分析报告](http://blog.jobbole.com/93923/)    
[为何你的iOS应用审核总是被拒，先看15个被拒纬度分析 《腾讯互娱iOS预审团队》](http://mp.weixin.qq.com/s?__biz=MjM5NTQ5MjIyMA==&mid=400574641&idx=3&sn=64671b7d6c0fdeb1e8b01bdccd53f628&scene=1&srcid=1101oa2xYpojq7wfmuDLeTzr&uin=MzgxNTY4NQ%3D%3D&key=04dce534b3b035ef1501cd16a431a196a094b724bb3ac2bb67318946c111c23c152623f3a9c49c6a23ed429caff12609&devicetype=iMac+MacBookPro11%2C1+OSX+OSX+10.10.1+build%2814B25%29&version=11020201&lang=zh_CN&pass_ticket=wJ3x9Eeq7IaHcNoPVSIRq5Fbh10Og%2F%2FwrYCQAruEK3k%3D)    


<a name="TEST"></a>
##测试思维
[A new level of testing?](http://www.huibschoots.nl/wordpress/?p=1995)  
[经营成功的测试生涯](http://www.cnblogs.com/skytraveler/p/3546703.html)  
[反思：别被敏捷忽悠](http://www.infoq.com/cn/news/2014/02/agile-rethink)  
[测试工程师的进阶之路](http://www.ltesting.net/ceshi/ceshijishu/rjcsgcsrm/2015/0430/207949.html)  
[持续软件代码质量提升](http://doc.hz.netease.com/download/attachments/45203055/%E6%8C%81%E7%BB%AD%E7%9A%84%E8%BD%AF%E4%BB%B6%E4%BB%A3%E7%A0%81%E8%B4%A8%E9%87%8F%E6%8F%90%E5%8D%87.pdf)   
[对前端质量保障的思考](http://www.51testing.com/html/36/n-2980636.html)  
[一些产品测试经验](http://www.jianshu.com/p/9f3041818702)  
[算法、技术及其他 ](http://www.cnblogs.com/aquastone/p/algorithm-technology-and-others.html)  
[如何有效地报告bug](http://www.cocoachina.com/programmer/20150626/12284.html)  
[软件缺陷的有效管理](http://insights.thoughtworkers.org/defect-management/)  
[你的敏捷用对了吗？](http://chuansong.me/n/1600022)   
[敏捷是怎样改变测试管理的](http://www.infoq.com/cn/articles/agile-changed-test-management?utm_source=tuicool)  
[在数据仓库中实现敏捷](http://www.infoq.com/cn/news/2015/05/data-warehouse)  
[分布式系统场景注入测试](http://mp.weixin.qq.com/s?__biz=MzA3MDQ4MzQzMg==&mid=246713986&idx=1&sn=90998cd4a6fa0a4c0310074bb862dd1f&key=c76941211a49ab58868b8738e15475907084ffad474267a1781d535968a47c823c0d0b164bc8fc40258b0da25e626de4&ascene=1&uin=MjIxMTg5NDUwMA%3D%3D&devicetype=Windows+7&version=61010029&pass_ticket=UEWChUZBbEANEFjVpxCT%2F2QbsZmJJWXk2fbxUzMQzfkhh3a9qFEFHoXxXR8tNMPs)   
[天哪，BUG居然可以这样报！](http://mp.weixin.qq.com/s?__biz=MjM5ODY4ODIxOA==&mid=205869689&idx=1&sn=cbcc4e0c648dd0bc4478c4c7d01a91ff&scene=5#rd)  
[故障管理工作方法和技巧分享](http://weibo.com/p/1001603835134481714741)  
[BDD怎样帮助你解决沟通问题并增进协作](http://www.infoq.com/cn/news/2015/05/BDD-collaboration)   
[程序员7大软技能测验 你得几分？](http://www.codeceo.com/article/programmer-soft-skills-quiz.html)   
[移动测试人员的未来：测试开发技术的融合](http://www.infoq.com/cn/articles/mobile-testing-future?utm_source=infoq&utm_medium=popular_widget&utm_campaign=popular_content_list&utm_content=homepage)       
[James Whittaker：经营成功的测试职业生涯 ](http://blog.jobbole.com/74611/)  
[从测试人员的角度看敏捷中的障碍](http://www.testwo.com/article/436)  
[通过心理学知识提高问题定位与解决能力](http://kb.cnblogs.com/page/522261/)  
[一种基于存储过程的复杂计算功能测试方法](http://qa.baidu.com/blog/?p=897)  
[一大波平台来袭，可用性测试怎么破](http://isux.tencent.com/usability-test-of-multi-platform.html)  
[手机淘宝高质量持续交付探索之路](http://www.testwo.com/article/379)  
[探索式测试实践之缺陷大扫除和结对测试](http://blog.sina.com.cn/s/blog_6cf812be01012h6l.html#bsh-161-314253713)  
[How To Write Effective Test Cases and Procedures?](http://www.softwaretestingclass.com/how-to-write-effective-test-cases-and-procedures/?utm_source=tuicool)  
[58同城沈剑：好的架构是进化来的，不是设计来的 ](http://news.oneapm.com/shenjian-oneapm-course/)  
[界面之下：还原真实的MV*模式](https://github.com/livoras/blog/issues/11)   
[Uber 背后架构揭秘](http://mp.weixin.qq.com/s?__biz=MzA4MjEyNTA5Mw==&mid=401167039&idx=1&sn=b9c4a7f4c46e29a8aef89e07ecaf52a2&scene=0#rd)      
[在实际工作中评估你的工程师伙伴 - 写给非技术向小伙伴的参考](http://gulu-dev.com/post/2015-11-05-tips-for-non-programmers)    
[被误解的MVC和被神化的MVVM ](http://www.infoq.com/cn/articles/rethinking-mvc-mvvm)    

<a name="BASIC"></a>
##基础知识 
[大话测试数据系列一](http://www.testwo.com/article/383)  
[大话测试数据系列二](http://www.testwo.com/article/384)  
[大话测试数据系列三](http://www.testwo.com/article/384)  
[十分钟搞清字符集和字符编码](http://cenalulu.github.io/linux/character-encoding/)  
[基础篇：移动端尺寸基础知识](http://colachan.com/post/3435)  
[基础篇：究竟什么是敏捷测试](http://www.testtao.com/article-15694-1.html)   
[基础篇：猴子都能懂的 Git 入门](http://backlogtool.com/git-guide/cn/)  
[基础篇：GIT分支管理是一门艺术](http://roclinux.cn/?p=2129)  
[讲点python基础知识](http://segmentfault.com/a/1190000003887422)  
[前端入门方法总结](http://gold.xitu.io/entry/562ed6f160b20bd5e401e800)   
[Git指令大全图](http://www.colorfulcat.xyz/2015/09/06/git-command/)    
[testng.xml文件结构组成及节点属性说明](http://blog.csdn.net/five3/article/details/25907693)   
[Java API 快速速查宝典](http://www.cnblogs.com/liuhongfeng/p/4806871.html)   
 
<a name="TESTTOOLS"></a>
##测试工具
[infer中文使用说明](http://infer.liaohuqiu.net/)  
[一些命令行效率工具 ](http://wulfric.me/2015/08/zsh/)  
[七牛开源的http测试工具](https://github.com/qiniu/httptest.v1)  
[腾讯的移动质量跟踪平台](http://bugly.qq.com/)  
[10个免费的服务器监控工具](http://blog.jobbole.com/88115/)  
[使用Spock框架进行单元测试 ](http://blog.2baxb.me/archives/1398)  
[SonarQube 3.6 代码质量管理实战](http://www.uml.org.cn/rjzl/201507213.asp)  
[GitHub项目的同行审查自动化工具 ](http://www.infoq.com/cn/news/2015/07/github-code-review-bot)  
[Android UI 自动化测试的代码覆盖率 ](https://testerhome.com/topics/2501)  
[9款免费且超实用的响应式网页测试工具](http://www.uisdc.com/9-free-responsiveness-testing-tools)  
[XebiaLabs TestView整合了多种测试工具](http://www.infoq.com/cn/news/2015/07/xebialabs-testview)  
[Sixpack-java：用于Android和Java应用的A/B测试工具 ](http://www.infoq.com/cn/news/2015/08/Sixpack-java)  
[WEB 端批量移动设备管理控制工具 STF 的环境搭建和运行](https://testerhome.com/topics/2988)  



<a name="AUTOTEST"></a>
##自动化测试
[接口测试总结](blog.sina.com.cn/s/blog_6e0d94750102vjqf.html)  
[前端自动化测试探索 ](http://fex.baidu.com/blog/2015/07/front-end-test/)  
[iOS9 UI Tests探索笔记 ](http://blog.csdn.net/zhao18933/article/details/46621999)  
[自动化测试: 策略及工具 ](http://liguanglei.name/blogs/2014/09/05/automation-test-strategy-and-tools/)   
[实战Android自动化测试](http://testerhome.com/topics/658)  
[Monkey的专项测试浅谈](http://www.testwo.com/article/402)  
[自动化测试：真的是银弹？](http://www.ibm.com/developerworks/cn/rational/r-testing-automation/)  
[Google+ 团队的 Android UI 测试](http://allenlsy.com/android-ui-tests-in-google-plus-team/)  
[智能正交请求参数自动化测试](http://www.infoq.com/cn/articles/orthotropic-requesttestbase)  
[在CI中实现持续Web安全扫描](http://www.infoq.com/cn/articles/WebScan-CI)  
[当谈论覆盖率时我们在谈什么](http://liguanglei.name/blogs/2015/06/01/code-coverage-vs-test-coverage/)   
[功能测试自动化在敏捷过程中的实践与技术展望](http://doc.hz.netease.com/download/attachments/45191251/%E5%8A%9F%E8%83%BD%E6%B5%8B%E8%AF%95%E8%87%AA%E5%8A%A8%E5%8C%96%E5%9C%A8%E6%95%8F%E6%8D%B7%E8%BF%87%E7%A8%8B%E4%B8%AD%E7%9A%84%E5%AE%9E%E8%B7%B5%E4%B8%8E%E6%8A%80%E6%9C%AF%E5%B1%95%E6%9C%9B.pdf)  
[What are Unit Testing, Integration Testing and Functional Testing?](http://codeutopia.net/blog/2015/04/11/what-are-unit-testing-integration-testing-and-functional-testing/)  

<a name="CI"></a>
##持续集成
[Build To Win ](http://zhuanlan.zhihu.com/goujianzhifa/20003750)  
[持续测试的益处](http://www.infoq.com/cn/news/2015/05/benefits-continuous-testing)  
[持续集成和“云”](http://dockone.io/article/470)  
[Docker持续部署图文详解 ](http://www.infoq.com/cn/articles/effective-ops-part-06)  
[Jenkins User Conference 2015](https://www.cloudbees.com/jenkins/juc-2015/)  
[IOS项目的持续集成与管理(译文)](http://www.jianshu.com/p/9ae446d76271)  
[蚂蚁金服AQC持续集成平台漫谈](http://www.oktest.me/site/article/3143.html)  
[针对gitlab Merge Request跑jenkins测试](http://louiseyang.github.io/blog/2015/03/26/zhen-dui-gitlab-merge-requestpao-jenkinsce-shi/)  
[“持续集成”也需要重构------持续集成实践在Cruise开发过程中的演进](http://www.testwo.com/article/434)  
[基于Docker整合开发测试环境, 是不是每个测试人员应该梦想有一套这样的环境？](http://dockone.io/article/342) 

<a name="WEBTEST"></a>
##WEB测试
[Web前端技术栈](https://github.com/unruledboy/WebFrontEndStack)  
[深入详解SQL中的Null](http://blog.jobbole.com/85902/)  
[七牛前端测试实践](http://weibo.com/p/1001603864951990185052?sudaref=toutiao.io)  
[成为一名优秀的Web前端开发者](http://www.infoq.com/cn/news/2015/08/great-front-end-developer)  
[How to Write a Quality Bug Report](http://university.utest.com/writing-quality-bug-reports-and-utest-etiquette/)  
[谷歌Web开发技术变迁史与踩坑史](http://36kr.com/p/533342.html?utm_source=site_search)  
[【web测试】你必须验证的检查点](http://www.sogouqa.com/2015/05/14/%e3%80%90web%e6%b5%8b%e8%af%95%e3%80%91%e4%bd%a0%e5%bf%85%e9%a1%bb%e9%aa%8c%e8%af%81%e7%9a%84%e6%a3%80%e6%9f%a5%e7%82%b9/?utm_source=tuicool)  
[用猫咪图片来记忆HTTP状态码](http://blog.jobbole.com/88450/)  
[使用Selenium测试时必需知道的7件事](http://www.infoq.com/cn/news/2015/07/selenium-7things)  
[Moco 框架以及其在 Web 集成测试的应用](http://www.uml.org.cn/Test/201508043.asp)  
[15个对开发人员有用的Chrome扩展插件](http://info.9iphp.com/15-chrome-extensions-for-developers/)  
[估计很难有比代码改进更不受团队欢迎的事](http://www.newsmth.net/bbstcon.php?board=SoftEng&gid=88109&start=88109&pno=1)  
[专访阿里巴巴毕玄：异地多活数据中心项目的来龙去脉](http://www.infoq.com/cn/articles/interview-alibaba-bixuan)   
[当你在浏览器中输入Google.com并且按下回车之后发生了什么？ ](http://blog.jobbole.com/84870/)  
[浏览器利用框架BeEF测试](http://drops.wooyun.org/tips/9929)   
[WEB开发者应该有哪些必备的技能？](http://info.9iphp.com/essential-skills-every-web-developer-should-have/)  


<a name="MOBILETEST"></a>
##移动测试
[Android测试入门](www.sage42.org/2013/11/25/getting-started-with-android-testing/)  
[【易测试201505】Gradle 安卓打包实战](http://ks.netease.com/blog?id=2050)  
[移动应用测试 - 打造完美应用的秘诀](http://www.infoq.com/cn/articles/mobile-app-testing-the-secret-to-the-perfect-app)  
[Android Studio入门指南](http://blog.csdn.net/wirelessqa/article/details/14222041)  
[Android 常用 adb 命令总结](https://testerhome.com/topics/2565)   
[Html5移动应用风口已经开始来临](http://www.cocoachina.com/game/20150629/12306.html)  
[【CDC翻客】移动端App测试实用指南](http://cdc.tencent.com/?p=6545)  
[Quality Tools for Android](https://github.com/stephanenicolas/Quality-Tools-for-Android)  
[iOS中几种数据持久化方案：我要永远地记住你！](http://www.cocoachina.com/ios/20150720/12610.html)  
[用Robolectric来做Android unit testing](http://www.testwo.com/article/428)    
[iOS应用程序的生命周期](http://www.jianshu.com/p/aa50e5350852)   
[WWDC15 Session笔记 - iOS 9 多任务分屏要点](http://www.cocoachina.com/apple/20150618/12169.html)   
[检测和解决Android应用的性能问题](http://www.csdn.net/article/2015-07-27/2825310/1)   
[Android内存使用分析和程序性能分析 ](http://www.liaohuqiu.net/cn/posts/memory-and-profile-analysis-in-android/)   
[在Android Studio中使用Roboletric和Espresso ](http://codethink.me/2015/05/27/use-robolectric-with-espresso-in-android-studio/)  
[Android应用性能评测调优](http://www.csdn.net/article/2015-06-12/2824949)  
[如何在ios应用开发中提高滚屏的性能](https://code.facebook.com/posts/456535491190613?__tn__=H)  
[国内移动测试服务盘点](http://www.infoq.com/cn/news/2015/06/mobile-testing-service)  
[小强的HTML5移动开发之路](http://blog.csdn.net/column/details/dawanganban-html5.html)  
[How to Use Instruments in Xcode](http://www.raywenderlich.com/23037/how-to-use-instruments-in-xcode)  
[解放双手--Android自动化测试](http://blog.csdn.net/eclipsexys/article/details/45622813)  
[实战Android自动化测试](http://testerhome.com/topics/658)  
[IOS项目的持续集成与管理(译文)](http://www.jianshu.com/p/9ae446d76271)   
[Google的Android性能模式](http://www.infoq.com/cn/news/2015/01/google-android-performance)  
[深入探讨Chrome iOS版测试及发布流程](http://www.infoq.com/cn/articles/testing-releasing-chrome-ios)  
[在Android Studio中进行单元测试和UI测试](http://www.jianshu.com/p/03118c11c199)  
[12 Best Mobile App Testing Frameworks 的简单了解](https://testerhome.com/topics/2416)  
[手机淘宝性能优化](http://mp.weixin.qq.com/s?__biz=MzAxNDEwNjk5OQ==&mid=203376980&idx=1&sn=eabbaa3ab4a4660d39361f92ee4ef3f5&scene=18&scene=5&srcid=10275GQZvsW7RegbPnyKxo4O#rd)  
[【2015 SACC】手机淘宝性能优化全记录](http://mp.weixin.qq.com/s?__biz=MzAxNDEwNjk5OQ==&mid=400169977&idx=1&sn=02881324b62e11adca3a43bc57ddd623&scene=5&srcid=1026xBvxM66LBwoX4g7HAAtD#rd)   
[Android打包的那些事](http://www.jayfeng.com/2015/11/07/Android%E6%89%93%E5%8C%85%E7%9A%84%E9%82%A3%E4%BA%9B%E4%BA%8B/)    
[Android UI：机智的远程动态更新策略](http://bugly.qq.com/blog/?p=732)    
[Android 性能专项之 Memory Monitor 工具](http://www.testwo.com/article/518)    
[移动端图片格式调研](http://blog.ibireme.com/2015/11/02/mobile_image_benchmark/)    



<a name="PERFORMANCETEST"></a>
##性能测试
[Java内存问题 ](http://mp.weixin.qq.com/s?__biz=MjM5NzMyMjAwMA==&mid=207945653&idx=1&sn=9e300f05d20de8dcccdb8c739d6e2422&scene=1&srcid=uFL9E08mmgatx5DVye0N&key=dffc561732c22651cbc40adf49e81520c14987540f04c83255e5c251102748d16bcc9fe9765308c75f71c873a4d451e5&ascene=1&uin=MjU1NDA4Mjk1&devicetype=Windows+7&version=6102002a&pass_ticket=yITCUaUbUCFFrZOk98MTFoL2dfVYWyvog5cREU1nL18%3D)  
[为最佳性能调优Nginx](http://mp.weixin.qq.com/s?__biz=MjM5MTM0NjQ2MQ==&mid=210898312&idx=1&sn=05cfc9b0df0c5816d01db4c15f334cea&scene=1&key=0acd51d81cb052bc4576ecbb18611c9b50fc723d166977da7cee736c2a6339ebf313a9bea76d34afcb9487f544ef21ae&ascene=1&uin=MjU1NDA4Mjk1&devicetype=Windows+7&version=61020019&pass_ticket=jj%2F9wKidZkP23mS63oaHQENez0M82F%2BiAW3UXkLGwig%3D)  
[小白看云，一份非主流测试报告 ](http://mp.weixin.qq.com/s?__biz=MzA5MjA2MjgyNg==&mid=206406218&idx=1&sn=73269f52333b2a043842ca1972ed5f84&scene=5#rd)  
[携程App的网络性能优化实践](http://www.infoq.com/cn/articles/how-ctrip-improves-app-networking-performance)  
[Shift Left性能测试--不一样的测试方法](http://www.uml.org.cn/Test/201410204.asp)    
[2015年度Web框架性能基准测试](http://www.infoq.com/cn/news/2015/04/web-frameworks-benchmark-2015)  
[美团性能分析框架和性能监控平台](http://www.tuicool.com/articles/UFJvee)  
[web性能测试你问我答之测试准备](http://ks.netease.com/blog?id=2216)  
[你可能不知道的jprofiler使用小贴士](http://ks.netease.com/blog?id=2198)  
[Web性能API——帮你分析Web前端性能](http://www.infoq.com/cn/news/2015/06/web-performance-api)  
[NoSQL性能测试白皮书](http://www.infoq.com/cn/articles/nosql-performance-test)    
[Performance Tuning Technique: 几个角度](http://liguanglei.name/blogs/2012/03/11/performance-tuning-technique/)  
[web性能优化：what？why？how](http://www.cnblogs.com/dojo-lzz/p/4591446.html)   
[如何生成每秒百万级别的HTTP请求](http://blog.jobbole.com/87509/)   
[谁在关心toString的性能？ ](http://mp.weixin.qq.com/s?__biz=MjM5NzMyMjAwMA==&mid=207724610&idx=1&sn=da9d46842c9d96952f82e8029a60b899&key=0acd51d81cb052bc17432249dcf7f882e65fb552fd82f26f6d33b79b8bb11b32c9596087dd9d66ef5eab0b504db6507b&ascene=1&uin=MjU1NDA4Mjk1&devicetype=Windows+7&version=61020019&pass_ticket=%2BwUQkVnBradxyFD98eb4WO2wDkJZgA64e5Pj2wxzN2M%3D)  
[腾讯游戏如何使用Docker？ ](http://mp.weixin.qq.com/s?__biz=MjM5MDE0Mjc4MA==&mid=208808439&idx=1&sn=04824ac4c161981d31ee0b02191f28bb&scene=1&srcid=O8tvzXkBHsmwuRlXF6VL&key=dffc561732c22651e96c3ec7c2a3ec46de033289d71e82192ac9aa2156d48c9b4c815deb3d0aa26af55e89bd84055d98&ascene=1&uin=MjU1NDA4Mjk1&devicetype=Windows+7&version=6102002a&pass_ticket=yITCUaUbUCFFrZOk98MTFoL2dfVYWyvog5cREU1nL18%3D)   
[LeakCanary:让内存泄露无所遁形](http://www.liaohuqiu.net/cn/posts/leak-canary/)  
[Google的Android性能模式](http://www.infoq.com/cn/news/2015/01/google-android-performance)  
[阿里无线前端性能优化指南](https://github.com/amfe/article/issues/1)  
[如何彻底解决 "网络延迟 "这个根本性的问题？](http://www.zhihu.com/question/34689035/answer/59675675?utm_source=weibo&utm_medium=weibo_share&utm_content=share_answer&utm_campaign=share_button)  
[参数调优：合理设置线程池，将Nginx性能提升9倍](http://nginx.com/blog/thread-pools-boost-performance-9x/)  
[MySQL性能优化的21个最佳实践和MySQL使用索引](http://www.tuicool.com/articles/6NbiYza)  
[高性能Tomcat：漫谈行走在sendfile之上的Tomcat ](http://jvmplus.duapp.com/blog/view/B143878703)  
[如何从程序优化的角度解释淘宝支付宝的安卓版卡顿？](http://www.zhihu.com/question/30033704/answer/46615625)  
[百度运维部：大型网站的HTTPS实践 - HTTPS 对性能的影响](http://op.baidu.com/2015/04/https-s01a02/)  

<a name="SECURITYTEST"></a>
##安全测试
[超大Cookie拒绝服务攻击](http://blog.jobbole.com/87394/)  
[业务安全漏洞挖掘归纳总结 ](http://drops.wooyun.org/web/6917)  
[“互联网+”时代的移动安全实践](http://www.infoq.com/cn/news/2015/07/mobile-security) 
[用黑客思维做测试---大型项目安全测试思路分享 ](http://www.taobaotest.com/blogs/2559) 

<a name="COURSE"></a>
##实用教程
[Maven 那点事儿 ](http://my.oschina.net/huangyong/blog/194583)  
[LeakCanary 中文使用说明 ](http://www.liaohuqiu.net/cn/posts/leak-canary-read-me/)  
[程序员技术练级攻略](http://coolshell.cn/articles/4990.html)   
[STF 框架之 minicap 工具 ](https://testerhome.com/topics/3115)   
[如何参与一个GitHub开源项目？](http://mp.weixin.qq.com/s?__biz=MjM5MzA0ODkyMA==&mid=200909764&idx=1&sn=5184c6637977a94916508379b194f3e0)  
[深入NGINX：我们如何设计它的性能和扩展性](http://www.cnbeta.com/articles/402709.htm)  
[Gradle Android Plugin 使用手册（中文版）](http://chaosleong.gitbooks.io/gradle-for-android/content/)   
[工具资料片：Linux 工具速查手册，Linux小白必备！](http://http//linuxtools-rst.readthedocs.org/zh_CN/latest/base/index.html)   
[WEB 端批量移动设备管理控制工具STF的环境搭建和运行 ](https://testerhome.com/topics/2988)  

<a name="TOPICS"></a>
##话题
[内测的那些事](http://www.jianshu.com/p/aa47959365ab#)   
[软件测试转型之路](www.infoq.com/cn/articles/transformation-way-software-testing/)  
[怎样成为全栈工程师（Full Stack Developer）？ ](http://www.zhihu.com/question/22420900)  
[通往测试架构师之路（转载）](http://www.taobaotest.com/blogs/2553) 
[从 Code Review 谈如何做技术](www.testwo.com/article/378)  
[访谈：关于持续敏捷交付与服务矩阵](http://www.infoq.com/cn/articles/book-unblock-continuous-agile)    
[Just Say No to More End-to-End Tests(译文)](http://testerhome.com/topics/2457)  
[团队协作的秘诀：为什么小团队效率更高？](http://www.51testing.com/html/51/n-3171551.html)  
[开发是妈妈、产品经理是爸爸、测试是医生、产品是孩子](http://www.testwo.com/article/387)  
[the-present-and-future-of-manual-testing](http://blog.utest.com/2015/07/14/the-present-and-future-of-manual-testing/)  
[有的人喜欢创造世界，他们做了程序员；有的人喜欢拯救世界，他们做了测试员](http://www.zhihu.com/question/20269633)  
[如果软件测试是门艺术，软件测试工程师就是艺术家 －－ 浅析ZStack是如何做智能软件测试](http://mp.weixin.qq.com/s?__biz=MzA4MDQyMDY5OQ==&mid=210641905&idx=1&sn=030ea6052c12030867f8395f3a790e60&scene=2&from=timeline&isappinstalled=0#rd)  
[易评: bug丛生 苹果软件部门肿么了](http://tech.163.com/15/1024/08/B6M917JQ000915BD.html)  
[一共30个！你不得不看的3D Touch使用技巧](http://mt.sohu.com/20151021/n423756358.shtml)





