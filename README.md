# markup-1
https://skyroma.github.io/markup-1/


| Deadline  | Folder name |
|-----------|-------------|
| 01.04.2018 23:59 | markup-1 |


Create web page, strictly according to:

**[Lambda restaurant layout](https://www.dropbox.com/s/xvhx2kxlvzxu5n0/Restaurant_2.psd?dl=0)**

Pixel Perfect is reference point of the task.

Browser support: Google Chrome, Mozilla Firefox, Microsoft Edge.

## Как сдавать

Сверстанный макет и папки с контентом залить в ветку *markup-1* в **своем** репозитории. Сделать пулл реквест и указать в ревьюверах своего ментора.

```
*На Github: заходим в выданный от RS **приватный** репозиторий. Искать его тут - https://github.com/rolling-scopes-school/
*На Github: клонируем его себе на компьютер(git clone or download)
*На компьютере: открываем его в консоли и создаем новую ветку под названием **markup-1** (git checkout -b markup-1)
*На компьютере: закидываем свои файлы и папки в этот клонированный репозиторий
*На компьютере: далее делаем коммит и пушим в ветку markup-1  (git add .) --> (git commit -m 'commit name') --> (git push origin markup-1)
*На Github: далее создаем pull request (кнопка new pull request)
*На Github: выбираем для сравнения  master <-- markup-1, дальше на странице в правой части в меню кликаем **reviewers** и выбираете вашего ментора
*На Github: ну и наконец кликаем **pull request**
*Итог: по сути, этими действиями мы предлагаем смержить ветку markup-1 с веткой master, а как **проверяющего** мы указываем нашего ментора.
```

## Критерии оценки

За полностью выполненное задание, без нарушений, в сумме можно набрать **100 баллов**.

**!оценка: 0-10** означает, что если требование полностью не выполнено, то выставляется 0 баллов; если полностью выполнено, то выставляется 10 баллов; за частичное выполнение выставляется промежуточное значение на усмотрение ментора.

Также баллы могут сниматься за ошибки, указанные в ТЗ.

## Техническое Задание

1. Общее:
	 - Файл HTML назвать index.html
	 - Сделать отдельные папки с картинками, шрифтами, стилями. Если все будет в одном каталоге на уровне с index.html, **минус 10 баллов**.
   - Ширина макета 1600px. И проверяться все будет, соотвественно, на такой ширине экрана, либо больше. Тогда ваш макет должен быть центрирован. Если делать на экранах, разрешение которых меньше, то будет полоса прокрутки, и это нормально. Можно использовать zoom out;
   **!оценка: 0-10**

2. Семантическая верстка:
	 - Использование HTML5 тегов, таких как header, nav, section, article, footer, form + fields, figure;
	 **!оценка: 0-10**
	 - Правильное и разумное наименование классов, избегать наименований вроде .right-column, .third-form, .left, .big, а использовать осмысленные, вроде .heading, .form-container, .wrapper, .menu-column, а так же псевдоклассы, вроде :first-child, last-child и другие;
	 **!оценка: 0-10**
	 - Использование id для стилей - ошибка, **минус 5 баллов**.

3. Правильно оформить логотип. Не забыть, что на странице должен быть h1.
**!оценка: 0-5**

4. Навигация выполнена с использованием тега nav. Кликабельные элементы меню должны быть ссылками.
**!оценка: 0-5**

5. Обратить внимание, что страница не на белом фоне, а на заднем плане должен быть графический паттерн.
**!оценка: 0-5**

6. Шрифты. Их всех можно найти бесплатно, ниже будут приведены ссылки. Проверить правильное подключение. Причем правильно нужно подобрать и подходящий вес шрифта.
**!оценка: 0-10**

7. Требования по колонкам и блокам:
	 - Проверяем, что случится, если мы в колонке, либо блоке, увеличим количество текста. Просто копируем внутрь больше текста. (Расположение колонок не должно портиться, ограничение на overflow);
	**!оценка: 0-10**
	 - Проверяем, что случится, если мы добавим еще одну колонку в раздел меню. (Она должна быть либо под первой колонкой, либо посередине следующей строки, либо быть скрыто свойством overflow, но никак не 3-м видимым элементом в строку, выходящим за границу макета)
	**!оценка: 0-5**
	 - Если использован display: inline-block, убедиться в том, что нету "пробельного" зазора между элементами в строке. Если есть, **минус 5 баллов**.

8. Картинки в разделе "fine ingredients" должны иметь формат обычных изображений (прямокгольник или квадрат) и должны быть обработаны средствами CSS (border, border-radius).
**!оценка: 0-10**

9. Форма должна быть оформлена в виде тега form и всего надлежащего внутри. Форма должна содержать базовую браузерную валидацию на Email, а поля Name, Email и Date должны быть required. В макете, учтите, ошибка в названии поля. У вас ее быть не должно.
**!оценка: 0-10**

10. Footer должен прибит к низу. Прибитие значит, что если убрать контент на странице, кроме футера, то футер будет все равно внизу.
**!оценка: 0-5**

11. На сайте динамики может не быть, кроме событий hover. К ним можно и нужно применить стилевое оформление на ваше усмотрение, например при наведении курсором на элементы верхенго меню.
**!оценка: 0-5**

Header можно делать фиксированным при прокрутке на фоне градиента, но доп. баллов за это не предусмотрено.

Использовать можно любую сеточную технологию. Можно использовать font-awesome для иконок.

Препроцессоры и постпроцессоры использовать не обязательно. Отдавать на выходе файлы типа .scss, .less нельзя. Также нельзя использовать bootstrap или подобную библиотеку. Все должно быть сделано самостоятельно. штраф **минус 40 баллов**.

## Полезные ссылки

[Презентации](https://github.com/rolling-scopes/front-end-course/wiki/Position.-Floats.-Semantics.-CSS3)

[Видео лекции от 06.10.2017](https://youtu.be/gYYWe7vlEQk)

Ссылки на шрифты:

[yeseva-one](https://www.fontsquirrel.com/fonts/yeseva-one)

[gentium-basic](https://www.fontsquirrel.com/fonts/gentium-basic)

[lato](https://www.fontsquirrel.com/fonts/lato)

[open-sans](https://www.fontsquirrel.com/fonts/open-sans)
