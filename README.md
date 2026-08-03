<div align="center">

# Zapret Discord Youtube 19.9

### YouTube Unban · Discord connecting / RTC · обход DPI без VPN

**[viceprivatesafeguard/zapret-discord-youtube-19.9](https://github.com/viceprivatesafeguard/zapret-discord-youtube-19.9)** — сборка для Windows 10/11

[**⬇ Скачать последний релиз**](https://github.com/viceprivatesafeguard/zapret-discord-youtube-19.9/releases/latest)

Обход замедлений **YouTube**, **Discord** (голос / RTC) и **Telegram** без VPN  
Альтернатива сборкам на базе [zapret](https://github.com/bol-van/zapret) / GoodbyeDPI

</div>

> [!CAUTION]
>
> ### ФЕЙКИ
> Я не веду никакие другие страницы / группы в Telegram / YouTube.  
> Если вы наткнулись на что-то вне репозитория `viceprivatesafeguard/zapret-discord-youtube-19.9`, что распространяется от моего лица — **ФЕЙК**.

> [!WARNING]
>
> ### АНТИВИРУСЫ / SmartScreen
> WinDivert и `winws.exe` часто дают **ложное** срабатывание Defender / Chrome Safe Browsing при скачивании с GitHub — это типично для DPI-сборок, не признак вируса.  
> WinDivert — перехват трафика (аналог iptables/NFQUEUE под Windows); драйвер WinDivert64.sys подписан.
>
> **Если не даёт скачать:** берите файл **`.rar`** (не `.zip`), откройте ссылку в Edge/Firefox, либо добавьте папку загрузок в исключения Defender.  
> После скачивания: ПКМ по архиву → Свойства → **Разблокировать**. После распаковки — исключение на папку сборки или временно отключить PUA.

> [!IMPORTANT]
> Запускайте файлы только после распаковки архива (не изнутри ZIP / RAR).  
> Путь лучше без кириллицы и спецсимволов. Одновременно с VPN обычно не работает.

## Что исправляет

| Сервис | Типичная проблема | Что делать |
| :--- | :--- | :--- |
| **YouTube** | буферизация, нет 4K, Shorts / превью | `Обход YouTube.bat` или общий запуск |
| **Discord** | Connecting…, нет голоса / RTC | `Обход Discord.bat` или общий запуск |
| **Telegram** | медленное подключение, медиа | `Обход Telegram.bat` или общий запуск |

## Быстрый старт

1. Откройте [**Releases → Latest**](https://github.com/viceprivatesafeguard/zapret-discord-youtube-19.9/releases/latest) и скачайте **`.rar`** (предпочтительно)
2. ПКМ по архиву → **Свойства** → галочка **Разблокировать** (если есть) → ОК
3. Распакуйте по пути без кириллицы / спецсимволов
4. Запустите нужный `.bat` **от имени администратора**
5. Полностью закройте браузер / Discord / Telegram и откройте снова

## Файлы в корне

- [**`Запуск всех сервисов.bat`**](./Запуск%20всех%20сервисов.bat) — Discord + YouTube + Telegram одним кликом
- [**`Обход Discord.bat`**](./Обход%20Discord.bat) — голос, медиа, Discord connecting / RTC
- [**`Обход YouTube.bat`**](./Обход%20YouTube.bat) — буферизация, 4K, Shorts
- [**`Обход Telegram.bat`**](./Обход%20Telegram.bat) — Telegram без прокси
- [**`Статус подключения.bat`**](./Статус%20подключения.bat) — проверка / диагностика

Работоспособность зависит от провайдера. Если один вариант не помог — попробуйте другой bat из корня.

## Частые поисковые запросы

<details>
<summary>YouTube / Discord / DPI (развернуть)</summary>

- YouTube Unban 2026 · youtube не грузит · буферизация YouTube
- Discord connecting · Discord RTC · голос Discord не работает
- обход DPI Windows · обход замедления без VPN
- Zapret Discord YouTube · GoodbyeDPI скачать
- Telegram не подключается · обход блокировок 2026

</details>

## FAQ

### После запуска ничего не изменилось

Полностью закройте браузер / Discord / Telegram и откройте снова. Отключите VPN и расширения вроде Censor Tracker / Browsec. При необходимости выполните `ipconfig /flushdns` в cmd.

### Антивирус удалил файл

Восстановите из карантина, добавьте папку в исключения, запустите bat снова от администратора.

### Конфликт с VPN

В большинстве случаев обход и VPN одновременно не работают — для проверки выключите VPN.

### Только Windows?

Да. Сборка рассчитана на **Windows 10/11**. Для Android/iOS нужны другие решения (ByeByeDPI и т.п.).

<!-- gbzap-unban-flowseal:v4 -->
