# Проект Дзержинского — 360° Панорамный тур

Интерактивные панорамные туры по помещениям квартиры. Технологии: [Pannellum.js](https://pannellum.org/) (equirectangular projection), GitHub Pages.

## 🏠 Комнаты

| # | Помещение      | URL                                                                                                      |
|---|----------------|----------------------------------------------------------------------------------------------------------|
| 1 | Ванная комната | [Панорама](https://viztemplate.github.io/360-panorama-tour/Dserjinsky/1.vanaya/index.html)                                                    |
| 2 | Детская        | [Панорама](https://viztemplate.github.io/360-panorama-tour/Dserjinsky/2.detskaya/index.html)                                                    |
| 3 | Спальня        | [Панорама](https://viztemplate.github.io/360-panorama-tour/Dserjinsky/2.spalnya/index.html)                                                    |

## 🛠 Структура `Dserjinsky/`

```
Dserjinsky/
├── README.md              ← этот файл (навигация по всем комнатам)
├── 1.vanaya/              ← Ванная комната
│   ├── index.html         ← Pannellum.js тур
│   └── 360_1.jpg          ← панорама
├── 2.detskaya/            ← Детская комната
│   ├── index.html         ← Pannellum.js тур
│   └── 360_1.jpg          ← панорама
└── 2.spalnya/            ← Спальня
    ├── index.html         ← Pannellum.js тур
    └── 360_1.jpg          ← панорама
```

## 📌 Шаблон для новых комнат

Каждая комната — отдельная папка с:
- `index.html` — универсальный шаблон Pannellum.js (CDN v2.5.6)
- `360_1.jpg` — equirectangular панорама (JPEG)
- `readme.md` — описание + ссылка на тур

URL формат: `/Dserjinsky/{room}/index.html`

---

GitHub Pages: https://viztemplate.github.io/360-panorama-tour/Dserjinsky/
