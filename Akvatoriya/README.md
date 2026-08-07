# ЖК «Акватория» — 360° Панорамный тур

Интерактивные панорамные туры по помещениям квартиры. Технологии: [Pannellum.js](https://pannellum.org/) (equirectangular projection), GitHub Pages.

## 🏠 Комнаты

| # | Помещение      | URL                                                                                                      |
|---|----------------|----------------------------------------------------------------------------------------------------------|
| 1 | Ванная         | [Панорама](https://viztemplate.github.io/360-panorama-tour/Akvatoriya/1.%20Vanaya/)                                                    |
| 4 | Кухня-гостиная (ракурс 1) | [Панорама](https://viztemplate.github.io/360-panorama-tour/Akvatoriya/4.%20Kukhnya-Gostinaya/1/) |
| 5 | Кухня-гостиная (ракурс 2) | [Панорама](https://viztemplate.github.io/360-panorama-tour/Akvatoriya/4.%20Kukhnya-Gostinaya/2/) |
| 6 | Кухня-гостиная (ракурс 3) | [Панорама](https://viztemplate.github.io/360-panorama-tour/Akvatoriya/4.%20Kukhnya-Gostinaya/3/) |
| 7 | Кухня-гостиная (ракурс 4) | [Панорама](https://viztemplate.github.io/360-panorama-tour/Akvatoriya/4.%20Kukhnya-Gostinaya/4/) |

## 🛠 Структура `Akvatoriya/`

```
Akvatoriya/
├── README.md              ← этот файл (навигация по всем комнатам)
├── 1. Vanaya/             ← Ванная комната
│   ├── index.html         ← Pannellum.js тур
│   └── 360_1.jpg          ← панорама
└── 4. Kukhnya-Gostinaya/  ← Кухня-гостиная (4 ракурса)
    ├── 1/                   ← ракурс 1
    │   ├── index.html
    │   └── 360_1.jpg
    ├── 2/                   ← ракурс 2
    │   ├── index.html
    │   └── 360_1.jpg
    ├── 3/                   ← ракурс 3
    │   ├── index.html
    │   └── 360_1.jpg
    └── 4/                   ← ракурс 4
        ├── index.html
        └── 360_1.jpg
```

## 📌 Шаблон для новых комнат

Каждая комната — отдельная папка с:
- `index.html` — универсальный шаблон Pannellum.js (CDN v2.5.6)
- `360_1.jpg` — equirectangular панорама (JPEG)
- `readme.md` — описание + ссылка на тур

URL формат: `/Akvatoriya/{room}/`

---

GitHub Pages: https://viztemplate.github.io/360-panorama-tour/Akvatoriya/
