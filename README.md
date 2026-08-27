<p align="center">
  <img src="assets/phoenix-icon.png" width="120" alt="PHOENIX" />
</p>

<h1 align="center">PHOENIX Launcher</h1>

<p align="center">
  <strong>Панель управления SCUM Dedicated Server для Windows</strong>
</p>

<p align="center">
  Сервер · RCON · Discord-бот · экономика · игроки · карта · модули · веб-доступ с телефона
</p>

<p align="center">
  <a href="../../releases/latest"><img src="https://img.shields.io/badge/Скачать-PHOENIX--Launcher--Setup.exe-ff7a18?style=for-the-badge&logo=windows&logoColor=white" alt="Скачать" /></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/версия-3.8.9-ff7a18" alt="версия" />
  <img src="https://img.shields.io/badge/Windows-10%20%2F%2011%20x64-0078d4" alt="платформа" />
  <img src="https://img.shields.io/badge/интерфейс-RU%20%2F%20EN-3fb950" alt="язык" />
  <a href="LICENSE"><img src="https://img.shields.io/badge/лицензия-EULA-8b949e" alt="лицензия" /></a>
</p>

---

## Что это

**PHOENIX** — лаунчер для владельцев и админов **SCUM Dedicated Server**.
Один интерфейс вместо десятка скриптов, ручных правок конфигов и сторонних модов.

Поставили, указали папку сервера — дальше всё из окна: запуск и расписание, настройки,
Discord, игроки, экономика, модули. И то же самое с телефона, если нужно.

---

## Свой RCON — главное в этой версии

Раньше, чтобы лаунчер мог отдавать команды серверу, приходилось ставить **сторонний RCON-мод**.
Лаунчер зависел от чужой работы: обновят его или нет, будут ли поддерживать дальше — решали не мы.

**Теперь RCON свой, и всё в одних руках.**

|  |  |
|---|---|
| **Ставится одной кнопкой** | Вкладка «RCON мод» → установить. Лаунчер сам кладёт на сервер небольшой мод и включает его |
| **Работает без игроков** | Команды выполняет «призрак» — админ внутри самой игры. Он есть всегда, поэтому RCON отвечает, даже когда на сервере нет ни одного человека |
| **Невидим** | Призрака не видно, не слышно и об него нельзя споткнуться — в мире не стоит ничьё тело |
| **Поднимается сам** | Связь восстанавливается после рестарта сервера без вашего участия |
| **Можно на другую машину** | Если сервер не на этом компьютере — выгрузка файлов в папку или заливка по FTP / SFTP прямо из лаунчера |

**Что это даёт на практике.** Тайники, награды, стартовые наборы, выдача по расписанию и объявления
работают круглосуточно — а не только пока кто-то держит админа в игре.

---

## Возможности

| | |
|---|---|
| **Сервер** | Start / Stop / Restart, флаги запуска, расписание рестартов, watchdog (автоподъём после падения), обновление через SteamCMD |
| **Настройки** | Редактор `ServerSettings.ini` по категориям с пояснениями к каждой строке, экономика (EconomyOverride), админы / рейды / бан / whitelist, страховочные копии перед каждым сохранением |
| **Discord** | Игровой чат, входы и выходы, убийства, постройки, техника, тикеты, алерты, логи модулей |
| **Игроки** | Онлайн и отряды, карточки игроков из `SCUM.db`, VIP, Season Pass, телепорт к базе, награды по расписанию |
| **Базы** | Список по флагам, прокачка базы одной кнопкой, снять флаг, удалить базу, показать на карте, готовая команда телепорта |
| **Карта** | Сектора, метки, ящики, координаты для телепортов |
| **Модули** | Рулетка · Стартовый набор · Магазин · Аренда техники · Тайники · Карго-дроп · Промокоды · Daily / Playtime · Казино · WARGM |
| **Удалённо** | Веб-панель с паролем (LAN / Tailscale / Cloudflare) и мобильная версия `/m` |

---

## Что нового в 3.8.9

- **Свой RCON** — подробно выше.
- **Прокачка базы из лаунчера.** Кнопка «Прокачать» поднимает постройки базы на уровень — тот же шаг, что делает игра. Стоять в игре не нужно, радиус задавать не нужно: лаунчер обходит постройки именно этой базы, поэтому соседнюю не заденет даже вплотную. Проверено на площадках в шести метрах друг от друга.
- **Вкладка «Базы» переделана.** Строка на флаг, а не на общую запись игры: две базы рядом снова видно по отдельности. Пять кнопок на карточке, удаление забирает только свои постройки.
- **Стартовый набор стал стартовым.** Новый режим «Новичкам и после смерти» выдаёт набор тому, кто только пришёл, и тому, кто с прошлого раза погиб. Смерти читаются из файла сохранения, поэтому считаются все — и от зомби, и от голода.
- **Тайники: лаунчер больше не тормозит.** Списки лута хранятся один раз на всех: 75 МБ базы превратились в 0,4 МБ, страница открывается мгновенно. Ваши точки переносятся сами при первом запуске.
- **Настройки сервера разложены заново** после обновления игры — 24 настройки уехали не в те категории, все вернулись на места, у каждой есть пояснение.
- **Сохранение настроек стало безопаснее.** Файл пишется целиком и подменяется разом, поэтому обрыв посреди записи не оставит сервер без `ServerSettings.ini`.
- **Кнопки «Копировать» работают в браузере.** Раньше через веб-доступ лаунчер рапортовал об успехе, ничего не скопировав.
- **Платная рулетка** — третий режим: игрок покупает прокрутку командой в чате.
- Модули приведены к общему виду: полоса с переключателем сверху, настройки карточками рядом.

Полный список изменений — в самом лаунчере: **Настройки → Обновления → Журнал**.

---

## Установка

1. Скачайте **`PHOENIX-Launcher-Setup-3.8.9.exe`** из [последнего релиза](../../releases/latest).
2. Запустите установщик. Если Windows SmartScreen предупредит о неизвестном издателе —
   «Подробнее» → «Выполнить в любом случае» (сборка не подписана сертификатом).
3. После первого запуска в **Настройках** укажите:
   - папку SCUM Dedicated Server — или установите сервер через SteamCMD прямо из лаунчера;
   - Discord-токен бота и каналы, если нужен Discord;
   - RCON — вкладка «RCON мод», кнопка установки сделает всё сама.

**Требования:** Windows 10 / 11 x64. Данные лежат в `%APPDATA%\PHOENIX` — папку можно сменить в Настройках.

---

## Обновления

Начиная с **3.8.1** лаунчер сам проверяет этот репозиторий: **Настройки → Обновления → PHOENIX Launcher**.
Как часто проверять — выбираете вы. Когда выходит новая версия, окно всплывает само;
скачивание и установка — только после вашего подтверждения.

**SCUM-сервер останавливать не нужно.** Обновление лаунчера его не трогает — как работал, так и будет работать.

---

## Лицензии

- **PHOENIX Launcher** — проприетарная EULA © 2026 ХоМыЧ / Homych → [LICENSE](LICENSE).
  Бесплатно для серверов, которыми вы управляете.
  **Продавать лаунчер, ребрендить или продавать сборки запрещено.**
- **UE4SS** — MIT (upstream) · **SteamCMD** — условия Valve · **Electron / npm** — свои лицензии
  → [THIRD-PARTY-LICENSES.md](THIRD-PARTY-LICENSES.md)

Исходный код не публикуется. Распространяются только официальные сборки из [Releases](../../releases).

---

## Контакты

- Discord: **`xoma_kz_ekb`**
- Обратная связь — прямо из лаунчера, кнопка **Feedback**
- Индивидуальные доработки — платно, по договорённости в личке

---

<h2 align="center">English</h2>

**PHOENIX** is a Windows control panel for **SCUM Dedicated Server**: process control and schedules,
watchdog, `ServerSettings.ini` and economy editors, SteamCMD updates, a Discord bot
(chat / kills / joins / tickets), a player database, map, bases, VIP / Season Pass / stashes /
cargo drops and other modules, plus a password-protected web remote with a mobile panel.

**Its own RCON — the headline of 3.8.9.** PHOENIX used to depend on a third-party RCON mod;
now the RCON is ours. One button on the “RCON mod” tab installs it. Commands run as a *ghost* admin
inside the game, so RCON answers **even with nobody on the server**, and the ghost is invisible —
no body standing in the world for anyone to bump into. The bridge reconnects by itself after a
server restart, and it can be deployed to a server on another machine over FTP / SFTP.

**Also new in 3.8.9:** upgrade a base from the launcher (it walks that base’s own structures, so the
neighbouring base is never raised — tested six metres apart); the Bases tab rebuilt around flags;
a starter kit that can trigger for newcomers and after death; stash loot lists stored once instead of
per point (75 MB → 0.4 MB); server settings re-sorted after the game update and saved atomically.

**Install:** grab `PHOENIX-Launcher-Setup-3.8.9.exe` from the [latest release](../../releases/latest)
and run it (SmartScreen: “More info” → “Run anyway”). Windows 10/11 x64.

**Updates:** from 3.8.1 the launcher checks this repository on a schedule you choose
(Settings → Updates). A dialog appears when a new version is out; download and install happen only
after you confirm. There is no need to stop the SCUM server — a launcher update does not touch it.

**License:** proprietary EULA © 2026 ХоМыЧ / Homych — see [LICENSE](LICENSE). Free to use on servers
you operate; selling or rebranding PHOENIX is forbidden. Sources are not published; only official
builds are distributed via Releases.

**Contact:** Discord `xoma_kz_ekb`.
