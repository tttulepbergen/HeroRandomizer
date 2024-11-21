# HeroRandomizer
## Superhero Viewer App 🦸‍♂️🦸‍♀️

Superhero Viewer App — это iOS-приложение, позволяющее просматривать информацию о случайных супергероях, включая их изображения, характеристики, биографию и внешний вид. Все данные загружаются из Superhero API.

## 📱 Скриншоты и видео
![Uploading Simulator Screenshot - iPhone 16 Pro - 2024-11-21 at 19.05.33.png…]()

<Добавьте сюда скриншоты и видео>

Скриншот 1: Главный экран с информацией о супергерое.
Скриншот 2: Загрузка данных.
Видео: Демонстрация приложения.
🚀 Функциональность

Загрузка данных о случайном супергерое.
Отображение имени, характеристик (интеллект, сила, скорость), биографии и внешнего вида.
Загрузка изображения супергероя с плавным появлением.
Удобная и минималистичная анимация.
⚙️ Технологии

UIKit: интерфейс и анимация.
URLSession: загрузка данных из сети.
JSONDecoder: декодирование данных из формата JSON.
UIView.animate: плавные анимации элементов интерфейса.
🛠 Установка и запуск

Склонируйте репозиторий:
git clone <URL вашего репозитория>
Откройте проект в Xcode.
Убедитесь, что ваш симулятор или реальное устройство выбрано.
Нажмите Cmd + R для запуска приложения.
📋 Структура проекта

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
🧩 Пример использования API

Для получения данных о герое используется Superhero API:

Пример URL:

https://akabab.github.io/superhero-api/api/id/1.json
Ответ содержит следующую информацию:

{
  "id": 1,
  "name": "A-Bomb",
  "powerstats": {
    "intelligence": 38,
    "strength": 100,
    "speed": 17
  },
  "appearance": {
    "gender": "Male",
    "race": "Human",
    "height": ["6'8", "203 cm"],
    "eyeColor": "Yellow"
  },
  "biography": {
    "fullName": "Richard Milhouse Jones",
    "alterEgos": "No alter egos found",
    "publisher": "Marvel Comics",
    "placeOfBirth": "Scarsdale, Arizona"
  },
  "images": {
    "sm": "https://path.to/image.jpg"
  }
}
📖 Особенности кода

Плавная анимация: Кнопки и изображения анимируются для лучшего UX.
Обработка ошибок: Вывод ошибок загрузки в консоль и сообщение на интерфейсе.
Асинхронная загрузка: Используется URLSession для работы с сетью и обновления интерфейса в DispatchQueue.main.
🛡 Лицензия

Этот проект находится под лицензией MIT. См. файл LICENSE для подробностей.

Добавьте свои ссылки на видео и скриншоты в соответствующие места, чтобы README выглядел полным и готовым для публикации.






Вы сказали: