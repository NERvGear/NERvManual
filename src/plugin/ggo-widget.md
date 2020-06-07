
# GGO 桌面挂件 {#plugin-ggo_widget}

> SAO Utils\\Plugins\\GGO Widget

# 插件-GGO桌面挂件 {#plugin-ggo_widget-2}
![](Images/temp/5-2-1.jpg)<br>
左键可以拖动GGO桌面挂件（以下将简称为GGO挂件）的位置，右键或长按其中一个项目（即那个方块）可以使用此项目的菜单<br>
![](Images/temp/5-2-2.jpg)<br>
排序：可以移动此项目或项目所在行<br>
大小：调整此项目大小，自定义可以以像素为单位进行调整<br>
添加项目…：在当前的GGO桌面挂件块添加一个项目<br>
编辑项目…：编辑此项目，关于编辑具体事项查看@ref plugin-ggo_widget-2-1 "插件-GGO桌面挂件-编辑项目"<br>
移除项目：删除此项目（复原需在当前的GGO桌面挂件手动重新添加并编辑）<br>
添加一行：在当前的GGO桌面挂件向下添加一行项目<br>
移除本行：删除在当前的GGO桌面挂件的此行项目（复原需在当前的GGO桌面挂件手动重新添加并编辑）<br>
添加挂件：建一个GGO桌面挂件块,相对于新建一个分离并独立的挂件块<br>
移除挂件：删除当前的GGO桌面挂件块（复原需手动重新添加并编辑）<br>
[[当只存在一个GGO挂件时无法移除挂件，需停用插件，如何停用看@ref preference-2-6 "插件"]]<br>
置顶挂件：置顶显示这个GGO挂件<br>
锁定所有挂件：锁定所有GGO挂件，无法移动和使用GGO挂件菜单，如需解锁请点击![](Images/temp/5-2-3.jpg)解锁<br>
对齐到：移动此GGO挂件到适当位置
 
# 编辑项目 {#plugin-ggo_widget-2-1}
打开GGO挂件项目编辑界面
![](Images/temp/5-2-1-1.jpg)<br>
名称：用于标注挂件的命名,此命名仅显示在选择类型选项的"条形图、直方图"时会显示，如：![](Images/temp/5-2-1-2.jpg)<br>
空白：此项目不显示任何文本以及其它显示<br>
静态图片：类型选项选择静态图片,点击下方<br>
![](Images/temp/5-2-1-3.jpg)<br>
点击选择图片进行添加,即可在该挂件项目中显示所选择图片(类型PNG)<br>
数字或文本：选择"数字或文本"选项,点击下方"点击选择数据",进入<br>
![](Images/temp/5-2-1-4.jpg)<br>
选择数值框内选择对应需要设置的"数值或数据"，详情看@ref plugin-ggo_widget-2-2 "数字或文本"<br>
条形图：点选后按下面的长条，选择显示的数字，只能显示百分比数据，显示效果如此：![](Images/temp/5-2-1-5.jpg)<br>
直方图：点选后按下面的长条，选择显示的数字，只能显示百分比数据，显示效果如此：![](Images/temp/5-2-1-6.jpg)<br>
勾选[动作]可以使项目在点击后做出相应动作<br>
勾选[执行前需确认]，使项目点击后确认才能实行动作<br>
勾选[执行后保持启动器]，使项目点击后不会退出主菜单<br>
程序：勾选[程序]后点![](Images/temp/3-1-2-1-2-2.jpg)<br>
可以选择项目点击后所打开的程序<br>
文件：勾选[文件]后点![](Images/temp/3-1-2-1-2-2.jpg)<br>
可以选择项目点击后所打开的文件<br>
文件夹：勾选[文件夹]后点![](Images/temp/3-1-2-1-2-2.jpg)<br>
可以选择项目点击后所打开的文件夹<br>
链接：勾选[链接]后点![](Images/temp/3-1-2-1-2-2.jpg)<br>
可以输入项目点击后所打开的链接<br>
链接前需加入协议，如：<br>
http://（后面加上网址可以使项目点击后打开此网址，如：http://www.baidu.com）<br>
file://（后面加上文件夹路径和文件名可打开文件夹或文件，如：file://c:/）<br>
keys://（后面加上项目点击后自动实行的按键，如：keys://win+s）<br>
mailto://（后面加上要收件人的电子邮箱地址，这个链接的作用就是发邮件）<br>
我的电脑：file://::{20D04FE0-3AEA-1069-A2D8-08002B30309D}<br>
系统库：file://::{031E4825-7B94-4dc3-B131-E946B44C8DD5}<br>
我的文档：file://::{031E4825-7B94-4dc3-B131-E946B44C8DD5}\\Documents.library-ms<br>
我的音乐：file://::{031E4825-7B94-4dc3-B131-E946B44C8DD5}\\Music.library-ms<br>
我的图片：file://::{031E4825-7B94-4dc3-B131-E946B44C8DD5}\\Pictures.library-ms<br>
我的视频：file://::{031E4825-7B94-4dc3-B131-E946B44C8DD5}\\Videos.library-ms<br>
回收站：file://::{645FF040-5081-101B-9F08-00AA002F954E}<br>
命令：勾选[命令]后点![](Images/temp/3-1-2-1-2-2.jpg)<br>
可以输入项目点击后所实行的cmd命令<br>
常用cmd命令：<br>
取消关机：shutdown.exe -a <br>
关机：shutdown.exe -s -t 0（0可更改为等待关机的秒数）<br>
重启：shutdown.exe -r -t 0（0可更改为等待关机的秒数）<br>
锁定：rundll32.exe user32.dll,LockWorkStation<br>
挂起：rundll32.exe powrProf.dll,SetSuspendState<br>
命令行：cmd<br>
记事本：notepad<br>
计算器：calc<br>

# 数字或文本 {#plugin-ggo_widget-2-2}
![](Images/temp/5-2-2-1.jpg)<br>
1：此处选择要显示的数字或文本<br>
注意：![](Images/temp/5-2-2-2.jpg)
![](Images/temp/5-2-2-3.jpg)
![](Images/temp/5-2-2-4.jpg)都需要相应软件的支持<br>
关于音乐播放器支持详情查看@ref plugin-music_player_support "插件-音乐播放器支持"<br>
2：预览所选数字或文本（部分数字或文本不能马上预览）<br>
3：调整显示的模式<br>
4：调整数字或文本更新间隔<br>
5：调整单位和后缀显示<br>
6：根据[7]中的注释填写，如注释没提无需填写<br>
7：所选数字或文本其显示的注释<br>

# 上传\下载速度监控 {#plugin-ggo_widget-2-3}
![](Images/temp/5-2-3-1.jpg)