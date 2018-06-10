# 资料汇总
目录：
- [Github编辑](##Github编辑)

<a href="##macbook配置">`点这里从头再读一遍`</a>

积累平时的代码
## Github编辑
**名词解释**
    解释(代码引用示例之一)
        `select * from table where a=3 limit 10;`
> 备注信息：
* [Git简易指南](http://www.bootcss.com/p/git-guide/),[图说Git](http://marklodato.github.io/visual-git-guide/index-en.html),[git文件状态和工作区域](https://www.cnblogs.com/polk6/p/git-fileStatus.html)
* ![flow](https://images2017.cnblogs.com/blog/153475/201710/153475-20171013183602293-822234036.png)
* [github官方markdown指南](https://guides.github.com/features/mastering-markdown/ "英文版")
* [github readme语法简介](http://blog.csdn.net/guodongxiaren/article/details/23690801?utm_source=tuicool&utm_medium=referral "跟一般markdown语法不同")
* [MarkDown语法笔记（完整版）](http://blog.csdn.net/witnessai1/article/details/52551362)
* [马克飞象markdown语法在线测试](https://maxiang.io/ "可以在线测试MD语言！")
* [Latex在线调试](https://latexbase.com/)
* [Markdown如何插入目录](https://github.com/ekalinin/github-markdown-toc)
---
***流程图***：
(代码引用示例之二)
```bash
flow
st=>start: Start:>https://www.zybuluo.com
io=>inputoutput: verification
op=>operation: Your Operation
cond=>condition: Yes or No?
sub=>subroutine: Your Subroutine
e=>end
st->io->op->cond
cond(yes)->e
cond(no)->sub->io
```
***
## macbook配置
- 汇总

| **功能** | **方法** | **备注** |
|----|:------:|:---- |
| 终端用户名自定义 | 系统偏好设置->共享->编辑电脑名称  | - |
| 画图工具OmniGraffle+Pro | [6下载地址](http://www.onlinedown.net/soft/87746.htm),[注册码](http://blog.csdn.net/x_focus/article/details/41349623);[7下载地址（含许可证）](https://d11.baidupcs.com/file/890a1f15ffddb6f3c3dab4fdadb47912?bkt=p3-000080d1e545b74de7d8e2a7d8017edaf20c&xcode=ff73db6f0d13a10269722ca0706f4f2d57cb92d68ca6af42837047dfb5e85c39&fid=1610614513-250528-218454854633625&time=1494382563&sign=FDTAXGERLBHS-DCb740ccc5511e5e8fedcff06b081203-HpWzZufk4Ih1Y%2FFYHmSq25HYFyM%3D&to=d11&size=93883767&sta_dx=93883767&sta_cs=11417&sta_ft=dmg&sta_ct=5&sta_mt=0&fm2=MH,Yangquan,Netizen-anywhere,,hunan,ct&newver=1&newfm=1&secfm=1&flow_ver=3&pkey=000080d1e545b74de7d8e2a7d8017edaf20c&sl=83034191&expires=8h&rt=pr&r=580566339&mlogid=3001796489994348567&vuk=1610614513&vbdid=502618811&fin=OmniGraffle+7.2+for+Mac.dmg&fn=OmniGraffle+7.2+for+Mac.dmg&rtype=1&iv=0&dp-logid=3001796489994348567&dp-callid=0.1.1&hps=1&csl=300&csign=SlvW2m2iS5Dhs4IYR0kvCbxY%2BwQ%3D&by=themis)  | 兼容viso，功能强大 |
|Mac Office 2016破解|操作简单，安装完mac office正式版后，下载破解文件，双击锁，就可以|[参考地址](http://www.jianshu.com/p/2172835cfb17)|
|Mac下安装Windows|[Mac电脑上用VMware Fusion安装Windows7](http://jingyan.baidu.com/article/54b6b9c0f8830f2d583b47ce.html)|提前下载vmware+Windows安装包，添加Windows虚拟机后默认无法启动，需要单独指定iso镜像位置，再重启即可|
| 画图工具OmniGraffle+Pro | [6下载地址](http://www.onlinedown.net/soft/87746.htm),[注册码](http://blog.csdn.net/x_focus/article/details/41349623);[7下载地址（含许可证）](http://bbs.feng.com/forum.php?mod=viewthread&tid=10739827)  | 兼容viso，功能强大（【2017-12-6】注：7.4版才能用许可证，7.5以上不行） |
| 安装pip | sudo easy_install pip  | pip直接安装其他工具 |
|软件包管理器|homebrew安装（[参考地址](http://www.itbulu.com/macbook-wget-install.html)）；安装wget：brew install wget|brew安装命令：ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"|
| 翻墙 | 1.有代理ip的直接设置：网络->高级->代理->勾选网页代理+安全网页代理，输入服务器域名及端口，无需填入账号。2.用[lantern下载](https://github.com/getlantern/forum/issues/833) | 备选方案很多 |
|vim颜色显示|1.vim ~/.vimrc,2.添加colorscheme desert;syntax on |vim [sublime颜色主题](http://www.cnblogs.com/fsjohnhuang/p/3911611.html)|
|vim开发环境|[vim IDE部署](https://github.com/wklken/k-vim)|其他主题包，[vim-go开发环境[(http://blog.csdn.net/chosen0ne/article/details/40782991)|
|shell目录颜色显示|开启方法：编辑~/.bash_profile,增加：export CLICOLOR=1;export LSCOLORS=exfxaxdxcxegedabagacad|注：[如何在shell字符串中显示彩色字符？](http://7938217.blog.51cto.com/7928217/1651807/),显示白色：echo -e "\033[37m white \033[0m"|
|mac免密码远程登录|使用ssh创建rsa公钥密码。基本步骤：*   1.ssh-keygen生成密钥(ssh-keygen -t rsa)  *   2.复制密钥文件到远程机器(scp ~/.ssh/id_rsa.pub wangqiwen@ip.com:/home/wangqiwen/.ssh) *   3.登录远程机器，修改文件权限(cd ~/.ssh && cat id_rsa.pub >> authorized_keys; chmod 644 authorized_keys;chmod 700 ~/.ssh/)|参考地址：[mac无密码登录](http://blog.csdn.net/cdut100/article/details/70277091),[Linux 下 SSH 命令实例指南](https://linux.cn/article-3858-1.html),[菜鸟学Linux命令:ssh命令 远程登录](https://blog.csdn.net/sky786905664/article/details/60580594)|
|ssh会话管理|[ssh配置文件实现别名快捷登录](http://blog.csdn.net/newjueqi/article/details/47293897)||
|chrome浏览器中右键失灵|双指触碰链接时，并未弹出右键菜单，而是“图片另存为”|解决办法：这是由于chrome浏览器上开启了鼠标手势，造成干扰，关闭或删除插件即可|
|image not recognized|dmg文件无法安装，原因：文件损坏，dmg权限不允许任意来源的包；换浏览器|如何开启任意来源包？sudo spctl --master-disable|
|redis安装|brew install redis|使用方法：启动服务，redis-server，连接服务：redis-cli|
|mac mail客户端设置|连接163时，需要先去163邮箱开启pop3/imap选项，通过手机验证码设置连接密码；mail终端配置时填入的密码是连接密码（非登录密码！）|wqw3721|
|安装虚拟机|vmware安装，下载地址|vmware fusion 8激活码：FY75A-06W1M-H85PZ-0XP7T-MZ8E8，ZY7TK-A3D4N-08EUZ-TQN5E-XG2TF，FG1MA-25Y1J-H857P-6MZZE-YZAZ6|
|Mac下运行Windows软件|（1）boot camp安装Windows虚拟机（win 10文件过大）；（2）安装wine|步骤：（1）brew cask install xquartz（2）brew install wine|
|java|官方下载地址：http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html|优先使用绿色版（tar.gz，非二进制的rpm）。环境变量配置方法：修改/etc/profile文件，在文件的最下边加入下边的文本：export JAVA_HOME=/opt/jdk1.7; export CLASSPATH=.:$JAVA_HOME/lib/rt.jar:$JAVA_HOME/lib/dt.jar:$JAVA_HOME/lib/tools.jar; export PATH=$JAVA_HOME/bin:$PATH|
|Web服务|[Mac OS 启用web服务](http://www.jianshu.com/p/d006a34a343f),[简网教程](http://www.jianshu.com/p/d006a34a343f)||
|linux 服务器mail|mail command not found|解决方法：sudo yum install mailx;echo "test" (竖线) mail -s "content" wangqiwen@p1.com|
|linux下安装http服务|安装httpd|1.yum install httpd -y 2.随系统启动:chkconfig httpd on 3.开启Apache:service httpd start|
|terminal下如何开启应用？|用open命令开启（open .用finder打开当前位置目录；<font size=4 color='res'>open file自动调用默认程序打开文件;</font>say hello语音说话），可以传参，备注：放到别命中，alias view='open /Applications/Preview.app'或alias edit='open /Applications/Sublime\ Text.app'|open /Applications/Sublime\ Text.app README.md|
|shell美化|[Oh My ZSH!](http://ohmyz.sh/)|安装：sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"|
|刻盘|[Etcher](https://etcher.io/)全平台工具|操作过程极其简单|
|移动硬盘无法写入|原因：mac不支持ntfs格式，需要安装特殊软件：[ntfs for mac](http://www.ntfsformac.cn/xiazai.html)||
|mac显示当前路径|命令：defaults write com.apple.finder _FXShowPosixPathInTitle -bool YES|顶栏出现路径，还可以点击定位到子目录|
|mac当前位置打开终端|命令：https://jingyan.baidu.com/article/ce436649281a293773afd3d8.html||
|mac下excel打开csv中文乱码|原因是mac底下中文一律utf8编码，而excel文档默认中文是gbk编码，需要单独设置下才行。http://blog.csdn.net/wqdwin/article/details/76058154|亲测有效|
|【2018-1-11】|[网易mumu模拟器](http://mumu.163.com/)||
|【2018-1-11】|[mac下安装adb，调试Android](https://www.jianshu.com/p/1b3fb1f27b67)|brew cask install android-platform-tools|
---
```shell
wqw:code wangqiwen$ git clone https://github.com/p1cn/backend.git
Cloning into 'backend'...
Username for 'https://github.com': wqw547243068
Password for 'https://wqw547243068@github.com':
remote: Invalid username or password.
fatal: Authentication failed for 'https://github.com/p1cn/backend.git/'
```
原因：Github没有fork项目代码，或没加所在机器的sshkey（settings->deplot keys）

## python使用mysql方法
### 安装方法
mac下安装MySQL-python

要想使python可以操作mysql，就需要MySQL-python驱动，它是python 操作mysql必不可少的模块。
- [下载地址](https://pypi.python.org/pypi/MySQL-python/)
- 下载MySQL-python-1.2.5.zip 文件之后直接解压。
- 进入MySQL-python-1.2.5目录:
```shell
python setup.py install
```
### 连接mysql
shell 代码，shell脚本中调用sql脚本
```shell
#mysql初始化-shell
mysql=/usr/local/mysql/bin/mysql
$mysql -uroot -pwqw  < init.sql
```
或者shell脚本中直接执行sql
```shell
mysql=/usr/local/mysql/bin/mysql
$mysql -uroot -p123456 <<EOF  
source /root/temp.sql;  
select current_date();  
delete from tempdb.tb_tmp where id=3;  
select * from tempdb.tb_tmp where id=2;  
EOF
```
- [PostgreSQL学习笔记](http://www.cnblogs.com/stephen-liu74/archive/2012/06/08/2315679.html)

## 爬虫
### python抓取链接二手房数据
- [链家二手房数据分析](https://zhuanlan.zhihu.com/p/25132058)
- [scrapy爬链家成都房价并可视化](https://github.com/happyte/buyhouse)
- [抓知乎爬虫](http://www.csuldw.com/2016/11/05/2016-11-05-simulate-zhihu-login/)

## json使用

### shell中使用json
- #[2016-12-31] shell中使用json
- 安装：
> pip install git+https://github.com/dominictarr/JSON.sh#egg=JSON.sh

- 使用：
```shell
echo '{"a":2,"b":[3,6,8]}' |JSON.sh
```
详情参考：https://github.com/dominictarr/JSON.sh

## 可视化
### 地图数据可视化
- [地图汇](http://www.dituhui.com/)
- [5min上手写echarts第一个图标](http://echarts.baidu.com/echarts2/doc/start.html),[echarts如何从json文件读数据？](http://bbs.csdn.net/topics/392042291)
- 【2017-7-30】Google开发的数据可视化web工具[Facet Dive](https://pair-code.github.io/facets/)，【2018-3-13】可以嵌入jupyter notebook做特征工程可视化分析, 安装方法参考[PAIR-CODE](https://github.com/PAIR-code/facets),[Google AI](https://ai.google/pair)
- ![facets](https://github.com/PAIR-code/facets/blob/master/img/dive-census.png)
- [北大可视化](http://vis.pku.edu.cn/wiki/start)
- 词云生成[图悦](http://www.picdata.cn/)
- [北大可视化](http://vis.pku.edu.cn/wiki/start)
- [2018-2-28] OLAP可视化分析工具,[官网](https://www.meteorite.bi/products/saiku),[saiku社区版](https://community.meteorite.bi/)，[安装方法](http://www.kanhaige.com/post-5.html),[简介]()，[Kylin, Mondrian, Saiku系统的整合](https://tech.youzan.com/kylin-mondrian-saiku/?utm_source=tuicool&utm_medium=referral),[saiku安装教程](http://blog.csdn.net/longshenlmj/article/details/17359645)
- ![saiku](http://www.joyofdata.de/blog/wp-content/uploads/2014/06/data-insights.png)
- 【2018-3-5】[python+echarts给你的数据做美颜](https://zhuanlan.zhihu.com/p/24952863),[pycharts](https://github.com/pyecharts/pyecharts)安装，[官方文档](http://pyecharts.org/#/zh-cn/prepare)，[jupyter notebook中使用pycharts](https://zhuanlan.zhihu.com/p/28157126)，[github代码完整示例](https://github.com/pyecharts/pyecharts-users-cases/blob/master/notebook-users-cases/notebook-user-cases.ipynb)，效果示例:
![echarts](https://pic4.zhimg.com/v2-5cc223125d7b0a0e051cbc91e0a19e07_b.gif)
## 学习资料
### 学习技巧
- [@爱可可-爱生活(新浪微博)](http://weibo.com/fly51fly?is_search=0&visible=0&is_all=1&is_tag=0&profile_ftype=1&page=2#_rnd1501558283451)：
>
 - 互联时代怎么阅读？
 - 读书重在结构生长，形成扎实的支撑；
 - 碎片阅读重在视野的纳新和扩展，开枝散叶；
 - 思考重在提炼和关联，勾画错综的经脉。
 - 学习就是如此，由外而内，无广不精，无博不深，但能坚持必有所成。
 - 网络阅读的最佳实践，不在“取”，在“舍”，知舍才能知关键，料不在多，有感悟一二足矣。
---
- 费曼技巧：通过向别人清楚地解说一件事，来确认自己真的弄懂了这件事。参考：[号称终极快速学习法的费曼技巧，究竟是什么样的学习方法？](https://www.zhihu.com/question/20576786)
-
![费曼技巧](https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1505214981844&di=c9a85fee49f3eba5dbad2f575d260e69&imgtype=0&src=http%3A%2F%2Fs1.sinaimg.cn%2Fmw690%2F001UzQQOgy72rDwKKBy40)
---
- 学习金字塔

![学习金字塔](https://gss0.baidu.com/9fo3dSag_xI4khGko9WTAnF6hhy/zhidao/wh%3D600%2C800/sign=dae5bdf00ef79052ef4a4f383cc3fbf2/78310a55b319ebc44d04b87a8526cffc1f1716d1.jpg)
### 数学基础
- [可微可导可积连续之间的关系](http://blog.csdn.net/huxiaokang1234/article/details/52550999)
- ![关系图](http://img0.imgtn.bdimg.com/it/u=4072625409,2144649604&fm=214&gp=0.jpg)
- [如何通俗讲解放射变换？](https://www.zhihu.com/question/20666664)
_ [在线几何作图GeoGebra](https://www.geogebra.org/apps/)（源自 [马同学高等数学](http://www.matongxue.com/madocs/244.html)）
- [3Blue1Brown](www.patreon.com/3blue1brown)出品（接受捐助）：[线性代数的本质-Essence of Linear Algebra-视频教程](http://www.3blue1brown.com/)，[Bilibili上《线性代数本质》双语视频教程](http://www.bilibili.com/video/av6731067/).类似视频还有微积分本质.[制作教学视频的代码](https://github.com/3b1b/manim)
- 【2017-12-23】神经网络原理视频（十分直观形象），包含3部分，[直观理解反向传播](https://www.bilibili.com/video/av16577449/)
- ![](http://www.tensorflownews.com/wp-content/uploads/2017/11/1511693406697-678x381.jpg)
- [行列式的本质（马同学高等数学）](http://www.matongxue.com/madocs/247.html).《数学拾遗》[英文版百度云地址](https://pan.baidu.com/share/link?shareid=1204761446&uk=2416092239&fid=2111748288).
- [矩阵分解(加法偏)](https://mp.weixin.qq.com/s?src=3&timestamp=1498919864&ver=1&signature=lwM3ouw-FlaVYwhol06JImHUQz-gJ00kBAYkssdiD3pSLwOS48Mv9ntL97readD8AZrXS2q0D28PegS*LE6Cxp88Hy8RPP9VLGdWA29zARcLVFuwHbJJl8SPtB*dq7njgt7suMGouSV-FP5b9BlFeWtQ8XNSO9aJyrh8mBJNYS8=),[矩阵分解(乘法篇)，很不错](https://mp.weixin.qq.com/s?src=3&timestamp=1498919864&ver=1&signature=lwM3ouw-FlaVYwhol06JImHUQz-gJ00kBAYkssdiD3q4iNXi-7lf9GzKeq2CvP0yAofBNF7OoCG21M1YDLrrhHHA15K4rrKyP1FFPjQtmNGv0yv5IFeA7LmvuBiea1Xrsa79Gf8c6IT1JiTdra-mU8JNHdj0zp-lYaJUUfp0CHw=)
- [如何通俗的解释放射变换](http://www.matongxue.com/madocs/244.html),[生动讲解矩阵的空间变换](http://blog.csdn.net/a396901990/article/details/44905791)：平移、缩放、旋转、对称（xy或原点）、错切、组合。[行列式的本质是什么？---万门大学童哲的解释](https://www.zhihu.com/question/36966326/answer/70687817):行列式就是线性变换的放大率！理解了行列式的物理意义，很多性质你根本就瞬间理解到忘不了！

![Essence of Linear Algebra](https://pic4.zhimg.com/v2-f0b763934f02eda66a5eef93cc47eaa3_b.jpg)
- 行列式：行列式，记作 det(A)，是一个将方阵 A 映射到实数的函数。行列式等于矩阵特 征值的乘积。行列式的绝对值可以用来衡量矩阵参与矩阵乘法后空间扩大或者缩小 了多少。如果行列式是 0，那么空间至少沿着某一维完全收缩了，使其失去了所有的 体积。如果行列式是 1，那么这个转换保持空间体积不变
- 【2017-11-24】遇见数学：[图解线性代数](https://www.toutiao.com/i6490094296459379213/)
- [六大概率分布](http://www.csuldw.com/2016/08/19/2016-08-19-probability-distributions/)
- [最优化算法-避开鞍点](http://www.csuldw.com/2016/07/10/2016-07-10-saddlepoints/)
- [频率学派与贝叶斯学派之争](http://www.cnblogs.com/549294286/archive/2013/04/08/3009073.html)：[知乎网友解释](https://www.zhihu.com/question/20587681/answer/21294468),频率学派最先出现，疯狂打压新生的贝叶斯学派，贝叶斯很凄惨，就跟艺术圈的梵高一样，死后的论文才被自己的学生发表，经过拉普拉斯之手发扬光大，目前二派就像华山派的剑宗和气宗。频率学派挺煞笔的，非得做大量实验才能给出结论，比如你今年高考考上北大的概率是多少啊？频率学派就让你考100次，然后用考上的次数除以100。而贝叶斯学派会找几个高考特级教师对你进行一下考前测验和评估，然后让这几个教师给出一个主观的可能性，比如说：你有9成的把握考上北大。
   - 这个区别说大也大，说小也小。（1）往大里说，世界观就不同，频率派认为参数是客观存在，不会改变，虽然未知，但却是固定值；贝叶斯派则认为参数是随机值，因为没有观察到，那么和是一个随机数也没有什么区别，因此参数也可以有分布，个人认为这个和量子力学某些观点不谋而合。（2） 往小处说，频率派最常关心的是似然函数，而贝叶斯派最常关心的是后验分布。我们会发现，后验分布其实就是似然函数乘以先验分布再normalize一下使其积分到1。因此两者的很多方法都是相通的。贝叶斯派因为所有的参数都是随机变量，都有分布，因此可以使用一些基于采样的方法（如MCMC）使得我们更容易构建复杂模型。频率派的优点则是没有假设一个先验分布，因此更加客观，也更加无偏，在一些保守的领域（比如制药业、法律）比贝叶斯方法更受到信任。
   - 频率 vs 贝叶斯 =   P(X;w)  vs  P(X|w) 或 P(X,w)
   - 频率学派认为参数固定，通过无数字实验可以估计出参数值——客观；
   - 贝叶斯学派认为参数和数据都是随机的，参数也服从一定的分布，需要借助经验——主观
- [统计学基础知识【脑图笔记】](http://www.cnblogs.com/xiaofeng1234/p/5987845.html)
- 大矩阵相乘：[分布式版本](http://weibo.com/ttarticle/p/show?id=2309404091643656571557),[MapReduce实现矩阵相乘](http://blog.csdn.net/jiangsanfeng1111/article/details/51025744)，[Hadoop实现大矩阵相乘之我见](http://www.cnblogs.com/eczhou/p/3340731.html)
 - A大B小(内存受限)
 ![图](http://images.cnitblog.com/blog/310680/201309/26133812-99b31a08aa934015a11a19cc178713db.png)
 - AB都大(内存受限)
 ![图](http://images.cnitblog.com/blog/310680/201309/26133859-83d01098a7ac4192a7ff02fbaacb2369.png)
 - 不受内存限制（最小粒度）
 ![图](http://images.cnitblog.com/blog/310680/201309/26134115-f5041d455fbe4ef98e3653a77cb31774.png)
- Colah的[Visual Information Theory](http://colah.github.io/posts/2015-09-Visual-Information/)，[中文翻译](http://blog.csdn.net/xtydtc/article/details/52265952)
- 【2017-11-24】遇见数学，[图解普林斯顿微积分系列](https://www.toutiao.com/i6489560900662460942/)
![图](http://p9.pstatp.com/large/3b110004d8b47a0abc46)
### 计算机基础
- 【2018-5-1】[数据结构总结篇](http://lib.csdn.net/article/datastructure/11369)_
- 排序算法总结：[视觉感受常见排序算法](http://blog.jobbole.com/11745/)
![对比](http://hi.csdn.net/attachment/201105/24/0_1306225542srVx.gif)
- 【2017-8-1】排序算法可视化对比[Sorting Algorithms Animations](https://www.toptal.com/developers/sorting-algorithms/),[日本程序猿做的排序动画](http://jsrun.it/norahiko/oxIy)，[舞动的排序算法【舞蹈视频】](http://v.youku.com/v_show/id_XNTA3NDUwODA4.html?spm=a2h0j.8191423.module_basic_relation.5~5!2~5~5!3~5~5~A)
- 【2018-4-28】算法可视化网站[Visualgo](https://visualgo.net/en),包含动画演示+伪代码，[旧金山大学的数据结构算法可视化](https://www.cs.usfca.edu/~galles/visualization/Algorithms.html)
- [海量数据处理算法总结【超详解】](http://www.cnblogs.com/ECJTUACM-873284962/p/6910842.html)
- [水库抽样算法精简](http://blog.csdn.net/u012397189/article/details/52181005),空间亚线性算法
![水库抽样](http://s11.sinaimg.cn/mw690/005yGsbEty6QDWko4gq0a&690)
- [2017-9-19]视频集合：[内存原理解析](http://www.365yg.com/group/6467022800149283342/),[CPU缓存原理解析](http://www.365yg.com/group/6467021466209616397/),[TCP,UDP协议原理对比](http://www.365yg.com/group/6467022804800766477/),[IPv4,IPv6原理解析](http://www.365yg.com/group/6467021492105249293/)，[代理服务器原理解析](http://www.365yg.com/group/6467022795812373005/)，[集线器-交换机-路由器区别](http://www.365yg.com/group/6467021483385291277/)，[DNS域名解析](http://www.365yg.com/group/6467021479107101197/)，[超线程原理解析](http://www.365yg.com/group/6467021487722201614/),[磁盘碎片原理解析](http://www.365yg.com/group/6467021470504583693/)
- 【2018-3-13】松果云科普：动画解释，[详解硬盘工作原理](https://www.365yg.com/a6524897664687931911)，[详解显卡工作原理：GPU和CPU的区别](https://www.365yg.com/i6525769921438155272)
### 分布式计算
- [flume+kafka+hdfs+storm组合](http://www.aboutyun.com/thread-6855-1-1.html)
### 推荐系统
- [项量：关于LDA，pLSA，SVD和Word2vector的一些看法](https://zhuanlan.zhihu.com/p/21377575)：
  - SVD算法是指在SVD的基础上引入隐式反馈，使用用户的历史浏览数据、用户历史评分数据、电影的历史浏览数据、电影的历史评分数据等作为新的参数
  - LSA最初是用在语义检索上，为了解决一词多义和一义多词的问题,将词语（term）中的concept提取出来，建立一个词语和概念的关联关系（t-c relationship），这样一个文档就能表示成为概念的向量。这样输入一段检索词之后，就可以先将检索词转换为概念，再通过概念去匹配文档。在实际实现这个思想时，LSA使用了SVD分解的数学手段.x=T*S*D
  - PLSA和LSA基础思想是相同的，都是希望能从term中抽象出概念，但是具体实现的方法不相同。PLSA使用了概率模型，并且使用EM算法来估计P（t|c）和P（c|d）矩阵.LDA是pLSA的generalization：一方面LDA的hyperparameter设为特定值的时候，就specialize成pLSA了
  - NMF：一种矩阵分解，要求输入矩阵元素非负，目标和 SVD 一样。
  - pLSA：SVD 的一种概率解释方法——要求矩阵元素是非负整数。LDA：pLSA 加上 topics 的 Dirichlet 先验分布后得到的 Bayesian model，数学上更漂亮。为什么是 Dirichlet 先验分布，主要是利用了 Dirichlet 和 multinomial 分布的共轭性，方便计算。
- [从item-base到svd再到rbm，多种Collaborative Filtering(协同过滤算法)从原理到实现](http://blog.csdn.net/dark_scope/article/details/17228643)
- 案例分享：[世纪佳缘推荐系统经验分享](http://www.csdn.net/article/2015-02-15/2823976)
- 《推荐系统实践》[阅读笔记：LFM模型、图模型、slop one和SVD算法](http://www.aiuxian.com/article/p-952427.html)
- 实时推荐系统
 - [实时推荐系统的三种方式](http://www.jianshu.com/p/356656ce2901)
### 机器学习
#### 特征工程
- 江湖名言：<font color=#0099ff size=5 face="黑体">数据和特征决定了机器学习的上限，而模型和算法只是逼近这个上限而已</font>
- [知乎：特征工程到底是什么](https://www.zhihu.com/question/29316149)
 - [使用sklearn做特征工程](http://www.cnblogs.com/jasonfreak/p/5448385.html)
 - [使用python进行描述性统计](http://www.cnblogs.com/jasonfreak/p/5441512.html)
 - [使用sklearn优雅的进行数据挖掘](http://www.cnblogs.com/jasonfreak/p/5448462.html)
 - 使用sklearn进行集成学习:[理论](http://www.cnblogs.com/jasonfreak/p/5657196.html),[实践](http://www.cnblogs.com/jasonfreak/p/5720137.html)
![fe](http://images2015.cnblogs.com/blog/927391/201606/927391-20160628112051062-1290708859.jpg)
 特征工程常用方法：
![常用方法](https://pic3.zhimg.com/20e4522e6104ad71fc543cc21f402b36_r.png)
- 不平衡数据集如何处理？研究表明，在某些应用下，1∶35的比例就会使某些分类方法无效，甚至1∶10的比例也会使某些分类方法无效。
 - [分类问题中不平衡数据集的解决方案](https://www.52ml.net/16294.html)，正负样本玄虚
 - 1.过抽样：简单赋值负样本——最常用，容易过拟合，SVM模型里用途不大
 - 2.欠抽样：随机减少正样本——造成信息丢失
 - 3.算法层面：（1）重构训练集，按错分代价对训练集重构（2）代价敏感函数，大样本高代价，小样本低代价
 - 4.特征选择：选取有区分度的特征
 - [解决真实世界的问题：如何在不平衡数据集上使用机器学习](https://www.52ml.net/17957.html?utm_source=tuicool&utm_medium=referral)
 ![图解](https://www.52ml.net/wp-content/uploads/2016/08/4ffce04d92a4d6cb21c1494cdfcd6dc1-7.jpg)
 - 【2017-12-25】知乎：[机器学习中的测试机和训练集如何划分？](https://www.zhihu.com/question/59683792)，与时间强相关的问题需要按照时间划分，否则（大部分ML问题）应该随机抽样，与时间无关（应用了未来函数）。随机划分保证了训练集和测试集的历史场景是类似的，就类似于这些数据都是同一台机器同一时期产生的两类数据集。这样计算出的准确率能最真实的反映模型对这段数据学习的效果
 - 【2018-4-8】[【(Google)机器学习全面入门(96页)】《Jason's Machine Learning 101》by Jason Mayes]
(https://docs.google.com/presentation/d/1kSuQyW5DTnkVaZEjGYCkfOxvzCqGEFzWBy4e9Uedd9k/preview?slide=id.g168a3288f7_0_58), ppt展示google机器学习+深度学习中的应用，含视频
- 【2018-4-15】Google机器学习43条军规，[中文版](https://blog.csdn.net/np4rHI455vg29y2/article/details/79341774)，[原版pdf](http://martin.zinkevich.org/rules_of_ml/rules_of_ml.pdf)
-【2018-5-4】SAP的梁劲（Jim Liang）整理的[从基础概念到数学公式，这是一份520页的机器学习笔记（图文并茂）](https://mp.weixin.qq.com/s/Pxww9VJY8PKfoZ2vGECqUw)，[百度云地址](https://pan.baidu.com/s/1tNXYQNadAsDGfPvuuj7_Tw#list/path=%2F&parentPath=%2FJim%2FmyPresentation)，[Dropbox地址](https://www.dropbox.com/sh/c3l3zrhvbxjsso3/AAD8vI21DW81c7gatikRlv6Fa?dl=0)
- 【2018-5-18】《[Random Forests - What, Why, And How](https://nyhackr.blob.core.windows.net/presentations/Random-Forests-What-Why-and-How_Andy_Liaw.pdf)》by Andy Liaw, 随机森林解析
#### 算法总结
- 微软-ML算法指南：[pdf版下载地址](https://docs.microsoft.com/en-us/azure/machine-learning/machine-learning-algorithm-cheat-sheet)
![微软算法](微软-ML算法指南.png)
 - [详细讲解](How to choose algorithms for Microsoft Azure Machine Learning)
- [scikit-learn官方总结](http://scikit-learn.org/stable/tutorial/machine_learning_map/index.html#)，Scikit-learn Cookbook:[英文本](https://www.packtpub.com/big-data-and-business-intelligence/scikit-learn-cookbook),[中文译本](https://www.gitbook.com/book/wizardforcel/sklearn-cookbook/details)，[MarkDown格式](http://git.oschina.net/wizardforcel/sklearn-cb/blob/master/SUMMARY.md)
![算法对比](http://scikit-learn.org/stable/_static/ml_map.png)
- 【2017-12-20】[Dlib机器学习指南](https://www.cnblogs.com/oloroso/p/6607888.html),方法选择：![svg图](http://dlib.net/ml_guide.svg),中文版,![中文指南](http://images2015.cnblogs.com/blog/693958/201703/693958-20170323225348940-2043166934.png)
- 算法对比
《统计学习方法》总结：
- ![算法总结](https://img3.doubanio.com/view/page_note/large/public/p27390874-1.jpg)

- [xgboost: 速度快效果好的boosting模型](https://cos.name/2015/03/xgboost/)
- 最优化：各种优化算法对比
- ![表达式](https://raw.githubusercontent.com/SwordYork/simplified-deeplearning/master/sgd-comparison/figures/relation.png)
- 最优化：各种优化算法对比
- ![各种优化算法对比](http://cs231n.github.io/assets/nn3/opt2.gif)
- 【2017-8-30】[SGD comparision](https://blog.slinuxer.com/2016/09/sgd-comparison)
- ![优化算法对比](http://cs231n.github.io/assets/nn3/opt1.gif)
- [SGD，Adagrad，Adadelta，Adam等优化方法总结和比较](http://ycszen.github.io/2016/08/24/SGD%EF%BC%8CAdagrad%EF%BC%8CAdadelta%EF%BC%8CAdam%E7%AD%89%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95%E6%80%BB%E7%BB%93%E5%92%8C%E6%AF%94%E8%BE%83/),[An overview of gradient descent optimization algorithms](http://ruder.io/optimizing-gradient-descent/)
- [为什么更偏爱随机梯度下降](https://zhuanlan.zhihu.com/p/28060786)
- 【2017-7-31】[10686 一次 CTC-RNN 调参经历](https://zhuanlan.zhihu.com/p/28133530)
- ![网格搜索](https://pic3.zhimg.com/v2-88f640c13e27402154eb8e93e50468a2_b.png)
- 【2018-3-5】[google 出品的机器学习速成课程](https://developers.google.cn/machine-learning/crash-course/)，基于tensorflow
- 谷歌新出的jupyter开发环境，免费试用GPU，试用谷歌账号即可，[google colaboratory](http://g.co/colab)，[colaboratory简介](https://colab.research.google.com/notebooks/welcome.ipynb#scrollTo=atsEmPJiubuX)
#### 异常检测
- IsolationForest。欺诈等是一系列的异常孤立点，而IsolationForest则是检测这类孤立点的一个有效算法。无需样本标记、线性时间复杂度。一般情况下要比OneClasSVM等表现要好。尤其是对非高斯分布的样本空间。
- 【2017-7-31】[反欺诈(Fraud Detection)中所用到的机器学习模型有哪些？](https://www.zhihu.com/question/30508773/answer/205831957)：
 - （1）可视化：相关矩阵+多维尺度变换
 - （2）算法模型：时序相关（时间序列分析）、时序无关（无监督学习Isolation Forest、监督学习one-class SVM、统计学密度估计）
#### 机器学习经验总结
- [Google机器学习经验总结](http://martin.zinkevich.org/rules_of_ml/rules_of_ml.pdf)
- [pluskid总结的SVM系列文章](http://blog.pluskid.org/?page_id=683)（浙大计算机，MIT博士，跟陈天奇和李沐一块做过Mxnet）
- 【2017-8-22】【非常好的web讲解】[可视化机器学习（决策树讲解）](http://www.r2d3.us/%E5%9B%BE%E8%A7%A3%E6%9C%BA%E5%99%A8%E5%AD%A6%E4%B9%A0/)
- 【2017-8-22】剑桥大学的书籍[Introduction to Machine Learning](http://alex.smola.org/drafts/thebook.pdf)
- 【2017-8-22】Machine Learning is Fun!系列教程。[Part 3:Deep Learning and Convolutional Neural Networks](https://medium.com/@ageitgey/machine-learning-is-fun-part-3-deep-learning-and-convolutional-neural-networks-f40359318721),[中文翻译：第三章:图像识别【鸟or飞机】？深度学习与卷积神经网络](https://zhuanlan.zhihu.com/p/24524583)
- 【2017-9-2】维数灾难：精华，[维数诅咒](http://www.mamicode.com/info-detail-645884.html),原文[The Curse of Dimensionality in classification](http://www.visiondummy.com/2014/04/curse-dimensionality-affect-classification/)https://software.intel.com/en-us/ai-academy/students/kits/machine-learning-101
- 【2017-12-9】[Intel AI机器学习课程资料]()
- 【2017-12-22】[图解机器学习（含动图）](https://my.oschina.net/taogang/blog/1544709)
- 【2017-12-22】[knn原理及代码实现（含kd树）](http://www.hankcs.com/ml/k-nearest-neighbor-method.html)，[详解kd树](http://blog.csdn.net/silangquan/article/details/41483689)
- ![kd-tree](http://img.blog.csdn.net/20141125162151359)
- 【2018-3-23】[概率图模型体系：HMM、MEMM、CRF](https://zhuanlan.zhihu.com/p/33397147),精华
#### 流形学习
- 什么是流形学习？传统的机器学习方法中，数据点和数据点之间的距离和映射函数f都是定义在欧式空间中的，然而在实际情况中，这些数据点可能不是分布在欧式空间中的，因此传统欧式空间的度量难以用于真实世界的非线性数据，从而需要对数据的分布引入新的假设。流形(Manifold)是局部具有欧式空间性质的空间，包括各种纬度的曲线曲面，例如球体、弯曲的平面等。流形是线性子空间的一种非线性推广。参考[流形学习的简单介绍](https://jlunevermore.github.io/2016/06/25/43.%E6%B5%81%E5%BD%A2%E5%AD%A6%E4%B9%A0/)
- 流形学习：本质上，流形学习就是给数据降维的过程。这里假设数据是一个随机样本，采样自一个高维欧氏空间中的流形（manifold），流形学习的任务就是把这个高维流形映射到一个低维（例如2维）的空间里。流形学习可以分为线性算法和非线性算法，前者包括主成分分析（PCA）和线性判别分析（LDA），后者包括等距映射（Isomap），拉普拉斯特征映射（LE）等。流形学习可以用于特征的降维和提取，为后续的基于特征的分析，如聚类和分类，做铺垫，也可以直接应用于数据可视化等。注：摘自[集智百科流形学习（优质，包含代码及案例）](http://wiki.swarma.net/index.php/%E6%B5%81%E5%BD%A2%E5%AD%A6%E4%B9%A0)。
 - 拟合线性的流形学习模型：LLE, LTSA, Hessian LLE, 和Modified LLE
 - 拟合非线性的流形学习模型：Isomap，MDS和Spectral Embedding
 - 效果示意如下：![降维效果](http://wiki.swarma.net/images/thumb/a/ad/Manifoldlearning_figure_1.png/800px-Manifoldlearning_figure_1.png)
 - [浙大何晓飞的流形学习ppt](http://www.cad.zju.edu.cn/reports/%C1%F7%D0%CE%D1%A7%CF%B0.pdf),讲的很清楚，全面，最佳资料
#### 降维
 常见的pca属于无监督{【2017-12-28】【精华】[PCA可视化讲解](http://setosa.io/ev/principal-component-analysis/),马尔科夫链可视化讲解[Markov Chains](http://setosa.io/ev/markov-chains/)}，lda有监督,常用降维方法如下图。
 ![常用降维方法脑图](http://img.blog.csdn.net/20150522194801297)
 - t-SNE是深度学习大牛Hinton和lvdmaaten（他的弟子？）在2008年提出的，lvdmaaten对t-SNE有个主页介绍：[tsne](http://lvdmaaten.github.io/tsne/),包括论文以及各种编程语言的实现,t-SNE是非线性方法，非常适用于高维数据降维到2维或者3维，进行可视化,具体参考:[t-SNE完整笔记（优质,含Python代码实现）](http://www.datakit.cn/blog/2017/02/05/t_sne_full.html)，[t-SNE原理及python实现](http://blog.csdn.net/jyl1999xxxx/article/details/53138975).t-SNE交互体验：[How to Use t-SNE Effectively](https://distill.pub/2016/misread-tsne/)；[t-SNE CSV web demo](http://cs.stanford.edu/people/karpathy/tsnejs/csvdemo.html)，可以直接输入csv数据
 - ![t-sne](http://ac-cf2bfs1v.clouddn.com/fe6782ce2f1b7875.gif)
 - [2018-1-29][从SNE到t-SNE再到LargeVis](https://bindog.github.io/blog/2016/06/04/from-sne-to-tsne-to-largevis/),t-SNE原理最佳资料，深刻讲解
 - 其他方法参考[流形学习](http://blog.csdn.net/zhulingchen/article/details/2123129),[MNIST数据集降维可视化效果展示(经典)](http://colah.github.io/posts/2014-10-Visualizing-MNIST/). [Google高维数据交互可视化Web页面](http://projector.tensorflow.org/)，（TensorBoard 的一个内置的可视化工具 Embedding Projector，可以上传数据文件）
 - ![mnist图示](http://upload-images.jianshu.io/upload_images/1667471-54ad06e9664e89e4.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)，【2018-1-22】[手写汉字识别](https://zhuanlan.zhihu.com/p/33071173?iam=cc759c5d7c383aa95e7633f06bcf6d82?utm_medium=social&utm_source=wechat_session)
 - 参考：[TensorFlow-7-TensorBoard Embedding可视化](http://blog.csdn.net/aliceyangxi1987/article/details/71079387)
### 深度学习
#### 神经网络发展历史
- [重磅！神经网络浅讲：从神经元到深度学习](http://www.cnblogs.com/subconscious/p/5058741.html)
![brief history of neural network](https://raw.githubusercontent.com/qingkaikong/blog/master/38_ANN_part1/figures/figure1_ANN_history.jpg)
[图片源自ANN简介](http://qingkaikong.blogspot.com/2016/11/machine-learning-3-artificial-neural.html)
![神经网络发展历史](http://www.36dsj.com/wp-content/uploads/2016/01/391-880x478.jpg)
#### 神经网络网络结构变化
![网络结构变化历史](http://www.36dsj.com/wp-content/uploads/2016/01/40-880x584.jpg)
当然，光有强大的内在能力，并不一定能成功。一个成功的技术与方法，不仅需要内因的作用，还需要时势与环境的配合。神经网络的发展背后的外在原因可以被总结为：更强的计算性能，更多的数据，以及更好的训练方法。只有满足这些条件时，神经网络的函数拟合能力才能得已体现
-【2017-8-7】[The mostly complete chart of Neural Networks, explained](https://medium.com/towards-data-science/the-mostly-complete-chart-of-neural-networks-explained-3fb6f2367464),神经网络结构大全
![all type of nerual network](https://cdn-images-1.medium.com/max/2000/1*cuTSPlTq0a_327iTPJyD-Q.png)

![发展外因](http://www.36dsj.com/wp-content/uploads/2016/01/418.jpg)
#### 深度学习大牛
 - Geoffrey Hinton ：深度学习鼻祖
 - [Yann Lecun(杨立昆)](http://yann.lecun.com/),CNN发明人，Goeffery Hinton的学生，首创LeNet
 - Yoshua Bengio ：也是深度学习
 - Andrew Ng ：Hinton的合作伙伴。coursera公开课,[Andrew Ng: Deep Learning, Self-Taught Learning and Unsupervised Feature Learning](https://www.youtube.com/watch?v=n1ViNeWhC24),[《MACHINE LEARNING YEARNING》翻译](http://blog.csdn.net/nnnnnnnnnnnny/article/details/53524858)
- 深度学习四大天王及其关系
- ![四大天王](http://upload.semidata.info/new.eefocus.com/article/image/2017/11/01/59f91af871499-thumb.png)
- ![关系](http://images0.cnblogs.com/blog2015/678029/201508/221936578479366.png)
- ![关系](http://images2015.cnblogs.com/blog/899685/201612/899685-20161211130512538-166288396.jpg)
 - [Yann Lecun(杨立昆)](http://yann.lecun.com/),CNN发明人，Goeffery Hinton的学生，首创LeNet
  - ![LeNet-5结构](http://img.blog.csdn.net/20160107230058907)
 - [LeNet-5手写数字识别示意图](http://yann.lecun.com/exdb/lenet/),[CNN手写数字识别实时3D交互，能看到详细的参数（非常直观）](http://scs.ryerson.ca/~aharley/vis/conv/),【2017-8-8】更令人震惊的3D模拟效果（视频）[Neural Network 3D Simulation](https://www.youtube.com/watch?v=3JQ3hYko51Y)，[制作方官网提供的解释](https://www.cybercontrols.org/neuralnetworks),实时视频中的CNN各层效果[What convolutional neural networks see](https://www.youtube.com/watch?v=Gu0MkmynWkw),[Deep Visualization Toolbox](https://www.youtube.com/watch?v=AgkfIQ4IGaM)
 - ![LeNet-5 gif](http://yann.lecun.com/exdb/lenet/gifs/asamples.gif)

  - 可视化资料:[Google PlayGround神经网络训练在线演示](http://playground.tensorflow.org/#activation=tanh&batchSize=10&dataset=circle&regDataset=reg-plane&learningRate=0.03&regularizationRate=0&noise=0&networkShape=4,2&seed=0.45786&showTestData=false&discretize=false&percTrainData=50&x=true&y=true&xTimesY=false&xSquared=false&ySquared=false&cosX=false&sinX=false&cosY=false&sinY=false&collectStats=false&problem=classification&initZero=false&hideText=false),【2017-12-28】汉化版，[好玩的神经网络](http://playground.tensorflowjiaocheng.com/),来自[Tensorflow教程网](http://www.tensorflowjiaocheng.com/). [ConvNetJS两层神经网络实时训练和可视化（可定制网络结构，看隐层空间,作者是Andrej Karpathy）](http://cs.stanford.edu/people/karpathy/convnetjs//demo/classify2d.html)，[Andrej Karpathy的其他Demo主页](http://cs.stanford.edu/people/karpathy/convnetjs/)
  - 【2018-3-21】[2分钟论文 | 用 谷歌「AI可解释性」 看懂机器学习](https://www.toutiao.com/a6534574654458167815/?tt_from=mobile_qq&utm_campaign=client_share&timestamp=1521592137&app=news_article&utm_source=mobile_qq&iid=28217844450&utm_medium=toutiao_android),[Building Blocks of AI Interpretability | Two Minute Papers #234](https://www.youtube.com/watch?v=pVgC-7QTr40)，可视化展示Web地址[The Building Blocks of Interpretability](https://distill.pub/2018/building-blocks/)
- 资料：[Deep Learning(ppt)](http://www.cs.nyu.edu/~yann/talks/lecun-20090720-vlpr-01.pdf),[Manifold](http://www.cs.nyu.edu/~yann/talks/lecun-20080905-mlss-manifold.pdf)
- [Google AI实验室](https://aiexperiments.withgoogle.com/)，包含多种AI Demo(手写预测，[卷积网络可视化](https://aiexperiments.withgoogle.com/what-neural-nets-see)，[高维数据可视化](http://projector.tensorflow.org/)，autodraw，quickdraw，[摄像头物品识别](https://aiexperiments.withgoogle.com/giorgio-cam/view/)，声音合成，[实物翻译](https://oxism.com/thing-translator/)，手势控制)。
- 【2017-12-26】[AI人工智能不断前进，看神经网络如何玩超级玛丽（视频）](https://www.yidianzixun.com/article/V_01NRsCrl?title_sn/0&s=9&appid=xiaomi&ver=4.5.4.0&utk=a8pzx7na)
-【2017-11-24】[卷积核效果在线实验](https://graphics.stanford.edu/courses/cs178/applets/convolution.html)

- 【2017-9-8】[Data Science and Robots](http://brohrer.github.io/blog.html),[Brandon Rohrer](http://brohrer.github.io/index.html).[How Deep Neural Networks Work](https://www.youtube.com/watch?v=ILsA4nyG7I0&feature=share),[ppt](https://docs.google.com/presentation/d/1AAEFCgC0Ja7QEl3-wmuvIizbvaE-aQRksc7-W8LR2GY/edit#slide=id.g1cc8f6e4e5_0_303)
- [2017-9-13]Lighthouse:smart camera,video: [the future of home](https://youtu.be/erZBQ8nv_M0)
- 【2017-10-11】[吴恩达眼中的深度学习七雄](https://mp.weixin.qq.com/s?__biz=MzA5NzkxMzg1Nw==&mid=2653163378&idx=1&sn=1d7728cdad982c0cc595036bcbe8fbd7&chksm=8b49321cbc3ebb0ac0ba0daf9f65f44fc86a26a019c7bf4ce9627cbd42d98b90c24787caaa40&mpshare=1&scene=23&srcid=1009kT4PvNGcTlOHrcm9cgm9#rd)
- 【2017-12-22】[李沐：博士这五年](https://zhuanlan.zhihu.com/p/25099638)，[动手学深度学习](http://zh.gluon.ai/),[GPU购买指南](http://zh.gluon.ai/chapter_preface/buy-gpu.html)

#### 深度学习书籍
几本有名的书籍：
-【2017-8-5】**Neural Network and Deep Learning(神经网络与深度学习)**
- [Michael Nielsen](http://michaelnielsen.org/)，这本书通俗易懂，由浅入深,细致讲解了神经网络，[英文版(官网)](http://neuralnetworksanddeeplearning.com/index.html),[配套Code](https://github.com/mnielsen/neural-networks-and-deep-learning),[中文版CSDN下载地址](http://download.csdn.net/download/pb09210/9556832)，书籍开源，作者求捐助5美元，[GitBook中文翻译地址](https://www.gitbook.com/book/tigerneil/neural-networks-and-deep-learning-zh/details)
-【2017-12-13】Deep learning（AI圣经）。
 - （1）[Deep Learning中文版](https://exacity.github.io/deeplearningbook-chinese/),[英文版](http://www.deeplearningbook.org/front_matter.pdf),[官方slides地址](http://www.deeplearningbook.org/lecture_slides.html),[github中文读书笔记](https://github.com/exacity/simplified-deeplearning)，[Deep Learning presented by Ian Goodfellow现场版（youtube）](https://www.youtube.com/watch?v=vi7lACKOUao).
 - （2）[雷锋网读书会历次分享集合：Deep Learning解读合辑](http://www.mooc.ai/bbs/blog/423/show)，更完整的集合[AI研习社公开课年度盘点](http://www.mooc.ai/bbs/blog/2474/show)
 - （3）[清华读书会分享笔记（pdf）](https://pan.baidu.com/s/1pKCiBO3#list/path=%2F)

| **时间** | **类型** | **名称** | **备注** |
| --- | --- | --- | --- |
| Andrew NG|cs229:Andrew NG斯坦福机器学习[网易公开课](http://open.163.com/special/opencourse/machinelearning.html)|中文字幕|
| 台大林轩田 | 机器学习基石和机器学习技法，[bilibili视频地址](https://www.bilibili.com/video/av4294020/) | |
| Hinton | 机器学习和神经网络，[网易云课堂](https://study.163.com/course/introduction.htm?courseId=1003842018)||
| chris manning | [斯坦福2017季CS224n深度学习自然语言处理课程](https://www.bilibili.com/video/av13383754/?from=search&seid=11933326047978202113) ||
|李宏毅|[李宏毅Machine Learning (2017,秋，台湾大学) ](https://www.bilibili.com/video/av15889450/?from=search&seid=16362427614856778742)||
|牛津|深度学习NLP（牛津大学 2017）（英文字幕）[bilibili地址](https://www.bilibili.com/video/av9817911/)||
|andrew ng|吴恩达深度学习与神经网络,[bilibili地址](https://www.bilibili.com/video/av15235628/)，黄海广博士写的学习笔记,源自[AI初学者--（机器学习爱好者）](http://www.ai-start.com/)，[2014斯坦福机器学习](http://www.ai-start.com/ml2014/),[深度学习](http://www.ai-start.com/dl2017/)|deeplearning.ai|
|andrew ng|[《MACHINE LEARNING YEARNING》翻译](https://blog.csdn.net/nnnnnnnnnnnny/article/details/53524858)，|2018-4-23|
|Ian good fellow|《深度学习》读书会分享视频集,[bilibili地址](https://www.bilibili.com/video/av15558220/#page=14)||
||[普林斯顿-算法](https://www.bilibili.com/video/av9995456/)||
|吴恩达|[DeepLearning.ai学习笔记彩绘版](https://pan.baidu.com/s/1DtYg3TyplXQOVZ-YmplJaw),百度云地址|很好的资料,作者TessFerrandez的[信息图地址](https://www.slideshare.net/TessFerrandez/notes-from-coursera-deep-learning-courses-by-andrew-ng),相关[github地址](https://github.com/mbadry1/DeepLearning.ai-Summary)|
|google|[Google AI 教学系列片 《Cloud AI Adventures》](https://zhuanlan.zhihu.com/p/33996430)||
|机器学习概念图示|来自Chris Albon博士，[英文原版](https://machinelearningflashcards.com/)需要12$,中文版[百度网盘地址](https://pan.baidu.com/s/1hsTPt7A)（密码：hje1）由大数据文摘提供|参考资料：[300张小抄表搞定机器学习知识点](http://www.sohu.com/a/217940688_464065)|


#### 大神博客
- [Andrej Karpathy博客](http://karpathy.github.io/neuralnets/),[Colah's Blog](http://colah.github.io/),[Neural Networks, Manifolds, and Topology](http://colah.github.io/posts/2014-03-NN-Manifolds-Topology/),[Understanding LSTM Networks](http://colah.github.io/posts/2015-08-Understanding-LSTMs/),[印度人总结的cnn笔记](https://deepnotes.io/implementing-cnn)
- [如何简单有趣的讲解神经网络(优质)](https://www.zhihu.com/question/22553761),[什么是人工神经网络（数学模拟过程清晰）](https://mp.weixin.qq.com/s?__biz=MzIyNDA1NjA1NQ==&mid=2651003012&idx=1&sn=323f7ebd22520d8cb08f35fa35d4e89a&chksm=f3e37f1cc494f60aabe5fd38235e6779769a6031d8128adfb912fc5f4c34c33e23c369d7a827&mpshare=1&scene=23&srcid=0630lUih5zoLdXoKDEZtXLBT#rd)
- [一文读懂深度学习](http://www.36dsj.com/archives/20382)，[深度学习：像人脑一样深层次思考](http://blog.csdn.net/yinlili2010/article/details/47760389)
- Deep Learning（深度学习）学习笔记整理[第一部分](http://blog.csdn.net/zouxy09/article/details/8775360/)|[第二部分](http://blog.csdn.net/zouxy09/article/details/8775488)|[第三部分](http://blog.csdn.net/zouxy09/article/details/8775518)|[第四部分](http://blog.csdn.net/zouxy09/article/details/8775524)|[第五部分](http://blog.csdn.net/zouxy09/article/details/8777094)|[第六部分](http://blog.csdn.net/zouxy09/article/details/8781396)|[第七部分](http://blog.csdn.net/zouxy09/article/details/8781543)|[第八部分](http://blog.csdn.net/zouxy09/article/details/8782018)
- [深度学习为何要深?](https://zhuanlan.zhihu.com/p/22888385),[超智能体gitbook](https://www.gitbook.com/book/yjango/superorganism/details),[台大李宏毅：一天搞懂深度学习](http://v.youku.com/v_show/id_XMTY5NDUzNjIxNg==.html?from=s1.8-1-1.2&spm=0.0.0.0.LZsB12%EF%BC%8C%E4%B8%80%E5%A4%A9%E6%90%9E%E6%87%82%E6%B7%B1%E5%BA%A6%E5%AD%B8%E7%BF%92--%E5%AD%B8%E7%BF%92%E5%BF%83%E5%BE%97)，[CNN原理3D交互演示](http://scs.ryerson.ca/~aharley/vis/conv/)，
-【2017-8-6】Andrew NG, 优质ppt [Machine Learning and AI via brain simulations](https://forum.stanford.edu/events/2011/2011slides/plenary/2011plenaryNg.pdf)
- 【TensorFlow】：[Gentlest Introduction to Tensorflow-日本人Khor SoonHin](https://www.youtube.com/watch?v=dYhrCUFN0eM&feature=youtu.be)，中文翻译版：小白也能懂的TensorFlow介绍[上](https://baijiahao.baidu.com/po/feed/share?wfr=spider&for=pc&context=%7B%22sourceFrom%22%3A%22bjh%22%2C%22nid%22%3A%22news_3418700520043930080%22%7D),[下](https://www.jiqizhixin.com/articles/67507027-b7e2-4597-b510-2e060d64e1a3)；[CS 20SI: Tensorflow for Deep Learning Research](https://web.stanford.edu/class/cs20si/syllabus.html)，[TensorBoard使用方法](http://www.jianshu.com/p/076a3e794312)，[introduction-to-tensorflow(PPT)](https://ep2017.europython.eu/media/conference/slides/introduction-to-tensorflow.pdf)
- 【2018-1-5】[没有博士学位，照样玩转TensorFlow深度学习](https://zhuanlan.zhihu.com/p/25010476?utm_source=qq&utm_medium=social)
- 作者斯坦福学生[Chin Huyen](https://huyenchip.com/), [Yann LeCun连发三弹：人人都懂的深度学习基本原理（附视频）](https://www.leiphone.com/news/201612/Sjkmer9Kto5ILxFk.html?viewType=weixin)
- [上海复旦大学吴立德教授的《深度学习课程》](http://list.youku.com/albumlist/show?id=21508721&ascending=1&page=1),[张俊林：深度学习在搜索推荐领域的应用](http://blog.csdn.net/malefactor/article/details/52040228#0-tsina-1-63822-397232819ff9a47a7b7e80a40613cfe1)
- [深度学习](http://my.tv.sohu.com/pl/9161916/84849655.shtml)，[从神经元到深度学习](http://www.36dsj.com/archives/39775),神经网络与深度学习：[英文网址](http://neuralnetworksanddeeplearning.com/)，[中文版下载地址](http://download.csdn.net/detail/pb09210/9556832)
- 【2017-8-1】[反向传播神经网络极简入门](http://www.hankcs.com/ml/back-propagation-neural-network.html)（含python代码实现）。Colah的[Calculus on Computational Graphs: Backpropagation](http://colah.github.io/posts/2015-08-Backprop/).
- 1974年有个Harvard博士生Paul Werbos首次提出了backprop，不过没人理他。1986年，Rumelhart和Hinton一起重新发现了backprop，并且有效训练了一些浅层网络，一下子开始有了名气。那个时候的backprop从现在看来并不是个很清晰的概念，把梯度和更新一块打包了。（[知乎達聞西](https://www.zhihu.com/question/27239198/answer/43560763)）。论文：Rumelhart D E, Hinton G E, Williams R J. Learning representations by back-propagating errors[M]. MIT Press, Cambridge, MA, USA, 1988.
- BP算法解释（多图）：[Principles of training multi-layer neural network using backpropagation](http://galaxy.agh.edu.pl/~vlsi/AI/backp_t_en/backprop.html)。[BP算法推导](http://blog.csdn.net/sheng_ai/article/details/19931347),[A Gentle Introduction to Artificial Neural Networks](https://theclevermachine.wordpress.com/tag/backpropagation/),[一文弄懂神经网络中的反向传播法——BackPropagation](http://www.cnblogs.com/charlotte77/p/5629865.html),[如何直观地解释 back propagation 算法？](https://www.zhihu.com/question/27239198?rf=24827633)
- [寒小阳：深度学习视频](http://my.tv.sohu.com/pl/9161916/84849655.shtml)
- 【2017-8-22】非常好的机器学习/深度学习系列教程：[Machine Learning is Fun](https://medium.com/@ageitgey)，作者[Adam Geitgey](https://twitter.com/ageitgey),[知乎专栏中文翻译(来自混沌巡洋舰)](https://zhuanlan.zhihu.com/c_29122335)，系列：
 - [第一章：最简入门指南](https://zhuanlan.zhihu.com/p/24450104)
 - [第二章：用机器学习制作超级马里奥关卡](https://zhuanlan.zhihu.com/p/24344720)
 - [第三章：图像识别，鸟还是飞机？深度学习与卷积网络](https://zhuanlan.zhihu.com/p/24524583)
 - [第四章：用深度学习识别人脸](https://zhuanlan.zhihu.com/p/24567586)
 - [第五章：谷歌翻译背后的黑科技：神经网络和端到端学习](https://zhuanlan.zhihu.com/p/24590838),[Machine Learning is Fun Part 5: Language Translation with Deep Learning and the Magic of Sequences](https://medium.com/@ageitgey/machine-learning-is-fun-part-5-language-translation-with-deep-learning-and-the-magic-of-sequences-2ace0acca0aa)
 - [第六章：如何用深度学习进行语音识别？](https://zhuanlan.zhihu.com/p/24703268)，[Machine Learning is Fun Part 6: How to do Speech Recognition with Deep Learning](https://medium.com/@ageitgey/machine-learning-is-fun-part-6-how-to-do-speech-recognition-with-deep-learning-28293c162f7a)
 - [第七章：未翻译](),[Machine Learning is Fun Part 7: Abusing Generative Adversarial Networks to Make 8-bit Pixel Art](https://medium.com/@ageitgey/abusing-generative-adversarial-networks-to-make-8-bit-pixel-art-e45d9b96cee7)
 - [第八章：未翻译](),[Machine Learning is Fun Part 8: How to Intentionally Trick Neural Networks](https://medium.com/@ageitgey/machine-learning-is-fun-part-8-how-to-intentionally-trick-neural-networks-b55da32b7196)
- [2017-8-23]MRSA KaiMing He[Tutorial: Deep Learning for Objects and Scenes](https://www.youtube.com/watch?v=jHv37mKAhV4)
- [2017-8-23][Machine Learning Mindmap / Cheatsheet](https://github.com/dformoso/machine-learning-mindmap),[sklearn](https://github.com/dformoso/sklearn-classification),[Data Science, Classification Analysis Jupyter notebook](https://github.com/dformoso/sklearn-classification/blob/master/Data%20Science%20Workbook%20-%20Census%20Income%20Dataset.ipynb)
- 【2017-10-10】[26种神经网络激活函数可视化](https://www.jiqizhixin.com/articles/2017-10-10-3),[Visualising Activation Functions in Neural Networks](https://dashee87.github.io/data%20science/deep%20learning/visualising-activation-functions-in-neural-networks/)(可交互)
- 【2017-12-14】Google deepmind [深度学习实践和发展趋势](https://pan.baidu.com/s/1mhWGSpq)
- 【2018-4-10】Google AI面试题[https://medium.com/acing-ai/google-ai-interview-questions-acing-the-ai-interview-1791ad7dc3ae](https://medium.com/acing-ai/google-ai-interview-questions-acing-the-ai-interview-1791ad7dc3ae)
- 【2018-4-13】[Tensorflow中国社区](https://www.tensorflowers.cn/)
#### 案例及Demo
- [ClarifAI图像视频物体识别](https://www.clarifai.com/demo)
- 【2017-8-31】[Toranto Deep Learning Demos](http://deeplearning.cs.toronto.edu/i2t),涉及图像分类+图像标注，服务性能有限，响应不及时
- [Deeplearn.js](https://pair-code.github.io/deeplearnjs/#getting-started)
- [你们天天嚷嚷神经网络, 可是知道一开始的赫布律么?](http://v.youku.com/v_show/id_XMjg5ODUzMTEyMA==.html)
- 【2017-8-30】[45个问题测出你的深度学习基本功](https://jizhi.im/blog/post/45_questions_deep_learning),[45 Questions to test a data scientist on basics of Deep Learning (along with solution)](https://www.analyticsvidhya.com/blog/2017/01/must-know-questions-deep-learning/)
- [MIT Scene Recognition Demo](http://places.csail.mit.edu/demo.html)
- [DeepDream Demo](https://deepdreamgenerator.com/)
- [20个令人惊叹的深度学习应用(欢迎补充)：Demo+Paper+Code](https://zhuanlan.zhihu.com/p/26392608)
- [2017-9-20][ClarifAI在线Demo（目标检测、人脸识别、色情识别、场景识别等）](https://clarifai.com/demo#)
- 【2018-2-25】[在线demo：黑白图片着色](http://demos.algorithmia.com/colorize-photos/)
- 【2018-5-13】[TensorFlow.js浏览器里的实时人体姿态估计](https://github.com/tensorflow/tfjs-models/tree/master/posenet/demos)
- 【2018-5-13】[Kaggle Kernal免费GPU试用案例](https://www.kaggle.com/dansbecker/running-kaggle-kernels-with-a-gpu/code)
- 【2018-5-26】[无需深度学习框架，如何从零开始用Python构建神经网络](https://zhuanlan.zhihu.com/p/37340090)
#### CNN
- [ImageNet 缔造者：如何让冰冷的机器读懂照片背后的故事？](http://www.ifanr.com/648667), [TED视频](https://www.ted.com/talks/fei_fei_li_how_we_re_teaching_computers_to_understand_pictures?language=zh-cn#t-40455),[网易公开课](http://open.163.com/movie/2015/3/Q/R/MAKN9A24M_MAKN9QAQR.html)
- [CS231n Convolutional Neural Networks for Visual Recognition](http://cs231n.github.io/neural-networks-3/),[Youtube视频地址](https://www.youtube.com/playlist?list=PLkt2uSq6rBVctENoVBg1TpCC7OQi31AlC)，[Andrej Karpathy Youtube主页](https://www.youtube.com/channel/UCPk8m_r6fkUSYmvgCBwq-sw)，[CS231n官方笔记授权翻译总集篇发布](https://zhuanlan.zhihu.com/p/21930884?utm_medium=social&utm_source=wechat_session&from=groupmessage)
---
### NLP自然语言处理&RNN
- 【2017-8-1】[NLP十分钟入门](http://www.cnblogs.com/baiboy/p/learnnlp.html)
- [斯坦福CoreNLP在线Demo演示](http://nlp.stanford.edu:8080/corenlp/process)（含分词WS、POS词性标注、NER命名实体识别、语法树等等），[斯坦福NLP相关软件](https://nlp.stanford.edu/software/), 斯坦福深度学习与自然语言处理课程[CS224d: Deep Learning for Natural Language Processing学习笔记（我爱自然语言处理）](http://www.52nlp.cn/%E6%96%AF%E5%9D%A6%E7%A6%8F%E5%A4%A7%E5%AD%A6%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0%E4%B8%8E%E8%87%AA%E7%84%B6%E8%AF%AD%E8%A8%80%E5%A4%84%E7%90%86%E7%AC%AC%E4%B8%80%E8%AE%B2%E5%BC%95%E8%A8%80)
![示例](https://stanfordnlp.github.io/CoreNLP/images/Xi-Jinping.png)
- [国内外自然语言处理(NLP)研究组大全](http://blog.csdn.net/wangxinginnlp/article/details/44890553)
- 【2017-12-22】![词云](http://pic1.zhimg.com/v2-63e581c5fd5b57f9055b05553357c538_b.jpg)。
- [Boson NLP波森自然语言处理Web演示](http://bosonnlp.com/demo)
- ![boson_nlp](https://pic3.zhimg.com/50/v2-12a7e37b55fee8ef8b9b88001035ff8e_hd.jpg)
- 【2017-12-21】 深度学习为什么在NLP管用？[Deep Learning, NLP, and Representations](https://colah.github.io/posts/2014-07-NLP-RNNs-Representations/),[深度学习、自然语言处理和表征方法](http://blog.jobbole.com/77709/). [Deep Learning in NLP （一）词向量和语言模型](http://licstar.net/archives/328#comment-1636).如何生成好的词向量？[《How to Generate a Good Word Embedding?》导读](http://licstar.net/archives/620),[](),,[论文地址](http://arxiv.org/abs/1507.05523),[实验代码地址](https://github.com/licstar/compare)
- 【2018-4-15】[机器翻译简史](https://zhuanlan.zhihu.com/p/34612952)
![机器翻译简史](https://pic2.zhimg.com/80/v2-31559656eda02537d2d2b78e99052305_hd.jpg)
- 【2018-4-16】谷歌发布的自然语言理解（NLU）体验，[Semantic Experiences](https://research.google.com/semanticexperiences/)，Talk to Books + Semantris
- 【2018-4-19】[11款分词工具大比拼](https://segmentfault.com/a/1190000003971257),[jieba分词15min入门与进阶](https://blog.csdn.net/fontthrone/article/details/72782499)，jieba [Github地址](https://github.com/fxsjy/jieba)
- 【2018-5-13】[100+ Chinese Word Vectors 上百种预训练中文词向量](https://github.com/Embedding/Chinese-Word-Vectors)
#### RNN
- 循环神经网络RNN:[BiLSTM iMDB影评分类可视化Demo](https://transcranial.github.io/keras-js/#/imdb-bidirectional-lstm)
- 【2018-5-2】[可视化LSTM网络：探索「记忆」的形成](https://www.toutiao.com/a6539111834589331976/?tt_from=mobile_qq&utm_campaign=client_share&timestamp=1525255789&app=news_article&utm_source=mobile_qq&iid=29957305093&utm_medium=toutiao_android)。【2018-5-8】[对LSTM中M（Memory）的再思考](https://zhuanlan.zhihu.com/p/28263453?utm_source=wechat_session&utm_medium=social),[YJango的循环神经网络——实现LSTM](https://zhuanlan.zhihu.com/p/25518711)
- [ImageNet 缔造者：如何让冰冷的机器读懂照片背后的故事？](http://www.ifanr.com/648667), [TED视频](https://www.ted.com/talks/fei_fei_li_how_we_re_teaching_computers_to_understand_pictures?language=zh-cn#t-40455),[网易公开课](http://open.163.com/movie/2015/3/Q/R/MAKN9A24M_MAKN9QAQR.html)
- [2017-8-17][CS224n: Natural Language Processing with Deep Learning](http://web.stanford.edu/class/cs224n/)
- [Neural Nets for Generating Music](https://medium.com/artists-and-machine-intelligence/neural-nets-for-generating-music-f46dffac21c0)
![RNN](https://cdn-images-1.medium.com/max/2000/1*my_udGVBPa4U5L6U_9m81Q.png)
- Word2Vec教程：通俗易懂，Part-1，[Skip-Gram模型](http://blog.csdn.net/layumi1993/article/details/72866235),[原文：word2vec tutorial the skip-gram model]( http://mccormickml.com/2016/04/19/word2vec-tutorial-the-skip-gram-model/)；Part-2，[Negative Sampling](http://blog.csdn.net/Layumi1993/article/details/72868399)，[原文](http://mccormickml.com/2017/01/11/word2vec-tutorial-part-2-negative-sampling/)
![skip-gram net](http://mccormickml.com/assets/word2vec/skip_gram_net_arch.png)
- [The amazing power of word vectors](https://blog.acolyer.org/2016/04/21/the-amazing-power-of-word-vectors/?blogsub=confirming#subscribe-blog)
- 【2017-12-29】[Embedding Projector](http://projector.tensorflow.org/). ![](https://2.bp.blogspot.com/-Uql7bl2KEYM/WEfQ4Kl_0YI/AAAAAAAABck/GkktuPM8KoMcMl2Tot6GzH3-NgwPNETMgCLcB/s1600/image03.png)
- 【2017-12-11】CMU,[Neural Network for NLP](http://phontron.com/class/nn4nlp2017/schedule.html)
- 【2017-12-12】NLP牛人
 - 斯坦福[李纪为](https://web.stanford.edu/~jiweil/)
  - [李纪为：用于对话生成的深度强化学习](https://baijia.baidu.com/s?old_id=545627)
  - [让机器像人一样交流：斯坦福李纪为博士毕业论文](https://www.jiqizhixin.com/articles/2017-11-14)
  - 【2018-1-15】[李纪为创立的香侬科技获红杉千万投资](http://www.sohu.com/a/216713639_114778),金融搜索分析工具
 - 香港理工[李嫣然](http://yanran.li/about/)
 - 【2018-4-2】Google Brain开发者，[蔡善清](http://scai.io/#about), [Github主页](https://github.com/caisq), 2005进入清华，2012年MIT博士毕业， tensorflow debugger主要开发者(以后会集成到tensorboard中)，Eager动态计算图开发者
 - 【2018-4-27】[完全图解RNN、RNN变体、Seq2Seq、Attention机制](https://zhuanlan.zhihu.com/p/28054589),将各自的关系讲的清清楚楚。【2018-5-12】神经网络机器翻译模型可视化(注意力Seq2seq模型机制)[《Visualizing A Neural Machine Translation Model (Mechanics of Seq2seq Models With Attention)》](https://jalammar.github.io/visualizing-neural-machine-translation-mechanics-of-seq2seq-models-with-attention/).
 ![attention](https://jalammar.github.io/images/attention.png)
 - 【2018-5-1】机器阅读理解google QANet的[Tensorflow实现](https://github.com/NLPLearn/QANet)
 - 【2018-5-18】[解密谷歌 Gmail 新功能：结合 BoW 模型和 RNN-LM，帮助用户快速写邮件](https://www.jiqizhixin.com/articles/051705)
---
### 语音
- 【2018-5-13】[音频样本浏览器](https://www.sononym.net/),支持音频分析、相似搜索、智能分类等
- 【Google Duplex：通过电话进行自然对话以执行“真实世界”任务】[《Google Duplex: An AI System for Accomplishing Real World Tasks Over the Phone | Google AI Blog》](https://ai.googleblog.com/2018/05/duplex-ai-system-for-natural-conversation.html)
---
#### 对抗生成学习
VAE和GAN，[VAE和GAN](https://pic4.zhimg.com/v2-380cde71a2f6ece28b46038ea2455a97_b.png)
- [2017-7-28]AI专家的忏悔[Confession of a so-called AI expert](https://huyenchip.com/2017/07/28/confession.html?from=timeline)
- 【2017-7-30】Google的AI产品：[QuickDraw](https://quickdraw.withgoogle.com)，类似你画我猜，只是用机器来猜
- [Facebook AI实验室最新的实时GAN图片展示](http://soumith.ch/eyescream/)
- 集智俱乐部李嫣然：[《深入浅出GAN-原理与应用》学习笔记](https://zhuanlan.zhihu.com/p/27663439)，[厉害了，我的GAN](https://zhuanlan.zhihu.com/p/27663139)
### 强化学习
- 强化学习、监督学习和无监督学习对比：![强化学习、监督学习和无监督学习对比](http://upload-images.jianshu.io/upload_images/1667471-96a418676c3fed5d.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
- [一文了解强化学习](http://geek.csdn.net/news/detail/201928)
- 【2017-7-31】[David Silver 强化学习公开课中文讲解](https://zhuanlan.zhihu.com/reinforce)
- 【2017-8-21】[Q-learning算法简明教程](http://blog.csdn.net/itplus/article/details/9361915)，[英文原文](http://mnemstudio.org/path-finding-q-learning-tutorial.htm)
- 【2017-8-29】AK的博客[Deep Reinforcement Learning: Pong from Pixels](http://karpathy.github.io/2016/05/31/rl/)
- 【2017-12-19】强化学习领军人物Richard Sutton的经典教材[《强化学习》第二版](http://incompleteideas.net/book/the-book-2nd.html)。
- 【2017-12-21】[强化学习视频教程分享（从入门到精通）](https://mp.weixin.qq.com/s?__biz=MzIxNDgzNDg3NQ==&mid=2247484036&idx=1&sn=4f7abdaec180d425f84c133bed53335d&chksm=97a0c950a0d740467ee23bc8adb1aa081d8047d1ee8ba8ad60487a04c0f90383d480253448a4&scene=21#wechat_redirect)
- 【2017-12-21】【视频】[深度强化学习介绍 (John Schulman, OpenAI)](http://www.365yg.com/item/6463040754213192206/)
- 【2018-5-1】[强化学习用于比特币自动交易](https://github.com/samre12/deep-trading-agent)
### 迁移学习
- 【2017-9-3】中科院计算所[迁移学习pdf](http://jd92.wang/assets/files/l08_tl_zh.pdf)
- 【2017-9-3】集智俱乐部，迁移学习资料汇总[github](https://zhuanlan.zhihu.com/p/28792291)[知乎](https://github.com/wantingallin/transferlearning)
- 【2018-5-1】【主动学习：优化!=改进】[《Active Learning: Optimization != Improvement》](https://lighttag.io/blog/active-learning-optimization-is-not-imporvement/) by LightTag。注：主动学习是指监督学习中，用较少的训练样本来获得性能较好的分类器
![主动学习](https://images2015.cnblogs.com/blog/1082072/201701/1082072-20170115172446635-1237681929.png)
- 【2018-5-12】【无需博士学位的TensorFlow深度强化学习教程】《TensorFlow and deep reinforcement learning, without a PhD (Google I/O '18) - YouTube》by Martin Gorner. [Youtube地址](http://t.cn/R3bErsa), [Bilibili地址](https://www.bilibili.com/video/av23286922/)
### 知识图谱
- [精益知识图谱方法论](http://blog.memect.cn/?p=2005)，文因互联鲍捷组件的[北京知识图谱学习班](https://github.com/memect/kg-beijing),[知识管理和语义搜索的哲学思考](http://blog.memect.cn/?p=3022),更多资料参考[将门创业历届活动嘉宾视频及ppt](https://mp.weixin.qq.com/s?__biz=MzAxMzc2NDAxOQ==&mid=502876225&idx=1&sn=25894a894cc2c58214ddde13e0a8ef93&chksm=03907c9d34e7f58b57b068d0e7e74ac3db935a131cc7955478b58a98b9bc5c2b239c8ee03129&mpshare=1&scene=23&srcid=1201jRGgplUzlGGggjBesJuI#rd), [八一八聊天机器人](https://zhuanlan.zhihu.com/p/25190575)，[聊天机器人终极设计指南](http://www.woshipm.com/pd/441725.html)，[一文看懂聊天机器人的所有猫腻](http://www.eeworld.com.cn/qrs/article_2016081529734.html)，【2018-5-8】[自己动手做聊天机器人](https://github.com/warmheartli/ChatBotCourse)
- 【2017-12-22】李文哲[知识图谱的应用](https://zhuanlan.zhihu.com/liwenzhe/20394260) ![kg](http://pic1.zhimg.com/v2-5635f23d2df3ff971fa12a563510b1c0_b.jpg)
- 【2018-4-9】[十分钟上手图数据库](https://www.jianshu.com/p/97c6752e928b)
- 【2018-4-17】狗尾草CTO王昊奋[When KB meets Chatbots](http://blog.openkg.cn/%E7%8E%8B%E6%98%8A%E5%A5%8B-when-kg-meets-chatbots/)，知识图谱[Zhishi.me](http://zhishi.me/)，开放的知识图谱社区[OpenKG.cn](http://blog.openkg.cn/page/2/)
### 数据挖掘
- [谁说菜鸟不会数据分析【脑图笔记】](http://www.cnblogs.com/xiaofeng1234/p/5997018.html?from=timeline)
- [SQL必知必会【脑图笔记】](http://www.cnblogs.com/xiaofeng1234/p/6024479.html)
- SQL各种join区别:
![join区别](http://images2015.cnblogs.com/blog/594609/201601/594609-20160120105945578-386143616.png)
- 经验总结：[以什么姿势进入DataMining会少走弯路？](http://weibo.com/ttarticle/p/show?id=2309403973170330790744)
- [大嘴巴漫谈数据挖掘](http://download.csdn.net/detail/laoge/9386026)（易向军），图解各种基础知识和算法概念——五星推荐
- [分分钟带你杀入Kaggle Top 1%](https://zhuanlan.zhihu.com/p/27424282),[Kaggle求生：亚马逊热带雨林篇](https://zhuanlan.zhihu.com/p/28084438)
- [2017-8-30][Kaggle 首战拿银总结 | 入门指导 (长文、干货）](https://jizhi.im/blog/post/kaggle_silver)
- 【2017-12-13】知乎[如何快速成为分析师](https://www.zhihu.com/question/29265587),图表建议-思维指南
- ![excel选图](https://pic1.zhimg.com/50/v2-15e812e7de4c1ddd23144e4e53826cf0_hd.jpg)
- 【2017-12-14】知乎[数据分析&数据挖掘书籍推荐](https://www.zhihu.com/question/20757000)
- 【2018-5-2】[你费那么大劲做的数据分析，有用吗](https://zhuanlan.zhihu.com/p/21378331),左耳朵耗子-陈皓的[数据的游戏：冰与火](https://coolshell.cn/articles/10192.html)
### 人脸识别
- 权威书籍[Handbook of Face Recognition](https://cours.etsmtl.ca/sys828/REFS/Intro/Hanbook%20of%20Face%20Recognition.pdf)
- [Modern Face Recognition with Deep Learning](https://medium.com/@ageitgey/machine-learning-is-fun-part-4-modern-face-recognition-with-deep-learning-c3cffc121d78)
![How a basic pipeline for detecting faces might work](https://cdn-images-1.medium.com/max/1600/1*WxBM1lB5WzDjrDXYfi9gtw.gif)
- Face Point
- ![Face Point](https://cdn-images-1.medium.com/max/1600/1*AbEg31EgkbXSQehuNJBlWg.png)
- Face Compare
![Face Compare](https://cdn-images-1.medium.com/max/1600/1*n1R8VMyDRw3RNO3JULYBpQ.png)
- [2017-9-20][CMU OpenPose姿势识别](https://github.com/hxl1990/openpose)
- ![图](https://github.com/hxl1990/openpose/raw/master/doc/media/pose_face_hands.gif)
- [2017-9-21]自拍照三维重建[3D Face Reconstruction from a Single Image](http://www.cs.nott.ac.uk/~psxasj/3dme/index.php)
- ![demo](https://cdn.vox-cdn.com/thumbor/fXbE0rbXW6WlcmtB1cKBiTsV1b0=/0x0:482x334/1820x1213/filters:focal(203x129:279x205):no_upscale()/cdn.vox-cdn.com/uploads/chorus_image/image/56734861/3d_mark_take_2.0.gif)
- 【2018-2-25】[人脸识别：含年龄性别表情人种](https://www.haystack.ai/)

## IT资讯
- 查公司信息：[天眼查](http://www.tianyancha.com/),[IT桔子](https://www.itjuzi.com/)
- [互联网黑名单](https://github.com/shengxinjing/programmer-job-blacklist)
- 股权信息：[股权周刊](https://zhuanlan.zhihu.com/guquanzhoukan)(各种股权纠纷案例,作者[邓永权](https://www.zhihu.com/people/guquanzhoukan/answers))。[【干货】创业公司融资时如何分配股权？融资后一般怎么稀释？](http://bbs.pinggu.org/thread-4526409-1-1.html)
- [程序员跳槽全攻略-读书笔记](http://www.cnblogs.com/coderland/p/5903051.html)
![图](https://images2015.cnblogs.com/blog/1025005/201609/1025005-20160924130454027-1184504966.png)
- 【2018-1-7】程序员职业生涯蓝图。![fig](fig/coding_life.jpg)
- Gartner：技术成熟度曲线.[Gartner2016 年度新兴技术成熟度曲线解读：3 大趋势、16 个新技术](http://www.cniteyes.com/archives/26460)
![图](http://www.cniteyes.com/data/uploads/2016/08/2-4.jpg)
- [互联网大佬的出生地图鉴](http://www.toutiao.com/a6442203091621314818/?tt_from=mobile_qq&utm_campaign=client_share&app=news_article_lite&utm_source=mobile_qq&iid=12181093832&utm_medium=toutiao_android)
- [SixSence](https://www.ted.com/talks/pattie_maes_demos_the_sixth_sense?language=zh-cn#t-492870),[The thrilling potential of SixthSense technology](https://www.youtube.com/watch?v=YrtANPtnhyg),[Pranav Mistry](http://www.pranavmistry.com/projects/sixthsense/#VIDEOS)
- ![example](http://www.virtualspeechcoach.com/wp-content/uploads/2014/01/ppt-7-500x282.jpg)
- IT橘子[人工智能全产业链图谱](https://www.itjuzi.com/ai)
- 【2018-1-8】36Kr，[互联网中的少数派-女性开发者(视频)](https://www.ixigua.com/a6481129329202823693/?utm_medium=feed_steam&utm_source=toutiao#mid=3757989448)，全世界1850w程序员，中国占10%，主人翁司晓静、刘旸（iOS开发，天气旋律闹钟weather tunes）、创业公司castbox CEO王小雨（北大心理学系自学转Android开发，fruit boom杰作，Google）。
- 【2018-1-16】舒适区、恐慌区，参考知乎[不断跳出自己的「心理舒适区」真的能够让人们取得更大的成就吗？](https://www.zhihu.com/question/26111474)
![舒适区](https://pic2.zhimg.com/80/323317fb1c41a9dc053abc35cdb19a32_hd.jpg)
如何成为一个很厉害的人？
![如何](https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1516764722&di=14731e340d89fb197b011428a2ba80b0&imgtype=jpg&er=1&src=http%3A%2F%2Fwww.iyiplus.com%2Fwp-content%2Fuploads%2F2017%2F02%2F1.4-1024x687.png)
- 【2018-5-2】[技术人员的发展之路](https://coolshell.cn/articles/17583.html)
- 【2018-2-25】[纪实：中国人工智能之路](http://list.youku.com/show/id_zefbfbd2b2f7befbfbdef.html?spm=a2h0j.8191423.module_basic_title.5~A!2),[人工智能真的来了](http://list.youku.com/show/id_zefbfbd2b2f7befbfbdef.html?spm=a2h0j.8191423.module_basic_title.5~A!2)
- 【2018-4-25】[阿布量化](https://github.com/bbfamily/abu?from=groupmessage&isappinstalled=0)
## 工具
- 视频下载工具：[流媒体下载的10种方法](http://www.jianshu.com/p/e7d2c3a624f6)
 - [硕鼠](http://www.flvcd.com/)(可以下载流视频，可按专辑下载)，[硕鼠Mac版下载地址](http://www.pc6.com/mac/118056.html)（官网地址有问题）
 - [维棠](http://www.vidown.cn/)
 - YouTube视频下载：(更多方法参考知乎帖子：[如何下载youtube视频](https://www.zhihu.com/question/51714507?sort=created))
  - （1）每个视频域名稍作修改即可（youtube.com->kissyoutube.com）,[SaveMedia](https://savemedia.com/)提供，在线下载+系列视频自动推荐
  - (2) python代码下载,pip3 install you-get,you-get 'https://www.youtube.com/watch?v=jNQXAC9IVRw', 支持的视频网站范围广
  - (3) [clipconverter](http://www.clipconverter.cc/)
- [lantern下载](https://github.com/getlantern/forum/issues/833)，[蓝灯无限制版](https://github.com/JuncoJet/unlimited-landeng-for-win)
- 在线代码着色（高亮）：[国外：含语言类型自动识别（优）](http://markup.su/highlighter/),[国内：在线代码着色器（需要自己勾选）](http://tool.oschina.net/highlight),[实时英文拼写检测](https://app.grammarly.com/)
- [如何使用VIM搭建IDE？](http://harttle.com/2015/11/04/vim-ide.html),[vim键盘图大全](http://www.cnblogs.com/yu-lang/p/5413279.html),[所见即所得，像IDE一样使用vim](https://github.com/yangyangwithgnu/use_vim_as_ide)，![VIM键盘图](http://harttle.com/assets/img/blog/vim-key.png)
- ![vim命令图解](https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1513414506184&di=5592bf051e8a3b337830632ac037b1c0&imgtype=jpg&src=http%3A%2F%2Fimg4.imgtn.bdimg.com%2Fit%2Fu%3D3339508074%2C1265491893%26fm%3D214%26gp%3D0.jpg)
- [台湾人总结的vim命令图解（pdf打印版）](http://img.my.csdn.net/uploads/201211/24/1353759337_6781.png)
- 【2017-12-14】[awk思维导图](http://s1.51cto.com/wyfs02/M01/7D/18/wKiom1bf0R6wMA_sABZGEQxE4yg982.png)，[sed思维导图](http://scc.qibebt.cas.cn/docs/linux/script/sed%CB%BC%CE%AC%B5%BC%CD%BC.jpg),[更多linux工具总结](http://scc.qibebt.cas.cn/docs/doc-main.php?dir=linux)
- [python下的二维码生成与解析](http://peihao.space/2016/01/30/QR/)
- 【2018-2-17】[用PYTHON玩微信（非常详细）](http://www.cnblogs.com/jiaoyu121/p/6944398.html),通过微信网页版抓包的开源工具[itchat](https://github.com/littlecodersh/itchat)，可以分析微信数据，可视化（echart+wordcount），聊天机器人,接入图灵机器人,[示例](https://itchat.readthedocs.io/zh/latest/tutorial/tutorial0/),其它：[Python实现微信自动回复机器人](http://blog.csdn.net/weixin_40127725/article/details/78185193)，[python实现微信接口(itchat)](https://segmentfault.com/a/1190000009420701)资料全面
- 【2018-4-4】微信小程序开发,[官方小程序简易教程](https://developers.weixin.qq.com/miniprogram/dev/quickstart/basic/file.html),[微信小程序开发资源汇总](http://xn--vuqv9g32iftcfqq6am2a581eowevx8ayg8b/)
- 【2017-12-17】[如何用github搭建个人博客](https://cczeng.github.io/2017/05/03/git/%E6%88%91%E6%98%AF%E5%A6%82%E4%BD%95%E5%88%A9%E7%94%A8Github-Pages%E6%90%AD%E5%BB%BA%E8%B5%B7%E6%88%91%E7%9A%84%E5%8D%9A%E5%AE%A2%E2%80%94%E2%80%94%E7%BB%86%E6%95%B0%E4%B8%80%E8%B7%AF%E7%9A%84%E5%9D%91/)，【2018-2-19】[微信公众号如何接入图灵机器人](http://blog.csdn.net/jueyi1127/article/details/48291025)
- 【2018-2-16】[1997年世界黑客编程大赛冠军作品](http://blog.sina.com.cn/s/blog_882361720101d730.html)，[视频地址](http://v.youku.com/v_show/id_XMTY5NTI2NzY2OA==.html),汇编语言生成3D动画
- 【2018-3-31】文件转换，①[pdf转换器](http://www.pdfdo.com/pdf-to-word.aspx),②[迅捷pdf转换器](http://app.xunjiepdf.com/),pdf到各种文件格式的转换,③[国外的pdf converter](https://www.freepdfconvert.com/)
- 【2018-4-2】[Heavens Above](http://www.heavens-above.com/), 查看天体运行，如特斯拉实时位置，天宫一号降落过程
- 【2018-5-1】[《后端架构师技术图谱》](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#innodb)
- 【2018-5-20】[Linux,一生只为寻找欢笑](https://zhuanlan.zhihu.com/p/19796979)，Linus Torvalds名言：Talk is cheap，show me the code！翻译：①正经版：代码胜于雄辩②俗版：屁话少说，放码过来③文艺版：纸上得来终觉浅，觉知此事需躬行④红色版：空谈误国，实干兴⑤邦隐晦版：北沙滩，亮马桥
- 【2018-5-22】[基于HTML5超酷摄像头（HTML5 webcam）拍照功能实现代码](http://www.jb51.net/html5/67833.html),基于WebRTC技术
### 实验评估
- 第一种：<font color=#0099ff size=5 face="黑体">A/B-Test</font>. [什么是ab-test？](https://www.zhihu.com/question/20045543/answer/59025552)
 - A/B Test,也称为对比测试,是让两个版本的登陆页面的相互pk测试。看看哪个版本能更好地引导访问者达到你的预设目标,如注册或订阅。
 - [工程实施：叫你如何对产品进行AB Test？](http://blog.csdn.net/weiguang_123/article/details/49203239)，包含服务端、客户端如何实施ab-test，及各自的优缺点
- [ab-test有什么局限性？](https://www.zhihu.com/question/19631253)
 - 首先，A/B测试只有在关键效绩指标(KPI, or Key Performance Indicator)单一，且这个单一明确的目标可以被电脑量化时，适用
 - 其次，A/B测试相比起一些别的测试手段，如纸本原型(paper prototyping)，需要的工作量大、时间长，对设计的要求也相对较高。
 - 另外，A/B测试之所以进行，唯一原因是对结果的追求。但相对应的测试结果通常是短期、即刻的用户行为，比如购买、注册、点击等。
 - 此外，A/B测试并不能提供用户行为的具体细节。A/B测试的结果也仅限于被测试的两个选项：如果12号字比16号字为你的网站带来多1%的用户浏览时间，那10号字呢？8号呢？A/B测试并不能帮助你作更多的、长远的决定。
 - A/B测试还有别的缺点：需要的用户人数大，可能的影响因素多，可以测试的选项数有很大限制等等。
- [吆喝科技-ab-test最佳实践](http://www.appadhoc.com/blog/category/appadhoc/)
- 第二种：<font color=#0099ff size=5 face="黑体">interleaving</font>
- [灰度发布和A/B Test](http://www.jianshu.com/p/88f206f48278)
## 编程语言
- [命令式编程和声明式编程的区别](http://www.vaikan.com/imperative-vs-declarative/)
- [go语言开发者必读的陷阱、技巧、错误](http://www.cnblogs.com/Eilen/p/6944345.html)
- 【2018-5-2】Python入门神图，参考：[Python脚本图解](https://blog.csdn.net/GarfieldEr007/article/details/50898988)，[Python入门思维导图百度云盘下载](https://pan.baidu.com/s/1sl0o6tB)
![python入门神图](https://img-blog.csdn.net/20150429090744512)
- python：[python小白笔记](http://www.cnblogs.com/xiaofeng1234/p/6052051.html)，[python正则表达式](http://www.cnblogs.com/huxi/archive/2010/07/04/1771073.html)，【2018-5-4】[Python代码执行过程可视化](http://www.pythontutor.com/visualize.html#mode=display)
- 【2017-12-11】python面向对象:[初级篇](http://python.jobbole.com/82023/),[进阶篇](http://python.jobbole.com/83747/)
- 【2018-4-28】Dive into Python[中文版](https://woodpecker.org.cn/diveintopython/)
- 【2018-6-4】[图解深拷贝和浅拷贝](https://www.cnblogs.com/wilber2013/p/4645353.html)
- 【2018-5-30】request发明人的python教程：[The Hitchhiker’s Guide to Python!](http://docs.python-guide.org/en/latest/),[Python大神，requests库的作者放大招了](https://www.toutiao.com/a6533719066996113928/)
- 【2018-5-6】[Machine Learning Plus](https://www.machinelearningplus.com/blog/),包含numpy、pandas、scikit-learn各种工具包的代码实战示例，用python做科学计算-[Numpy快速数据处理](http://old.sebug.net/paper/books/scipydoc/numpy_intro.html)
- ![numpy](http://old.sebug.net/paper/books/scipydoc/_images/numpy_intro_03.png)
- [The Zen of Python(Python之禅)](http://blog.csdn.net/liang19890820/article/details/51734118)
- ![python](http://img.blog.csdn.net/20160908133049363)
- <font color='red' size=5>Python 之禅</font>， by Tim Peters
 - 优美胜于丑陋（Python 以编写优美的代码为目标）
 - 明了胜于晦涩（优美的代码应当是明了的，命名规范，风格相似）
 - 简洁胜于复杂（优美的代码应当是简洁的，不要有复杂的内部实现）
 - 复杂胜于凌乱（如果复杂不可避免，那代码间也不能有难懂的关系，要保持接口简洁）
 - 扁平胜于嵌套（优美的代码应当是扁平的，不能有太多的嵌套）
 - 间隔胜于紧凑（优美的代码有适当的间隔，不要奢望一行代码解决问题）
 - 可读性很重要（优美的代码是可读的）
 - 即便假借特例的实用性之名，也不可违背这些规则（这些规则至高无上）
 - 不要包容所有错误，除非你确定需要这样做（精准地捕获异常，不写except:pass风格的代码）
 - 当存在多种可能，不要尝试去猜测
 - 而是尽量找一种，最好是唯一一种明显的解决方案（如果不确定，就用穷举法）
 - 虽然这并不容易，因为你不是 Python 之父（这里的 Dutch 是指 Guido）
 - 做也许好过不做，但不假思索就动手还不如不做（动手之前要细思量）
 - 如果你无法向人描述你的方案，那肯定不是一个好方案；反之亦然（方案测评标准）
 - 命名空间是一种绝妙的理念，我们应当多加利用（倡导与号召）
- 【2017-11-23】python编码规范，目前有google和pep8两种，pylint默认pep8，[Google python编码规范](https://zh-google-styleguide.readthedocs.io/en/latest/google-python-styleguide/python_style_rules/)，[如何用pylint规范代码风格](https://www.ibm.com/developerworks/cn/linux/l-cn-pylint/)
 - 安装方法：sudo pip install -U pep8/pylint
- [给深度学习入门者的Python快速教程 - 基础篇](https://zhuanlan.zhihu.com/p/24162430),[numpy和Matplotlib篇](https://zhuanlan.zhihu.com/p/24309547).[Python超简洁教程,含图示,在线调试](https://jizhi.im/blog/post/pythonbasics)
- 老外的Matplotlib教程,[英文原文](http://www.labri.fr/perso/nrougier/teaching/matplotlib/)_,[中文译文](https://liam0205.me/2014/09/11/matplotlib-tutorial-zh-cn/)，[Matplotlib官方艺术馆](http://matplotlib.org/gallery.html)
- [Pandas学习笔记](http://blog.csdn.net/u012675539/article/details/47113147)，[十分钟搞定pandas](http://www.cnblogs.com/chaosimple/p/4153083.html),pandas cheetsheet, ![pandas](https://upload-images.jianshu.io/upload_images/2422746-c3dcf0bba1d9f616.png)
- pandas读取excel数据示例
 [2016-7-30]
 - 【2018-5-2】6张python工具包总结图，见[python数据分析实用小抄](https://www.jianshu.com/p/7f4945b5d29c),[Top 28 Cheat Sheets for Machine Learning, Data Science, Probability, SQL & Big Data](https://www.analyticsvidhya.com/blog/2017/02/top-28-cheat-sheets-for-machine-learning-data-science-probability-sql-big-data/),[百度云地址](https://pan.baidu.com/s/1kUQxyUN#list/path=%2F)
 - 【2018-6-6】[python最强思维导图合集](https://mp.weixin.qq.com/s/9a7_gq6eBHKJ8Hb5EJsxFA),来自[数林觅风](https://woaielf.github.io/)的github
 - 【2018-6-10】【精】[数据科学知识图谱](https://woaielf.github.io/2016/09/11/data-science/)，数林觅风，精美的脑图笔记
- 【2017-11-23】[史上最全设计模式导学目录](http://blog.csdn.net/lovelion/article/details/17517213)
- 【2017-12-14】[字符编码详解——彻底理解掌握编码知识，“乱码”不复存在](http://blog.51cto.com/polaris/377468),[字符字节和编码](http://www.regexlab.com/zh/encoding.htm)
- 【2017-12-16】编码总结
- ![coding](python/python-coding.png)

- ![编码](https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1513861868&di=806e504e1bf1cf8e95f64d5f2d006684&imgtype=jpg&er=1&src=http%3A%2F%2Fs1.knowsky.com%2F20170206%2Flabih04zb2137.png)
- 【2017-12-23】[[译]27 个Jupyter Notebook的小提示与技巧](http://liuchengxu.org/pelican-blog/jupyter-notebook-tips.html)
- 【2018-5-2】[scikit-learn]cheet sheet(https://upload-images.jianshu.io/upload_images/2422746-7a1d1aad161f9224.png)
- 【2018-5-7】精华：[流畅的Python：阅读笔记](http://python.jobbole.com/88735/)

## 视频资源
### 公开课
- 哈佛大学《公正》系列公开课：[哈佛英文主页](http://justiceharvard.org/justicecourse/),[网易中文翻译](http://v.163.com/special/sandel/episode06.html)
 - 自律更自由：康德
 - [一张图弄明白：从零维到十维空间](http://www.sohu.com/a/116444282_482877),[11分钟带你进入十次元的世界(video)](http://video.tudou.com/v/XMTc4ODE0ODAwMA==.html),[GuoKr's explornation](http://www.guokr.com/post/433527/)
 - [懂了这些之后 才知道如何去赚钱](https://www.youtube.com/watch?v=MtKHKPCy0cI)(经济学原理)
- 【2017-8-25】[宇宙揭秘：电子双缝干涉实验，绝对颠覆你的三观甚至让你怀疑人生](http://www.365yg.com/group/6457791347830030861/)
- [几幅图让你真正了解什么是硕士学位、什么是博士学位](http://www.toutiao.com/a6463373238914253326/?tt_from=mobile_qq&utm_campaign=client_share&app=news_article_lite&utm_source=mobile_qq&iid=12181093832&utm_medium=toutiao_android)
- [一部能让小孩喜欢汉字的动画片](http://music.163.com/#/video?id=912AF355DA533D2392052A27DFD28F26)。【2018-5-19】国产动画[小蝌蚪找妈妈](http://www.iqiyi.com/w_19rtv79nfd.html)
- 【2017-12-24】[一个故事告诉你比特币的原理及运作机制](http://blog.codinglabs.org/articles/bitcoin-mechanism-make-easy.html),视频：[一个故事告诉你比特币的原理](一个故事看懂货币发展史与比特币的原理)。【2018-1-23】[如何简单易懂的介绍区块链](https://www.zhihu.com/question/37290469),【2018-2-19】[区块链讲解及Demo](https://anders.com/blockchain/)，【2018-3-18】比特币在线Demo：[coinDemo](https://coindemo.io/),[blockchainDemo](https://blockchaindemo.io/)
- 【2017-12-31】视频短片：[时间](https://www.yidianzixun.com/article/V_01LMOyvQ?title_sn/0&s=9&appid=xiaomi&ver=4.5.5.0&utk=a8pzx7na)(工薪族一家三口的作息时间差)，[皮克斯2016创意动画《鹬》](https://www.yidianzixun.com/article/V_01DYkrTF?title_sn/0&s=9&appid=xiaomi&ver=4.5.5.0&utk=a8pzx7na)
- 【2018-2-25】【电影】[暖](http://www.1905.com/vod/play/85391.shtml),白狗秋千架。【2018--3-17】美丽心灵（博弈论创始人，纳什）+ [万物理论](https://pan.baidu.com/s/1HdrJpd-OXp371A8m9PI_Eg)(霍金)
- 【2018-3-1】[杭州买房知识大全github](https://github.com/houshanren/hangzhou_house_knowledge)
