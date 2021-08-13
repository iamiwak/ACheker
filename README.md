# ACheker.luaс
____
**Установка**
Установить lib и ACheker.luac в «*корень*/moonloader/»

**Работа скрипта**
Изначально, работают все 3 чекера и включаются по очереди с задержкой в 1.2 секунды после авторизации!
Если какой-то чекер не включился: [тык](#Если-скрипт-перезагрузился,-чтобы-восстановить-работу-чекеров-следует-ввести-команды:)

**Команды**

`/acsettings <list> <type> <command> [value]` - настройка чекера, команды;
`/stop <list>` - включить/выключить отображение чекера (изначально включено).

## Чекеры (листы):
* `a` — админский;
* `l` — лидерский;
* `h` — хелперский.

## Типы:
### fh
* `font <название шрифта>` — меняет шрифт для шапки чекера;
* `height <высота шрифта>` — меняет размер текста для шапки чекера;
* `flags <сумма флагов>` — устанавливает выделение шрифта для шапки чекера;
    * Флаги: 0 — none, 1 — bold, 2 — italics, 4 — border, 8 — shadow, 16 — underline, 32 — strikeout.
* `color <ABGR-цвет, пример красного цвета: 0xFF0000FF>` — меняет цвет для шапки чекера.

### fl
* `font <название шрифта>` — меняет шрифт для элементов чекера;
* `height <высота шрифта>` — меняет размер текста для элементов чекера;
* `flags <сумма флагов>` — устанавливает выделение шрифта для элементов чекера.
    * Флаги: 0 - none, 1 - bold, 2 - italics, 4 - border, 8 - shadow, 16 - underline, 32 - strikeout.

### c
* Для админского: `al` — включает/отключает отображение уровень администратора;
* Для лидерского: `f` — включает/отключает отображения фракции лидера;
* Общие:
    * `id` — включает/отключает отображение ID администратора;
    * `edit` — позволяет изменить расположение чекера.

____

#### Если скрипт перезагрузился, чтобы восстановить работу чекеров следует ввести команды:
`upda` — для админского чекеров;
`updl` — для лидерского чекера;
`updh` — для хелперского чекера;

**Не злоупотребляйте этими командами.**

