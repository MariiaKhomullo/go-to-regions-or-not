# Анализ эффективности бизнес модели в Google Sheets

``` Учебный проект ``` 


## Легенда 

Руководство онлайн-магазина хочет выйти в другие регионы. Необходимо понять, будет ли рентабельным такое расширение бизнеса.


## Цели проекта

 - Определить маркетинговые и продуктовые показатели бизнеса в данный момент.

 - Определить, рентабельно ли масштабировать этот бизнес и открывать магазин в новом регионе.

## Как посмотреть проект

[>> Ссылка на гугл-таблицу](https://docs.google.com/spreadsheets/d/1DNioowApKZQMv-_O2v_ItuPnzYyQY_cK0_px_rUNBOg/edit#gid=436637950)


## Дано 

- таблица с данными о посещениях сайта и покупках в марте и апреле Dataset_user_log
- таблица с данными о переходах по рекламе в марте и апреле в 5 городах Dataset_users

## Использованные методы
```
- Когортный анализ
- Юнит-экономика в разрезе когорт
- Прогноз LTV
- Сегментация по регионам
- ROI и ROMI
- Возвращаемость 
```


## Ключевые инструменты
```
- Сводные таблицы 
- ВПР и MINIFS
- Условное форматирование 
```

## Реализация 

Фрагмент расчета юнит-экономики в разрезе когорт: расчет приведенных показателей — frequency и conversion rate. 

![Скриншот реализации расчета юнит экономики](/unit_economy.png)

Фрагмент расчета LTV по когортам и его прогноза через Gross Profit. 
![Скриншот реализации расчета LTV](/ltv.png)

Фрагмент расчета показателей юнит экономики через сегментацию по регионам.
![Скриншот реализации анализа по регионам](/regions.png)



## Выводы

**Расширение бизнеса через выход в другие регионы не рекомендуется.**
Рекомендуется развивать свое присутствие в 2 крупнейших регионах — Москве и Петербурге. 

Как следует из анализа показателей юнит экономики в разделе Regions, CPL и маржинальность в разных регионах не отличается существенно, когда как показатели дохода у Москвы и Петербурга гораздо выше. Другими словами, при тех же расходах в Петербурге и Москве компания получит доход на 70% выше, чем в менее крупных регионах — Орле и Владимире. 

Кроме того, рекомендуется составить стратегию по образованию аудитории постоянных покупателей как со стороны маркетинговой команды (промокоды, акции, система лояльности и пр.), так и продуктовой. Это увеличит ключевые метрики успеха компании, какие как, например, LTV и Retention.

## Ревью ментора-эксперта учебного курса

> Ваш проект очень порадовал меня - одна из лучших работ, что приходила мне на проверку!...</br>
... Вы просили меня оставить комментарии по вашим выводам: </br>
> - Мне очень понравилось, что вы не стали категорично исключать источник привлечения SMM - на самом деле, он работает не столько на продажи, как на узнаваемость и продвижение бренда компании. В целом, вы даете хорошие выводы по полученному результату при анализе. Молодцы!
> - В реальном проекте, я бы учла дополнительные расходы, которые не представлены в условиях для анализа - аренда офиса, зарплата сотрудников, логистика и др, то есть хорошо было бы привести какой-то бизнес план, понимание точки безубыточности. Также очень важно понимать рынок: наличие конкурентов, ваше стратегическое преимущество, сравнение цен на схожую продукцию, покупательскую способность населения и емкость рынка
