# WordPress一键脚本
### 适用于centos7
### 脚本解决了主题插件安装等的文件权限问题
这边感谢 atrandys 提供一键安装 WordPress 的脚本。（包含SSL证书申请、MYSQL安装、PHP7.4部署、NGINX安装设置等）

yum install -y wget && wget https://raw.githubusercontent.com/atrandys/wordpress/master/wp_install.sh && chmod +x wp_install.sh && ./wp_install.sh
