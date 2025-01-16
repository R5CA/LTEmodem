Набор пакетов для конфигурации и отображения статистики модема DW5829e-esim в OpenWrt  
  
Использованные пакеты:  
sms-tool: https://github.com/obsy/sms_tool/tree/fce2b931c8d749c28b8281363950e963c98324eb  
3ginfo-lite: https://github.com/4IceG/luci-app-3ginfo-lite/tree/289dd61b627101504f100515ca1632f61beae6e1  
modemband: https://github.com/4IceG/luci-app-modemband/tree/e2cae4687addd68f86d16b510d45ae851ca7f19e  
luci-app-sms-tool-js: https://github.com/4IceG/luci-app-sms-tool-js/tree/749f16ee5020ba9b7901404faa848210aa2e8881  
  
В пакетах modemband и 3ginfo-lite добавлена поддержка модема dw5829e-esim, за основу взяты файлы конфигурации для модема dw5821 т.к. модемы практически идентичны и dw5829 является урезанной версией dw5821  
  
Для добавления пакетов необходимо в файл feeds.conf.default добавить строку  
```src-git LTEmodem https://github.com/R5CA/LTEmodem.git```
