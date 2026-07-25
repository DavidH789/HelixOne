# Changelog

[Українська](#українська) · [English](#english)

---

## Українська

### v1.1.0 — 2026

**Додано**

- Глосарій популяційно-генетичних термінів (Ashkenazi, Steppe, Hunter-Gatherer тощо) у панелі "чому таке число" — чесно позначає, коли термін не має усталеного наукового визначення
- Favicon (іконка вкладки браузера)
- Кольорові акцентні "корінці" для кожної секції — швидша орієнтація при прокручуванні
- Перевірка суми відсотків у джерелі (сигналізує, якщо явно не сходиться до ~100%)
- aria-label на кнопках-іконках, клавіатурна навігація (Enter/Space), видимий фокус
- Плавне прокручування сторінки, кастомний scrollbar

**Виправлено**

- Подвійне екранування в діалозі підтвердження очищення журналу рішень (замінено на вбудоване двоетапне підтвердження без залежності від нативного `confirm()`)
- `exportJSON`/`importBackup` тепер коректно включають архів, нотатки й пращурів

### v1.0.0 — 2026

Перший публічний реліз.

**Додано**

- Автопарсинг звітів (текст, CSV, TXT, JSON)
- Усереднення з кількох джерел: середнє, медіана, std, min–max
- Довіра ★ на основі кількості й узгодженості незалежних джерел
- Індекс узгодженості між джерелами
- Позначка конфлікту при сильному розходженні джерел
- Ручні кластери груп з автопідказками об'єднання
- Журнал рішень (з можливістю очищення)
- Версії (W1, W2…) зі знімками й порівнянням
- Простий/Науковий режим перегляду
- Розділ "Відомі пращури" — документальні нотатки поруч із ДНК-групами
- Таблиця збігів з родичами (сМ) з фільтром і сортуванням за національністю
- Кругова діаграма й барчарти на власному SVG
- Прапорці/іконки регіонів за назвою групи
- Експорт: JSON (повний бекап), CSV, друкований "Генетичний паспорт" (PDF), PNG-картка
- Архів джерел замість остаточного видалення
- Скасувати останню дію (undo)
- Нагадування про давність останнього бекапу
- Демо-режим ("спробувати на прикладі")
- Доступність: aria-label, клавіатурна навігація, видимий фокус
- Анімації: поява при завантаженні, hover-ефекти, анімовані цифри

**Технічні деталі**

- Один самодостатній HTML-файл, без білд-кроку
- Нуль зовнішніх JS-залежностей під час виконання
- Дані зберігаються локально (`localStorage`)

---

## English

### v1.1.0 — 2026

**Added**

- Glossary of population-genetics terms (Ashkenazi, Steppe, Hunter-Gatherer, etc.) in the "why this number" panel — honestly flags when a term has no established scientific definition
- Favicon (browser tab icon)
- Color-coded accent "spines" for each section — faster orientation while scrolling
- Percentage-sum check for a source (flags when it clearly doesn't add up to ~100%)
- aria-label on icon buttons, keyboard navigation (Enter/Space), visible focus
- Smooth page scrolling, custom scrollbar

**Fixed**

- Double escaping in the decision-log clear confirmation dialog (replaced with a built-in two-step confirmation, no longer relying on the native `confirm()`)
- `exportJSON`/`importBackup` now correctly include the archive, notes, and ancestors

### v1.0.0 — 2026

First public release.

**Added**

- Auto-parsing of reports (text, CSV, TXT, JSON)
- Averaging across multiple sources: mean, median, std, min–max
- Trust ★ score based on the number and consistency of independent sources
- Cross-source agreement index
- Conflict flag when sources diverge significantly
- Manual group clustering with auto-suggested merges
- Decision log (with the option to clear it)
- Versions (W1, W2…) with snapshots and comparison
- Simple/Scientific view mode
- "Known ancestors" section — documented notes placed alongside the DNA groups
- Relative matches table (cM) with nation filter and sorting
- Donut chart and bar charts on custom SVG
- Region flags/icons based on group name
- Export: JSON (full backup), CSV, printable "Genetic Passport" (PDF), PNG card
- Source archive instead of permanent deletion
- Undo last action
- Reminder about how stale the last backup is
- Demo mode ("try with example")
- Accessibility: aria-label, keyboard navigation, visible focus
- Animations: load-in reveal, hover effects, animated numbers

**Technical details**

- A single self-contained HTML file, no build step
- Zero external JS runtime dependencies
- Data is stored locally (`localStorage`)
