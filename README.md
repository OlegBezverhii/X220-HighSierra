# X220-HighSierra
Clover For Lenovo X220

# Для тех, кто вдруг решил поставить High Sierra в 2024 году на X220. 

В целом, было несколько проблем:
* Прошивка BIOS
* Система
* Clover

Обновление [БИОС](https://4pda.to/forum/dl/post/17002064/X220_v1.46_Modified_BIOS.zip) делал из под LiveUSB, но скрипт обновления и лог писал, что "verifying bios fail reflashing". Почитал в интернете, боялся, что сломалось что-то, но перезагрузился и зашел в BIOS - все прекрасно, появилось Advanced меню.

Сначала пришлось на торрентах (например, [здесь](https://nnmclub.to/forum/viewtopic.php?p=10023537) ) найти обновленную версию Mac OS, так как в старых версиях сертификат кончился и продолжить установку (даже после смены времени назад) не получалось.

После первого этапа установки с помощью файлов с [сайта](https://x220.mcdonnelltech.com), старый Clover не смог найти уже находящуюся систему на жестком диске. BDUшкой сделал обновленную версию, скинул конфигурационные файлы со старого кловера и всё завертелось. Wi-Fi модуль стандартный заменил на Atheros AR5B195, пришлось дополнительно поправить plist как на видео - [https://www.youtube.com/watch?v=3PgHDYleXRk](https://www.youtube.com/watch?v=3PgHDYleXRk). 

Файлы с настройками и новым Clover в Releases.
