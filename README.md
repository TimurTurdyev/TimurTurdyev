<h1 align="center">Тимур Турдыев</h1>

<p align="center"><b>Backend / Full-stack разработчик</b><br/>Серверный код пишу с 2014-го. До этого был свой интернет-магазин и SEO - в разработку пришёл, уже понимая, где бизнес теряет деньги. Сейчас - IoT-платформа Waviot (кабинет клиентов, телеметрия, лицензии, учёт производства), собственная платформа Mercurio для интернет-магазинов и пять open-source пакетов, выросших из неё.</p>

<p align="center"><img src="./assets/typing.svg" alt="Стек по годам: с 2014 до сегодня" /></p>

<p align="center">
  <a href="https://timcode.ru"><img src="https://img.shields.io/badge/timcode.ru-резюме%20и%20кейсы-111827?style=flat-square" /></a>
  <a href="https://t.me/borodatimur"><img src="https://img.shields.io/badge/Telegram-@borodatimur-26A5E4?style=flat-square&logo=telegram&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/Email-borodatimur@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white" />
</p>

## Обо мне

В разработке с 2014 года, самоучка. До кода был свой интернет-магазин и несколько лет SEO - в разработку пришёл, уже понимая, что нужно бизнесу и где именно он теряет деньги. Первой платформой стал OpenCart, несколько лет фриланса - форум OpenCart, затем сарафанное радио.

Сейчас основное время - продуктовая разработка в Waviot (IoT-платформа на протоколе NB-Fi): несколько поколений кода в одной компании, от самописного PHP-MVC и Laminas до Laravel, Go и TypeScript. Параллельно строю Mercurio - собственную платформу для интернет-магазинов (админка, CMS и витрина), а куски, полезные сами по себе, выношу в open-source.

## Как я работаю

- Жить с несколькими поколениями кода в одном проекте: legacy без фреймворка, Yii2 и Laminas, современный TypeScript и Go-сервисы.
- Миграции и апгрейды без downtime: PHP 5.6 -> 8.x, Zend Framework -> Laminas, обновления Yii, переключение поисковых движков под задачу.
- Интеграции: CRM, облачные АТС, службы доставки, сервисы данных, IoT-устройства, собственные шлюзы поверх RabbitMQ/AMQP.
- Инженерное суждение важнее стека: иногда правильный ответ - shell-скрипт или SQL-вьюха, а не новый сервис.
- Настройка серверов не живёт в моей голове и в истории ssh: всё описано в Ansible, секреты в Vault. Сервер можно пересобрать с нуля, и он получится таким же. Релизы - Deployer.
- Код должен работать у клиента без меня: запускается, обновляется и чинится в понятных местах.

## Опыт

**[Waviot](https://waviot.ru)** · Backend / Full-stack разработчик · 2021 - сейчас

Продуктовая разработка IoT-платформы на протоколе NB-Fi: кабинет для интеграторов, который партнёры разворачивают у себя, телеметрия, авторизация, лицензии, производство. С нуля написал систему учёта производства на Laravel 12, Inertia и React: с июня 2026 в ней ведут каждую плату по всем этапам. Перевёл кабинет lk.waviot.ru и бэкенд телеметрии с Zend Framework 2 и PHP 5.6 на Laminas и PHP 8 без остановки платформы (2022), следом PSR-12, Doctrine Migrations и Sentry. В кабинете с 2021 года около трети всех изменений: поиск на Sphinx, JWT-авторизация, показания по OBIS, регистрация модемов. Перенёс сервис HES в сервер авторизации, не меняя фронтенд. Сервер лицензий на Yii2 обновил с PHP 5.6 до PHP 8. С 2024 года единственный разработчик старого сервера производства на Python. Свои сервисы: CLI эксплуатации на Laravel Zero, геокодирование через DaData, вебхуки телеметрии поверх RabbitMQ.

**Свои клиенты** · Разработчик, параллельно с основной работой · 2022 - сейчас

Несколько давних клиентов, которых веду годами. prvoffice.ru (офисная мебель) с 2022 года: админка на Livewire, витрина на Blade, поиск LIKE -> Meilisearch -> Manticore, регионы поддоменами, переезд на новый сервер через Ansible. mayatriza.ru с 2024 года: три кодовые базы с нуля, текущая на Laravel 13 с админкой на Inertia и React. lpack-spb.ru (упаковка) с 2025 года: экран продаж поверх 1С, ролики на старом OpenCart, портал обучения и аттестации сотрудников. prvoffice и lpack переезжают на мою платформу Mercurio, которую строю с 2025 года.

**[Prime Wood](https://prime-wood.ru)** · Веб-разработчик · 2019 - 2021

Интернет-магазин офисной мебели. За два месяца в одиночку перенёс магазин с MyCMS на OpenCart (ocStore): каталог, цены в трёх валютах, коллекции и цвета, SEO и старые адреса - своими SQL-запросами; покупатели смены движка не заметили. Весь магазин мой: фронт и бэк, своя тема и редизайны, поисковые подсказки на Sphinx, обмен с 1С, Roistat, курсы валют по расписанию. Магазин работает до сих пор.

**Фриланс** · Веб-разработчик · 2014 - 2019

Магазины, интеграции и миграции на OpenCart и Laravel: начинал с русскоязычного форума OpenCart, дальше проекты шли по рекомендациям. Интеграции с Mango Office, Megaplan, Dadata, СДЭК, 1С и маркетплейсами.

## Кейсы

Разборы задач по истории git: что было, что решил, что вышло. Полностью на [timcode.ru](https://timcode.ru).

- **[Магазин офисной мебели, 2022-2026](https://timcode.ru/cases/office-furniture-shop)** (2026). Веду prvoffice.ru с нуля четвёртый год: своя админка, своя витрина, три редизайна, три этапа поиска и массовое редактирование каталога.
- **[Магазин упаковки: задачи вокруг старого OpenCart, не ломая его](https://timcode.ru/cases/lpack)** (2026). Оптово-розничный магазин упаковки в Петербурге с учётом в 1С. За год вокруг боевого OpenCart 2.3 появились экран показателей отдела продаж, видеораздел с фоновой конвертацией, портал аттестации сотрудников, отчёт по трафику и демо новой витрины на Mercurio. Магазин при этом не останавливался.
- **[Майятрица: калькулятор, админка и сайт, три кодовые базы за два года](https://timcode.ru/cases/mayatriza)** (2026). Долгий клиент: эзотерический сайт с расчётом «майянской матрицы» по дате рождения. С 2024 года написал с нуля три кодовые базы: сайт на Laravel 11, отдельную админку на MoonShine и нынешний сайт на Laravel 13 с новым дизайном, который прорабатывал вместе с заказчицей, и своей админкой на Inertia, React и shadcn. Расчёты сверены с документами заказчицы, клипы перекодирует ffmpeg.
- **[Учёт производства с нуля: платы, сканер и один маршрут в коде](https://timcode.ru/cases/factory)** (2026). Написал систему учёта плат для производства Waviot: сначала прототип на готовой админке, потом своя платформа. С июня 2026 года цех ведёт в ней каждую плату, и теперь в неё переезжает всё производство с легаси 2016 года.
- **[Mercurio: своя платформа для интернет-магазинов](https://timcode.ru/cases/mercurio)** (2025). С 2025 года строю Mercurio: платформу, где сырьё поставщиков неизменяемо, человек правит только решения, а каталог собирается детерминированно. Два клиента, обе витрины пока на демо-стендах.
- **[На один сервис меньше: перенос HES в сервер авторизации](https://timcode.ru/cases/hes-to-auth)** (2024). Два самописных PHP-сервиса Waviot делили один интерфейс: экраны жили в auth, их бэкенд в HES. Перенёс HES внутрь auth так, что фронт не заметил, и закрыл один сервис с отдельным деплоем.
- **[Кабинет и телеметрия IoT-платформы: с Zend Framework 2 на Laminas и PHP 8](https://timcode.ru/cases/zend-to-laminas)** (2022). Перевёл кабинет клиентов и бэкенд телеметрии Waviot с Zend Framework 2.3 и PHP 5.6 на Laminas и PHP 8 без остановки платформы, а потом закрепил результат: PSR-12, миграции БД, Sentry.
- **[Экран отдела продаж: сделки из Мегаплана, звонки из Mango Office](https://timcode.ru/cases/prime-wood-sales-screen)** (2020). Для отдела продаж Prime Wood сделал экран на офисный монитор: план месяца, оплаты за день, необработанные заявки и звонки по менеджерам. PHP без фреймворка и крон, потому что этого хватало. Работу с API Mango Office потом вынес в Laravel-пакет.
- **[Магазин мебели: с самописной CMS на OpenCart за два месяца](https://timcode.ru/cases/prime-wood-opencart)** (2019). В одиночку перенёс prime-wood.ru с самописной MyCMS 2013 года на OpenCart, релиз перед Новым годом. Покупатели смены движка не заметили, магазин работает на этой платформе седьмой год.

## Стек и почему так

| Часть | Стек | Почему так |
| --- | --- | --- |
| Кабинет клиентов lk.waviot.ru | Laminas · PHP 8 · MongoDB ODM | Кабинет для интеграторов, партнёры ставят его у себя deb-пакетом под своим брендом. В 2022 перевёл с Zend Framework 2 и PHP 5.6 на Laminas и PHP 8, дальше развиваю на месте |
| Новый кабинет | Go · Connect/protobuf · React | Слоистый сервис рядом со старым, старая БД кабинета переезжает по частям |
| Телеметрия b.waviot.ru | Laminas (ZF2) · Doctrine · AMQP | Центральное приложение: не переписывается разом, его по кускам заменяет HES |
| HES | PHP 8 · свой MVC · JWT | Замена бэкенда телеметрии на той же базе, JWT вместо сессий |
| Авторизация auth.waviot.ru | PHP 8 · свой MVC · JWT | Учётки, компании и лицензии для всех кабинетов; один JWT для соседних сервисов |
| Лицензии lic.waviot.ru | Yii2 · RBAC · JWT + Go | Работает стабильно, развиваю без переписывания; файлы лицензий отдаёт Go-сервис из deb-пакета |
| Учёт производства | Laravel 12 · Inertia · React · TypeScript | Моя система с нуля, на бою с июня 2026: платы по отделам, сканер, брак, сдельные отчёты; приборы и гарантия на подходе |
| Сервер производства (legacy) | Python · aiohttp | Работает, пока его не заменил новый: дорабатываю без простоя |
| Вебхуки телеметрии | Python · RabbitMQ | Телеметрия из очереди -> HTTP подписчикам; сбой БД или AMQP переживается ретраями |
| CLI эксплуатации | Laravel Zero · PHAR | Один файл на сервере: перенос деревьев объектов, каналы модемов, калибровка |
| Desktop-утилиты | Go · Wails · Vue 3 | Кроссплатформенный бинарник без Electron-веса |
| Свои и клиентские серверы | Ansible · Deployer · Ubuntu LTS | Сервер описан кодом, а не историей ssh-сессий: его можно пересобрать с нуля, и после меня в нём разберётся другой человек |
| Mercurio (свой проект) | Laravel 13 · Inertia · React · PostgreSQL | Сырьё поставщиков неизменяемо, человек правит решения, каталог - пересобираемая проекция; ядро пакетом, у клиента свой сервер |
| Витрины Mercurio | React SSR · Manticore · imgproxy | Своя тема и своё приложение у каждого клиента, поиск и фильтры на Manticore, картинки отдаёт imgproxy |

## Open source

Наружу выношу то, что уже отработало в бою и понадобилось во втором проекте. Организация [mercurioplatform](https://github.com/mercurioplatform) тоже моя.

| Пакет | О чём | Стек |
| --- | --- | --- |
| [mercurioplatform/tables](https://github.com/mercurioplatform/tables) [![packagist](https://img.shields.io/packagist/v/mercurioplatform/tables?style=flat-square&label=)](https://packagist.org/packages/mercurioplatform/tables) | **list/table-движок для Laravel-админок.** Декларативный Resource-класс -> admin-страница одной строкой роута: поиск, сортировка, фильтры, saved views, bulk/row actions, экспорт, prefs, history + undo. Пять сознательных точек расширения - дальше vendor:publish. Страница рендерится сервером, AJAX подгружает только корень таблицы. | PHP · Laravel 13 · Bootstrap 5 · jQuery |
| [timurturdyev/simple-settings](https://github.com/TimurTurdyev/Simple-Settings) [![packagist](https://img.shields.io/packagist/v/timurturdyev/simple-settings?style=flat-square&label=)](https://packagist.org/packages/timurturdyev/simple-settings) | **key-value настройки для Laravel.** Группы, кэш, автоприведение типов, пакетная запись одним upsert: невалиден хоть один ключ - не сохранится ни один. Фасад, Artisan-команды, обход кэша через fresh. | PHP 8.2+ · Laravel 12/13 |
| [simple-db-settings](https://github.com/TimurTurdyev/simple-settings-py) [![pypi](https://img.shields.io/pypi/v/simple-db-settings?style=flat-square&label=)](https://pypi.org/project/simple-db-settings/) | **тот же менеджер настроек для Python.** Порт на SQLAlchemy 2, совместимый с PHP-версией по таблице: сервис на Laravel и сервис на Python читают и пишут одни и те же настройки. TTL-кэш, инвалидация после коммита, аудит изменений с причинителем, работа на внешнем соединении. | Python 3.11+ · SQLAlchemy 2 · pydantic |
| [timurturdyev/simple-cart](https://github.com/TimurTurdyev/simple-cart) [![packagist](https://img.shields.io/packagist/v/timurturdyev/simple-cart?style=flat-square&label=)](https://packagist.org/packages/timurturdyev/simple-cart) | **корзина, закладки и сравнение.** Каждый список - один примитив с политикой из конфига. Деньги считает только корзина, через конвейер классов-корректировок: без float, без магических строк, без обязательных миграций. Написан на замену darryldecode/laravelshoppingcart. | PHP 8.3+ · Laravel 12/13 |
| [timurturdyev/simple-seo](https://github.com/TimurTurdyev/simple-seo) [![packagist](https://img.shields.io/packagist/v/timurturdyev/simple-seo?style=flat-square&label=)](https://packagist.org/packages/timurturdyev/simple-seo) | **meta, Open Graph, Twitter/X и JSON-LD.** Ядро без зависимостей, слой Laravel в том же пакете. Замена artesaos/seotools: дефолты подставляются на рендере и не прилипают к странице, JSON-LD собирается коллекцией в @graph вместо одного перетираемого блока. | PHP 8.2+ · Laravel 11/12 |

## Проекты

| Проект | О чём | Стек |
| --- | --- | --- |
| [Mercurio](https://timcode.ru/cases/mercurio) | Своя платформа для интернет-магазинов: сырьё прайсов поставщиков хранится как есть, человек правит только решения, каталог собирается из них детерминированно. Приём прайсов профилями без кода под поставщика, поиск и фильтры на Manticore, обмен с 1С. У каждого клиента своя витрина, своя база и свой сервер, общее ядро - пакетом. | Laravel 13 · Inertia · React · TypeScript · PostgreSQL · Manticore |
| [Экран продаж lpack](https://github.com/TimurTurdyev/dashboard-lpack) | Показатели отдела продаж оптового магазина упаковки на мониторе в офисе: виджеты из 1С, графики, вкладки сменяются по кругу. | Laravel 12 · jQuery · Chart.js |
| [Laravel-Mango-Office](https://github.com/TimurTurdyev/Laravel-Mango-Office) | Небольшой пакет для API облачной АТС Mango Office: сотрудники, статистика звонков, записи разговоров. Вырос из экрана продаж для Prime Wood. | PHP · Laravel |
| [Export-Import OpenCart + Vue](https://github.com/TimurTurdyev/Export-Import-Opencart-Vue) | Импорт и экспорт товаров OpenCart через Vue-интерфейс без перезагрузки страницы, форматы CSV и XLS. | PHP · Vue · OpenCart |
| [opencart-dadata](https://github.com/TimurTurdyev/opencart-dadata) | Подсказки адресов и ФИО от Dadata при оформлении заказа в OpenCart: быстрее ввод, меньше ошибок в адресах. | Vue · PHP · OpenCart |
| [my-tools-parse-message-waviot](https://github.com/TimurTurdyev/my-tools-parse-message-waviot) | Десктопная утилита для инженеров: разбирает ответы WAVIOT API в карточки по модемам и obis-кодам. Один бинарник без Electron-веса. | Go · Wails · Vue 3 · Tailwind 4 |
| [Экран продаж Prime Wood](https://timcode.ru/cases/prime-wood-sales-screen) | Монитор отдела продаж: сделки из Megaplan и звонки из Mango Office, план месяца и доля закрытых сделок по менеджерам. PHP и cron, без фреймворка. | PHP · Megaplan API · Mango Office API |
| [opencart-image-remover](https://github.com/TimurTurdyev/opencart-image-remover) | Чистка каталога изображений OpenCart от файлов, на которые больше не ссылается ни один товар. | PHP · OpenCart |
| [vpn-help](https://github.com/TimurTurdyev/vpn-help) | Утилиты macOS против конфликта OpenVPN и AmneziaVPN: диагностика, зачистка повисших utun-интерфейсов, сброс DNS. | Bash · macOS |
| [timcode.ru](https://timcode.ru) | Этот сайт: резюме в виде IDE, кейсы и статьи в markdown, справочник по паттернам на четырёх языках, curl-режим и машиночитаемые форматы. Собирается статикой. | VitePress · Vue · TypeScript |

## С чем работаю

**Языки:** PHP 8+ · JavaScript · TypeScript · Go · Python · Java · Bash

**Backend:** Laravel · MoonShine · Yii2 · Laminas · OpenCart · самописный PHP-MVC · FastAPI · aiohttp

**Frontend:** Vue · Alpine.js · Blade · jQuery · Tailwind · Bootstrap · Vite · Wails · Electron

**Базы и поиск:** MySQL · MariaDB · PostgreSQL · SQLite · MongoDB · Redis · SphinxSearch · Manticore · Meilisearch

**Очереди:** RabbitMQ · AMQP

**Инфраструктура:** Docker · Ansible · Deployer · Linux · Nginx · Git · systemd

**Интеграции:** Mango Office · Megaplan · Dadata · СДЭК · ВКонтакте API · OpenCart marketplace API

## Сотрудничество

Берусь за задачи, где нужно разобраться в чужом коде, связать системы или принять инженерное решение. Работаю по рекомендациям и с теми, кто понимает, что именно нужно сделать.

Интересно: интеграции между сервисами, сложная бизнес-логика, легаси без документации, высоконагруженные задачи, архитектурные решения.

Не беру: вёрстку по готовому макету, задачи "сделай как у конкурентов" и проекты без конкретной постановки.

Стоимость зависит от задачи - обсуждаем после того, как услышу, что нужно сделать.

## Контакты

- Telegram: [@borodatimur](https://t.me/borodatimur), обычно отвечаю в тот же день
- Email: borodatimur@gmail.com
- LinkedIn: [Timur Turdyev](https://www.linkedin.com/in/timur-turdyev/)
- Сайт: [timcode.ru](https://timcode.ru), справочник по паттернам: [timcode.ru/handbook](https://timcode.ru/handbook/)
