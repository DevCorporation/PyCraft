# PyCraft
Мультиплеер Войти / выход из системы (я только не пробовал, пока одновременно два ...)
Создание мира (по крайней мере ...)
Деревья: 1 тип
Руда: нет
Цветы: нет
Разное: нет ...
Разрушение блока (хотя тип элемента, который появляется другой ...)
Песок, гравий: падает
Пункт (так что так должен сделать)
Проверенные: скамейка, каменный резак, грудь, плита, двери, знаки, факелы
Кирка, лопата, топор, мотыга, меч: сломаны.
Биологический икру (появится независимо от яркости ...)
Исправлен баг со стеной
Летучая мышь: 
Это можно манипулировать с помощью scratch 1.4 удаленных соединений датчиков.
Атака (возможно)

И т.д и т.п

То не может ничего сделать. Для тех , кто карманный Mine MP рекомендуется.

!!Осторжно КРИВОЙ ПЕРЕВОД (Спасибо гуглу за перевод)!!
Царапины 1.4 сотрудничество

Царапина 1.4 имеет функцию дистанционного подключения датчиков. Вы должны быть в состоянии манипулировать Minecraft организмов с нуля, чтобы использовать эту функцию. удаленные подключения датчиков не в 2,0 нуля.

демонстрация

Как использовать

Царапины 1.4 подготовлен
Чтобы разрешить удаленные подключения датчика в пустом месте
Щелкните правой кнопкой мыши, чтобы выбрать значение датчика
разрешить удаленные подключения датчиков
Определить IP-адрес компьютера, который работает под управлением чистого листа
IPCONFIG
Для изменения настроек PyCraft
src/pycraft/service/config.pyscratch_networkИзменение
192.168.197.149 так scratch_network = '192.168.197.0/24'
192.168.20.15 если scratch_network = '192.168.20.0/24'
Для запуска PyCraft
Автоматически scratch_networkсканирует сеть на указанный де
На экране , с которого вы начинаете PyCraft успешное соединение new scratch agentотображается
Царапина enabledпосылается (она будет транслироваться в прямом ).
Создайте программу в пустом месте
образец
Когда сообщение посылается (вещает) приходит, значение в "значения датчика (значение датчика)" установлено
Отправить сообщение (в эфир) Иногда, будет посылать вам следует установить значение для "переменной (переменной)"
Направлено из PyCraft (радиопередача) устанавливается с сообщением "значение датчика (значение датчика)."
enabled : При подключении к PyCraft был успешным
mob found: search mobПодарок, когда организм находится
mob_id : Количество организмов
mob not found: search mobПодарок, когда вы не нашли биологический
status found: show statusПодарок, когда было установлено , что состояние организма (жил)
head_yaw : Горизонтальная ориентация головки (-180 градусов до 180 градусов, разница между ориентацией тела)
pitch : Глава вертикального направления (-90 градусов до 90 градусов)
status not found: show statusПодарок, когда вы не знаете , состояние организма (умер)
player found: search playerПодарок, когда организм находится игрок
player_id : Номер игрока
distance : Расстояние организма и игрока
angle_h : разница между положением в горизонтальном направлении, и игрок головы (-180 градусов до 180 градусов)
angle_v : разница между положением вертикальной ориентации, и игрок головы (-90 градусов до 90 градусов)
player not found: search playerПодача, когда организм не может найти игрока
Отправить с нуля (для передачи), установленного с сообщением "переменной (переменной)"
search mob : Найти организмы
mob_type : Найти тип организма (целое число)
control : Доминируют биологический
mob_id: Организмы доминировать число ( mob_foundв было получено mob_id)
mob_name : Имя для организма (только на японском языке)
free : Для того, чтобы освободить организмы
mob_id: Из организмов, номер выпуска ( controlв указанном mob_id)
show status : Просмотр состояния организма
mob_id: Из числа целевых организмов ( controlв указанном mob_id)
search player : Чтобы найти игрока, окружающие организмы
mob_id: Из числа целевых организмов ( controlв указанном mob_id)
move Чтобы переместить биологический
mob_id: Из числа целевых организмов ( controlв указанном mob_id)
yaw : Ориентация тела (-360 градусов до 360 градусов, разница между текущим направлением)
head_yaw : Горизонтальная ориентация головки (-180 градусов до 180 градусов, разница между ориентацией тела)
pitch : Глава вертикальной ориентации (-180 градусов до 180 градусов, разница между текущим направлением)
movement : До и после того, как от количества движения (-1,0 ~ 1,0)
mob_type	вид
десять	курица
одиннадцать	корова
двенадцать	свинья
13	овца
14	волк
15	сельский житель
16	Mushurumu
17	кальмар
19	летучая мышь
32	зомби
33	рептилия
34	остов
35	паук
36	Zombie Свиньи Man
37	муть
38	Эндер Человек
39	Серебряная рыба
40	Пещерный паук
41	порыв ветра
42	Магма куб
