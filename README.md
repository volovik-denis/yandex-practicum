# Анализ музыкальных предпочтений

[ipynb](https://github.com/mvs834/Yandex.Practicum-RUS/blob/92984f4b379980a681aa6aa0397c61cccecb6048/Music%20preferences%20analysis/Music_preferences_analysis.ipynb)

## Описание проекта

Сравнение Москвы и Петербурга окружено мифами:
- Москва — мегаполис, подчинённый жёсткому ритму рабочей недели;
- Петербург — город своеобразной культуры, непохожий на Москву.

Некоторые мифы отражают действительность. Другие — пустые стереотипы. Бизнес должен отличать первые от вторых, чтобы принимать рациональные решения. На реальных данных Яндекс Музыки вы проверите гипотезы и сравните поведение пользователей двух столиц.

## Гипотезы
- Активность пользователей зависит от дня недели. Причём в Москве и Петербурге это проявляется по-разному.
- Утром в понедельник в Москве преобладают одни жанры музыки, а в Петербурге — другие. Это верно и для вечера пятницы.
- Москва и Петербург предпочитают разные жанры музыки. В Москве чаще слушают поп-музыку, в Петербурге — русский рэп.

## Навыки и инструменты

- **python**
- **pandas**

## Вывод

Гипотезы проверены и установлено следующее:

1. День недели по-разному влияет на активность пользователей в Москве и Петербурге. 

Первая гипотеза полностью подтвердилась.

2. Музыкальные предпочтения не сильно меняются в течение недели — будь то Москва или Петербург. Небольшие различия заметны в начале недели, по понедельникам:
* в Москве слушают музыку жанра “world”,
* в Петербурге — джаз и классику.

Таким образом, вторая гипотеза подтвердилась лишь отчасти. Этот результат мог оказаться иным, если бы не пропуски в данных.

3. Во вкусах пользователей Москвы и Петербурга больше общего чем различий. Вопреки ожиданиям, предпочтения жанров в Петербурге напоминают московские.

Третья гипотеза не подтвердилась. Если различия в предпочтениях и существуют, на основной массе пользователей они незаметны.