# Yaw (V 1.3)
_Второе название:_
**P***ersonal* **C***omputer* **R***emote* **C***ontrol* **B***ot*

**Подходит только для Windows.**
*Основные тесты проходили на Windows 10.*

Персональный телеграм бот для управления компьютером на растоянии.

_Основной кодер:_ [**Revavi**](https://t.me/CleanVeins)  
_Помощь в разработке:_ [**msihek**](https://github.com/msihek)  
_Помощь с идеями:_ [**Chonnon**](https://t.me/wtflony)

## Команды бота

**/status** - *проверяет статус ПК (Вкл/выкл)*  
**/shutdown <время, сек>** - *полностью выключает ПК и бота через указанный промежуток времени*  
**/lock** - *блокирует ПК без выключения*  
**/sleep** - *вводит ПК в режим сна*  
**/reboot <время, сек>** - *перезапускает ПК через указанный промежуток времени*  
**/screenshot** - *делает скриншот монитора*  
**/workload** - *выводит данные загруженности процессора и оперативной памяти ПК*  
**/processes** - *выводит список запущенных процессов на ПК*  
**/kill <PID>** - *убивает процесс по его ID на ПК*  
**/runfile <полный путь до файла>** - *запускает файл на ПК по указанному пути*  
**/savepath <имя ярлыка без пробелов> <полный путь до файла>** - *сохраняет ярлык для быстрого запуска файла на ПК*  
**/fastrun <имя ярлыка>** - *запускает файл по сохранённому ранее ярлыку*  
**/waitbreak** - *отменяет выключение/перезапуск ПК*  
**/cmd <команда>** - *выполняет указанную команду в консоли на ПК*  
**/cd <путь>** - *Меняет рабочий каталог для команд /cmd*

## Зависимости

  - **Python**
  - **telebot (pip install pyTelegramBotAPI)**
  - **PyAutoGui (pip install PyAutoGUI)**
  - **PSUtil (pip install psutil)**
  - **PyScreeze (pip install pyscreeze)**
  - **Pillow (pip install pillow)**

## Как установить

  В начале создайте бота через [BotFather](https://t.me/BotFather), используя команду /newbot!  
  Ваш UID вы можете получить при запуска бота и вводе любой команды или же через [этого бота](https://t.me/userinfobot)

  Скачайте последний релиз бота, а затем следуйте инструкции в описании релиза.

### Список изменений
***Подробнее вы можете узнать в информации про релизы** (начиная с v1.3)*

**V 1.0 (Полностью написанна Revavi) >>** *НЕ РЕКОМЕНДУЕТСЯ ДЛЯ ИСПОЛЬЗОВАНИЯ*
  - /shutdown

**V 1.1 (Полностью написанна msihek) >>** *НЕ РЕКОМЕНДУЕТСЯ ДЛЯ ИСПОЛЬЗОВАНИЯ*
  - /sleep
  - /reboot
  - Изменение кода, названия команд
 
**V 1.2 >>**
  - /lock
  - /status
  - /screenshot
  - /workload
  - /processes
  - /runfile
  - /savepath
  - /fastrun
  - Изменение кода, названия команд

**V 1.3 >>**
  - оптимизация
  - /waitbreak
  - /cmd
  - /cd
  - Баг фикс
