<p align="center">
  <img src="assets/phoenix-icon.png" width="120" alt="PHOENIX Launcher" />
</p>

<h1 align="center">PHOENIX Launcher</h1>

<p align="center">
  <strong>Полный набор инструментов для управления SCUM Dedicated Server</strong><br />
  Собственный RCON · автоматизация · Discord · игроки и мир · игровые модули · веб-доступ
</p>

<p align="center">
  <a href="https://github.com/xomyak014-ui/phoenix-launcher-releases/releases/latest"><img src="https://img.shields.io/badge/Скачать-PHOENIX%20Launcher-ff7a18?style=for-the-badge" alt="Скачать PHOENIX Launcher" /></a>
  <img src="https://img.shields.io/badge/Windows-10%20%2F%2011%20x64-0078d4?style=for-the-badge" alt="Windows 10 / 11 x64" />
  <img src="https://img.shields.io/badge/Интерфейс-RU%20%2F%20EN-3fb950?style=for-the-badge" alt="Русский и английский интерфейс" />
</p>

<p align="center">
  <a href="#features">Возможности</a> ·
  <a href="#modules">Модули</a> ·
  <a href="#installation">Установка</a> ·
  <a href="#contacts">Контакты</a> ·
  <a href="#english">English</a>
</p>

---

## О лаунчере

**PHOENIX Launcher** — приложение для Windows, созданное для владельцев и администраторов **SCUM Dedicated Server**. Оно объединяет запуск сервера, настройку игрового мира, собственный RCON, Discord-бота, работу с игроками, экономикой, базами и транспортом в одной панели.

PHOENIX помогает автоматизировать повседневные задачи: перезапуски, выдачу наград, события, сообщения, резервное копирование и восстановление сервера после сбоя. Нужные функции настраиваются отдельно — можно использовать как базовое управление сервером, так и полный набор модулей.

Лаунчер устанавливается на ваш компьютер. Для управления из другого места предусмотрены полноценная веб-панель и отдельный мобильный интерфейс.

## Собственный RCON PHOENIX

**RCON-мод и лаунчер разработаны как единая система PHOENIX.** Для этой связки не требуется отдельный сторонний RCON-мод.

- **Установка из интерфейса.** Вкладка «RCON мод» позволяет установить и настроить компонент на выбранном SCUM-сервере.
- **Команды внутри игры.** Собственный мост связывает панель управления с сервером и выполняет административные команды.
- **Работа на пустом сервере.** Невидимый служебный исполнитель позволяет выполнять поддерживаемые команды и автоматические задачи без постоянно подключённого администратора.
- **Восстановление связи.** После перезапуска сервера лаунчер автоматически восстанавливает соединение.
- **Удалённое развёртывание.** Файлы компонента можно экспортировать в папку или загрузить на совместимый хостинг по FTP / SFTP.
- **Консоль и диагностика.** Подключение, отправка команд, проверка связи и отчёты доступны в самом лаунчере.

Это основа для тайников, выдачи предметов, наград, объявлений и других автоматических действий. Некоторые операции над конкретным игроком требуют его присутствия в игре.

<a id="features"></a>

## Возможности

### Управление сервером и автоматизация

- Запуск, остановка и перезапуск SCUM Dedicated Server.
- Настройка параметров запуска, портов и количества слотов.
- Установка и обновление сервера через SteamCMD.
- Расписание рестартов по времени, дням недели или повторяющемуся интервалу.
- Управление часовыми роботами по расписанию.
- Watchdog — контроль состояния и автоматический запуск после падения сервера.
- Параметры автозапуска лаунчера, сервера и Discord-бота.
- Главная панель с онлайном, CPU, памятью, временем работы и состоянием подключённых служб.
- Проверка новых официальных сборок PHOENIX; скачивание и установка только после подтверждения пользователя.

### Консоль и инструменты администратора

- Встроенная RCON-консоль с ответами сервера.
- Сохранённые, часто используемые и пользовательские команды.
- Административные действия из карточек игроков и объектов.
- Инструменты телепортации и копирование готовых команд с координатами.
- Диагностика подключения и отчёты о выполненных операциях.

### Игроки и отряды

- Список игроков с поиском и фильтрами активности.
- Просмотр онлайна и группировка игроков по отрядам.
- Карточки на основе данных `SCUM.db`: профиль Steam, статистика, баланс, активность, отряд, базы и транспорт.
- Заметки об игроках и доступные действия администратора, включая управление характеристиками, навыками и балансом.
- Состав отрядов, показатели, флаги и количество построек.
- Просмотр участников отряда в игре, сброс названия и управление базой отряда.

Доступность отдельных действий зависит от состояния игрока, подключения RCON и актуальности сохранения сервера.

### Базы и флаги

- Список баз по флагам с владельцами и сведениями о постройках.
- Просмотр базы на карте и копирование команды телепорта.
- Удаление флага или базы с проверками принадлежности объектов и отчётом о результате.
- Прокачка построек на один уровень либо до бетона.
- Выполнение прокачки сразу или после того, как сервер опустеет.
- Предупреждения перед потенциально тяжёлыми операциями с большими базами.

### Транспорт и карта

- Список транспорта, владельцы, идентификаторы объектов и координаты.
- Переход к машине на карте и копирование готовой команды телепорта.
- Удаление отдельной машины; массовое удаление транспорта с дополнительным подтверждением.
- Интерактивная карта SCUM с секторами, масштабированием и слоями.
- Метки игроков, транспорта, баз, флагов, ящиков, тайников и карго-дропов.
- Переход между списком объектов, карточками и соответствующими точками на карте.

### Настройки сервера и экономика

- Редактор `ServerSettings.ini` с категориями и пояснениями к параметрам.
- Управление списками администраторов, банов, whitelist и временем рейдов.
- Редактор `EconomyOverride`: поиск и сортировка предметов, настройка цен и параметров.
- Массовое изменение цен на заданный процент.
- Копирование кодов предметов для команд и конфигурации модулей.
- Резервные копии настроек и запись критических файлов через безопасную подмену.

### Discord-бот и журналы

- Передача игрового чата в Discord.
- Уведомления о входе и выходе игроков.
- Журналы убийств: PvP, NPC и самоубийства.
- События строительства и активности транспорта.
- Уведомления о состоянии сервера и служб лаунчера.
- Система тикетов и инструменты whitelist.
- Выгрузки данных, логи модулей и событий.
- Настройка бота и каналов для нужных типов сообщений.

<a id="modules"></a>

## Игровые и общественные модули

### События и выдача предметов

- **Рулетка.** Запуск командой, по общему таймеру или в платном режиме; настройка призов и правил участия.
- **Стартовые наборы.** Предметы для новых игроков и режим выдачи после смерти.
- **Выдача по расписанию.** Автоматическая раздача настроенных предметов в заданное время.
- **Тайники.** Точки размещения по координатам, тип контейнера или транспорта, лут, охрана, подсказки и настройки появления. Отслеживание срока жизни, тестовый запуск и автоматическая очистка созданных объектов.
- **Карго-дроп.** Настройка точек, содержимого, появления и уведомлений о событии.

Под **точкой тайника** понимается место его появления на карте, а не очки или игровая валюта.

### Экономика и транспорт

- **Магазин.** Настраиваемый каталог предметов, цены и покупка через игровые команды.
- **Аренда техники.** Каталог транспорта, стоимость и срок аренды, учёт выданных машин и обработка окончания аренды.
- **Страховка транспорта.** Настройки и учёт страхования автомобилей.
- **Казино.** Игровые ставки, выигрыши и настраиваемые правила.

### Награды и привилегии

- **Промокоды.** Коды с настраиваемыми наградами и условиями использования.
- **Daily.** Награды за ежедневное получение бонуса.
- **Playtime.** Награды за время, проведённое на сервере.
- **VIP.** Управление привилегиями и отдельными либо общими правилами модулей.
- **Season Pass.** Сезонный прогресс и настроенные награды.
- **Телепорт на базу.** Возвращение игрока к базе по заданным правилам.
- **WARGM.** Интеграция с мониторингом и системой наград за голосование.

### Общение с игроками

- Автоматические сообщения и объявления по расписанию.
- Приветствия и уведомления о входе и выходе.
- Публикация информации об онлайне в игровом чате.
- Уведомления о событиях модулей и результатах выдачи.

Каждый модуль включается и настраивается отдельно. Для автоматических задач лаунчер должен оставаться запущенным, а необходимые подключения и права — настроенными.

## Редактор миссий

- Создание и редактирование собственных миссий.
- Поиск, примеры и фильтры по торговцам и уровням заданий.
- Работа с целями и параметрами миссий.
- Просмотр официальных заданий и управление их доступностью.
- Создание необходимых папок и резервных копий файлов миссий.
- Встроенные пояснения по настройке.

## Резервные копии и файлы

- Автоматические и ручные снимки базы SCUM.
- Резервное копирование перед рестартами, обновлением сервера и рядом операций с игровыми событиями.
- Просмотр, создание, восстановление и удаление копий из интерфейса; восстановление базы выполняется при остановленном сервере.
- Настройка количества сохраняемых копий.
- Выбор папки данных, просмотр занимаемого места и очистка кэша.
- Работа с файлами хостинга по FTP / SFTP.
- Дополнительный локальный FTP / SFTP-сервис для доступа к файлам сервера.

## Веб-панель и мобильный доступ

- Полный интерфейс лаунчера в браузере.
- Отдельная компактная панель для телефона по адресу `/m`.
- Вход по паролю.
- Доступ через локальную сеть, Wi-Fi, Tailscale или Cloudflare.
- Управление сервером, ботом, RCON и поддерживаемыми модулями с другого компьютера или телефона.
- Синхронизация изменений между настольным приложением и веб-панелью.

Для удалённого доступа требуется настройка сети. Используйте надёжный пароль и ограничивайте доступ к панели и файловым службам. Возможности удалённого хостинга зависят от предоставленных прав и доступа к файлам сервера.

## Интерфейс

- Русский и английский языки.
- Настраиваемое название сервера, эмблема и акцентный цвет главной страницы.
- Навигация по разделам управления, игрового мира и инструментов.
- Изменяемый порядок разделов.
- Индикаторы состояния, прогресс операций и отчёты о результатах.

<a id="installation"></a>

## Установка и начало работы

1. Откройте [официальную страницу загрузки](https://github.com/xomyak014-ui/phoenix-launcher-releases/releases/latest) и скачайте установщик **PHOENIX Launcher Setup**.
2. Установите приложение на Windows и запустите его.
3. В настройках выберите папку **SCUM Dedicated Server** или установите сервер через SteamCMD.
4. Настройте соединение во вкладке **«RCON мод»** для игровых команд и связанных с ними модулей.
5. При необходимости подключите Discord-бота, веб-доступ и файловые службы.
6. Включите нужные модули, проверьте их настройки и сохраните резервную копию перед важными изменениями.

**Требования:** Windows 10 / 11 x64 и доступ к SCUM Dedicated Server. Для некоторых операций могут потребоваться права администратора. Полное локальное управление предполагает доступ к файлам и процессу сервера; Discord и удалённые подключения настраиваются отдельно.

Рабочие данные по умолчанию находятся в `%APPDATA%\PHOENIX`; папку можно изменить в настройках.

**О загрузке:** установщик не подписан сертификатом, поэтому Windows SmartScreen может показать предупреждение о неизвестном издателе. Проверяйте источник файла. Если доверяете установщику из этого репозитория, продолжить можно через «Подробнее» → «Выполнить в любом случае».

## Лицензия

**PHOENIX Launcher** — независимый проект **ХоМыЧ / Homych**, распространяемый по [проприетарной EULA](LICENSE). Бесплатен для серверов, которыми вы владеете или которые уполномочены администрировать.

Продавать лаунчер или доступ к его скачиванию, присваивать авторство и подменять брендинг в распространяемых сборках запрещено. Полные условия определяются EULA. Сторонние компоненты сохраняют свои лицензии — [THIRD-PARTY-LICENSES.md](THIRD-PARTY-LICENSES.md).

Этот репозиторий содержит описание продукта и официальные сборки. **Исходный код не публикуется.** PHOENIX не является официальным продуктом разработчиков или издателей SCUM.

<a id="contacts"></a>

## Контакты и официальные страницы

- **Разработчик:** ХоМыЧ / Homych
- **Discord:** `xoma_kz_ekb`
- **GitHub:** [PHOENIX Launcher](https://github.com/xomyak014-ui/phoenix-launcher-releases)
- **YouTube:** [PHOENIX Launcher](https://www.youtube.com/@PHOENIXLauncherSCUM)
- **Nexus Mods:** [Страница PHOENIX Launcher](https://www.nexusmods.com/scum/mods/216)
- **Обратная связь:** кнопка **Feedback** в приложении
- **Индивидуальные доработки:** по договорённости с автором в Discord

Не публикуйте Discord-токены, пароли RCON, конфигурации с секретами и личные данные игроков в открытых обращениях.

---

<a id="english"></a>

## English

### SCUM server administration in one application

**PHOENIX Launcher** is a Windows control panel for **SCUM Dedicated Server** owners and administrators. It combines server control, its own RCON system, configuration and economy editors, Discord integration, player and world management, gameplay modules, backups and remote access.

### PHOENIX's own RCON

Install the RCON component from the launcher, connect through the built-in console and diagnose the connection without a separate third-party RCON mod. An invisible in-game executor handles supported commands and automated tasks even on an empty server. The connection is restored after server restarts. Files can be exported or deployed to compatible hosting through FTP / SFTP. Some player-specific actions require that player to be online.

### Server control and administration

- Start, stop and restart the server; configure launch options, ports and player slots.
- Install and update SCUM Dedicated Server through SteamCMD.
- Schedule restarts by time, weekday or interval, and configure sentry schedules.
- Use watchdog recovery and launcher, server and Discord-bot autostart options.
- View online count, CPU, memory, uptime and service status.
- Use the RCON console, saved commands, admin actions, diagnostics and operation reports.
- Check for official PHOENIX builds; downloading and installation require your confirmation.

### Players, squads and world

- Search players and activity, inspect online lists and squad membership.
- View player profiles, statistics, balance, notes, bases, vehicles and available administrative actions.
- Inspect squad members, scores, flags and building counts; see who is online, reset squad names and manage squad bases.
- Manage bases by flag, inspect ownership, locate them on the map, remove flags or structures and upgrade buildings by one level or to concrete.
- Run base upgrades immediately or defer them until the server is empty.
- Inspect vehicles, owners, IDs and coordinates; copy teleport commands and remove vehicles with confirmation.
- Browse map sectors and layers for players, vehicles, bases, flags, chests, stashes and cargo drops.

Available actions depend on RCON connectivity, player state and the freshness of server-save data.

### Configuration, economy and Discord

- Edit `ServerSettings.ini` by category with explanations for settings.
- Manage admin, ban, whitelist and raid-time files.
- Edit `EconomyOverride`, search and sort items, adjust prices in bulk and copy item codes.
- Use configuration backups and safer atomic writes for critical files.
- Relay game chat to Discord and log joins, leaves, PvP / NPC kills, suicides, building and vehicle events.
- Configure tickets, whitelist tools, server alerts, data exports and module logs.

### Gameplay and community modules

- **Roulette:** command-triggered, timer-based and paid modes with configurable prizes.
- **Starter kits:** rewards for newcomers and post-death recovery.
- **Scheduled distribution:** automated item delivery at configured times.
- **Stashes:** spawn locations, containers or vehicles, loot, guards, hints, lifetime tracking, test spawning and automatic cleanup. A stash point is a location on the map, not a score or currency.
- **Cargo drops:** locations, contents, spawning and announcements.
- **Store:** configurable catalog, prices and in-game purchases.
- **Vehicle rental and insurance:** rental catalogs, prices, durations, expiry handling and insurance settings.
- **Casino:** bets, winnings and configurable rules.
- **Promo codes:** rewards and redemption conditions.
- **Daily and playtime rewards:** bonuses for daily claims and time spent on the server.
- **VIP and Season Pass:** privileges, shared or separate module rules, seasonal progress and rewards.
- **Base teleport:** player travel to a base under configured rules.
- **WARGM:** monitoring and voting-reward integration.
- **Messaging:** scheduled announcements, welcome messages, join / leave notices, online-count messages and module notifications.

Modules are enabled separately. Keep the launcher running and the necessary connections configured for scheduled tasks and automation.

### Missions, backups and files

- Create and edit custom missions, use examples and filter by trader or tier.
- Configure mission objectives and manage the availability of official missions.
- Create mission folders and backups, with built-in setup guidance.
- Create automatic or manual SCUM database snapshots, manage retention and restore with the server stopped.
- Inspect data-folder usage, change its location and clean the cache.
- Work with remote server files through FTP / SFTP or configure an optional local file service.

### Remote access and interface

Use the full browser panel or the compact `/m` mobile interface with password authentication through LAN, Wi-Fi, Tailscale or Cloudflare. Supported settings synchronise between the desktop launcher and web panel. Remote-hosting capabilities depend on the access granted by the provider.

The interface supports Russian and English, a custom server name and emblem, accent colour, adjustable navigation order, status indicators and operation reports. Protect remote panels and file services with strong credentials and appropriate network restrictions.

### Getting started

Download **PHOENIX Launcher Setup** from the [official download page](https://github.com/xomyak014-ui/phoenix-launcher-releases/releases/latest). Install it on Windows 10 / 11 x64, select your SCUM Dedicated Server folder and configure PHOENIX RCON. Enable Discord, remote access and modules as needed. Administrative privileges may be required for some operations.

The installer is unsigned, so SmartScreen may warn about an unknown publisher. Verify the download source. If you trust the file from this repository, choose **More info → Run anyway**. Working data defaults to `%APPDATA%\PHOENIX` and can be relocated in Settings.

**License:** proprietary [EULA](LICENSE), © 2026 **ХоМыЧ / Homych**. Free for servers you own or are authorised to administer. Selling the launcher or charging for downloads, claiming authorship and replacing branding in distributed builds are prohibited. See the EULA for complete terms. Source code is not published.

**Contact:** Discord `xoma_kz_ekb` or the in-app **Feedback** button. Custom development is available by arrangement with the author. Never include tokens, passwords or private player information in public support requests.

PHOENIX is an independent community tool, not an official product of SCUM's developers or publishers.

<p align="center">© 2026 ХоМыЧ / Homych · PHOENIX Launcher</p>
