<p align="center">
  <img src="assets/phoenix-icon.png" width="110" alt="PHOENIX" />
</p>

<h1 align="center">PHOENIX Launcher</h1>

<p align="center">
  <strong>Панель управления SCUM Dedicated Server для Windows</strong><br/>
  Сервер · Discord-бот · RCON · экономика · карта · модули · веб-доступ с телефона<br/>
  <em>© 2026 ХоМыЧ / Homych</em>
</p>

<p align="center">
  <a href="../../releases/latest"><img src="https://img.shields.io/badge/⬇%20Скачать-PHOENIX--Launcher--Setup.exe-ff7a18?style=for-the-badge" alt="Download" /></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/version-3.8.8-orange" alt="version" />
  <img src="https://img.shields.io/badge/platform-Windows%2010%2F11%20x64-blue" alt="platform" />
  <img src="https://img.shields.io/badge/UI-RU%20%2F%20EN-green" alt="language" />
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-EULA-lightgrey" alt="license" /></a>
</p>

---

## Что это

**PHOENIX** — лаунчер для владельцев и админов **SCUM Dedicated Server**.
Один интерфейс вместо десятка скриптов и ручных правок конфигов:

| | |
|---|---|
| 🖥 **Сервер** | Start / Stop / Restart, флаги запуска, расписание рестартов, watchdog (автоподъём после падения), обновление сервера через SteamCMD |
| ⚙️ **Конфиги** | Редактор `ServerSettings.ini` по категориям, экономика (EconomyOverride), админы / рейды / бан / whitelist, страховочные бэкапы перед опасными операциями |
| 🤖 **Discord** | Игровой чат, входы/выходы, убийства, постройки, техника, тикеты, алерты, логи модулей |
| 🎮 **Игроки** | Онлайн и отряды, карточки игроков из SCUM.db, VIP, Season Pass, телепорт к базе, запланированная выдача наград |
| 🗺 **Карта** | Сектора, метки, ящики, координаты для телепортов |
| 🧩 **Модули** | Рулетка · Стартовый набор · Магазин · Аренда техники · Тайники · Карго-дроп · Промокоды · Daily / Playtime · Казино · WARGM |
| 📱 **Удалённо** | Веб-панель с паролем (LAN / Tailscale / Cloudflare), мобильная версия `/m` |
| 🔌 **RCON** | Подключение, диагностика, импорт локального config.ini |

## Установка

1. Скачайте **`PHOENIX-Launcher-Setup-3.8.8.exe`** из [последнего релиза](../../releases/latest).
2. Запустите установщик. Если Windows SmartScreen предупредит о неизвестном издателе — «Подробнее» → «Выполнить в любом случае» (сборка не подписана сертификатом).
3. После первого запуска в **Настройках** укажите:
   - папку SCUM Dedicated Server (или установите сервер через SteamCMD прямо из лаунчера);
   - Discord-токен бота и каналы (если нужен Discord);
   - RCON — кнопка «Диагностика / Подключить» сама подскажет, чего не хватает.

**Требования:** Windows 10/11 x64. Данные хранятся в `%APPDATA%\PHOENIX` (папку можно сменить в Настройках).

## Обновления

Начиная с **3.8.1** лаунчер сам проверяет этот репозиторий: **Настройки → Обновления → PHOENIX Launcher**.
Можно выбрать, как часто проверять GitHub. Когда выходит новая версия — само всплывает окно. Скачивание и установка — только после вашего подтверждения.

**SCUM-сервер останавливать не нужно.** Обновление лаунчера его не трогает — он как работал, так и будет работать.

Новые версии публикуются здесь, в [Releases](../../releases) — установленный лаунчер увидит их сам.

## Лицензии

- **PHOENIX Launcher** — проприетарная EULA © 2026 ХоМыЧ / Homych → [LICENSE](LICENSE)
  Бесплатно для серверов, которыми вы управляете. **Продавать лаунчер, ребрендить или продавать сборки запрещено.**
- **UE4SS** — MIT (upstream) · **SteamCMD** — условия Valve · **Electron / npm** — свои лицензии → [THIRD-PARTY-LICENSES.md](THIRD-PARTY-LICENSES.md)

Исходный код не публикуется. Распространяются только официальные сборки из Releases.

## Контакты

- Discord: **`xoma_kz_ekb`**
- Обратная связь — прямо из лаунчера (кнопка Feedback)
- Индивидуальные доработки — платно, по договорённости в личке

---

## English

**PHOENIX** is a Windows control panel for **SCUM Dedicated Server**: process control and schedules, watchdog, `ServerSettings.ini` and economy editors, SteamCMD updates, Discord bot (chat / kills / joins / tickets), RCON connect and diagnose, player database, map, VIP / Season Pass / stashes / cargo drops and other modules, plus a password-protected web remote with a mobile panel.

**Install:** grab `PHOENIX-Launcher-Setup-3.8.8.exe` from the [latest release](../../releases/latest) and run it (SmartScreen: "More info" → "Run anyway"). Windows 10/11 x64.

**Updates:** from 3.8.1 the launcher checks this repository on a schedule you choose (Settings → Updates). A dialog appears when a new version is out. Download and install happen only after you confirm. Do not stop the SCUM server — a launcher update does not touch it.

**License:** proprietary EULA © 2026 ХоМыЧ / Homych — see [LICENSE](LICENSE). Free to use on servers you operate; selling or rebranding PHOENIX is forbidden. Sources are not published; only official builds are distributed via Releases.

**Contact:** Discord `xoma_kz_ekb`.
