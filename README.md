# 💿 CUE Master Editor

[🇺🇸 English](#english) | [🇷🇺 Русский](#русский)

**[🌐 USE ONLINE / ИСПОЛЬЗОВАТЬ ОНЛАЙН ПРЯМО В БРАУЗЕРЕ](https://vadimlevo.github.io/CUE-Master-Editor/index.html)**

---

<a name="english"></a>
## 🇺🇸 CUE Master Editor
A powerful, zero-dependency, single-file web application for creating, editing, merging, and repairing CUE sheets. It runs 100% locally in your browser.

### ✨ Key Features
* **Zero Dependencies:** No installations, no server uploads. Your files never leave your computer.
* **Full-Window Drag & Drop:** Drop `.cue`, `.txt`, `.xml`, `.m3u`, `.m3u8`, `.flac`, `.wav`, or `.mp3` files anywhere onto the window.
* **M3U/M3U8 Playlist Support:** Import multi-file playlists to automatically generate custom CUE sheets while preserving the original full folder paths.
* **XML Chapter Parsing:** Instantly convert Blu-ray/MKV XML chapter formats into perfectly timed CUE tracks.
* **Encoding Auto-Fixer:** Automatically detects and repairs broken Cyrillic (Windows-1251) text encoding, converting it to standard UTF-8.
* **Smart Timeline Tools:**
    * **Batch Merge:** Convert a multi-file layout into a single, continuous CUE matrix with a progressive timeline (ideal for seamless live mixes or album rips).
    * **Time Shift:** Smartly shift cues forward, starting from any specific track, by entering the duration of an inserted audio track (`MM:SS`).
    * **Auto-Split Generator:** Enter total duration to automatically create equal parts or specific time intervals.
    * **Duration Parser:** Paste raw text lists containing track lengths to generate cumulative timestamp structures instantly.
* **Advanced Text Styling:**
    * **Setlist Importer:** Copy-paste a text tracklist to update titles sequentially.
    * **Smart Clean:** Strip leading numbers (`01.`, `2 -`, `3)`) from titles across the whole table with a single click.
    * **Case Formatter:** Batch update title registry (Title Case, Sentence case, UPPERCASE, lowercase).
* **Smart UI & Caching:** Automated Genre auto-complete system powered by local browser storage. Full bilingual layout (EN/RU).

---

<a name="русский"></a>
## 🇷🇺 CUE Master Editor
Мощное автономное веб-приложение в одном файле для создания, редактирования, склейки и исправления CUE-файлов.

### ✨ Главные особенности
* **Никаких зависимостей:** Без сторонних серверов и скриптов. Все файлы обрабатываются на 100% локально на вашем компьютере.
* **Бронебойный Drag & Drop:** Перетаскивайте файлы `.cue`, `.txt`, `.xml`, `.m3u`, `.m3u8`, `.flac`, `.wav` или `.mp3` в любое место окна приложения.
* **Полная поддержка M3U/M3U8:** Импортируйте многофайловые плейлисты для автоматической сборки CUE-разметки с сохранением полных путей к файлам.
* **Парсинг XML-глав Blu-ray:** Конвертируйте файлы глав из Matroska (MKV) и Blu-ray дисков в CUE с автоматическим пересчетом наносекунд во фреймы (`MM:SS:FF`).
* **Починка кодировки:** Автоматическое исправление "кракозябр" старой кириллицы (Windows-1251) и перевод текста в современный UTF-8.
* **Умная работа со временем:**
    * **Пакетная склейка (Merge):** Соберите многофайловый релиз в один сплошной CUE-образ с расчетом индексов нарастающим итогом (идеально для склеенных концертов).
    * **Сдвиг таймингов:** Сдвигайте временную сетку вперед начиная с любого выбранного трека на заданное время вставки (`MM:SS`).
    * **Генератор нарезки:** Нарезайте треки на равные части или равные промежутки времени.
    * **Расчет по длительности:** Вставьте список песен с их хронометражем (например, с обложки пластинки), и программа сама вычислит абсолютное время старта для каждого трека.
* **Пакетная обработка текста:**
    * **Импорт сетлистов:** Вставляйте текстовые списки треков из интернета для мгновенного переименования всех позиций в таблице.
    * **Очистка от нумерации:** Удаляйте мусорные номера треков в названиях (`01. `, `2 - `, `3) `) одним нажатием кнопки по всей таблице.
    * **Регистр строк:** Массовое форматирование регистра (Каждое Слово С Заглавной, С учётом слов-связок, Как в предложении, ВЕРХНИЙ, нижний).
* **Умный кэш жанров:** Система автозаполнения жанров, запоминающая ваши предпочтения локально в браузере. Полный двуязычный интерфейс (RU/EN).

---
**License:** MIT License. Feel free to fork and improve!
