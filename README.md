# Testing_theory

Тестирование- это процесс оценики качества продукта который позволяет снизить риск отказа програмного обеспечения в момент его использвоания. В момент проведения тестирования сравниваются ожидаймый результат с фактическим на наборе  определенных тестовых сценариев выбранных определнным способом.
> Отказ - это нарушение работы модуля или системы которое приведит либо к полному прекращению работаспособности системы либо  ее части.

## цели тестирвоания
1. Оценка рабочих продуктов, таких как требования, пользовательские истории, макеты.

2. Предоствления актуальной информации о состаянии продукта на данный момет.

3. Проверка соответсвия ПО всем заявленным требованиям.

> Цели тестирвоания могут меняться в зависмости от контекста тестируемого компонента или системы, уровня тестировния и модели SDLC. При компонентном тестировании одна из целей может заключаться в том, чтобы выявить как можно больше сбоев и устранить основные дифекты на ранних стадиях. Либо целью может быть увелечения покрытия кода тестами.

# Принцепы тестирования

- Тестировние демонстрирет наличие дефектов, а не их отсутвие.

Тестирование только снижает вероятность наличия дефектов, которое находится в продукте, но не гарантирует их отсутвия

- Исчерпывающее тестирование невозможно

Тестированние с использованием всех входных данных и сценариев, результатов и предъусловий физически не возможно.

- Ранее тестирование

Тестирование необходимо начинать на ранних стадиях разработки продукта, чтобы найти дефекты как можно раньше и исправить пока это стоит не дорого.

-  Скопление дефектов

Большая часть дефектов находиться в ограниченом количестве модулей


- Эффект пестицида

Если повторять те же тестовые сценарии снова и снова, в какой-то момент они перестанут находить новые дефекты.

> Суть в том, что если вы долго проводите одни и теже сценарии, скорее всего вы не найдете новых дефектов. В избежании данной ситуации, переодически необходимо тестовую базу ревьюить и проводить иследовательское тестирование

- Тестирование зависит от контекста

Продукт в котором важна безопасность, тетисруется иначе, чем новосной портал

- Заблюждение об отсутвии ошибок

Отсутвие ошибок найденых при тестировании продукта, не говорит нам о готовности. Система должна быть удобна пользователю и удовлетворять его ожидания и потребности


> Существует заблуждение, что тестирование состоит только из прогона тестовых сценариев и проверки результатов. Процес тестирование состоит из множества активностий выполнение тестовых сценариев(включая сверку результатов) является одной из таких активностей. Процесс тестирования содердит такие активности как, планирование, анализ, проектирование и реализация тетов, создание отчетов о ходе и результате тестирования, а также оценка качества объекта тестирования.

> Рецензирование - это  статический вид тестирования ПО (включая код), который может проводиться перед динамическим тестированием. Исправление дефектов, обнаруженных во время рецензирования на ранних этапах жизненного цикла ПО (например, дефектов, найденных в требованиях), часто обходится значительно дешевле по сравнению с дефектами, найденными во время выполнения тестов и исполнения кода.
>
> Взято из ISTQB CTFL Syllabus 2011 RU - Стр 5

# Тестировщик, QA, QC

Тестировщик - это спкециалист который проверяет качество продукта и уровень его соответвия заранее определенным требованиям

Глобально QС (Quality Control), или тестировщики, — это часть QA. Тестировщик изучает продукт, проводит исследования, отрабатывает возможные сценарии и ловит баги. Он предоставляет команде общую картину о продукте. QC не повышает качество, а даёт представление о том, что происходит в разработке. QA же помогает команде наладить процессы, связанные с качеством. Он смотрит на всю картину целиком и делает так, чтобы ошибок было меньше.

# Что такое баг
Баг- это отклонения фактического результата от ожидаемого.
Ожидаемый результат - описание того, как именно должна работать система в соответсвии с документацией
Фактический результат - результат который получаем в процессе тестирования продукта. То как система работает на самом деле.
> Если баг - это недосмотр, то фича- специально предусмотренная возможность

## Жизненный цикл бага
![изображение](https://sun9-27.userapi.com/impf/c855628/v855628440/13fb92/9a2SNh-BGGc.jpg?size=807x427&quality=96&sign=b8b49ea3e73b581a588cf999eb4625b7&type=album)

# UX/UI дизайн
UX(user expireence - опыт пользователя). То какое впечатление получает пользователь от работы с интерфейсом. Насколько просто/сложно достичь желаемой цели 

UI(user interface - пользовательский интерфейс). То как выглядит интерфейс, отвечает на вопрос как будет выглядить продукт, удобно ли  будет  пользователю работать с продуктом, какого продукт будет цвета, читабельный ли текст и тд.

UI/UX дизайн - проектирование любых пользовательских интерфейсов, в которыми будет удоюно пользоватеься, а также внешний вид продукта.
