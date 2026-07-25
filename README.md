# HelixOne

[Українська](#українська) · [English](#english)

---

## Українська

**HelixOne** — зведення етнічних джерел ДНК-звітів (GEDmatch, MyHeritage, FTDNA тощо) в одному місці: усереднення, медіана, довіра й конфлікти між джерелами.

Це не сервіс, а особистий інструмент: ти сам вставляєш цифри, які тобі вже видали різні бази, і бачиш їх поруч — без нового аналізу ДНК і без відправки сирих даних кудись.

### Що вміє

- Автопарсинг звітів (текст, CSV, TXT, JSON)
- Усереднення з кількох джерел: середнє, медіана, std, min–max
- Довіра ★ на основі кількості й узгодженості незалежних джерел
- Індекс узгодженості між джерелами (Agreement index)
- Позначка конфлікту при сильному розходженні джерел
- Ручні кластери груп з автопідказками об'єднання
- Глосарій популяційно-генетичних термінів у панелі "чому таке число"
- Журнал рішень з можливістю очищення
- Версії (W1, W2…) зі знімками й порівнянням
- Простий/Науковий режим перегляду
- Розділ "Відомі пращури" — документальні нотатки поруч із ДНК-групами
- Таблиця збігів з родичами (сМ) з фільтром і сортуванням за національністю
- Кругова діаграма й барчарти на власному SVG
- Експорт: JSON (повний бекап), CSV, друкований "Генетичний паспорт" (PDF), PNG-картка
- Архів джерел замість остаточного видалення, скасування останньої дії (undo)
- Демо-режим ("спробувати на прикладі") з прикладами джерел, пращурів і збігів
- Доступність: aria-label, клавіатурна навігація, видимий фокус

### Технічні деталі

- Один самодостатній HTML-файл, без білд-кроку
- Нуль зовнішніх JS-залежностей під час виконання
- Дані зберігаються локально в браузері (`localStorage`) — нічого не йде на сервер

### Як користуватись

Відкрий `HelixOne.html` у браузері (подвійний клік або перетягни у вкладку) — жодного встановлення чи інтернету не потрібно.

Список змін — у [CHANGELOG.md](./CHANGELOG.md).

---

## English

**HelixOne** — a ledger of ethnic DNA report sources (GEDmatch, MyHeritage, FTDNA and others) in one place: averages, medians, trust scores and conflicts between sources.

This isn't a service — it's a personal tool: you paste in the numbers various databases already gave you, and see them side by side, with no new DNA analysis and no raw data sent anywhere.

### Features

- Auto-parsing of reports (text, CSV, TXT, JSON)
- Averaging across multiple sources: mean, median, std, min–max
- Trust ★ score based on the number and consistency of independent sources
- Cross-source agreement index
- Conflict flag when sources diverge significantly
- Manual group clustering with auto-suggested merges
- Glossary of population-genetics terms in the "why this number" panel
- Decision log, with the option to clear it
- Versions (W1, W2…) with snapshots and comparison
- Simple/Scientific view mode
- "Known ancestors" section — documented notes placed alongside the DNA groups
- Relative matches table (cM) with nation filter and sorting
- Donut chart and bar charts on custom SVG
- Export: JSON (full backup), CSV, printable "Genetic Passport" (PDF), PNG card
- Source archive instead of permanent deletion, undo for the last action
- Demo mode ("try with example") with sample sources, ancestors and matches
- Accessibility: aria-label, keyboard navigation, visible focus

### Technical details

- A single self-contained HTML file, no build step
- Zero external JS runtime dependencies
- Data is stored locally in the browser (`localStorage`) — nothing is sent to a server

### Usage

Open `HelixOne.html` in a browser (double-click or drag it into a tab) — no install and no internet connection required.

See [CHANGELOG.md](./CHANGELOG.md) for the list of changes.
