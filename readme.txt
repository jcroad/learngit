﻿#activeMQ配置
ActiveMQ.URL=tcp://172.16.102.253:61616
ActiveMQ.username=admin
ActiveMQ.password=admin

#zookeeper配置172.16.102.245
zookeeper.address=172.16.102.253:2181
dubbo.CacheFilePath=dubbo.cache

js 获取当前时间 年月日
var date = new Date();

date .getYear(); //获取当前年份(2位)
date .getFullYear(); //获取完整的年份(4位)
date .getMonth(); //获取当前月份(0-11,0代表1月)
date .getDate(); //获取当前日(1-31)
date .getDay(); //获取当前星期X(0-6,0代表星期天)
date .getTime(); //获取当前时间(从1970.1.1开始的毫秒数)
date .getHours(); //获取当前小时数(0-23)
date .getMinutes(); //获取当前分钟数(0-59)
date .getSeconds(); //获取当前秒数(0-59)
date .getMilliseconds(); //获取当前毫秒数(0-999)
date .toLocaleDateString(); //获取当前日期
var mytime=date .toLocaleTimeString(); //获取当前时间
date .toLocaleString( ); //获取日期与时间

asdfasdf