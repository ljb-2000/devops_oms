自动化运维系统(v1.0) 自动化运维开发交流群:342844540.

1、目录说明
OMS----项目主目录
 |----OMS：项目配置文件，添加了一个自定义配置文件config.ini
 |----SaltstackServer：控制层服务端程序脚本及相关安装方法
 |     |----rpycserver.py：传输进程脚本
 |     |----rpycserver.sh：传输服务脚本
 |----app：应用配置文件，网站代码主目录
 |     |----migrations
 |     |----static：静态文件，基本使用的是Bootstrap框架，
 |     |             除了nav_left.css（左侧导航样式）、img目录（存储图片）和js/formatJSON.js格式化插件
 |     |----templates：HTML模板文件
 |----pagination：DJANGO分页插件
 |----upload：文件上传目录
