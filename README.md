# aria2-docker
使用alpine构建的aria2镜像
###使用方法
- 编辑aria2.conf配置文件
- 修改docker-compose.yml 中的挂载点及端口
- 运行 docker-compose build
- 运行 dokcer-compose start
###镜像信息
- 配置文件位置为/home/aria2/aria2.conf
- VOLUME /home/aria2/downloads
- EXPOSE 6800
###注意事项
- 注意下载目录的权限
- 注意aria2.session文件的位置及权限
