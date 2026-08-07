# ЖК «Акватория» — 360° Панорамный тур

Интерактивные панорамные туры по помещениям квартиры. Технологии: [Pannellum.js](https://pannellum.org/) (equirectangular projection), GitHub Pages.

## 🏠 Комнаты

| # | Помещение      | URL                                                                                                      |
|---|----------------|----------------------------------------------------------------------------------------------------------|
| 1 | Ванная         | [Панорама](https://viztemplate.github.io/360-panorama-tour/Akvatoriya/1.%20Vanaya/)                                                    |
| 5 | Кухня-гостиная (4 ракурса) | [Панорама](https://viztemplate.github.io/360-panorama-tour/Akvatoriya/5.kuhnya-gostinaya/) |

## 🛠 Структура `Akvatoriya/`

```
Akvatoriya/
├── README.md              ← этот файл (навигация по всем комнатам)
├── 1. Vanaya/             ← Ванная комната
│   ├── index.html         ← Pannellum.js тур
│   └── 360_1.jpg          ← панорама
├── 5.kuhnya-gostinaya/    ← Кухня-гостиная (все 4 ракурса в одном туре)
│   ├── index.html         ← Тур с навигацией между ракурсами
│   ├── readme.md          ← Описание тура
│   ├── 360_001_0000.jpg   ← панорама ракурс 1
│   ├── 360_002_0000.jpg   ← панорама ракурс 2
│   ├── 360_003_0000.jpg   ← панорама ракурс 3
│   └── 360_004_0000.jpg   ← панорама ракурс 4
```

## 📌 Шаблон для новых комнат

Каждая комната — отдельная папка с:
- `index.html` — универсальный шаблон Pannellum.js (CDN v2.5.6)
- `360_1.jpg` — equirectangular панорама (JPEG)
- `readme.md` — описание + ссылка на тур

URL формат: `/Akvatoriya/{room}/`

---

GitHub Pages: https://viztemplate.github.io/360-panorama-tour/Akvatoriya/
