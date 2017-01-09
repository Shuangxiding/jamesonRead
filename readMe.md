#西风云阅读APP
###[扫描下载演示app](http://demo.xf512.com/xifeng/demo.apk)
![扫描二维码下载app](http://demo.xf512.com/xifeng/demo.png)

# [使用方法](http://www.kancloud.cn/yuan1314/xifeng)

-	基于apicloud开发，请同步至你的apicloud工程后编译
-	ajax请求，返回json数据
>	成功返回 
	`{status:1,error:0,data:[...]}
>	失败返回
	`{status:0,error:msg}
>   数据端使用php返回json

1. 确保已安装 [小说阅读器专业版](http://addon.discuz.com/?@jameson_read.plugin)
2. 将xifeng文件夹上传到你的网站根目录下
3. 每个图书分类准备一个图片。尺寸为 100*100px，格式为png，名字为分类id.png，上传到xifeng/image目录下
4. 到网站后台-应用-小说插件--手机版-拉到底部，填写app相关的各项信息
5. 三张介绍图片，在用户刚安装app后，第一次打开时显示，共三张，点击第三张时进入app首页，格式为png，名字分别为s1.png，s2.png，s3.png，尺寸为1080*1920，替换  源码/image/目录下的s1.png s2.png s3.png
6. 到www.apicloud.com 注册一个帐号，并创建一个native应用，下载 apicloud studio，使用该帐号登录，同步下载刚才创建的应用，然后打开创建的文件目录，将所有文件删除，将源码目录下的所有文件复制到此处
7. 打开源码目录下 config.xml。修改<widget id="A6914623403868"为你创建的应用的id
8. 打开源码 目录下 index.html，将 http://demo.jameson512.com替换为你的域名
9. 在apicloud studio中 云端同步你的代码
10. [www.apicloud.com](http://www.apicloud.com)的控制台，端设置中配置你的应用logo、启动页图片。左侧证书中创建android证书、左侧点击编译，填写名字、选择android、选择正式版，进行编译
11. 编译后将安装包下载，重命名为此处显示的版本号.apk，比如 0.0.1.apk。然后上传到 xifeng/目录下，
12. 网站后台-小说插件-手机版，填写app的安装包地址


# [点此链接查看详细教程](http://www.kancloud.cn/yuan1314/xifeng/214858)
