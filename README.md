# Тестер компонентов

## Краткое описание
Тестер компонентов основан на базе проекта от немецких разработчиков Markus Frejek и Karl-Heinz Kübbeler. Данный прибор использует альтернативное программное обеспечение с некоторыми изменениями в пользовательском интерфейсе и переработанными методами тестирования и измерения.

Данная версия работает на микроконтроллере LGT8F328P, который наследует архитектуру и набор команд микроконтроллера ATmega328p, но имеет более совершенную периферию:
* 12-битный АЦП
* несколько прецизионных источников опорного напряжения
* ЦАП
* улучшенный аналоговый компаратор
* дополнительный таймер
* ускоритель целочисленных операций
* увеличенное количество портов ввода-вывода
* и др.

Так же, данный микроконтроллер поддерживает работу на тактовой частоте до 32МГц, что вдвое превышает тактовую частоту микроконтроллеров ATmega.

Кроме того, микроконтроллер LGT8F328P выполняет большинство команд за меньшее количество тактов, по сравнению с Atmega, что дает дополнительный прирост производительности.

Более совершенная периферия и лучшая производительность микроконтроллера LGT8F328P позволила реализовать более точные методы измерения, а также, расширить диапазоны измерений, по сравнению с тестерами компонентов, использующих микроконтроллеры ATmega.

## Рекомендации по безопасности
Тестер компонентов — это не профессиональный цифровой измеритель! Это простой тестер для измерения некоторых деталей.

Тестовые контакты не имеют защиты и не допускают работу на напряжениях выше, чем 5В. Не используйте тестер для цепей под высоким напряжением! Просто используйте его для демонтированных электронных компонентов.

Это не просто безопасность, ваша жизнь может находиться в опасности, если вы соедините тестовые контакты с цепью под напряжением или источником питания, особенно в электросети!

> $\color{red}\texttt{\large⚠\normalsize\ Предупреждение}$
> * Если Вы тестируете конденсатор, обязательно разрядите его прежде, чем подключить к прибору!
> * Если Вы тестируете катушку индуктивности, то дождитесь завершения тестирования перед тем, как отключить ее от прибора!

## Короткая ссылка на документ
<http://t.ly/nGNKp>







# Примеры разметки, удалить позже

* <https://www.markdownguide.org/basic-syntax/>
* <https://www.markdownguide.org/hacks/>
* <https://docs.github.com/en/get-started/writing-on-github>
* <http://pad.haroopress.com/user.html>
* <https://www.compart.com/en/unicode/block>
* <https://gist.github.com/luigiMinardi/4574708d404cdf4fe0da7ac6fe2314db>

[![Видео](https://img.youtube.com/vi/StTqXEQ2l-Y/0.jpg)](https://www.youtube.com/watch?v=StTqXEQ2l-Y "Кликни для просмотра видео")

> [!NOTE]  
> Highlights information that users should take into account, even when skimming.

> [!TIP]
> Optional information to help a user be more successful.

> [!IMPORTANT]  
> Crucial information necessary for users to succeed.

> [!WARNING]  
> Critical content demanding immediate user attention due to potential risks.

> [!CAUTION]
> Negative potential consequences of an action.

> ![](https://placehold.co/130x30/red/white?text=Внимание!!!&font=open-sans) Внимание!
>
> gdjkfgh



$\color{red}\text{\LARGE⚠\normalsize\ Предупреждение}$

$\color{red}\textup{\Large⚠\normalsize\ Предупреждение}$

$\color{red}\textbf{\Large⚠\normalsize\ Предупреждение}$

$\color{red}\text{\Large⚠\normalsize\ \itПредупреждение}$

$\color{red}\texttt{\Large⚠\normalsize\ Предупреждение}$

$\colorbox{red}{\textsf{lorem ipsum ⚠}}$

$\large{ \color{white} \colorbox{Red}{ \textsf{⚠ Предупреждение}}}$


| $\color{black}{\textsf{Black}}$ |  $\color{blue}{\textsf{Blue}}$ | $\color{brown}{\textsf{Brown}}$ | $\color{darkgray}{\textsf{Dark Gray}}$  | $\color{gray}{\textsf{Gray}}$ | 
| ------------- | ------------- | ------------- | ------------- | ------------- | 
| $\color{lightgray}{\textsf{Light Gray}}$ |  $\color{green}{\textsf{Green}}$ | $\color{lightblue}{\textsf{Light Blue}}$ | $\color{lime}{\textsf{Lime}}$  | $\color{magenta}{\textsf{Magenta}}$ |
| $\color{olive}{\textsf{Olive}}$ |  $\color{orange}{\textsf{Orange}}$ | $\color{pink}{\textsf{Pink}}$ | $\color{purple}{\textsf{Purple}}$  | $\color{red}{\textsf{Red}}$ | 
| $\color{teal}{\textsf{Teal}}$ |  $\color{violet}{\textsf{Violet}}$ | $\color{white}{\textsf{White}}$ | $\color{yellow}{\textsf{Yellow}}$  | $\color{BurntOrange}{\textsf{Burnt Orange}}$ |
| $\small{ \color{white} \colorbox{Green}{ \textsf{White on Green}}}$   | $\color{pink} \fcolorbox{teal}{blue}{ \textsf{ \small{Pink on Blue w/ teal border}}}$  | $\color{black} \fcolorbox{white}{red}{ \small{ \textsf{Black on Red w/ white border}}}$   | $\color{black} \fcolorbox{red}{white}{ \small{ \textsf{Black on White w/ red border}}}$ | $\color{black} \colorbox{BurntOrange}{ \small{ \textsf{Black on Orange}}}$ |
| $\color{purple} \colorbox{olive}{ \textsf{Purple on Olive}}$ |  $\color{green} \colorbox{white}{ \textsf{Green on White}}$ | $\color{Orange} \fcolorbox{blue}{black}{ \textsf{Orange on Black w/ blue border}}$  | $\color{blue} \small{ \fcolorbox{lime}{white}{ \textsf{Blue on White w/ lime border}}}$ | $\color{lime} \colorbox{violet}{ \textsf{Lime on Violet}}$ |



**✄❗⚠**

