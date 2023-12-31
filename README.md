# Project-1 Проект "Игры — Анализ рекламных источников"
**Описание проекта**

Описание проекта: Целью данного проекта является анализ поведения игроков в мобильной игре "Космические братья" в зависимости от источника перехода. Проект предполагает проведение исследовательского анализа данных, анализ влияния источника перехода на поведение пользователей, а также проверку статистических гипотез.

**Описание данных**

В данном проекте используется набор данных, содержащий следующие поля:

Датасет game_actions.csv: 
- event_datetime — время события; 
- event — одно из трёх событий: 
1. building — объект построен, 
2. finished_stage_1 — первый уровень завершён, 
3. project — проект завершён; 
- building_type — один из трёх типов здания: 
1. assembly_shop — сборочный цех, 
2. spaceport — космопорт, 
3. research_center — исследовательский центр; 
- user_id — идентификатор пользователя; 
- project_type — тип реализованного проекта; 

Помимо основного датасета есть два датасета с информацией о рекламных 
активностях. 

Датасет ad_costs.csv: 
- day - день, в который был совершен клик по объявлению 
- source - источник трафика 
- cost - стоимость кликов 

Датасет user_source.csv содержит колонки: 
- user_id - идентификатор пользователя 
- source - источников, с которого пришёл пользователь, установивший 
приложение 

**Заключение**

В ходе анализа рекламных источников в игре "Космические братья" были получены следующие ключевые выводы:
- Предпочтения по типу построенных объектов: Большинство игроков предпочитают строить объекты типа 'spaceport', за которыми следует 'assembly_shop'. Количество построенных объектов типа 'research_center' оказалось наименьшим.
- Уникальные пользователи: В исследовательском анализе было выявлено, что в игре "Космические братья" приняло участие 13576 уникальных пользователей, что представляет количество различных игроков, взаимодействовавших с игрой в данном периоде.
- Динамика активности пользователей: Построена гистограмма распределения событий по времени, которая позволила выявить динамику активности пользователей. Количество событий достигло пика к 10 маю и постепенно снижалось.
- Анализ эффективности источников перехода: Проведенный анализ распределения пользователей по различным источникам позволил выявить наиболее привлекательные каналы для привлечения пользователей. Наибольшее количество пользователей пришло из источника 'yandex_direct', что делает его наиболее востребованным. Следом идут 'instagram_new_adverts' и 'facebook_ads'. Также стоит отметить, что источник 'youtube_channel_reklama' также привлек значительное количество пользователей.
- Успешное завершение первого уровня: Анализ данных по успешному завершению первого уровня показал, что наибольший процент успешного завершения уровня наблюдается у пользователей, пришедших из источников Instagram, YouTube и Yandex.Direct. Это может указывать на более эффективные рекламные кампании в этих источниках.
- Оценка стоимостей привлечения пользователей по каналам: Самой дорогой канал рекламы является Facebook Ads со средней стоимостью привлечения одного пользователя равной 0,79. Вторым по дороговизне каналом рекламы является Instagram Ads со средней стоимостью привлечения одного пользователя равной 0,65. Третьим по дороговизне каналом рекламы является Yandex.Direct со средней стоимостью привлечения одного пользователя равной 0,46. Самым дешевым каналом рекламы является YouTube Channel Reklama со средней стоимостью привлечения одного пользователя равной 0,40.

- **Как запустить проект**

Установите Jupyter Notebook или Jupyter Lab.

Откройте файл с проектом в Jupyter.

Запустите все ячейки по порядку.
