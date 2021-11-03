# 同步问题

## 问题一：**Windows电脑客户端不能同步网页端**

PC端新建一篇同步笔记，将把这篇失败笔记复制粘贴到新建的笔记中，然后删除这篇失败笔记，再同步一下试试。若不行就按照以下操作：\
\
1、查看下电脑自带的IE浏览器能否正常上网（一定要是IE浏览器哦），若不能上网，请重置IE浏览器试试（在桌面右键单击IE图标，选择“属性”。在弹出的对话框中选择“高级”、“重置”，然后点击确定。勾选“删除个人设置”，点击确定。等待完成后，重启电脑即可）；

2、请检查IE设置中的cookie设置，看下是否“滑块”是否移动在最顶端呢？如果移动到最顶端则是选择“阻止所有的Cookie”，此时系统将阻止所有网站的Cookie，则无法进行云笔记的同步（启动IE浏览器，在“工具”菜单上，单击“Internet选项”，打开“Internet选项”对话框。然后单击“隐私”选项卡，检查下滑块是否移动到更高的隐私级别）；

3、电脑是否挂了代理、杀毒软件呢？如有，请关闭后，完全退出云笔记账号，重启软件，再登录同步试试；

4、如是通过公司内网使用云笔记，一般企业网络都有安全设置，请您咨询运维人员是否限制或屏蔽了云笔记；

建议您进入 http://wanproxy.127.net/lbs?version=1.0\&bucketname=bucket-ynote-online 网页看看 具体返回什么提示。

**5、若有内容表示网络没受限制；若空白表示网络有问题。或者公司使用受限制了，将这些端口找it添加开放一下**

\*.youdao.com\
login.ynote.youdao.com\
login.note.youdao.com\
ynote.youdao.com\
note.youdao.com\
notify.ynote.youdao.com\
notify.note.youdao.com\
notify3.ynote.youdao.com\
notify3.note.youdao.com\
rpc1.ynote.youdao.com\
rpc1.note.youdao.com\
rpc2.ynote.youdao.com\
rpc2.note.youdao.com\
rpc3.ynote.youdao.com\
rpc3.note.youdao.com\
rpc4.ynote.youdao.com\
rpc4.note.youdao.com\
rpc5.ynote.youdao.com\
rpc5.note.youdao.com\
rpc6.ynote.youdao.com\
rpc6.note.youdao.com\
rpc7.ynote.youdao.com\
rpc7.note.youdao.com

&#x20;\*.push.126.net\
epay.163.com\
payments.163.com

## **问题二：Windows客户端插入图片或其他附件就同步失败**

1. 建议同步好所有笔记后，退出PC端。桌面右键云笔记图片===以管理员身份运行，打开后再次插入图片或附件试试，看能不能同步成功。
2. 进入 http://wanproxy.127.net/lbs?version=1.0\&bucketname=bucket-ynote-online 网页看看 具体返回什么提示。\
   若是 空白 的结果，代表使用网络有问题，需要更换网络，或者网络管理者开发名单限制下试试。或者公司运维禁用了端口需要开放【可参考上面的第5条，开放下端口】

## **问题三：Web端笔记无法同步到手机端**

一般受网络或笔记内容影响。建议在WIFI环境下多同步几次下拉刷新。\
若未解决，备份好未同步的笔记，（文本可另存备忘录，图片保存到本地相册），然后删除笔记，重新登录尝试同步或卸载重装APP试试。

