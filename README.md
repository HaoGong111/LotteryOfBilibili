# LotteryOfBilibili
B站转发动态抽奖~半自动
***所谓半自动，就是不用自己转赞评以及打开网页了
但是仍需要扫码登录，自己收集抽奖链接放到links.txt中***
### **特点**
+ 采用Python + Selenium模拟人为操作
+ 可以抽官抽，非官抽，固定转赞评，评论内容在四条评论内随机选取，不会重复，避免触发机器验证。
+ 为防止被检测，采用大量等待，每条耗时5-15s之间
### 说在后面
之前好好的cookie登录的功能不知道为什么用不了了，也就是说get_cookie.py这个文件没用了。
每次运行**get_sups.py**程序都会打开一个没有cookie数据的B站首页，**只能自己扫码登录，然后回到程序控制台输入回车（"Enter"一下）**。等以后研究一下怎么自动登录吧。
