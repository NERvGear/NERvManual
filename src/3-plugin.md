
# 3.插件 / 扩展 {#plugin}

![挂件对应插件](Images/plugin-1.jpg)

# 插件一览 {#plugin-list}

## 官方插件 {#plugin-list-official}

| 插件名称                               | 简介                                                                  |
| :------------------------------------: | --------------------------------------------------------------------- |
| \subpage plugin-bangumi                | 可查询每日新番放送列表的桌面挂件。                                    |
| \subpage plugin-cardinal_system        | 基于 Cardinal 的桌面辅助精灵。(计划)                                  |
| \subpage plugin-ggo_theme              | 可选的 Gun Gale Online 启动器风格。                                   |
| \subpage plugin-ggo_widget             | 可定制的 Gun Gale Online 风格数据挂件。                               |
| \subpage plugin-hp_bar                 | HP 计量表风格的数据挂件。                                             |
| \subpage plugin-image_widget           | 在桌面上显示自定义的图片。                                            |
| \subpage plugin-mail_box               | 包含在线用户列表的邮件收发客户端插件。                                |
| \subpage plugin-quick_launch           | 在桌面上显示一个便捷功能按钮。                                        |
| \subpage plugin-sensor_data_extension  | 可在 \ref plugin-hp_bar 或 \ref plugin-ggo_widget 中使用的传感器数据。|
| \subpage plugin-weather_data_extension | 可在 \ref plugin-hp_bar 或 \ref plugin-ggo_widget 中使用的天气数据。  |
| \subpage plugin-web_browser_engine     | 可在 SAO Utils 中打开浏览网页。                                       |
| \subpage plugin-web_widget             | 在桌面上显示自定义的网页。                                            |

## 第三方插件 {#plugin-list-more}

| 插件名称                                | 简介                                 | 作者            |
| :-------------------------------------: | ------------------------------------ | :-------------: |
| \subpage plugin-music_player_support    | 提供各种常见播放器的信息及控制支持。 | \ref _RangerCD  |
| \subpage plugin-pdh_data_extension      | 提供系统'性能计数器'中的数据。       | \ref _RangerCD  |
| \subpage plugin-shortcut_keys_extension | 允许用户定义一些组合键。             | \ref _RangerCD  |

# 插件管理 {#plugin-manage}

![](Images/plugin-manage-1.jpg)

## 安装插件 {#plugin-manage-install}

-# 点击【安装…】按钮后选择 .NVG 后缀的插件安装包；
-# 安装成功后，在插件列表选中该插件，勾选【启用】；
-# 点击【保存】启用。

> 某些浏览器可能会更改插件包的后缀，如果下载下来的插件包是压缩包，请换个浏览器重新下载。

## 升级插件 {#plugin-manage-upgrade}

- 操作与 \ref plugin-manage-install 相同，需要重启 SAO Utils 完成升级。

## 启用 / 禁用插件 {#plugin-manage-switch}

-# 在插件列表选中需要开关的插件，取消或勾选【启用】；
-# 点击【保存】应用设置。

## 移除插件 {#plugin-manage-remove}

- 暂时不支持卸载操作。如需删除插件，退出程序后，删除 SAO Utils\\Plugins 目录下对应的文件夹即可。

## 重置插件设置 {#plugin-manage-reset}

- 暂时不支持插件重置操作。如需恢复插件到原始设定，禁用插件后，删除 SAO Utils\\Configs 目录下对应的文件夹后启用插件即可。