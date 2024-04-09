:clipboard: 9.04.2024 Win10 x64

## Risen

:star: :star: :star: :star: :star:

### Игра

https://www.gog.com/ru/game/risen

### Фикс русской локализации

> Устраняет рассинхрон между текстом и озвучкой.

[Отсюда](https://steamcommunity.com/sharedfiles/filedetails/?id=2404591957)

### ReShade

> Дополнительная постообработка кадра.

[Программа](https://reshade.me/)

[Risen.ini](Risen.ini)

### Разное

> Файл настроек ConfigUser.xml находится в папке C:\Users\*****\AppData\Local\Risen.

#### Widescreen

- В файле ConfigUser.xml установить разрешение экрана
```
<Window
 AdapterNumber="0"
 Bottom="1080"
 Left="0"
 RefreshRate="60"
 Right="2560"
 Top="0"
 Vsync="false"
 FOV="90.000000"
>
```
- В файле ...\Risen\data\ini\ConfigUser.xml в разделе Aspect16x9 заменить значение параметра VirtalWidth так, чтобы оно соответствовало эквивалентному соотношению сторон для высоты 768 пикселей, что равно 1820 для монитора с разрешением 2560x1080.
```
<Aspect16x9
  VirtalWidth="1820"
  VirtalHeight="768"
  EnableDrawScale="True"
>
```

#### Нормализация громкости звуков и диалогов

- Добавить строчку Master="765" в файл ConfigUser.xml

```
<Volume
  Ambient="255"
  Effect="252"
  Master="765"
  Music="203"
>
```

#### ⁉️ Remaster

> Есть проблема - после обновления игры до x64 мод перестал работать, т.к. был расчитан на x32.

https://www.nexusmods.com/risen/mods/22?tab=description
