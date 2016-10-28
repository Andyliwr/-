###李迪康的实习笔记

####笔记信息
+ 实习职位：前端开发实习生
+ 实习地点：[上海浦东新区世纪金融广场一号楼](http://map.baidu.com/?shareurl=1&poiShareUid=7297df8908a17f5203ec01eb) 
+ 实习公司：[东吴在线](www.idwzx.com)
+ 实习时间：2016/05/20 -- 2016/10/28

####实习日记
1. 第一篇

#####东吴在线实习笔记（一）
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;来东吴在线整整一个月了，我每天的工作就是早上打开JIRA看测试组提出的bug以及产品组提出的新功能，然后打开sublime和xshell开始一天的coding生活。以前我喜欢用webstome这样的集成开发环境，后来发现公司都用sublime，自己也不能太格格不入，然后就开始使用sublime。后来发现sublime有些新的插件和快捷键用起来却是很爽，而且最为一名前端开发人员，有太多定制好的工具和代码提示确实不利于提升自己的能力提升。玩git就用git命令行，多简单粗暴，跑服务就用linux，用命令操作电脑才有种黑客的感觉。
![jira](http://b252.photo.store.qq.com/psb?/V132S0cx4g5U7i/t7elfsgmuvBrka3vogSHBQZ4E*QvAAAuRsdO4sHuR6k!/b/dPwAAAAAAAAA&ek=1&kp=1&pt=0&bo=UAWAAlYFgwIDCCg!&su=243061905&sce=0-12-12&rf=2-9)
虽然这一个月的工作没怎么变过，前端部的其他人都跑去开发新系统去了，公司的老工程和keystone建的新网站的前端方面全我一个维护（队长，你也太看得起我了 ）。看我每天待解决的JIRA问题就知道了....

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;问题变化还是很多的，小到简单样式的修改，大到调用各种接口做逻辑的判断。我那会儿上高中的时候就特烦自己做数学题算错，每次算错都想打自己，尼玛都是分啊。不过还好高考的时候数学从第1题对到了第18题，高考也就数学可以看看。然而我成功的把算错的习惯带到了写代码里，还那么自然。

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;前些天04版本上线，本来测试啥的都过了，结果今天一个客户打电话过来说优惠劵不能用。队长找到了我，说我修改的代码出问题了，是不是做了啥不该有的提交。我懵逼了，我每次提价代码前都有git diff看看这些修改是不是自己的，再说我最近也没修改过优惠劵功能啊。然后队长根据我的提交历史，一个个查，搞了一上午终于找到了问题所在---在一次发送ajax请求的时候比较运算符用了“=”而不是“==”，这就导致了代码的功能不是比较而是赋值，所有的标即使就结束了它的状态还是可投资。如果用户这个时候投资将会没有收益，并且钱拿不回来。我也不知到当时是怎么写成了“=”，不过还是谢谢队长帮我找到了错误的位置，及时纠正了。不然这种错误出现在了生产上可能会带来公司的损失。当然还有一个错误不是我导致的，是另一个程序猿在提交代码的时候注释了不该注释的代码。
 
![错误1](http://r.photo.store.qq.com/psb?/V132S0cx2lBdKm/BAGfLKaa9jRV8EmxUzG4U3r0eXs8VwTRTwxTnYcoM4Y!/o/dKwAAAAAAAAA&ek=1&kp=1&pt=0&bo=FQXQABUF0AADACU!&su=143614769&sce=0-12-12&rf=2-9)
![错误2](http://r.photo.store.qq.com/psb?/V132S0cx2lBdKm/aQSV*zWgvGZcK2wAhiNGlqf50DojfcAKvHzISvkJavM!/o/dKwAAAAAAAAA&ek=1&kp=1&pt=0&bo=vwMKAr8DCgIDCC0!&su=1128432129&sce=0-12-12&rf=2-9)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;其实技术不是天生就有的，是人教你的，是在碰壁后领悟到的。人不怕无知，但怕明知无知还是不去努力。写代码不是ctrl+c, ctrl+v，得动脑子去想去理解。在学校的时候你可能随便写个应用就可以做为作业交差，因为没人会检查你的代码。但在公司你做的都是实际的项目，是有人用的，你得考虑方方面面。就像在学校没人会告诉你if判断的时候把变量放在右边，把常量放在左边一样（这样可以避免我之前犯的错误）。最后加油吧！菜鸟，永远不要怀疑自己的梦想，向着它一直跑，有一天你会发现你的努力都是值得的。

2. 第二篇
3. 第三篇
4. 第四篇
5. 第五篇
