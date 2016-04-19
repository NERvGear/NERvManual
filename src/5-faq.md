
# 5.常见问题 FAQ {#faq}

[TOC]

# SAO Utils 使用问题 {#faq-usage}

## 为什么手势失效？杀软报毒？ {#faq-G001}

- 目前小红伞/360会把Win32版本误报为病毒，而360还会拦截程序热键和手势…因此如果程序手势失效，99%的可能是由你的杀软引起的。<BR>
  升级后无法使用手势、桌面下无法使用手势等请自行重新添加信任到360等拦截软件。<BR>
  若添加信任后仍然无法在桌面使用手势，建议 **禁用或卸载360**。
  
## 重启后设置或菜单丢失？ {#faq-G002}
- 首先，请确保解压后启动 SAO Utils.exe，不要直接在压缩包里面执行。 <BR>
  其次，不要把程序解压到系统文件夹等特殊位置，如果无论如何都要放到系统文件夹，请确保 SAO Utils 根目录及其子目录拥有读写权限。

## 如何更改程序显示语言？(暂时) {#faq-G009}
-# 查找本机系统语言名称:
   -# 打开命令行窗口
   -# 输入 ‘systeminfo’
   -# 记下 ‘系统语言’ 的值
-# 复制已有的语言文件:
   -# 在 SAO Utils/Locales 目录下复制一份你想要的语言
   -# 以 1.3 节的名字重命名该语言目录(xx_YY格式)
-# 重启 SAO Utils

## 关于图标？ {#faq-G010}
- SAO Utils 完整版自带200组包括悬停状态的图标，放置于程序目录下Images文件夹内，两类图标都有对应的图标组:
  - Images/symbol：用于一级菜单的标识型图标.
  - Images/icon：用于列表菜单及分类菜单的圆形图标

## 如何在多点触摸屏上使用【双指下滑】呼出启动器？ {#faq-G011}
- 配合 <A HREF="https://github.com/TransposonY/GestureSign/releases/" TARGET="_blank">GestureSign</A> 这款开源绿色小工具使用即可。<BR>
  只需把【运行 SAO Utils.exe】命令绑定到任何你喜欢的手势即可，当然双指下滑也不例外。

## 如何在 VR 设备上使用 SAO Utils？ {#faq-G012}
A: 请参考 <A HREF="http://www.gpbeta.com/post/develop/sao-utils-vr-patch/" TARGET="_blank">SAO Utils VR 潜行补丁及使用说明（仅限 Beta 1 Update 1）</A>。