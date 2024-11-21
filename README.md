# HeroRandomizer
## Superhero Viewer App 🦸‍♂️🦸‍♀️

Superhero Viewer App — это iOS-приложение, позволяющее просматривать информацию о случайных супергероях, включая их изображения, характеристики, биографию и внешний вид. Все данные загружаются из Superhero API.

## 📱 Скриншоты и видео

<Добавьте сюда скриншоты и видео>

Скриншот 1: Главный экран с информацией о супергерое.
Скриншот 2: Загрузка данных.
Видео: Демонстрация приложения.
## 🚀 Функциональность

Загрузка данных о случайном супергерое.
Отображение имени, характеристик (интеллект, сила, скорость), биографии и внешнего вида.
Загрузка изображения супергероя с плавным появлением.
Удобная и минималистичная анимация.
## ⚙️ Технологии

UIKit: интерфейс и анимация.
URLSession: загрузка данных из сети.
JSONDecoder: декодирование данных из формата JSON.
UIView.animate: плавные анимации элементов интерфейса.

## 📋 Структура проекта

Основные компоненты:
Hero Struct: Определяет структуру супергероя, включая:
name — имя героя.
powerstats — характеристики героя.
appearance — внешние данные героя (рост, цвет глаз и т.д.).
biography — биографические данные героя.
images — ссылка на изображение героя.
ViewController: Основной контроллер, содержащий:
UI-компоненты (картинка, текстовые метки).
Логика загрузки и отображения данных.
Анимации кнопок и изображений.

## 📖 Особенности кода

Плавная анимация: Кнопки и изображения анимируются для лучшего UX.
Обработка ошибок: Вывод ошибок загрузки в консоль и сообщение на интерфейсе.
Асинхронная загрузка: Используется URLSession для работы с сетью и обновления интерфейса в DispatchQueue.main.

## App Creator


|       Name        |    ID     |
|-------------------|-----------|
| Tulepbergen Anel  | 22B030602 |






