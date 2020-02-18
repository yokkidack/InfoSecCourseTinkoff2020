# Lection 2

- Основы сетей
- - Модель OSI,  Модель TCP/IP, ...

Зачем?

 ```
 ну их много лол
 ```

 ```
 критична основа всей инфраструктуры
 ```


MAC *Media Access Control*

IP *Internet Protocol adress*

[ARP](https://ru.wikipedia.org/wiki/ARP) *Adress resolution prot*


<dope scheme>

internet
<- router x2 (передача трафика в интернет и обратно)
    <- layer 3 backbone switch (ip и трафик)
        <- layer 3 switch (поменьше)
            <- layer 2 switch (еще меньше)
                <- device

## термины

*switch*  - маршрутизация

*router*  -  отправка трафика

*proxy* - менять/скрывать/балансировать

*firewall* - межсетевой экран

*load balancer* -  балансеровщик

*reverse proxy* - маскерующая функция

*intrusion detection* - смотрит копию трафика ищет атаки.

*prevention system* - блокирует запросы. очень дорого и все становится медленным. смотрит в трафик.

*Next Gen FireWall*


## StateFul and StateLess

StateFul - если запрос был инициирован файервол запомнит это и не заблокирует когдп придет ответ

StateLess - на все свои правила

## OSI модель

- физ уровень - провода         | network interface
- уровень данных - 0/1          |

- уровень сети - пакеты данных  | network

- уровеь транспорта - порты     | transport

- уровни приложений             | application

- - уровень сессиии - подготовка к отправке
- - уровень презентации - (шифрование)
- - уровень приложения

## DHCP


## Комутация

- работают только с мак адресами
- ARP

## VLAN

## STP ()

## BGP

?? TCPDump EVE-NG Олифер. 
