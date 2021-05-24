# 同步问题

问题一：  
**Windows电脑客户端不能同步网页端（看笔记列表有没有出现感叹号或蓝色圆圈图标）**

①PC端新建一篇同步笔记，将把这篇失败笔记复制粘贴到新建的笔记中，然后删除这篇失败笔记，再同步一下试试  
②若不行就按照以下操作：  
1、查看下电脑自带的IE浏览器能否正常上网（一定要是IE浏览器哦），若不能上网，请重置IE浏览器试试（在桌面右键单击IE图标，选择“属性”。在弹出的对话框中选择“高级”、“重置”，然后点击确定。勾选“删除个人设置”，点击确定。等待完成后，重启电脑即可）；

2、请检查IE设置中的cookie设置，看下是否“滑块”是否移动在最顶端呢？如果移动到最顶端则是选择“阻止所有的Cookie”，此时系统将阻止所有网站的Cookie，则无法进行云笔记的同步（启动IE浏览器，在“工具”菜单上，单击“Internet选项”，打开“Internet选项”对话框。然后单击“隐私”选项卡，检查下滑块是否移动到更高的隐私级别）；

3、电脑是否挂了代理、杀毒软件呢？如有，请关闭后，完全退出云笔记账号，重启软件，再登录同步试试；

4、如是通过公司内网使用云笔记，一般企业网络都有安全设置，请您咨询运维人员是否限制或屏蔽了云笔记；

建议您进入 http://wanproxy.127.net/lbs?version=1.0&bucketname=bucket-ynote-online 网页看看 具体返回什么提示。

**5、接4；若有内容表示网络没受限制；若空白表示网络有问题。或者公司使用受限制了，将这些端口找it添加开放一下**

\*.youdao.com  
login.ynote.youdao.com  
login.note.youdao.com  
ynote.youdao.com  
note.youdao.com  
notify.ynote.youdao.com  
notify.note.youdao.com  
notify3.ynote.youdao.com  
notify3.note.youdao.com  
rpc1.ynote.youdao.com  
rpc1.note.youdao.com  
rpc2.ynote.youdao.com  
rpc2.note.youdao.com  
rpc3.ynote.youdao.com  
rpc3.note.youdao.com  
rpc4.ynote.youdao.com  
rpc4.note.youdao.com  
rpc5.ynote.youdao.com  
rpc5.note.youdao.com  
rpc6.ynote.youdao.com  
rpc6.note.youdao.com  
rpc7.ynote.youdao.com  
rpc7.note.youdao.com

 \*.push.126.net  
epay.163.com  
payments.163.com

**6、确认PC端的笔记都同步到网页版云笔记上正常显示后（若PC端有未同步的笔记，建议您先将它们备份好：文字复制保存到其他软件，图片下载到本地文件夹，再进行下一步操作），完全退出笔记软件（在系统托盘点击笔记图标右键选择退出），将电脑上的配置目录和数据库目录中的内容全部删除后，再登录官网（http://note.youdao.com/），重新下载最新版登录同步试试。**

l 配置目录：%USERPROFILE%\Local Settings\Application Data\youdao\ynote

l 数据库目录：%USERPROFILE%\Local Settings\Application Data\YNote\Data

注：删除卸载前，请您先在网页版云笔记（http://note.youdao.com/ ）确认笔记是否全部正常，全部正常就在本地可以放心删除，以避免因“删除本地数据”导致未同步成功的笔记被清除且无法恢复的麻烦。成功同步储存在云端的笔记数据，以网页版显示的为准

**若还是无法操作，咨询一下以下问题**  
1、同步失败有哪些提示或现象呢？  
2、网页端新建笔记，插入图片后保存。然后在PC端点击同步，能否同步下来  
3、PC端无法同步的笔记一共多大？  
4、电脑版本号多少？**indows电脑版本号获取方法：打开cmd，第一行会显示版本号；（mac在右上角：关于系统，，，，，，）然后云笔记的版本号是多少？**  
5、提供本地log，路径：%USERPROFILE%\Local Settings\Application Data\youdao\ynote\log

**PC插入图片或其他附件就同步失败**

① 建议同步好所有笔记后，退出PC端。桌面右键云笔记图片===以管理员身份运行，打开后再次插入图片或附件试试，看能不能同步成功。

② 建议您进入 http://wanproxy.127.net/lbs?version=1.0&bucketname=bucket-ynote-online 网页看看 具体返回什么提示。  
若是 空白 的结果，代表使用网络有问题，需要更换网络，或者网络管理者开发名单限制下试试。或者公司运维禁用了端口需要开放【可参考上面的第5条，开放下端口】

**MAC电脑PC端不同步mac web端（看笔记列表有没有出现感叹号或蓝色圆圈图标）**

1. 检查网络是否正常；

2. 检查网页版是否能够正常打开；

3. 先备份好Mac客户端未同步的笔记（文字复制到其他软件保存，图片保存到本地文件夹），然后注销退出客户端后重新打开客户端，点击同步；

4. 看看在笔记列表中有没有出现感叹号或蓝色圆圈的图标。  
出现此情况，是由于您的这篇笔记同步失败造成的，您可以进行以下操作：先在您的笔记中，新建一篇笔记，然后把同步失败的笔记内容复制粘贴到新建的笔记中，接着删除这篇同步失败的笔记，再同步一下新笔记即可。

5. 检查笔记存储空间是否不足；

6.如果以上都无法解决，建议您备份好未同步的笔记后（文字复制到其他软件保存，图片保存到本地文件夹；以免数据丢失），再删除本地数据目录，具体删除步骤为：在Mac上打开Finder，按快捷键Shift+Command+G，弹出一个“前往文件夹”的框，在框里输入“~/Library/Containers/com.youdao.note.YoudaoNoteMac/Data/Library/ApplicationSupport/com.youdao.note.YoudaoNoteMac”，即可看到自己都用什么类型的账号登录过，确认已将该账号的数据备份好之后，选择那个账号的文件夹，移除到废纸篓就可以了。也可以将整个文件夹中的内容，都进行删除。删除后卸载笔记软件，到官网下载安装最新版云笔记并重新登录查看试试。  
  
**若网页版使用正常，仅Mac客户端使用卡顿的话，建议您先完全同步好目前Mac客户端所有的笔记（可登录网页版检查确认是否已同步成功）之后，然后使用腾讯柠檬清理：https://lemon.qq.com/ ，彻底卸载有道云笔记， 再到官网重新下载安装再使用试试，看是否可改善该情况。**

**WEB端笔记无法同步到手机端**

一般受网络或笔记内容影响。建议在WIFI环境下多同步几次下拉刷新。  
若未解决，备份好未同步的笔记，（文本可另存备忘录，图片保存到本地相册），然后删除笔记，重新登录尝试同步或卸载重装APP试试。  
**2、【仅针对安卓用户】**  
未同步的笔记数据备份好之后，返回手机设置-&gt;应用-&gt;找到云笔记-&gt;存储-&gt;清除数据，在清除数据后重新登陆云笔记软件，重新操作笔记同步试试呢。或者杀掉笔记进程后或者删掉去手机设置了选择清除数据，然后再删掉sdcard-&gt;.youdaonote文件夹。（若是在本地查看不到该文件夹的话，就需要在手机先下载re管理器App后，找到“.YoudaoNote ”这个文件夹。

