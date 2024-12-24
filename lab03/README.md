### Underlay. IS-IS

### Цель
Настроить IS-IS для Underlay сети


### Схема сети Underlay IS-IS
![img_19.png](IS-IS.png)

### Таблица ip адресов

|Source switch|Source Interface|Source IP|Destination switch|Destination interface|Destination IP|Loopback address|
|---|---|---|---|---|---|---|
SPINE-01|Eth1/1|172.16.250.1|LEAF-01|Eth1/1|172.16.250.0|
SPINE-01|Eth1/2|172.16.250.5|LEAF-02|Eth1/1|172.16.250.4|
SPINE-02|Eth1/1|172.16.250.3|LEAF-01|Eth1/2|172.16.250.2|
SPINE-02|Eth1/2|172.16.250.7|LEAF-02|Eth1/2|172.16.250.6|
SPINE-01|Eth1/3|172.16.250.9|LEAF-03|Eth1/1|172.16.250.8|
SPINE-02|Eth1/3|172.16.250.11|LEAF-03|Eth1/3|172.16.250.10|