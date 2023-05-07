要使设备正常工作，您必须：<br>
一、安装此插件<br>
配置——加载项——加载项商店——菜单——仓库——增加https://github.com/hunl1986/haos-broadlink-ac-mqtt——强制刷新页面——在加载项商店安装AC MQTT proxy for home assistant<br>
二、安装 Mosquitto broker管理 MQTT<br>
三、获取设备的 IP 和 MAC 地址<br>
四、配置AC MQTT proxy for home assistant<br>
  1、AC MQTT proxy for home assistant——配置——mqtt——把user后面值改为HA用户名，passwd后面值改为HA密码<br>
  2、devices按格式设置为需要连接的机器配置，可增加多个<br>
