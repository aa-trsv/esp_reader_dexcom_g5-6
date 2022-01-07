# esp_reader_dexcom_g5-6

Прошивка для M5Stick-C Plus(https://a.aliexpress.com/_9G4p2w);

Позволяет считывать показания с трансмиттеров Dexcom G5 и G6;

Прошивается через Arduino IDE, предварительно нужно добавить в настройках Arduino IDE ссылку для Менеджера плат https://dl.espressif.com/dl/package_esp32_index.json и перезапустить Arduino IDE;

При прошивке выбирать плату M5Stick-C;

В файле ESP32_Reader_me, в строке transmitterID = "40MEYD" указать свой ID трансмиттера;
