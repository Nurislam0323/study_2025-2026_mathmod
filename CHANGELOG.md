# Changelog

Все изменения

---

## [1.4.1] - 2026-04-02

### ✨ Добавлено

#### Документация отчёта
- `heuristics_report.qmd` — основной QMD-файл отчёта с интеграцией изображений и библиографии
- `heuristics_report_clean.qmd` — чистая версия отчёта (альтернативное оформление)
- `references.bib` — файл библиографии в формате BibTeX (11 источников)

#### Документация презентации
- `heuristics_presentation.qmd` — основной QMD-файл презентации (10 слайдов, Reveal.js)
- `heuristics_presentation_clean.qmd` — чистая версия презентации (альтернативное оформление)

#### Сгенерированные файлы отчёта
- `heuristics_report.html` — HTML-версия отчёта
- `heuristics_report.pdf` — PDF-версия отчёта
- `heuristics_report.docx` — DOCX-версия отчёта (Word)

#### Сгенерированные файлы презентации
- `heuristics_presentation.html` — HTML-версия презентации (Reveal.js)
- `heuristics_presentation.pdf` — PDF-версия презентации

#### Изображения
Создана папка `Image/` со следующими файлами:
- `fig-00-archimedes-concept.png` — концептуальное изображение (Архимед/философ)
- `fig-01-labyrinth-concept.png` — человек в лабиринте (концепция поиска)
- `fig-02-blind-search.png` — модель слепого поиска (блок-схема)
- `fig-03-labyrinth.png` — лабиринтная модель (лабиринт с путём)
- `fig-04-semantic-model.png` — структурно-семантическая модель (сетевой граф)
- `fig-04-three-models.png` — три типа эвристических моделей (сводная схема)
- `fig-05-comparison-table.png` — таблица сравнения эвристик и алгоритмов
- `fig-05-heuristics-algo.png` — блок-сема сравнения подходов
- `fig-06-heuristics-applications.png` — применение эвристик в ИИ (таблица)
- `fig-07-insight.png` — инсайт и озарение (лампочка над головой)
- `fig-09-system1-system2.png` — две системы мышления (Канеман)
- `fig-10-brainstorming.png` — мозговой штурм (командная работа)
- `fig-11-data-analysis.png` — анализ данных (учёный у мониторов)

#### Текст выступления
- `heuristics_speech_text.md` — текст для суфлёра (9 минут, разговорный стиль)

---

### 🔧 Изменено

#### Отчёт (heuristics_report.qmd)
- Интегрировано 12 изображений с перекрёстными ссылками
- Обновлена библиография (`references.bib`) — 11 источников с правильным оформлением
- Добавлены цитирования на все источники из библиографии
- Исправлены пути к изображениям (`Image/`)
- Настроены подписи к рисункам и таблицам

#### Презентация (heuristics_presentation.qmd)
- Сокращено количество слайдов: ~40 → 10 слайдов
- Убраны библиографические ссылки из слайдов
- Настроены размеры изображений (height вместо width, чтобы не перекрывали текст)
- Убраны разделы «Задачи» и «Дополнительные задачи»
- Оставлена только цель и план выступления
- Добавлены настройки Reveal.js (slide-number, transition, height)

#### Библиография (references.bib)
- Все источники оформлены в едином стиле
- Добавлены поля: `language`, `langid`, `PageTotal`, `Series`, `Abstract`
- 11 источников: Polya (1945), Tversky & Kahneman (1974), Kahneman (2011), Gigerenzer (1999), Wikipedia, Newell & Simon (1972), Cialdini (1984), Thaler & Sunstein (2008), Ariely (2008), Gilovich et al. (2002)

---

### 📦 Структура проекта

```

├── heuristics_report.qmd              # Отчёт (Quarto Markdown)
├── heuristics_report_clean.qmd        # Отчёт (чистая версия)
├── heuristics_report.html             # Отчёт (HTML)
├── heuristics_report.pdf              # Отчёт (PDF)
├── heuristics_report.docx             # Отчёт (Word)
├── heuristics_presentation.qmd        # Презентация (Quarto Markdown)
├── heuristics_presentation_clean.qmd  # Презентация (чистая версия)
├── heuristics_presentation.html       # Презентация (HTML, Reveal.js)
├── heuristics_presentation.pdf        # Презентация (PDF)
├── heuristics_speech_text.md          # Текст выступления
├── references.bib                     # Библиография (BibTeX)
└── Image/                             # Изображения (14 файлов)
    ├── fig-00-archimedes-concept.png
    ├── fig-01-labyrinth-concept.png
    ├── fig-02-blind-search.png
    ├── fig-03-labyrinth.png
    ├── fig-04-semantic-model.png
    ├── fig-04-three-models.png
    ├── fig-04-three-models-dup.png    # Дубль (можно удалить)
    ├── fig-05-comparison-table.png
    ├── fig-05-heuristics-algo.png
    ├── fig-06-heuristics-applications.png
    ├── fig-07-insight.png
    ├── fig-09-system1-system2.png
    ├── fig-10-brainstorming.png
    └── fig-11-data-analysis.png
```

---

### 📝 Описание проекта

**Тема:** Эвристики: методы поиска решений в условиях неопределённости

**Дисциплина:** Имитационное моделирование

**Докладчик:** Закиров Нурислам Дамирович  
**Группа:** НФИбд-01-23  
**Университет:** Российский университет дружбы народов (РУДН)

**Продолжительность выступления:** 9 минут

**Ключевые темы:**
- Понятие и сущность эвристик
- Три типа эвристических моделей (слепого поиска, лабиринтная, структурно-семантическая)
- Когнитивные эвристики и искажения (доступности, репрезентативности, якорения)
- Две системы мышления по Канеману (Система 1 и Система 2)
- Применение эвристик (психология, ИИ, образование, бизнес)
- Практические рекомендации по использованию эвристик

---

### 🛠️ Технические детали

**Инструменты:**
- Quarto CLI — рендеринг QMD в HTML, PDF, DOCX
- Pandoc — конвертация форматов
- Reveal.js — презентация в формате HTML
- BibTeX — управление библиографией



---

### 📅 Дата релиза

2 апреля 2026 г.

---

### 📞 Контакты

**Email:** 1132236040@rudn.ru  

