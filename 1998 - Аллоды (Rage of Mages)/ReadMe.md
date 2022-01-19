:clipboard: 19.01.2022 Win10 x64

## Аллоды: Печать тайны 

:star: :star: :star: :star: :star:

### Игра

https://www.gog.com/game/rage_of_mages

### Зависание видео

Заменить файл smackw32.dll в папке с установленной игрой на [этот файл](https://github.com/Unicornum/Db.Games/releases/download/Allods/smackw32.dll).

> Проблема возникает не всегда, поэтому замену делать сразу не стоит; также иногда это приводит к мерцанию видео.

### DxWnd

При проблемах с запуском игры через созданный оригинальным инсталлятором ярлык:

1. Скачать [DxWnd](https://github.com/Unicornum/Db.Games/releases/download/Allods/DxWnd_v2_05_80.rar) и распаковать в любое место.
2. Запустить DxWnd, в окне выбрать File -> Import -> папка DxWnd -> exports -> Rage of Mages.
3. Изменить настройки (RClick -> Modify); см. скриншот.
4. В папке игры переименовать ddraw.dll to ddraw.dll.baсkup.
5. Запускать игру GOG ярлыком при запущенном DxWnd!

![DxWnd](DxWnd.png)

[Оригинал](https://sourceforge.net/projects/dxwnd/)
