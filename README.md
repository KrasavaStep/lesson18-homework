# Домашка до четверга, 24 марта

## Общий прогресс ДЗ
https://github.com/vshat-tms/homework-all

## Рекомендации по выполнению ДЗ
Если вам что-то непонятно в описании задачи, то задавайте вопросы в чате. Если вы видите в коде непонятные для вас конструкции, классы или методы - то гуглите их. Если вам нужен какой-то метод, но вы не знаете как он называется - гуглите. Если вы не знаете, как что-то сделать - гуглите. Если гугл вам не помог, то задавайте вопрос в чат. 

Чем более вы коммуникабельны, самостоятельны, проактивны, тем ценнее как специалист вы становитесь. Отвечая на вопросы в чате, вы структурируете у себя в голове и обучаетесь доносить информацию, с которой вы уже разобрались. 

## Что делать?
1. Форкнуть себе этот репозиторий
2. Выполнить задачи по проекту (ниже)
3. Сделать пулл реквест в этот репозиторий
4. Если в списке пулл реквестов вы увидите другие пулл реквесты (кроме вашего) - то зайдите в них и напишите "approve" в комментариях, если вы согласны с решением вашего коллеги. Оставьте комментарии к коду, если в чём-то не согласны.

## Проект "Калькулятор"

### Описание
<image src="images/img.png" width="200">


Мы будем упрощенную версию калькулятора выше.

Рекомендую скачать и потыкать в [классический калькулятор](https://play.google.com/store/apps/details?id=com.developstudios.casio)


### Что уже сделано?
В этом репозитории скелет проекта "Калькулятор". Добавлен интерфейс (UI), реализована базовая обработка нажатий и сложение. 

### Правила
- Калькулятор на "дисплее" отображает или число или знак операции (сложение, вычитание и т.п.).
- Число не может начинаться с нуля
- Может быть только одна точка
- Число не может начинаться с точки (без знаков в начале)
- ...
- *И прочие правила, которые есть у настоящих калькуляторов*

### Задачи
1. Запустить приложение
2. Попробовать сложение 
3. Выяснить, как смотреть и фильтровать логи в андроид студии
3. Посмотреть логи, которые выводит калькулятор
4. Разобраться, как реализован калькулятор (`MainActivity.kt`, `main_activity.xml`)
5. Добавляйте логи во всех методах (и моих, и в тех, которые напишите). С их помощью вам будет проще понять, в каком месте что-то идёт не так. (Обычно, с первой попытки не пишется идеально рабочий код). При этом логов не должно быть слишком много, чтобы не захламлять `LogCat` ненужной для себя информацией. 
6. Реализовать вычитание, сложение и умножение
7. Реализовать возможность вводить дробные числа (точка).
8. Добавить кнопку "sign" (справа от "del"). Она будет менять знак введённого числа на противоположный (например, `5` -> `-5` -> `5`).


### P.S.
В моём коде (как и в реальных проектах) могут быть баги и неточности. 