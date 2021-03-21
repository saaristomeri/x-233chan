# x-233chan
Kusaba X Fork with a translated Chinese frontend, powering a certain project starting with 2333
Kusaba X的fork，增加以下特性：
- 中文前台
- BBCode支持
- 文字颜文字输入
- 彩色饼干ID
- 音频上传（需要服务器支持，基于Flash播放器）

# 安装方法
Clone本repo后，用文本编辑器打开``config.php``，修改其中的变量
将OTHER文件夹中的``install.php``, ``install-dbtype.php``以及``kusaba_freshinstall.dbtype.sql``（对应``config.php``中``KU_DBTYPE``）复制粘贴进根目录
浏览器打开``/install.php``进行安装
安装完毕后，删除上述安装文件及``/OTHER``文件夹
管理页面``/manage.php``，默认用户名和密码均为``admin``，请记得修改

# 参考 
波兰球插件  https://github.com/exclude/kusaba-int-module
文字颜文字列表来自于A岛
``/assets``文件夹中图像的作者为Woody-Rinn
Kusaba X制作组  https://github.com/Edaha

原README内容
Installation Guide  http://kusabax.cultnet.net/wiki/installation_guide
Other Info (Including Upgrading)  http://kusabax.cultnet.net/wiki/basics
Support Board  http://kusabax.cultnet.net/sup/
