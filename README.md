# ibFinder

### English

This is a tool to find out, explore and configure Bluetooth Smart beacons managed under the server-side Management System iBecom xMS produced by iBecom LLC.

ibFinder fully supports iBecom beacons to configure, firmware update, monitor and post data to server and RSSI graph visualization.

ibFinder supports Kontakt beacons to configure, monitor and post data to server and RSSI graph visualization. It works better, more stable and user-friendly than official Kontakt application. You need to know Kontakt DevCode to use ibFinder.

ibFinder supports Estimote beacons to monitor and RSSI graph visualization.

ibFinder works on iOS platform only. On iOS 7 it is possible to visualize RSSI of each Bluetooth broadcast channel (#37, #38, #39) separately. Keep your iOS 7 tech tool devices out of upgrade to iOS 8 - new iOS system doesn't support this feature.

You can get installation ipa file from this repo or download and install ibFinder directly from our corporate web site.

https://ibecom.ru/ibfinder

To use iBFinder you have to be a customer of iBecom LLC. Try the following parameters to unlock auth screen in demo mode:

1. System Settings - ibFinder - Auth - Address: contentsrv.ibecom.ru
1. System Settings - ibFinder - Auth - Server Root: ibfinder/mobile
1. System Settings - ibFinder - Auth - Port: 80
1. Authorization Required screen - Login: demo
1. Authorization Required screen - Password: demo

After pass through auth screen you will get "No devices found" message in device list. To manage your devices feel free to write message to support@ibecom.ru, send your beacons identificators (iBecom and Kontakt devices only) and get your personalized account.

To get documentation look at Wiki.

### Русский

Это инструмент для обнаружения, определения параметров и конфигрурирования Bluetooth Smart маяков, поддерживаемых через систему управления контентом iBecom xMS, разработанную компанией ООО Ибиком.

ibFinder полностью поддерживает маяки производства Ибиком, позволяя изменять параметры, обновлять встроенное программное обеспечение маяка, отслеживать состояние и передавать его на сервер системы, а также визуализировать график изменения мощности принимаемого сигнала (RSSI).

ibFinder поддерживает маяки производства Kontakt, позволяя изменять параметры, отслеживать состояние и передавать его на сервер системы, а также визуализировать график изменения мощности принимаемого сигнала (RSSI). ibFinder работает лучше, стабильнее и удобнее, чем официальная утилита конфигурирования Kontakt. Для работы с ibFinder вам необходимо знать Kontakt DevCode.

ibFinder поддерживает маяки производства Estimote, позволяя визуализировать график изменения мощности принимаемого сигнала (RSSI).

ibFinder работает только на платформе iOS. На версии 7 возможно отображение RSSI по каждому из широковещательных Bluetooth каналов (#37, #38, #39) по отдельности. Сохраняйте ваши iOS 7 инженерные устройства, не позволяя им обновиться до 8 версии iOS, потому что в новой версии операционной системы эта возможность уже отсутствует.

Вы можете установочный ipa файл из этого репозитория или скачать и установить ibFinder напрямую с нашего корпоративного веб сайта.

https://ibecom.ru/ibfinder

Для того, чтобы использовать ibFinder, вам необходимо быть клиентом компании Ибиком. Вы можете использовать следующие параметры для того, чтобы авторизоваться на стартовом экране приложения в демонстрационном режиме:

1. System Settings - ibFinder - Auth - Address: contentsrv.ibecom.ru
1. System Settings - ibFinder - Auth - Server Root: ibfinder/mobile
1. System Settings - ibFinder - Auth - Port: 80
1. Authorization Required screen - Login: demo
1. Authorization Required screen - Password: demo

После авторизации вы увидите сообщение "No devices found" в списке устройств. Для работы со своими маяками напишите письмо на адрес support@ibecom.ru, приложив список идентификаторов маяков (поддерживаются только маяки производства iBecom и Kontakt) и получите ваш персонализированный аккаунт.

Для получения полной документации перейдите в раздел Wiki.
