# Полная автоматизация двухкомнатной квартиры :department_store: c помощью Home Assistant, MegaD-2561, Sonoff и Electrodragon
В репозитории представлена полная конфигурация [Home Assistant](https://github.com/home-assistant/hassio) для всех устройств в квартире.

Read this in other languages: [English](README.md), [Русский язык](README.ru.md).

______________

Автоматизация была сделана при помощи реле [Wifi IoT Relay Board Based on ESP8266](https://www.electrodragon.com/product/wifi-iot-relay-board-based-esp8266/) и [Sonoff Basic WiFi Wireless Switch](https://www.itead.cc/smart-home/sonoff-wifi-wireless-switch.html) с прошивкой [Tasmota](https://github.com/arendst/Tasmota). Реле установлены в распаячные коробки увеличенного размера в стенах квартиры. Для получения данных с датчиков и частично для управления реле используется многофункциональный контроллер [MegaD-2561](https://www.ab-log.ru/smart-house/ethernet/megad-2561).

Описание истории создания в статьях на Хабре:
- [Умная хрущёвка на максималках](https://habr.com/ru/post/503646/). 
- [Умная хрущёвка на максималках. Продолжение](https://habr.com/ru/post/506550/). 
- [Как я 1000 дней пользовался OpenHAB, а затем перешел на Home Assistant](https://habr.com/ru/post/485848/). 

Текущий вид интерфейса Home Assistant:
![Текущий вид интерфейса Home Assistant](https://github.com/empenoso/two-bedroom-flat-Home-Assistant/blob/master/2019_11_screenshot.png)
_________
:sound: В планах миграция на прошивку [ESPHome](https://github.com/esphome/esphome).
