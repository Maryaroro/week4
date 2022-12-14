# week4

Вопросы 5 недели:

1. Почему в большинстве ситуаций стоит использовать flexbox-позиционирование?
   Flexbox эффективнее справляется с выравниванием, распределением и направлением элементов страницы.
2. Самостоятельно изучите способ позиционирования через display: table и ответьте на вопрос, для каких ситуаций оно лучше всего подходит?
   Это значение можно использовать для создания табличной структуры, и можно использовать в декоративных целях для ограничения видимой области по содержанию — например, если в дизайне фон заголовка ограничивается текстом заголовка.
3. Какими способами можно сделать горизонтальное выравнивание по центру? Минимум 3 варианта, можно больше
   justify-content: center;
   text-align: center;
   margin: auto;
4. Какие есть оси во флекс-верстке и как задается их направление?
   Главная и поперечная оси.
   Направление задается через свойство flex-direction: row (слева направо) - по умолчанию row-reverse (справа налево) column (сверху вниз) column-reverse (снизу вверх)
5. Разберитесь, как работает свойство margin: auto во флекс-верстке, приведите пример использования
   Свойство margin позволяет выравнивать элемент по центру горизонтали, если использовать значение auto и задать ширину элемента через width.
6. В чем преимущества box-sizing?
   По умолчанию все элементы имеют box-sizing: content-box. Размеры блока рассчитываются из размеров контента.
   box-sizing: border-box меняет то, как расчитываются width и height. Border и padding включаются в расчёт. Высота будет состоять из: высота контента + вертикальные padding’и + ширина вертикальных border. Ширина будет состоять из: ширина контента + горизонтальные padding’и + ширина горизонтальных border.
7. Чем отличается flex-grow от flex-shrink?
   flex-shrink : определяет, как flex-элемент будет уменьшаться относительно других flex-элементов во flex-контейнере
   flex-grow : определяет, как flex-элемент будет увеличиваться относительно других flex-элементов во flex-контейнере
8. Как можно добиться следующего позиционирования элементов:
   Через выравнивание по главной оси
   Свойство justify-content:space-between
9. Какой в итоге будет размер у элемента (можно округлить)?
   Высота=17,807px
   Ширина=148,523px
10. Самостоятельно разберитесь, зачем нужно свойство order?
    CSS свойство order устанавливает порядок следования флекс элемента в контейнере относительно остальных.
11. Каким кодом можно сделать такую таблицу?
<table style="width:40%" border="1">
 <tr>
    <td>Column 1</td>
    <td>Column 2</td>
    <td>Column 3</td>
 </tr>
 <tr>
    <td rowspan="2">Row 1 Cell 1</td>
    <td>Row 1 Cell 2</td>
    <td>Row 1 Cell 3</td>
 </tr>
 <tr>
    <td>Row 2 Cell 2</td>
    <td>Row 2 Cell 3</td>
 </tr>
 <tr>
    <td colspan="3">Row 3 Cell 1</td>
 </tr>
</table>
12. Изучите материалы и найдите, для каких ситуаций подходит position: fixed?
    Подвид абсолютного позиционирования, при котором элемент привязывается к координатам окна, а не документа.
    При прокрутке он остаётся на том же месте.
13. Каким способом лучше всего верстать большие блоки текста?
    Flexbox не подходит для верстки больших текстов.
    Через Float удобно верстать текст с иллюстрациями.
14. Как рассчитывается размер flex-контейнера?
    Это гибкая модель, рассчитать размер мы можем по размерам осей.

Вопросы 4 недели:

1. Какими способами можно подключать CSS-стили? Найдите сами еще один способ, не указанный в уроке
   • Через атрибут style (нежелательно)
   • Через тег <style> в заголовке документа
   • Через тег <link> можно добавить готовый css стиль
   • С помощью команды @import

2. Зачем нужен Normalize.css?
   Normalize.css обеспечивает для HTML-элементов лучшую кроссбраузерность в стилях по умолчанию:
   • сохраняет полезные настройки браузера
   • нормализует стили для широкого круга HTML-элементов
   • корректирует ошибки и основные несоответствия браузера
   • совершенствует юзабилити незаметными улучшениями
   • объясняет код, используя комментарии и детальную документацию

3. Что такое CSS-директивы?
   • Директивы — это конструкции, которая позволяет создавать в CSS инструкции для изменения отображения либо поведения элементов страницы. Директива начинается со знака @, за которым следует одно из служебных слов. Это общий синтаксис, которому следуют все директивы.

4. В чем разница между margin и padding?
   • Margin-внешний отступ
   • Padding-внутренний отступ

5. Как в CSS определяются приоритеты? Какое из свойств будет приоритетнее - #link .main или span #login?
   • Существует специальная таблица, по которой можно рассчитать значимость каждого селектора
   • Приоритетнее #link .main

6. В чем разница между CSS1 и CSS3?

• Основное различие между CSS и CSS3 заключается в том, что в CSS3 есть модули. CSS является базовой версией и не поддерживает адаптивный дизайн. CSS3, с другой стороны, является последней версией и поддерживает адаптивный дизайн.
• CSS нельзя разбить на модули, но CSS3 можно разбить на модули. Быть старой версией CSS медленнее, чем CSS3.
• В дополнение к этим CSS3 имеет много функций выравнивания. CSS3 предоставляет инструмент для изменения размеров ячеек, который позволяет пользователю получить правильный размер любого элемента без каких-либо изменений в размерах или заполнении элемента. CSS не имеет какого-либо инструмента для определения размера блоков, и поэтому пользователю необходимо использовать стандартные процедуры, определенные для выравнивания текста.
• Анимации и 3D-преобразования лучше в CSS3. Элементы можно перемещать по экрану с помощью flash и JavaScript. Используя это, элементы также смогут менять свой размер и цвет. Все виды переходов, преобразований и анимаций могут быть выполнены с использованием CSS3. CSS не предоставляет 3D анимацию и преобразования.

7. ПроЧто такое псевдоклассы? А псевдоэлементы?
   • Псевдокласс - это ключевое слово, определяющее динамическое состояние элементов, которое изменяется с помощью действий пользователя, а также положение в дереве документа.
   • Псевдоэлемент - это ключевое слово, добавляемое к селектору, которое позволяет стилизовать определённую часть выбранного элемента.

8. Изучите статью про "плохие" теги https://msiter.ru/tutorials/html-srednego-urovnya/plokhie-tegi и пришлите список тегов, которые нежелательно использовать
   • <layer>
   • <u>
   • <font>
   • <big>

9. Как можно подключать шрифты локально?
   • Через правило @font-face src позволяет задать название локального шрифта, т.е. если у пользователя на компьютере уже установлен нужный шрифт, то будет использоваться именно он, при этом существенно увеличится скорость загрузки и отрисовки страницы.

10. Почему не стоит использовать сокращенную запись без необходимости? И если все же использовать, как это делать правильно?
    • Применение этих свойств сокращает объём кода и повышает его читабельность, но с другой стороны иногда добавляет путаницу.
    • Следует, во-первых, группировать свойства по смыслу, это позволит быстрее находить ошибки, а во-вторых, если вам нужно переопределить значения ранее заданных свойств, не используйте сокращённую запись.
