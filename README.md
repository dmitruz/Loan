Доброго времени суток, разработчик. Вы получили архив с исходниками нашего проекта. У вас есть голая
верстка без интерактива. В архиве содержится всё, что нужно для её выполнения: HTML верстка, стили,
все необходимые изображения и шрифты (уже подключены). Учтите, что некоторым элементам необходимо
будет задавать свойство display(flex), чтобы скрыть/показать их.

Вы имеете право изменять проект так, как вам нужно для достижения цели - добавлять необходимые id,
классы, стили, анимации, подключать дополнительные стили (например animate.css)...

Но так же есть несколько условий: JavaScript код должен быть нативным, без использования библиотек,
фреймворков или плагинов (напр. JQuery) В консоли должны отсутствовать любые ошибки Названия всех
переменных/классов не должны содержать кириллицу или транслит. Никаких peremennaya Итоговый вариант
должен быть построен на любой модульной структуре. В будущем планируем расширяться.
Работоспособность во всех современных браузерах (Chrome, Firefox, Opera, IE11, Edge, Safari)
Анимации очень приветствуются, но также остаются на усмотрение (установленные классы от animate.css
можете менять как вам угодно) Использование ES6

Список задач для реализации:

Страница index.html должна быть реализована в виде большого слайдера, где каждый слайд - на всю
страницу. Переключение страниц идет только вперед при помощи клика на эту стрелку:

При клике на логотип - идет переход к первому слайду:

Если слайды кончились - переход к первому слайду.

Страница modules.html должна быть реализована аналогичным образом. Кроме этого, необходимо
реализовать навигацию под контентом модуля.

На первом экране при клике на кнопку с классом play

Необходимо показать блок с классом overlay и показать необходимое видео, ссылка на которое в
data-url у кнопки, которую нажал пользователь. Учтите, что этот скрипт должен быть универсальным и
менял видео в зависимости от кнопки.

Также при клике на крестик необходимо полностью закрыть модальное окно.

На первом экране есть слайдер с модулями.

Необходимо его реализовать: стрелки для переключения слайдов.

На том же слайдере: В текущем слайде opacity заголовка меняется с 0.4 на 1. В текущем слайде стрелка
(card\_\_controls-arrow) становится видимой. (через opacity) На неактивных - скрыть.

На второй странице есть список различий.

Изначально оба списка должны выглядеть как показано в позиции 1. При клике на крестик открывается
следующий шаг - добавление карточки спереди, карточка “click to show” смещается ниже. При появлении
третьей карточки - карточка “click to show” исчезает. Желательно применить анимацию, аналогичную
fadeIn.

На третьей странице необходимо реализовать слайдер:

Стрелки должны работать обязательно, условия такие же как и в первом слайдере. В самом слайдере
необходимо автоматическое перелистывание каждые 5 секунд. Также на активном слайде необходимо
показать элементы(через opacity): card**description card**controls-arrow На неактивных - скрыть.

Этот блок необходимо показать через 3 секунды после того, как человек попадает на данную страницу:

Необходимо реализовать отправку формы без перезагрузки страницы

Должны передаваться все выбранные/введенные данные. Необходимо запретить ввод кириллицы в поле
Email. В поле номера телефона необходима маска с кодом США. При успешной отправке оповестить
пользователя любым способом, кроме alert. (модальное окно, надпись/картинка снизу и тд). Аналогично
при ошибке.

На странице №5 реализовать слайдер:

Условия для стрелок такие же. У активного слайда также должен быть класс .feed\_\_item-active для
его стилизации. У неактивных - убираем.

На странице №6 необходимо реализовать отправку формы:

В поле email запретить ввод кириллицы. Отправка формы без перезагрузки страницы с оповещением
пользователя о результате.

На странице модулей

При клике на кнопку play - показать ролик, аналогичным способом как и в пункте №3. Второй ролик
открывается для просмотра только если человек просмотрел первый. До этого - на нем клик не
срабатывает. Также изменить стили при открытии.

Реализовать небольшой аккордеон (1)

При клике на него - снизу плавно должен появляться небольшой текст-рыба. При повторном клике -
скрывается.

При клике на кнопку Download PDF - идет скачивание файла. Подключите любой, небольшой файл.
Необходима модульная структура проекта, подключена должна быть сборка(bundle). Никакого дублирования
кода. Не нужно привязывать к каждой кнопке отдельные действия. Воспользуйтесь функцией или циклами.

Обязательно тестируйте своё детище, чтобы не было багов поведения и несостыковок. Представьте себя
на месте пользователя, который будет совершать неочевидные действия. Также и в консоли не должно
быть ошибок.

Успехов в выполнении проекта!
