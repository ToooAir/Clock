# Usage
A script for OBS Studio (https://obsproject.com/) to embed a current date and timestamp. No other softwares and plugins are needed. Just OBS Studio and the built-in Browser Source input.

這代碼是為了在OBS Studio中嵌入現在的日期和時間而寫的。而且不需要安裝其他軟件或插件即可使用，只需要OBS Studio和原生的Browser Source輸入。

## Examples
* Vanilla
```https://toooair.github.io/Clock/```

* White text
```https://toooair.github.io/Clock/?style=font: bold 30px monospace; color: white;```

* Rounded rectangle
```https://toooair.github.io/Clock/?style=font: bold 30px monospace; color: lightgray; display: inline-block; border-radius: 5px; padding: 2px 5px; background-color: rgba(0, 0, 0, 0.5);```

* With US date formatting
```https://toooair.github.io/Clock/?style=font: bold 30px monospace; color: lightgray; display: inline-block; border-radius: 5px; padding: 2px 5px; background-color: rgba(0, 0, 0, 0.5)&format=MMM DD YYYY HH:mm:ss;```

## Parameters
Use **style** to add more style to the output element
While **bodyStyle** for the style to the body element
Use **format** to control the date format. For the syntax, see https://momentjs.com/docs/#/displaying/format/

## License
This software is licensed under the MIT License.