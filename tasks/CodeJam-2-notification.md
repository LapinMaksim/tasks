# CodeJam-2 Нотификации для пользователя

- **Deadline:** 16-04-2018 20:00
- **Куда сдавать:** Приватный репозиторий, бранч "code-jam2-dom", папка "code-jam2-dom", минимум 2 коммита, далее Pull Request вешать на своего ментора.
- **Что сдавать:** Вы должны реализовать компонент. Сначала его надо сверстать. Потом делать необходимую функциональность по элементам интерфейса, добавляя скрипты / интерактивное поведение к элементам. Как только вы реализовали одну из функций, вы коммитает файл. Можно рефакторить и коммитать исправления до дедлайна.
- **Ограничение:**
    - Должно работать в Chrome
    - Нельзя использовать jQuery и другие библиотеки
    - Нельзя использовать Bootstrap и другие css фреймворки
    - Нельзя использовать Angular/React/Vue и другие фреймворки
    - Можно использовать CSS препроцессоры 
    - Можно гуглить,общаться между собой и пользоваться stackoverflow

Необходимо сделать компонент, который будет показываться пользователю через 5 секунд после старта в правом верхнем углу экрана и будет содержать какую то полезную информацию. Информация задается отдельно в виде массива строк.
![codejam-2-dom](http://varabei.com/public/codejam-2-dom.png)

Компонент должен содержать следующие элементы:  
- (1) иконка закрытия. При клике на нее - нотификация закрывается
- (2) Чекбокс отключения нотификации, выставляет флаг в локал сторадж
- (3) и (4) стрелки, которые переключают при клике содержимое элемента (6) на предыдущую нотификацию или следующую нотификацию 
- (5) элемент пять показывает визуально какой по номеру текст из массива конфигурации показывается

### Бонусное задание. 
Реализовать переключение вперед/назад с помощью клавиатуры.
Для того чтобы работать с клавиатуры, можно сделать элемент в фокусе, либо ловить события с элемента боди либо другим способом.

### Критерий оценки:
- Реализована верстка компонента (расположение в правом верхнем углу) +5
- Реализовано закрытие по клику на крестик +10
- Реализовано сохранение в локал сторадж +5
- Реализовано переключение по стрелке вперед + 20
- Реализовано переключение по стрелке назад + 10
- Реализован бесконечный луп (после последнего начинает с начала) + 20
- Реализовано управление с клавиатуры + 30