# STlink v2.1


 - swd 6-pin IDC pinout

|	2	|	4	|	6	|
|:-----:|:-----:|:-----:|
|swdio	|swclk	|swo	|			
|VTref	|nRESET	|GND	|
|	1	|	3	|	5	|

 - swim интерфейс для stm8
 - uart
 - Контрольные точки снизу платы с swdio,swclk,nRESET,3v3,gnd,boot0,Rx,Tx. [mpp_stlink_v2x1_fw_jig](https://github.com/mpp2508/mpp_stlink_v2x1_fw_jig) для быстрой смены прошивки программатора, точнее бутлоадера. Прошивка обновляется с помощью ST-Link Utility. Причем это можно сделать как и другим программатором, так и с помощью переходника uart и утилиты demonstrator. То есть, если это будет ваш первый программатор, который вы самостоятельно собираете, нет необходимости покупать другой программатор. Достаточно, например переходника USB-uart, который можно собрать без необходимости прошивки.

![](/img/001.PNG)