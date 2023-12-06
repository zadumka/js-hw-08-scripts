# Домашнє завдання №8

# Завдання — Галерея зображень

Створи галерею з можливістю кліку по її елементах і перегляду повнорозмірного
зображення в модальному вікні. Подивись демовідео роботи галереї.

# 1 - Розмітка галереї

Логічно почати з того, що створити те, куди ми будемо додавати елементи галереї.
Для цього в HTML коді додай тег контейнера галереї — невпорядкований список із
класом gallery.

# 2 - Масив зображень

Для створення елементів галереї тобі знадобляться дані. Додай цей масив об’єктів
у свій JavaScript файл. Кожний об’єкт являє собою один елемент галереї.

<ul>
<li>preview — посилання на маленьку версію зображення для картки галереї</li>
<li>original — посилання на велику версію зображення для модального вікна</li>
<li>description — текстовое описание изображения, для атрибута alt изображения, атрибута title ссылки и подписи изображения в модальном окне.</li>
</ul>

# 3 - Розмітка елементів галереї

У тебе є контейнер, в який можна додати елементи галереї, і дані, за якими їх
можна створити. Саме час наповнювати галерею розміткою.

Використовуй масив об’єктів images і цей HTML шаблон елемента галереї та створи
в JavaScript коді розмітку елементів, після чого додай усю розмітку всередину
ul.gallery. Не додавай інші HTML теги, крім тих, що містяться в цьому шаблоні.

<ul>
<li>В атрибуті src тега img вказуємо посилання на маленьку версію зображення.</li>
<li>Для атрибута alt використовуємо опис зображення.</li>
<li>Посилання на велике зображення повинно зберігатися в data-атрибуті source на елементі img, і вказуватися в href посилання.</li>
<li>Зверни увагу на те, що зображення огорнуте посиланням, отже, по кліку на нього за замовчуванням користувач буде перенаправлений на іншу сторінку, куди вказує href. Заборони цю поведінку за замовчуванням.</li>
</ul>

# 4 - Стилі

Додай мінімальну стилізацію галереї та позиціонування її елементам,
використовуючи Flexbox. (Сделать макет!!!)

# 5 - Делегування

Саме час додати функціонал прослуховування кліка по елементах галереї та
отримання посилання на велике зображення при кліку. Для цього використовуй
прийом делегування на ul.gallery. Поки що при кліку на елемент галереї виводь у
консоль посилання на велике зображення.

# 6 - Підключення бібліотеки

Бібліотека basicLightbox представляє повністю функціональне модальне вікно, яке
відмінно підходить під нашу задачу. Використовуй CDN сервіс jsdelivr і додай в
HTML файл посилання на мініфіковані (.min) JS та CSS файли бібліотеки.

# 7 - Модальне вікно

Доповни свій код так, щоб при кліку по елементу галереї відкривалось модальне
вікно підключеної бібліотеки. Для того щоб дізнатися, як ініціалізувати модальне
вікно у своєму коді і як його використовувати, ознайомся з документацією і
прикладами.

# 8 - Велике зображення

Використовуй свій код отримання посилання на велике зображення, щоб замінити
значення атрибута src елемента img в модальному вікні перед відкриттям.
Використовуй готову розмітку модального вікна із зображенням із прикладів
бібліотеки basicLightbox.

# 9 - Закриття з клавіатури

Додай функціонал закриття модального вікна після натискання клавіші Escape.
Зроби так, щоб прослуховування клавіатури було тільки доти, доки відкрите
модальне вікно. Бібліотека basicLightbox містить метод для програмного закриття
модального вікна.
