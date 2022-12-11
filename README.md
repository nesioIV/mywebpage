
Вы открыли мою персональную страницу.

СОДЕРЖАНИЕ 

1.  МОИ АЛГОРИТМЫ И ПУБЛИКАЦИИ ПО ТЕМАМ
  * [Сжатие данных без потерь](#Compress)
  * [Разложение натуральных чисел на простые множители](#Factor)
  * [Технический анализ рисков при покупке акций фондового рынка](#Stock)
  * [Финансовый анализ бизнес-процессов предприятия](#Finance)
 2. МОИ ПРИЛОЖЕНИЯ И ПРОГРАММЫ
  * [Комбинаторная головоломка ТРАНСВОРДЫ (TRANSWORDS)](#Transwords)
  * [Примеры решения тестовых задач программирования](#TestTask)

### МОИ АЛГОРИТМЫ И ПУБЛИКАЦИИ ПО ТЕМАМ

#### <a name="Compress"></a> СЖАТИЕ ДАННЫХ БЕЗ ПОТЕРЬ
BIN@ERN: ДВОИЧНО-ТРОИЧНОЕ СЖИМАЮЩЕЕ КОДИРОВАНИЕ ДАННЫХ

<code> https://arxiv.org/ftp/arxiv/papers/1201/1201.5603.pdf </code>

<span style="color:red">Программная реализация выполнена на языке Visual Basic</span>

В данной работе предлагается авторский алгоритм сжатия данных, используемых в современных цифровых, компьютерных и телекоммуникационных системах, средствах и устройствах. Он позволяет уменьшать и восстанавливать объем исходных данных, предназначенных для хранения или передачи, без потерь содержащейся в них информации. Алгоритм  отличается простотой реализации, высоким быстродействием, плотным сжатием. Он основывается на специальной схеме префиксного кодирования букв алфавита, из которых состоят исходные данные. Эта схема не требует передачи кодовых таблиц букв алфавита от кодера к декодеру, допускает линейные списки представления префиксных кодов букв исходного алфавита, позволяет использовать вычисляемый индекс префиксного кода в линейном списке при декодировании букв, разрешает оценивать степень сжатия до выполнения кодирования, может обходиться без использования операций умножения и деления, вычислений с плавающей точкой при кодировании-декодировании, работоспособна как пристатическом (двухпроходном), так и при адаптивном (однопроходном) кодировании, применима к данным сразличными по мощности алфавитами, допускает повторное сжатие для его дополнительного уплотнения.


####РАЗЛОЖЕНИЕ НАТУРАЛЬНЫХ ЧИСЕЛ НА МНОЖИТЕЛИ

ФАКТОРИЗАЦИЯ НАТУРАЛЬНЫХ ЧИСЕЛ МЕТОДОМ УМНОЖЕНИЯ

https://arxiv.org/ftp/arxiv/papers/1903/1903.12449.pdf

<span style="color:red">Программная реализация: на языке Java</span>

В данной работе предлагается авторский алгоритм факторизации больших натуральных чисел методом умножения, который расширяет группу алгоритмов факторизации Ферма и Лемана и характеризуется сложностью выполнения 𝑂(𝑛^1/3). В данной публикации обосновывается конечность его работы в зависимости от величины факторизуемого числа 𝑛. Представлены результаты сравнительных испытаний родственных алгоритмов на большом объеме вычислительных тестов и продемонстрированы выявленные преимущества предлагаемого алгоритма перед другими. Показаны возможности оптимизации алгоритма для снижения трудоемкости факторизации

---

СКРЫТОЕ ЧИСЛОВОЕ РЕШЕТО С РЕГУЛИРУЕМОЙ СПОСОБНОСТЬЮ ПРОСЕИВАНИЯ В МЕТОДЕ ФАКТОРИЗАЦИИ ФЕРМА

https://www.researchgate.net/publication/337403112_Hidden_numerical_sieve_with_an_adjustable_sieving_ability_within_Fermat's_factorization_method

<span style="color:red">Программная реализация: на языке Java</span>

В данной работе предлагается авторский алгоритм применения в методе факторизации Ферма скрытого числового решета с регулируемой способностью просеивания. Решето позволяет многократно – в 2^𝛼 раз – уменьшать трудоемкость факторизации, вычисляемую по описанной в работе метрике, где параметр 𝛼 = {1, 2, 3, ... } является регулятором,определяющим структуру решета и его просеивающую способность. В работе приведено строгое обоснование и формальное описание алгоритма, представлены вычислительные эксперименты, подтверждающие эффективность применения этого решета.


####ТЕХНИЧЕСКИЙ АНАЛИЗ РИСКОВ ПРИ ПОКУПКЕ АКЦИЙ ФОНДОВОГО РЫНКА

РАНЖИРОВАНИЕ ИНВЕСТИЦИОННОЙ ПРИВЛЕКАТЕЛЬНОСТИ АКЦИЙ И ДВОИЧНО-ТРОИЧНОЕ СЖИМАЮЩЕЕ КОДИРОВАНИЕ

https://arxiv.org/ftp/arxiv/papers/2201/2201.11507.pdf

<span style="color:red">Программная реализация: на языке Java</span>

В данной работе предлагается авторский алгоритм ранжирования инвестиционной привлекательности
ценных бумаг фондового рынка, в котором их инвестиционный риск оценивается не по 
традиционному показателю волатильности доходности, а по показателю сжатия временных рядов
данных изменения их биржевой цены. В работе подробно описан алгоритм ранжирования,
представлен пример ранжирования акций всех компаний, входящих в фондовый индекс Dow 
Jones, дополнительно проведено сравнение результатов ранжирования этих акций по показателям
волатильности и сжатия и отмечены сильные стороны второго показателя, формируемого с
использованием метода двоично-троичного сжимающего кодирования исторических данных биржевых котировок ценных бумаг.













 

