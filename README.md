NET-Link
本程序模拟了一个电脑系统(基于windows)
支持通过设定的标识符打开文件、应用程序、网页等

link.ini
- lmax <总数(最大支持128)>
- TAG INPUT LINK

TAG 类型：
file  用于打开非命令行exe文件
note  用于打开文本文件
sys   用于打开其他文件、网页、文件夹等
...   持续更新中

INPUT：
任意连续字符(读到空格及Tab停止)

LINK：
TAG          e.g.
file  C:\\Program Files (x86)\\Microsoft\\Edge\\Application\\msedge.exe
note  D:\\NET-Link\\link.ini
sys   C:\\Desktop\\Edge.lnk
      C:\\Desktop\\软件启动器.exe
      https://github.com/
...   持续更新中
