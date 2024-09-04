# Django взаимодействие с API Яндекс.Диск 
Это веб-приложение на Django, которое позволяет просматривать файлы и папки на Яндекс.Диске, загружать выбранные файлы и скачивать их.

## Функционал
Просмотр файлов: Пользователи могут вводить публичный ключ Яндекс.Диска, чтобы увидеть список всех файлов и папок, доступных по этому ключу.
Скачивание файлов: Пользователи могут выбрать файлы и скачать их.

## Использование
Просмотр файлов: Введите публичный ключ Яндекс.Диска в поле ввода на главной странице и нажмите кнопку "Показать файлы". После этого вы увидите список файлов и папок, доступных по этому ключу.

Фильтрация файлов: Используйте выпадающий список для фильтрации файлов по типу (изображения, документы, прочие).

Скачивание файлов: выберите файлы и скачать их.

Требования
Python 3.6+
Django 3.0+
requests (для взаимодействия с API Яндекс.Диска)
Документация к коду
views.py: Обрабатывает запросы для отображения файлов и скачивания выбранных файлов.
index.html: Шаблон для отображения формы ввода публичного ключа, списка файлов и кнопки для скачивания файлов.
