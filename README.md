# xUpdate
xCopy方式是一种绿色的安装方式，无疑是一种最简单又易于理解的安装方式，本项目参考了xCopy的命名方式，所以叫做xUpdate，以期望提供一种简单的应用程序更新方式。

xUpdate更新程序

支持以web纯静态文件模式分发更新文件

支持基于文件版本号的更新版本控制
支持单文件的安装程序，实现初始版本的安装
全部配置基于json文件
实现方式支持任何web容器
对应用无任何侵入
更新过程可视化
更新全过程记录完备的日志
支持更新程序自身的更新
先编这些吧...

待实现功能
更新文件基于MD5码的检查，避免重复下载
更新配置的json需要提供可视化工具
安装过程需要提供进度提示
更新自更新需要提供进度提示
原始文件的备份机制
应用运行中通知应用更新的机制（计划采用无侵入的模式，由另一个进程轮询web配置的版本号，弹出提示，提示用户更新）
下载的鉴权，避免非法下载
编不下去了...

路线图
没时间写呢
