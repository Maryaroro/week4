# week4

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
