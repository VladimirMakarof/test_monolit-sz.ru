# Тестовое задание PHP-разработчик

## Описание проекта

Данное тестовое задание было выполнено для компании **Монолит Северо-Запад** и представляет собой реализацию страницы с новостями на CMS MODX. Было создано несколько страниц и элементов, которые демонстрируют навыки работы с MODX, PHP и HTML/CSS.

## Доступы

- **URL проекта:** [Перейти на сайт](http://j911797l.beget.tech)
- **URL админ-панели:** [Войти в админку](http://j911797l.beget.tech/manager/)
- **Логин:** `admin`
- **Пароль:** `123456`

## Реализованные задачи

### 1. Вывод списка новостей

- На странице новостей был реализован вывод списка новостей, где каждая новость отображается с заголовком, датой публикации, изображением и обрезанным текстом.
- Для реализации использовался сниппет `getNews`, который выводит новости из MODX.

### 2. Вывод детальной страницы новости

- При клике на заголовок новости происходит переход на детальную страницу, где отображается полное содержание выбранной новости.
- Также на детальной странице был реализован вывод изображения и кнопка возврата на главную страницу.

### 3. Реализация динамического футера

- Внизу каждой страницы был добавлен футер с контактной информацией, навигацией и описанием компании.
- Футер автоматически закрепляется внизу страницы, даже если контента недостаточно.
- В футере динамически отображается текущий год с использованием сниппета `currentYear`.

### 4. Динамическое меню новостей

- В верхнем меню реализован пункт "Новости", при наведении на который выводится динамически генерируемый список последних новостей с использованием сниппета `getMenuNews`.

### 5. Стилизация элементов

- Для всех реализованных элементов (новости, детальная страница, футер, меню) были разработаны стили, соответствующие современным стандартам.
- Внесены изменения в стили для ссылок в футере, чтобы сделать их более привлекательными.

## Структура проекта

- **Шаблоны:**
  - `Начальный шаблон` — основной шаблон сайта.
  - `Новость` — шаблон для отображения детальной страницы новости.
  - `Список новостей` — шаблон для отображения списка новостей.

- **Дополнительные поля (TV):**
  - `preview_image` — поле для загрузки превью изображения новости.

- **Сниппеты:**
  - `getNews` — сниппет для вывода списка новостей.
  - `getMenuNews` — сниппет для генерации меню с последними новостями.
  - `currentYear` — сниппет для вывода текущего года в футере.

- **Ресурсы:**
  - `Новости` — контейнер для хранения всех новостных страниц.

## Используемые технологии

- **MODX Revolution** — система управления контентом.
- **PHP** — для написания сниппетов и динамического вывода данных.
- **HTML/CSS** — для разметки страниц и их стилизации.
- **JavaScript** — для реализации взаимодействия с DOM.

## Инструкции по запуску

1. Перейдите по [ссылке](http://j911797l.beget.tech) для просмотра проекта.
2. Используйте ссылку для доступа к админ-панели: [Войти в админку](http://j911797l.beget.tech/manager/).

## Заключение

В ходе выполнения тестового задания были продемонстрированы навыки работы с CMS MODX, разработка сниппетов на PHP, а также верстка и стилизация элементов веб-страницы. Проект является примером реализации новостного сайта с возможностью управления контентом через админ-панель.
