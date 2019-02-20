# netcrakertask
netcrakertask

## Немного о проекте:
+ Используемый язык Java
+ Сборка проекта Maven
+ Используемый браузер Chrome
+ Работа с браузером осуществляется через библиотеку selenium

## Предварительная настройка для работы программы:
1. Поместите файл keywords.csv в каталог по умолчанию C:\Users\* ,где * - имя вашего компьютера
2. Поместите chromedriver в каталог по умолчанию C:\chromedriver.exe (изменить диск можно в файле application.properties)
3. Заполните файл keywords.csv следующими данными:
  
  ```
  Action,Locator Type,Locator Value,setValue, PATH....
  open_browser,chrome
  open_url,,,https://www.google.com
  set_value,xpath,//*[@id="tsf"]/div[2]/div/div[1]/div/div[1]/input,NetCracker
  click_element,xpath,//*[@id="tsf"]/div[2]/div/div[2]/div[2]/div/center/input[1]
  verify_value,xpath,//*[@id="tsf"]/div[2]/div/div[2]/div/div[1]/input,value,NetCracker
  click_element,id,logo,
  snapshot,,,,d://test2.png
  close_browser
  ```
  