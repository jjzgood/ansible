# ansible
some ansible role
## 1. os_init 
* 关闭防火墙
* 修改系统限制
* 安装时间服务器
* 修改内核参数
* 关闭selinux
* 安装gcc gcc-c++ make vim 等工具包

## 2. nginx
* 安装nginx
* 修改nginx配置文件
* 修改端口
* 启动nginx

## 3. redis
* 安装redis
* 安装ruby
* 安装redis-gem
* 多个节点配置及其启动：
>for i  in {7006,7012,7018,7024};do ansible-playbook -t report -e redis_port=$i redis.yml;done
