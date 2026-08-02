# 🌐 360° Interior Panorama Tour Template

![Platform](https://img.shields.io/badge/platform-GitHub%20Pages-brightgreen.svg)
![Pannellum.js](https://img.shields.io/badge/engine-Pannellum.js-violet.svg)

> **Профессиональные шаблоны для интерактивных панорамных туров по интерьерам.** Легковесные, готовые к использованию решения для студий интерьерной визуализации, риелторов и фотографов.

---

## ✨ Возможности

| Функция | Описание |
|---------|----------|
| 🖼️ **Equirectangular панорамы** | Поддержка стандартных 360° изображений (JPEG) |
| 📱 **Адаптивный дизайн** | Корректная работа на мобильных и десктопах |
| ⚡ **Zero Setup** | Загрузи панораму — тур готов к просмотру |
| 🔗 **GitHub Pages** | Мгновенный веб-просмотр без хостинга |
| 🎨 **Кастомизация** | Простая HTML/CSS структура для настройки |

---

## 🏠 Проекты

| ЖК | Комнаты | Демо |
|----|---------|------|
| [Акватория](https://viztemplate.github.io/360-panorama-tour/Akvatoriya/) | Ванная | [Смотреть](https://viztemplate.github.io/360-panorama-tour/Akvatoriya/1.%20Vanaya/) |
| [Дзержинский](https://viztemplate.github.io/360-panorama-tour/Dserjinsky/) | Ванная, Детская, Спальня, Кухня-гостиная, Прихожая | [Смотреть](https://viztemplate.github.io/360-panorama-tour/Dserjinsky/) |
| [Вейв](https://viztemplate.github.io/360-panorama-tour/veiv/) | Спальня, Ванная, Гардеробная | [Смотреть](https://viztemplate.github.io/360-panorama-tour/veiv/) |

---

## 🛠 Технологии

- **[Pannellum.js](https://pannellum.org/)** — лёгкий WebGL-вьювер для панорам
- **GitHub Pages** — бесплатный хостинг статических сайтов
- **Equirectangular projection** — стандартная проекция для 360° изображений

---

## 📂 Структура проекта

```
360-panorama-tour/
├── Akvatoriya/          ← ЖК "Акватория"
│   ├── README.md        ← Навигация по комнатам
│   └── 1. Vanaya/       ← Ванная комната
│       ├── index.html    ← Pannellum.js тур
│       └── 360_1.jpg     ← Панорама (equirectangular)
├── Dserjinsky/          ← ЖК "Дзержинский"
│   ├── README.md
│   ├── 1.vanaya/        ← Ванная комната
│   ├── 2.detskaya/      ← Детская комната
│   ├── 3.spamanya/      ← Спальня
│   ├── 4.kuhnya-gostinaya/ ← Кухня-гостиная
│   └── 5.prikhozhaya/   ← Прихожая
├── veiv/                ← ЖК "Вейв"
│   ├── README.md
│   ├── 1Spamanya/       ← Спальня
│   ├── 2Vannaya/        ← Ванная
│   └── 3Garderobnaya/   ← Гардеробная
└── test-panorama/       ← Тестовый пример
    ├── index.html
    └── test.jpg
```

---

## 📌 Шаблон для новых комнат

Каждая комната — отдельная папка с минимальным набором файлов:

| Файл | Назначение |
|------|-----------|
| `index.html` | Универсальный шаблон Pannellum.js (CDN v2.5.6) |
| `360_1.jpg` | Equirectangular панорама (JPEG, рекомендуется 4096×2048px) |

**Формат URL:** `/Akvatoriya/{room}/` или `/Dserjinsky/{room}/`

---

## 🚀 Быстрый старт

1. **Создай папку** для нового проекта (например, `01_NewProject/`)
2. **Добавь панораму:** помести свой `360_1.jpg` внутрь папки
3. **Открой index.html:** тур готов к просмотру!
4. **Deploy:** запушь в GitHub и включи GitHub Pages

---

**Создано [VizTemplate](https://github.com/VizTemplate)**
