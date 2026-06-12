# 💿 CUE Master Editor

[🇺🇸 English](#english) | [🇷🇺 Русский](#русский)

**[🌐 USE ONLINE / ИСПОЛЬЗОВАТЬ ОНЛАЙН ПРЯМО В БРАУЗЕРЕ](https://[твой-логин].github.io/[название-репозитория]/CUE_Master.html)**

---

<a name="english"></a>
## 🇺🇸 CUE Master Editor
A powerful, zero-dependency, single-file web application for creating, editing, and fixing CUE sheets. It runs 100% locally in your browser. You can use it directly online via GitHub Pages or download it for offline use!

### ✨ Key Features
* **Zero Dependencies:** No installations, no server uploads. Your files never leave your computer.
* **Smart Drag & Drop:** Drop `.cue`, `.txt`, `.xml` (Matroska/Blu-ray chapters), `.flac`, `.wav`, or `.mp3` files directly into the window. 
* **XML Chapter Parsing:** Instantly convert Blu-ray/MKV XML chapter files into perfectly timed CUE tracks.
* **Encoding Fixer:** Automatically detects and fixes broken Cyrillic (Windows-1251) encoding, converting it to standard UTF-8.
* **AI-Duration (Auto Audio Length):** Drop an audio file, and the app will instantly calculate its exact duration locally.
* **Auto-Split Generator:** Need to split a 2-hour mix or vinyl rip? Enter the total duration and automatically generate tracks split into equal parts or specific time intervals.
* **Track Timings Generator:** Paste a list of track durations (e.g., from a vinyl back cover), and it calculates cumulative CUE indexes automatically.
* **Merge to Single File:** Calculate sequential indexes for a continuous mix instantly.
* **Batch Operations:** 
    * **Smart Setlist Paste:** Paste a tracklist, and the app will automatically strip numbers/punctuation and apply titles to your tracks in order.
    * Apply the Album Performer or Global Audio File to all tracks with one click.
    * Change the case of all track titles instantly (Title Case, Sentence case, UPPERCASE, lowercase).
* **Bilingual UI:** Instantly switch between English and Russian.

### 🚀 How to Use

**Option 1: Use Online (No download required)**
1. Click the **[Live Demo](https://vadimlevo.github.io/CUE-Master-Editor/index.html)** link.
2. Drag and drop your audio, CUE, or XML files into the drop zone.
3. Edit metadata, generate timings, or paste a setlist.
4. Click **"SAVE CUE"** to download your perfectly formatted Master CUE sheet.

**Option 2: Use Offline**
1. Download the `index.html` file to your computer.
2. Double-click to open it in any modern web browser (Chrome, Edge, Firefox, Safari) without needing an internet connection.

---

<a name="русский"></a>
## 🇷🇺 CUE Master Editor
Мощное веб-приложение в одном файле для создания, редактирования и "починки" CUE-файлов. Работает на 100% локально прямо в вашем браузере. Вы можете использовать его прямо онлайн через GitHub Pages или скачать для работы без интернета!

### ✨ Главные особенности
* **Никаких зависимостей:** Без установок и без загрузки файлов на сервер. Все ваши файлы остаются только на вашем компьютере.
* **Умный Drag & Drop:** Перетаскивайте файлы `.cue`, `.txt`, `.xml` (Главы Matroska/Blu-ray), `.flac`, `.wav` или `.mp3` прямо в окно.
* **Парсинг XML-глав:** Мгновенная конвертация файлов глав от Blu-ray/MKV в готовые треки CUE с точным таймингом.
* **Починка кодировки:** Программа автоматически распознает "сломанную" кириллицу (Windows-1251) из старых файлов и корректно переводит её в современный UTF-8.
* **Авто-определение длительности:** Перетащите аудиофайл, и браузер мгновенно вычислит его точную длину.
* **Генератор нарезки (Auto-Split):** Нужно порезать 2-часовой диджей-микс или оцифровку винила? Укажите время, и программа сама расставит индексы на равные части или заданные интервалы.
* **Генератор по таймингам:** Вставьте список длительностей (например, с обложки пластинки), и программа сама рассчитает абсолютные индексы нарастающим итогом.
* **Склейка (Merge):** Мгновенный расчет индексов друг за другом для непрерывного микса (удобно при объединении нескольких файлов в один).
* **Массовые действия:**
    * **Умный Сетлист:** Вставьте список треков текстом — программа сама отбросит нумерацию (01., 2-) и переименует треки по порядку.
    * Применение Исполнителя или Общего аудиофайла ко всем трекам альбома в один клик.
    * Массовая смена регистра названий (Каждое Слово С Заглавной, ВСЕ ЗАГЛАВНЫЕ, все строчные и т.д.).
* **Двуязычный интерфейс:** Мгновенное переключение между русским и английским языком без перезагрузки страницы.

### 🚀 Как использовать

**Вариант 1: Использовать онлайн (Без скачивания)**
1. Просто перейдите по ссылке на **[Онлайн-версию](https://vadimlevo.github.io/CUE-Master-Editor/index.html)**.
2. Перетащите в окно ваши аудиофайлы, кривые CUE или XML-главы.
3. Отредактируйте теги, сгенерируйте тайминги или вставьте готовый сетлист.
4. Нажмите **"СОХРАНИТЬ CUE"**, чтобы получить идеальный файл CUE.

**Вариант 2: Локальное использование (Оффлайн)**
1. Скачайте файл index.html и сохраните как CUE_Master.html (или как вам нравится) на свой компьютер.
2. Запускайте его двойным кликом в любом браузере (Chrome, Edge, Firefox, Safari) даже когда нет интернета.

---
**License:** MIT License. Feel free to fork and improve!
