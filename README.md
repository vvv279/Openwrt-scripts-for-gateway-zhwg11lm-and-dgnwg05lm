# Обновляем\даунгрейд OpenWRT на шлюзах Xiaomi DGNWG05LM и Aqara ZHWG11LM

Выражаю благодарность [Ivan Belokobylskiy](https://github.com/devbis) и [mr G1K](https://github.com/G1K) за помощь в обновлении и даунгрейде OpenWRT.  который упростят переход с OpenWRT 19.07 на OpenWRT 21.02

**Проект Open Lumi Gateway**

https://github.com/openlumi

**Исходники**

1) https://openlumi.github.io/releases/

2) https://github.com/openlumi/releases/tree/2b87c8a6a5610e238b5b9748b8e461790c7c7919


**Release of OpenWrt 21.02.0 for Xiaomi DGNWG05LM and Aqara ZHWG11LM**

https://github.com/openlumi/openwrt/releases

Для удобства я создал скрипты, которые помогут вам обновить OpenWRT с версии 19.07 до 21.02 или сделать даунгрейд OpenWRT с версии 21.02 до 19.07. После того, как скрипт отработает, то шлюз перезагрузится и ждем, когда поднимется точка доступа с именем OpenWRT. Настройте подключение к роутеру WiFi.

**Внимание! Перед запуском скрипта, обязательно сделайте резервную копию шлюза**

**Шлюз Aqara ZHWG11LM**

Обновляем OpenWRT с версии 19.07 до 21.02
```
wget https://raw.githubusercontent.com/DivanX10/Openwrt-scripts-for-gateway-zhwg11lm-and-dgnwg05lm/main/aqara_zhwg11lm_update_openwrt_21.sh -O - | sh
```
Даунгрейд OpenWRT с версии 21.02 до 19.07
```
wget https://raw.githubusercontent.com/DivanX10/Openwrt-scripts-for-gateway-zhwg11lm-and-dgnwg05lm/main/aqara_zhwg11lm_downgrade_openwrt_19.sh -O - | sh
```



**Шлюз Xiaomi DGNWG05LM**

Обновляем OpenWRT с версии 19.07 до 21.02
```
wget https://github.com/DivanX10/Openwrt-scripts-for-gateway-zhwg11lm-and-dgnwg05lm/blob/main/xiaomi_dgnwg05lm_update_openwrt_21.sh -O - | sh
```
Даунгрейд OpenWRT с версии 21.02 до 19.07
```
wget https://raw.githubusercontent.com/DivanX10/Openwrt-scripts-for-gateway-zhwg11lm-and-dgnwg05lm/main/xiaomi_dgnwg05lm_downgrade_openwrt_19.sh -O - | sh
```

