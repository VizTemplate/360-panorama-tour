# ЖК «Вейв» — 360° Панорамный тур

Интерактивные панорамные туры по помещениям квартиры. Технологии: [Pannellum.js](https://pannellum.org/) (equirectangular projection), GitHub Pages.

## 🏠 Комнаты

| # | Помещение      | URL                                                                                                      |
|---|----------------|----------------------------------------------------------------------------------------------------------|
| 1 | Спальня        | [Панорама](https://viztemplate.github.io/360-panorama-tour/veiv/1Spalnya/)                                                    |
| 2 | Ванная         | [Панорама](https://viztemplate.github.io/360-panorama-tour/veiv/2Vannaya/)                                                    |
| 3 | Гардеробная    | [Панорама](https://viztemplate.github.io/360-panorama-tour/veiv/3Garderobnaya/)                                                |
| 4 | Кухня-гостиная (ракурс 1) | [Панорама](https://viztemplate.github.io/360-panorama-tour/veiv/4Kukhnya-Gostinaya/1Kukhnya-Gostinaya/) |
| 5 | Кухня-гостиная (ракус 2) | [Панорама](https://viztemplate.github.io/360-panorama-tour/veiv/4Kukhnya-Gostinaya/2Kukhnya-Gostinaya/) |

## 🛠 Структура `veiv/`

```
veiv/
├── README.md              ← этот файл (навигация по всем комнатам)
├── 1Spamanya/             ← Спальня
│   ├── index.html         ← Pannellum.js тур
│   └── 360_1.jpg          ← панорама
├── 2Vannaya/              ← Ванная
│   ├── index.html         ← Pannellum.js тур
│   └── 360_1.jpg          ← панорама
├── 3Garderobnaya/         ← Гардеробная
│   ├── index.html         ← Pannellum.js тур
│   └── 360-1.jpg          ← панорама
└── 4Kukhnya-Gostinaya/    ← Кухня-гостиная (2 ракурса)
    ├── 1Kukhnya-Gostinaya/    ← Кухня-гостиная (ракус 1)
    │   ├── index.html         ← Pannellum.js тур
    │   └── 360_1.jpg          ← панорама
    └── 2Kukhnya-Gostinaya/    ← Кухня-гостиная (ракурс 2)
        ├── index.html         ← Pannellum.js тур
        └── 360_2.jpg          ← панорама
```

## 📌 Шаблон для новых комнат

Каждая комната — отдельная папка с:
- `index.html` — универсальный шаблон Pannellum.js (CDN v2.5.6)
- `360_1.jpg` — equirectangular панорама (JPEG)
- `readme.md` — описание + ссылка на тур

URL формат: `/veiv/{room}/`

---

GitHub Pages: https://viztemplate.github.io/360-panorama-tour/veiv/
