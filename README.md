<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img src="assets/banner-light.svg" alt="Ким Тэ Ян, разработчик C#/.NET" width="100%">
</picture>

Пишу настольные приложения на C#/.NET 8 и Avalonia: интеграции по REST API, сетевые протоколы, нагрузочное тестирование. За год выпустил пять утилит. Каждую довожу до релиза сам: код, тесты, сборка в один exe и руководство пользователя в PDF.

Кроме этого автоматизирую процессы в n8n, пишу Telegram-ботов и администрирую Linux-серверы (Docker, nginx, systemd).

## Стек

**Основное** &nbsp;
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![.NET 8](https://img.shields.io/badge/.NET_8-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Avalonia](https://img.shields.io/badge/Avalonia-8B44AC?style=flat-square)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![xUnit](https://img.shields.io/badge/xUnit-5E2B97?style=flat-square)

**Веб и боты** &nbsp;
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Telegram Bot API](https://img.shields.io/badge/Telegram_Bot_API-26A5E4?style=flat-square&logo=telegram&logoColor=white)

**Данные и протоколы** &nbsp;
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![REST](https://img.shields.io/badge/REST_API-1F4E79?style=flat-square)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white)
![TCP/UDP](https://img.shields.io/badge/TCP%2FUDP-1F4E79?style=flat-square)

**Инфраструктура** &nbsp;
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![nginx](https://img.shields.io/badge/nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

## Рабочие проекты

Код закрыт: он принадлежит компании и заказчикам.

| Проект | Что делает | Результат |
|---|---|---|
| AssetAutoLoader | Автозагрузка медиа в Carrot по REST API, докачка при обрыве связи | Время оператора на загрузку меньше примерно на 90%; 48-часовой прогон, около 720 ГБ |
| MOS Load Tester | Нагрузочный тест MOS-адаптера реальным эфирным трафиком | 6,4 часа эфира за полторы минуты, до 300 сообщений в секунду |
| EventCleaner | Очистка неиспользуемых событий через API | Ручная чистка ушла, это около 4 часов инженера в месяц |
| Carrot Logs Analyzer | График активности и поиск типовых ошибок в логах | Поиск причины сбоя занимает 10 минут вместо часа |
| Port Tester | Имитация множества устройств на одном TCP/UDP-порту | Проверка без стенда из реального оборудования |
| WbAlert | Оповещение об авариях с контроллеров Wiren Board, эскалация, Telegram, MAX и WhatsApp | Оповещение в течение минуты, до 500 объектов |
| Сценарии n8n | Заявка с почты сразу становится задачей в YouGile | Путь от заявки до готовой графики стал вдвое короче |

## Открытые проекты

| Репозиторий | Что внутри |
|---|---|
| [figma-plugin](https://github.com/Tykkern/figma-plugin) | Плагин Figma: HTML-страница превращается в слои с анимациями, hover и кликами |
| [ktor-kmp-api](https://github.com/Tykkern/ktor-kmp-api) | REST API на Ktor в структуре Kotlin Multiplatform |
| [taskmanager_spring](https://github.com/Tykkern/taskmanager_spring) | REST API на Spring Boot: WebFlux, R2DBC, корутины |
| [user-message-service](https://github.com/Tykkern/user-message-service) | HTTP-сервер на Kotlin поверх TCP-сокетов, без фреймворков |
| [warehouse-app_java_retake](https://github.com/Tykkern/warehouse-app_java_retake) | Учёт запчастей сервисного центра: DAO, JDBC, транзакции |
| [minishop](https://github.com/Tykkern/minishop) | Интернет-магазин на Jakarta Servlet, JSP и JSTL |

## Контакты

Telegram [@tykimm](https://t.me/tykimm) · почта [kimteyan107@gmail.com](mailto:kimteyan107@gmail.com)

<details>
<summary><b>In English</b></summary>
<br>

C#/.NET developer. I build desktop tools on .NET 8 and Avalonia for the Carrot broadcast graphics platform: REST API integrations, network protocols, load testing. Each tool ships as a single exe with a PDF user guide.

Two examples: a media auto-uploader that cut operator time by about 90%, and a MOS load tester that replays 6.4 hours of live broadcast traffic in 90 seconds at up to 300 messages per second.

I also automate workflows with n8n, write Telegram bots and run Linux servers (Docker, nginx, systemd).

Contact: Telegram [@tykimm](https://t.me/tykimm), [kimteyan107@gmail.com](mailto:kimteyan107@gmail.com)

</details>
