# :mage: План автоматизации тестирования возможности записи на обучение профессии "Тестировщик ПО" :mage_woman:

### *Уровни тестирования:*

- Компонентное (модульное) тестирование - проверить функциональность и искать дефекты в частях анкеты для записи.
- Интеграционное - взаимодействие между компонентами системы.

### *Виды тестирования:*

- Дымовое тестирование - рассматривает как короткий цикл тестов, выполняемый для подтвержения того, что после сборки кода (нового или исправленного) устанавливаемое приложение стартует и выполняет основные функции.
- Функциональное тестирование - расматривает заранее указанное поведение и основывается на анализе спецификаций функциональности компонента или системы в целом.

## :whale: Перечень автоматизируемых сценариев: :whale2:

### *Возможные сценарии по переходу к анкете:*

> Сценарий №1

1. Зайти на главную страницу [Нетологии](https://netology.ru/)
2. Кликнуть на "Каталог курсов"
3. Направить мышку на "Программирование"
4. Кликнуть на "Тестирвщик ПО"
5. Кликнуть по кнопке "Записаться" - произойдет переход к экранной форме записи

>> Сценарий №2

1. Зайти на главную страницу [Нетологии](https://netology.ru/)
2. Кликнуть на "Каталог курсов"
3. Кликнуть на "Программирование"
4. Из всех перечисленных курсов найти курс "Тестировщик ПО" и кликнуть на него
5. Кликнуть по кнопке "Записаться" - произойдет переход к экранной форме записи

> > > Сценарий №3

1. Зайти на главную страницу [Нетологии](https://netology.ru/)
2. Кликнуть на "_НЕО_ для начинающих"
3. Из всех перечисленных курсов найти курс "Тестировщик ПО" и кликнуть на него
4. Кликнуть по кнопке "Записаться" - произойдет переход к экранной форме записи

> > > > Сценарий №4

1. Зайти на главную страницу [Нетологии](https://netology.ru/)
2. Найти оглавление "Изучайте актуальные темы"
3. Кликнуть на "Программирование"
4. Из всех перечисленных курсов найти курс "Тестировщик ПО" и кликнуть на него
5. Кликнуть по кнопке "Записаться" - произойдет переход к экранной форме записи

### *Заполнение анкеты `неавторизованным` пользователем*

![Курс Тестировщик ПО – обучение онлайн с сертификат](https://user-images.githubusercontent.com/79462466/125447714-84705bd0-8408-4d55-aa71-b4450a7010de.png)

#### Сценарий Happy path :heavy_check_mark: :

1. Заполнить поле `Имя` буквами из кириллицы или латиницы 
> - не менее двух букв
2. Заполнить поле `Номер телефона` так же, как и по шаблону
> - одиннадцать цифр
> - по шаблону +7 (999) 999-99-99
> - разрешено от девяти до четырнадцати цифр 
3. Заполнить поле `Почта` корректным e-mail 
> - не должен содержать русских букв
> - знак «собака» (@)
> - точку (.)
> - верное наименование почтового домена (mail.ru, yandex.ru, gmail.com и так далее)
4. Кликнуть по кнопке "Записаться" - произойдет переход к экранной форме записи

*Ожидаемый результат*: Выскакивает сообщение об успешной записи 

#### Сценарий UnHappy path :x: :

1. Заполнить поле `Имя` одной буквой
> - цифрами
> - спецсимволами (например, $%*)
2. Заполнить поле `Номер телефона`не по шаблону
> - буквами
> - числами, которых предел не достигает минимума
> - числами, которых предел превышает максимума
3. Заполнить поле `Почта` некорректным e-mail
> - русскими буквами 
> - без знака «собака» (@) 
> - без точки (.)
> - неверное наименование почтового домена
4. Кликнуть по кнопке "Записаться" 

*Ожидаемый результат*: Запись не пройдёт

#### Сценарий Empty path :ghost: :

### *Заполнение анкеты `авторизованным` пользователем*

![Курс Тестировщик ПО](https://user-images.githubusercontent.com/79462466/125448173-1f73485c-7e61-4659-a1e1-f2211217b9c7.png)


## :whale: Перечень используемых инструментов с обоснованием выбора: :whale2:

## :whale: Перечень необходимых разрешений/данных/доступов :whale2:

## :whale: Перечень и описание возможных рисков при автоматизации :whale2:

## :whale: Перечень необходимых специалистов для автоматизации :whale2:

## :whale: Интервальная оценка с учётом рисков (в часах) :whale2:
