# Раскладка для 60% клавиатуры

Руководство, которое описывает создание раскладки для повседневного использования 60% клавиатуры.

![Раскладка клавиатуры](./img/default-layer.png)

## Оглавление

* [Введение](#введение)
  * [Для кого](#для-кого)
  * [Что понадобится](#что-понадобится)
* [Раскладка](#раскладка)
    * [Переназначение функциональных клавиш](#переназначение-функциональных-клавиш)
    <kbd>Fn1</kbd> <kbd>Fn2</kbd>
    * [Клавиши навигации](#клавиши-навигации)
     <kbd>Up</kbd> <kbd>Down</kbd> <kbd>Left</kbd> <kbd>Right</kbd> <kbd>PageUp</kbd>
     <kbd>PageDown</kbd> <kbd>End</kbd> <kbd>Home</kbd>
    * [Клавиши редактирования текста](#клавиши-редактирования-текста)
     <kbd>Backspace</kbd> <kbd>Delete</kbd> <kbd>Enter</kbd>
    * [Клавиши Символов](#клавиши-символов)
     <kbd>,&lt;</kbd> <kbd>.&gt;</kbd> <kbd>\\&#124;</kbd> <kbd>/?</kbd>
     <kbd>=+</kbd> <kbd>-_</kbd> <kbd>\`~</kbd> <kbd>\[\{</kbd>
     <kbd>\]\}</kbd> <kbd>\(</kbd> <kbd>\)</kbd>
  * [Дополнительные клавиши](#дополнительные-клавиши)
     <kbd>F1</kbd>-<kbd>F12</kbd>
* [Результат](#результат)
* [Ссылки](#ссылки)


## Введение

Значительную часть своего дня я печатаю — пишу код, общаюсь в мессенджерах, играю в видеоигры. В какой-то момент я понял что больше не могу пользоваться своей громоздкой клавиатурой — длительное использование такой клавиатуры начало доставлять мне физическую боль. Каждый раз для нажатия <kbd>Up</kbd>, <kbd>End</kbd>, или любой другой клавиши за пределом домашнего ряда (центральный буквенный ряд), приходится менять положение правой руки, а после возвращать её на место. То же самое касается перехода между клавиатурой и мышью.

Переход на 60% клавиатуру помог мне решить эти проблемы — компактный форм-фактор сводит количество движений рук во время печати и навигации по документам к минимуму, так же уменьшая расстояние между домашним рядом клавиатуры и мышью, упрощая переключение между ними. В прочем, у меня нет медицинского образования и **я не берусь утверждать, что это положительно повлияет на ваше самочувствие**.

### Для кого

* Вы присматриваете себе 60% клавиатуру и не уверены будет ли удобна раскладка
* У вас уже есть такая клавиатура и вы хотите доработать свою раскладку

### Что понадобится

* Программируемая 60% клавиатура

Я буду использовать Anne Pro 2 в сочетании с [obinsKit](http://en.obins.net/obinskit) для этого руководства. Ссылки на готовую раскладку для Anne Pro 2 и таблицу с привязкой клавиш будут в [конце](#ссылки).


## Раскладка

Стоит упомянуть, что в раскладке отсутствуют следующие клавиши:

* <kbd>Right Shift</kbd>
* <kbd>Caps Lock</kbd>

### [Переназначение функциональных клавиш](./layout_table.md#привязка-функциональных-клавиш)

В первую очередь нужно переназначить функциональные клавиши <kbd>Fn1</kbd> и <kbd>Fn2</kbd>. Это необходимо для удобного доступа к клавишам, которые недоступны на основном слое.

Наиболее удобным мне показалось назначить <kbd>Fn1</kbd> на место <kbd>Caps Lock</kbd>, а <kbd>Fn2</kbd> на место <kbd>Enter</kbd>. Если при этом вынести <kbd>Enter</kbd> на *tap layer*, то доступ к нему сохранится — при нажатии сработает клавиша <kbd>Enter</kbd>, при удержании сработает клавиша <kbd>Fn2</kbd>. Так же, для нажатия <kbd>Enter</kbd> довольно удобно использовать <kbd>Fn1</kbd> + <kbd>Space</kbd>.

Далее будет подробно разобран каждый тип функционала на этих слоях.

### [Клавиши навигации](./layout_table.md#привязка-клавиш-навигации)

Благодаря близкому расположению <kbd>Caps Lock</kbd> к клавишам <kbd>w</kbd> <kbd>a</kbd> <kbd>s</kbd> <kbd>d</kbd>, сочетание <kbd>Fn1</kbd> + <kbd>w</kbd> подходит для нажатия <kbd>Up</kbd> одной рукой.

Аналогично строятся сочетания для других клавиш-стрелочек. Так же, если вы не используете блок из четырёх клавиш в правом нижнем углу (в моём случае по умолчанию там находятся <kbd>Right Shift</kbd>, <kbd>Fn1</kbd>, <kbd>Fn2</kbd>, <kbd>Right Ctrl</kbd>), то можете расположить там клавиши стрелочки и сохранить к ним доступ на основном слое.

Для нажатия клавиш <kbd>PageUp</kbd> <kbd>PageDown</kbd> <kbd>End</kbd> <kbd>Home</kbd> можно задействовать правую руку, например <kbd>Fn1</kbd> + <kbd>i</kbd> для <kbd>PageUp</kbd> и аналогично для других клавиш блока.

![Расположение клавиши навигации](./img/navigation.png)

### [Клавиши редактирования текста](./layout_table.md#привязка-клавиш-редактирования-текста)

Клавиши <kbd>Delete</kbd> и <kbd>Backspace</kbd> находятся довольно далеко от домашнего ряда клавиатуры как на стандартных, так и на 60% клавиатурах. Это можно исправить, перенеся их на домашний ряд на слое <kbd>Fn1</kbd>.

![Расположение клавиш редактирования текста](./img/text-editing.png)

### [Клавиши Символов](./layout_table.md#привязка-клавиш-символов)

Я решил так же упростить доступ к символам и перенести их как можно ближе к домашнему ряду и снизить нагрузку на мизинец, которым приходится нажимать не менее 7 клавиш при использовании метода десятипальцевой печати.

![Расположение клавиш символов](./img/symbols.png)

В результате раскладка на слое <kbd>Fn1</kbd> выглядит так:

![Расположение клавиш на слое fn1](./img/fn1-layer.png)

### [Дополнительные клавиши](./layout_table.md#привязка-дополнительных-клавиш)

Для доступа к <kbd>F1</kbd>-<kbd>F12</kbd> хорошо подходит сочетание клавиш верхнего буквенного ряда <kbd>q</kbd>-<kbd>]</kbd> и клавиши <kbd>Fn2</kbd>.

![Расположение клавиш F1-F12](./img/fn2-layer.png)


## Результат

<details>
  <summary>:camera: Спойлер со всеми слоями раскладки</summary>
  
  <br>
  
  ![Расположение клавиш на основном слое](/img/default-layer.png)
  ![Расположение клавиш на слое fn1](/img/fn1-layer.png)
  ![Расположение клавиш на слое fn2](/img/fn2-layer.png)
  ![Расположение клавиш на tap layer](/img/tap-layer.png)
</details>

## Ссылки

* [Таблица с привязкой клавиш](./layout_table.md)
* [Профиль раскладки для Anne Pro 2 под macOS](https://github.com/astronautr/keyboard-layout/releases/download/v1.0.0/ap2_macOS.json)
* [Профиль раскладки для Anne Pro 2 под Windows](https://github.com/astronautr/keyboard-layout/releases/download/v1.0.0/ap2_Windows.json)
* [Профиль альтернативной раскладки для Anne Pro 2 под macOS](https://github.com/astronautr/keyboard-layout/releases/download/v1.0.0/ap2_macOS.json)
* [Профиль альтернативной раскладки для Anne Pro 2 под Windows](https://github.com/astronautr/keyboard-layout/releases/download/v1.0.0/ap2_Windows.json)
