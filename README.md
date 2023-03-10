# Анализ платёжеспособности заёмщиков

[ipynb](https://github.com/volovik-denis/Yandex-Practicum/blob/DA-02-Bank-credit-scoring/Исследование%20надёжности%20заёмщиков.ipynb)

## Описание проекта

Заказчик — кредитный отдел банка. Нужно разобраться, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. Входные данные от банка — статистика о платёжеспособности клиентов.

Результаты исследования будут учтены при построении модели кредитного скоринга — специальной системы, которая оценивает способность потенциального заёмщика вернуть кредит банку.

## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- matplotlib.**pyplot**
- **seaborn**
- nltk.stem.**SnowballStemmer**
- pymystem3.**Mystem**



## Вывод

Начальные данные состояли из 21525 строк, после обработки их осталось 21424. Выборка является достаточной для проведения исследования.

Обработка данных состояла в заполнении пропусков, корректировке неверных значений, обработке дубликатов, категоризации и лемматизации.

Выявлены следующие зависимости:

- с возрастанием количества детей от 0 до 4 возрастает количество должников
- с возрастанием дохода уменьшается количество должников
- цели кредита влияют на своевременный возврат кредита: наибольшее количество должников берут кредит на автомобиль, далее - на образование, на свадьбу и наименьшее количество должников берут кредит на жильё.
