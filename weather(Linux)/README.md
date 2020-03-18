
###编译
zzz@zzz-VirtualBox:/mnt/share/weather$ gcc -std=c99 weather_client.c cJSON.c -o weather_client

zzz@zzz-VirtualBox:/mnt/share/weather$ ./weather_client

=================HTTP天气客户端==================
请输入要查询天气的城市名称的拼音（如：beijing）：beijing
===========北京此时的天气情况如下===========
天气：晴
气温：19℃
时区：Asia/Shanghai
时差：+08:00
天气更新时间：2020-03-18T12:02:00+08:00
===========北京近三天的天气情况如下===========
【2020-03-18】
天气：晴
最高温：23℃
最低温：5℃
风向：西北
风速：45.00km/h
风力等级：6

【2020-03-19】
天气：晴
最高温：18℃
最低温：4℃
风向：西北
风速：25.20km/h
风力等级：4

【2020-03-20】
天气：晴
最高温：23℃
最低温：6℃
风向：西南
风速：16.20km/h
风力等级：3
