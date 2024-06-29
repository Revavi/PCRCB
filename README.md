# Yaw (V 2.0)
_Второе название:_
**P***ersonal* **C***omputer* **R***emote* **C***ontrol* **B***ot*

**Подходит только для Windows.**  
*Основные тесты проходили на Windows 10.*

Персональный телеграм бот для управления компьютером на растоянии.

_Основной кодер:_ [**Revavi**](https://t.me/CleanVeins)  
_Помощь в разработке:_ [**msihek**](https://github.com/msihek)  
_Помощь с идеями:_ [**Chonnon**](https://t.me/wtflony)

## Команды бота и функционал

**/status** - *проверяет статус ПК. Нет ответа - ПК выключен.*  
**/shutdown <время, сек>** - *Полностью выключает ПК и бота через указанный промежуток времени. Если промежуток не указан - выключается сразу*  
**/lock** - *Блокирует ПК без выключения*  
**/sleep** - *Вводит ПК в режим сна*  
**/reboot <время, сек>** - *Перезапускает ПК через указанный промежуток времени. Если промежуток не указан - перезапускает сразу*  
**/waitbreak** - *Отменяет перезапуск или выключение ПК*  
**/screenshot** - *Отправляет снимок экрана ПК*  
**/record <время, сек>** - *Начинает запись микрофона на указанное время. Если время не указано - 30 секунд*  
**/setvolume <громкость>** - *Устанавливает на ПК указанную громкость в процентах. Если громкость не указана - 0%*  
**/workload** - *Выводит данные загруженности процессора и оперативной памяти*  
**/processes** - *Выводит список запущенных процессов*  
**/kill <PID>** - *Убивает процесс по его ID на ПК*  
**/runfile <полный путь до файла>** - *Запускает файл по указанному пути*  
**/savepath <имя ярлыка без пробелов> <полный путь до файла>** - *Сохраняет ярлык для быстрого запуска файлов*  
**/fastrun <имя ярлыка>** - *Запускает файл по сохранённому ранее пути*  
**/removepath <имя ярлыка>** - *Удаляет указанный ярлык*  
**/cmd <команда>** - *Вводит указанную команду в консоль*  
**/cd <путь до папки>** - *Меняет рабочий каталог для /cmd*  
**/changepass <пароль>** - *Меняет пароль для получения доступа к боту. Не указывайте пароль, если хотите отключить эту функцию*  
**/setadmcount <кол-во>** - *Устанавливает максимальное кол-во пользователей, которые могут получить доступ к боту*  
**/checkadm** - *Выводит никнеймы пользователей, которые имеют доступ к боту. Также это меню для удаления доступа к боту у конкретных пользователей*  
**/entercode <пароль>** - *Команда только для пользователей, которые не имеют доступа к боту. Если указан верный пароль, выдаёт доступ к боту*  

**Если вы отправите боту любой файл, видео, голосовое сообщение и т.д., то он сохранит их в папку *uploads*.**

## Зависимости

  - **Python**
  - **TelegramBotAPI *(pip install pyTelegramBotAPI)***  
  - **Screeze *(pip install PyScreeze)***  
  - **Pillow *(pip install pillow)***  
  - **PSUtil *(pip install psutil)***  
  - **PyAutoGUI *(pip install PyAutoGUI)***  
  - **flet *(pip install flet)***  
  - **pystray *(pip install pystray)***  
  - **pywin32 *(pip install pywin32)***  
  - **pycaw *(pip install pycaw)***  
  - **pyAudio *(pip install PyAudio)***

  После установки python вы можете скачать все зависимости через файл requirements.txt:  
  пропишите в консоли *(win+r -> cmd)*: *pip install -r path/to/requirements.txt*

## Как установить

  В начале создайте бота через [BotFather](https://t.me/BotFather), используя команду /newbot.   
  Ваш UID вы можете получить при запуска бота и вводе любой команды или же через [userinfobot](https://t.me/userinfobot)  

  Скачайте последний релиз бота, а затем следуйте инструкции в описании релиза.