# Список лабораторних робіт:
+ [Прейти до лабораторної "Вивчення Git"](#лабораторна-вивчення-git)
+ [Прейти до лабораторної "Вивчення Docker"](#лабораторна-вивчення-docker)
+ [Перейти до лабораторної "Реалізація перетворень між системами координат"](https://github.com/val-suprunovska/coordinate-system)
+ [Перейти до лабораторної "Розробка додатку для візуалізації вимірювань радару"](https://github.com/val-suprunovska/radar)
+ [Перейти до лабораторної "Розробка додатку для візуалізації вимірювань GPS"](https://github.com/val-suprunovska/gps)
+ [Перейти до лабораторної "Розробка додатку для візуалізації вимірювань LORAN"](https://github.com/val-suprunovska/loran)
+ [Перейти до лабораторної "Дослідження фільтра Калмана"](https://github.com/val-suprunovska/kalmanfilter)

___
# Лабораторна "Вивчення Git"

### *01* Встановлюю ім'я та адресу електронної пошти
<img src="githowto/screenshots/01.jpg">  

Результат:  

<img src="githowto/screenshots/01.1.jpg">

### *02* Назва гілки за замовчуванням
<img src="githowto/screenshots/02.jpg">

### *03* Коректна обробка закінчень рядків
<img src="githowto/screenshots/03.png">


## Створення проєкту
### *01* Створюю сторінку «Hello, World»
<img src="githowto/screenshots/001.jpg">
Замість "touch hello.html" пишу "New-Item hello.html -ItemType File"

<img src="githowto/screenshots/002.jpg">

### *02* Створюю репозиторій
<img src="githowto/screenshots/02.png">

### *03* Додаю сторінку у репозиторій
<img src="githowto/screenshots/04.jpg">

## Перевірка стану
### *01* Перевіряю стан репозиторія
<img src="githowto/screenshots/05.jpg">

## Внесення змін
### *01* Змінюю сторінку «Hello, World»
### *02* Перевіряю стан
<img src="githowto/screenshots/06.jpg">

## Індексація змін
### *01* Додаю зміни
<img src="githowto/screenshots/07.jpg">

## Коміт змін
### *01* Коміт зміни
<img src="githowto/screenshots/08.png">
Результат:  

<img src="githowto/screenshots/09.png">

### *02* Перевіряю стан
<img src="githowto/screenshots/10.png">

## Зміни, а не файли
### *01* Перша зміна: Додаю стандартні теги сторінок
### *02* Додаю ці зміни
### *03* Друга зміна: Додаю заголовок HTML
### *04* Перевіряю поточний статус
<img src="githowto/screenshots/11.png">

### *05* Коміт
<img src="githowto/screenshots/12.png">

### *06* Додаю другу зміну
<img src="githowto/screenshots/13.png">

### *07* Роблю коміт другої зміни
<img src="githowto/screenshots/14.png">

## Історія проєкту
### *01* Однорядкова історія
<img src="githowto/screenshots/15.png">

### *02* Кінцевий формат історії
<img src="githowto/screenshots/16.png">

+ ` --pretty="..."` — визначає формат виходу.
+ `%h` — скрочений хеш коміту.
+ `%ad` — дата коміту.
+ `|` візуальний роздільник.
+ `%s` — коментар.
+ `%d` — доповнення коміту («голови» гілок та теги).
+ `%an` — ім'я автора.
+ `--date=short` — зберігає формат дати коротким і симпатичним.

## Отримання старих версій
### *01* Отримую хеші попередніх комітів
<img src="githowto/screenshots/17.png">

<img src="githowto/screenshots/18.png">

### *02* Повертаюся до останньої версії в гілці `main`
<img src="githowto/screenshots/19.png">

## Створення тегів версій
### *01* Створюю тег першої версії
<img src="githowto/screenshots/20.png">

### *02* Теги для попередніх версій
<img src="githowto/screenshots/21.png">

<img src="githowto/screenshots/22.png">

### *03* Перемикання за ім'ям тегу
<img src="githowto/screenshots/23.png">

### *04* Перегляд тегів за допомогою команди `tag`
<img src="githowto/screenshots/24.png">

### *05* Перегляд тегів у логах
<img src="githowto/screenshots/25.png">

## Скасування локальних змін (до індексації)
### *01* Переходжу на гілку `main`
### *02* Змінюю `hello.html`
### *03* Перевіряю стан
<img src="githowto/screenshots/26.png">

### *04* Скасування змін в робочій директорії
<img src="githowto/screenshots/27.png">

## Скасування проіндексованих змін (перед комітом)
### *01* Вношу зміни у файл і індексую їх
### *02* Перевіряю стан
<img src="githowto/screenshots/28.png">

### *03* Скасовую індексацію змін
### *04* Переходжу на версію коміту
<img src="githowto/screenshots/29.png">

## Скасування комітів
### *01* Змінюю файл і роблю коміт
### *02* Роблю коміт з новими змінами, що скасовують попередні
<img src="githowto/screenshots/30.png">

### *03* Перевіряю лог
<img src="githowto/screenshots/31.png">

## Видалення комітів з гілки (revert)
### *01* Команда `reset`
### *02* Перевіряю історію
### *03* Для початку позначаю цю гілку
### *04* Відкіт до коміту, що передує до `oops`
<img src="githowto/screenshots/32.png">

## Видалення тегу `oops`
<img src="githowto/screenshots/33.png">

## Внесення змін до комітів
### *01* Змінюю сторінку, а потім роблю коміт
### *02* Змінюю попередній коміт
<img src="githowto/screenshots/34.png">

## Створення гілки
### *01* Створюю гілку
<img src="githowto/screenshots/35.png">

### *02* Додаю файл стилів `style.css`
<img src="githowto/screenshots/36.png">

### *03* Змінюю hello.html для того, щоб використовувати `style.css`
<img src="githowto/screenshots/37.png">

## Перемикання гілок
### *01* Перемикання на гілку `main`
### *02* Повертаюсь до гілки `style`
<img src="githowto/screenshots/38.png">

## Переміщення файлів
### *01* Перегляд історії змін конкретного файлу
<img src="githowto/screenshots/39.png">

### *02* Перегляд різниці між версіями певного файлу
<img src="githowto/screenshots/40.png">

### *03* Перейменовую `hello.html`
<img src="githowto/screenshots/41.png">

### *04* Безпечне переміщення файлу `style.css`
<img src="githowto/screenshots/42.png">

## Зміни в гілці `main`
### *01* Створюю файл `README`
### *02* Коміт файлу `README` у гілку `main`
<img src="githowto/screenshots/43.png">

## Перегляд розбіжних гілок
### *01* Переглядаю поточні гілки
<img src="githowto/screenshots/44.png">

## Злиття
### *01* Злиття гілок
<img src="githowto/screenshots/45.png">

## Створення конфлікту
### *01* Повертаюся у `main` і створюю конфлікт
### *02* Перегляд гілок
<img src="githowto/screenshots/46.png">

## Вирішення конфліктів
### *01* Злиття main до гілки `style`
<img src="githowto/screenshots/47.png">

### *02* Скасування злиття
### *03* Рішення конфлікту
### *04* Роблю коміт з розв'язаним конфліктом
<img src="githowto/screenshots/48.png">

## Відкочування гілки `style`
### *01* Відкочую гілку `style`
### *02* Перевіряю гілку
<img src="githowto/screenshots/49.png">

## Перебазування
### *01* Перебазовую гілку `style` на `main`
<img src="githowto/screenshots/50.png">

### *02* Розв'язую конфлікт
<img src="githowto/screenshots/51.png">

## Злиття в гілку `main`
### *01* Злиття `style` в `main`
### *02* Переглядаю логи
<img src="githowto/screenshots/52.png">

## Клонування репозиторіїв
### *01* Переходжу в директорію `repositories`
### *02* Створюю клон репозиторія `work`
<img src="githowto/screenshots/53.png">

## Перегляд клонованого репозиторія
### *01* Переглядаю історію репозиторія
<img src="githowto/screenshots/54.png">

## Що таке origin?
<img src="githowto/screenshots/55.png">

## Віддалені гілки
### *01* Список віддалених гілок
<img src="githowto/screenshots/56.png">

## Зміна оригінального репозиторія
### *01* Вношу зміни в оригінальний репозиторій `work`
<img src="githowto/screenshots/57.png">

## Підтягування змін
### *01* Перевіряю README
<img src="githowto/screenshots/58.png">

## Злиття підтягнутих змін
### *01* Зливаю підтягнуті зміни в локальну гілку `main`
### *02* Ще раз перевіряю файл README
<img src="githowto/screenshots/59.png">

## Додавання гілки відстеження
### *01* Додаю локальну гілку, котра відстежує віддалену гілку
<img src="githowto/screenshots/60.png">

## Чисті репозиторії
### *01* Створюю чистий репозиторій
<img src="githowto/screenshots/61.png">

## Додавання віддаленого репозиторія

### *01* Додаю репозиторій work.git до оригінального репозиторія.  
`cd work`  
`git remote add shared ../work.git`

## Відправка змін
<img src="githowto/screenshots/62.png">

## Підтягування спільних змін
<img src="githowto/screenshots/63.png">

____

# Лабораторна "Вивчення Docker"

### Запускаю перший контейнер
<img src="docker/screenshots/01.png">

Для цього контейнера інтерфейс доступний через порт 8080. Відкриваю у браузері localhost
<img src="docker/screenshots/02.png">

### Запускаю другий контейнер 
Програма завантажилася 
<img src="docker/screenshots/03.png">

Вношу зміни у файл `backend/src/routes/getGreeting.js`, а потім в плейсхолдер
<img src="docker/screenshots/04.png">
<img src="docker/screenshots/05.png">

Вношу зміни до `index.scss`
<img src="docker/screenshots/06.png">
