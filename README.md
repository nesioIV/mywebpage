
Вы открыли персональную web-страницу **nesioIV**.

<a name="Content"></a> <span style="color:brown"> СОДЕРЖАНИЕ СТРАНИЦЫ</span>

1.  МОИ АЛГОРИТМЫ И ПУБЛИКАЦИИ ПО ТЕМАМ
  * [Сжатие данных без потерь](#Compress)
  * [Разложение натуральных чисел на простые множители](#Factor)
  * [Технический анализ рисков при покупке акций фондового рынка](#Stock)
  * [Финансовый анализ бизнес-процессов предприятия](#Finance)
 2. МОИ НОВЫЕ ПРОГРАММНЫЕ РАЗРАБОТКИ
  * [Комбинаторная головоломка "Трансворды" / "Transwords"](#Transwords)
  * [Примеры решения тестовых задач программирования](#ProgramTask)
 3. МОИ ГУМАНИТАРНЫЕ ПРОЕКТЫ
  * [Telegam-канал по расширению запаса английских слов методом мнемонических ассоциаций](#XorZacepka)
  * [Аудио-подкаст в жанре "Истории для детей"](#deDskoeRadio) 

# МОИ АЛГОРИТМЫ И ПУБЛИКАЦИИ ПО ТЕМАМ

## <a name="Compress"></a> СЖАТИЕ ДАННЫХ БЕЗ ПОТЕРЬ

#### BIN@ERN: ДВОИЧНО-ТРОИЧНОЕ СЖИМАЮЩЕЕ КОДИРОВАНИЕ ДАННЫХ

[https://arxiv.org/ftp/arxiv/papers/1201/1201.5603.pdf](https://arxiv.org/ftp/arxiv/papers/1201/1201.5603.pdf)

`Программная реализация выполнена на языке Visual Basic`

В данной работе предлагается авторский алгоритм сжатия данных, используемых в современных цифровых, компьютерных и телекоммуникационных системах, средствах и устройствах. Он позволяет уменьшать и восстанавливать объем исходных данных, предназначенных для хранения или передачи, без потерь содержащейся в них информации. Алгоритм  отличается простотой реализации, высоким быстродействием, плотным сжатием. Он основывается на специальной схеме префиксного кодирования букв алфавита, из которых состоят исходные данные. Эта схема не требует передачи кодовых таблиц букв алфавита от кодера к декодеру, допускает линейные списки представления префиксных кодов букв исходного алфавита, позволяет использовать вычисляемый индекс префиксного кода в линейном списке при декодировании букв, разрешает оценивать степень сжатия до выполнения кодирования, может обходиться без использования операций умножения и деления, вычислений с плавающей точкой при кодировании-декодировании, работоспособна как пристатическом (двухпроходном), так и при адаптивном (однопроходном) кодировании, применима к данным сразличными по мощности алфавитами, допускает повторное сжатие для его дополнительного уплотнения.

[К оглавлению страницы](#Content)

## <a name="Factor"></a> РАЗЛОЖЕНИЕ НАТУРАЛЬНЫХ ЧИСЕЛ НА МНОЖИТЕЛИ

#### ФАКТОРИЗАЦИЯ НАТУРАЛЬНЫХ ЧИСЕЛ МЕТОДОМ УМНОЖЕНИЯ

[https://arxiv.org/ftp/arxiv/papers/1903/1903.12449.pdf](https://arxiv.org/ftp/arxiv/papers/1903/1903.12449.pdf)

`Программная реализация выполнена на языке Java`

В данной работе предлагается авторский алгоритм факторизации больших натуральных чисел методом умножения, который расширяет группу алгоритмов факторизации Ферма и Лемана и характеризуется сложностью выполнения 𝑂(𝑛^1/3). В данной публикации обосновывается конечность его работы в зависимости от величины факторизуемого числа 𝑛. Представлены результаты сравнительных испытаний родственных алгоритмов на большом объеме вычислительных тестов и продемонстрированы выявленные преимущества предлагаемого алгоритма перед другими. Показаны возможности оптимизации алгоритма для снижения трудоемкости факторизации

#### СКРЫТОЕ ЧИСЛОВОЕ РЕШЕТО С РЕГУЛИРУЕМОЙ СПОСОБНОСТЬЮ ПРОСЕИВАНИЯ В МЕТОДЕ ФАКТОРИЗАЦИИ ФЕРМА

[https://www.researchgate.net/publication/337403112_Hidden_numerical_sieve_with_an_adjustable_sieving_ability_within_Fermat's_factorization_method](https://www.researchgate.net/publication/337403112_Hidden_numerical_sieve_with_an_adjustable_sieving_ability_within_Fermat's_factorization_method)

`Программная реализация выполнена на языке Java`

В данной работе предлагается авторский алгоритм применения в методе факторизации Ферма скрытого числового решета с регулируемой способностью просеивания. Решето позволяет многократно – в 2^𝛼 раз – уменьшать трудоемкость факторизации, вычисляемую по описанной в работе метрике, где параметр 𝛼 = {1, 2, 3, ... } является регулятором, определяющим структуру решета и его просеивающую способность. В работе приведено строгое обоснование и формальное описание алгоритма, представлены вычислительные эксперименты, подтверждающие эффективность применения этого решета.

[К оглавлению страницы](#Content)

## <a name="Stock"></a> ТЕХНИЧЕСКИЙ АНАЛИЗ РИСКОВ ПРИ ПОКУПКЕ АКЦИЙ ФОНДОВОГО РЫНКА

#### РАНЖИРОВАНИЕ ИНВЕСТИЦИОННОЙ ПРИВЛЕКАТЕЛЬНОСТИ АКЦИЙ И ДВОИЧНО-ТРОИЧНОЕ СЖИМАЮЩЕЕ КОДИРОВАНИЕ

[https://arxiv.org/ftp/arxiv/papers/2201/2201.11507.pdf](https://arxiv.org/ftp/arxiv/papers/2201/2201.11507.pdf)

`Программная реализация выполнена на языках JavaSript и Visual Basic`

В данной работе предлагается авторский алгоритм ранжирования инвестиционной привлекательности
ценных бумаг фондового рынка, в котором их инвестиционный риск оценивается не по 
традиционному показателю волатильности доходности, а по показателю сжатия временных рядов
данных изменения их биржевой цены. В работе подробно описан алгоритм ранжирования,
представлен пример ранжирования акций всех компаний, входящих в фондовый индекс Dow 
Jones, дополнительно проведено сравнение результатов ранжирования этих акций по показателям
волатильности и сжатия и отмечены сильные стороны второго показателя, формируемого с
использованием метода двоично-троичного сжимающего кодирования исторических данных биржевых котировок ценных бумаг.

[К оглавлению страницы](#Content)

## <a name="Finance"></a> ФИНАСОВЫЙ АНАЛИЗ БИЗНЕС-ПРОЦЕССОВ ПРЕДПРИЯТИЯ

#### ФИНАНСОВЫЙ АНАЛИЗ КРУГООБОРОТА ХОЗЯЙСТВЕННЫХ СРЕДСТВ ПРЕДПРИЯТИЯ

[https://www.researchgate.net/publication/340398013_Financial_analysis_of_circulation_of_economic_means_of_the_enterprise](https://www.researchgate.net/publication/340398013_Financial_analysis_of_circulation_of_economic_means_of_the_enterprise)

`Программная реализация выполнена на языке Visual Basic`

В данной работе предлагается формализованный алгоритм финансового анализа кругооборота хозяйственных средств предприятия, который предусматривает:
- идентификацию регулярных циклов движения финансово-хозяйственных средств (методами теории графов);
- расчет предлагаемых интегральных характеристик таких циклов;
- финансовый анализ показателей эфффективности  циклов кругооборота средств. 

[К оглавлению страницы](#Content)

# МОИ НОВЫЕ ПРОГРАММНЫЕ РАЗРАБОТКИ

## <a name="Transwords"></a> КОМБИНАТОРНАЯ ГОЛОВОЛОМКА "ТРАНСВОРДЫ" / "TRANSWORDS"

#### БРАУЗЕРНАЯ HTML5-ИГРА ДЛЯ ПУБЛИКАЦИИ НА  GAME-ПЛАТФОРМАХ "ИГРЫ ВКОНТАКТЕ" И "ЯНДЕКС ИГРЫ"

[https://github.com/nesioIV/Transwords](https://github.com/nesioIV/Transwords)

`Программная реализация выполнена на языке JavaScript`

Трансворды или Transwords это браузерная HTML5-игра в жанре "головоломка" для одного игрока.
Она реализована на языке Javascript с использованием HTML-элемента canvas без применения сторонних библиотек и фреймворков. Игра поддерживает основные десктопные браузеры, предполагает альбомную ориентацию экрана, автоматически подстраивается под предоставляемые размеры окна браузера.
В указанном репозитории содержатся все файлы, необходимые для исполнения игры. В совокупности они преставляют собой версию #1.00 основного релиза. Основной релиз служит базой для клонирования игры под технические требования публичных игровых платформ (например, Игры Вконтакте или Яндекс Игры).
Игра обеспечивает пользовательский интерфейс на русском и английском языках.
Основной релиз игры можно запустить без регистрации по ссылке [https://nesioiv.github.io/Transwords/](https://nesioiv.github.io/Transwords/).
Пользователи социальной сети ВКонтакте могут найти игру в каталоге игровой платформы этой соцсети [https://vk.com/games](https://vk.com/games). В этой же соцсети организована группа ТРАНСВОРДЫ [https://vk.com/club217481609](https://vk.com/club217481609) для обсуждения приемов и алгоритмов сборки и решения трансвордов.

[К оглавлению страницы](#Content)

## <a name="#ProgramTask"></a> ПРИМЕРЫ РЕШЕНИЯ ТИПОВЫХ ЗАДАЧ ПРОГРАММИРОВАНИЯ

#### ЗАДАЧА ПРОГРАММИРОВАНИЯ НА ТЕМУ "РЕШЕТО ПРОСТЫХ ЧИСЕЛ"

[https://github.com/nesioIV/PrimeNumSieve](https://github.com/nesioIV/PrimeNumSieve)

`Программная реализация выполнена на языке Java`

ФОРМУЛИРОВКА ЗАДАЧИ: Найти все простые числа меньше или равные заданному числу N.

ОПИСАНИЕ РЕШЕНИЯ: приведено в файле [https://github.com/nesioIV/PrimeNumSieve/blob/main/README.md](https://github.com/nesioIV/PrimeNumSieve/blob/main/README.md) репозитория [https://github.com/nesioIV/PrimeNumSieve](https://github.com/nesioIV/PrimeNumSieve).



[К оглавлению страницы](#Content)
