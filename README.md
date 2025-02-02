# MAI_OS

Репозиторий лабораторных работ группы М8О-213Б-23 по дисциплине «Операционные системы»

## Порядок сдачи

Каждая лабораторная работа сдается в 2 этапа: код-ревью и очная 
защита. Чтобы допуститься к очной защите, необходимо пройти код-ревью. Без 
прохождения обоих этапов лабораторная работа не может быть сданной (даже на 
оценку 3).

### Код-ревью

Необходимо прикрепить написанный код и отчет в pull request к этому репозиторию. 
Каждая лабораторная работа сдается в отдельном pull request'е. После создания 
pull request'а я либо сообщу в комментариях под ним, что этап код-ревью успешно 
пройден и вы допускаетесь к очной защите, либо оставлю замечания, которые 
необходимо устранить и сообщить об устранении в комментариях, чтобы я проверил 
снова.

Правила оформления кода:

* Код должен быть написан на C или C++
* Операционная система: Linux, MacOS или Windows
* Обязательно используются системные вызовы
* Все, что относится к стандартной библиотеке C++, кроме `std::string` и 
`std::vector`, запрещено
* `stdio.h`, `threads.h`, `stdatomic.h` из стандартной библиотеки C запрещены
* Весь исходный код находится в папке `src`
* Бинарных файлов вроде `a.out`, `main.o` быть не должно
* На каждый системный вызов должна быть организована проверка на ошибку
* Код должен быть легко читаем (правильно расставлены отступы, переменные и 
функции имеют осмысленные названия)

Правила оформления отчета:

* Отчет должен быть в формате PDF, редактировать можно в любом формате 
(Word, Latex и тд)
* Отчет должен находиться в папке `doc`
* Отчет должен содержать вывод утилиты `strace` для Linux, `dtrace` для MacOS 
или `nttrace` для Windows. Должны быть выделены системные вызовы, которые были 
вызваны из пользовательского кода
* Структура отчета должна соответствовать [примеру](https://docs.google.com/document/d/13ydQ0_xVeFhwN5AY242K4Sf8GtPr2wt3/edit)

### Очная защита

После прохождения этапа код-ревью необходимо записаться в очередь на очную 
защиту работы и прийти к соответствующему времени.

Этапы очной защиты:

* Демонстрация работы программы
* Вопросы по работе программы
* Вопросы по теории
* Вопросы по системным вызовам

### Дедлайны

* на оценку 5 – не позднее 2 недель со дня выдачи
* на оценку 4 – не позднее 3 недель со дня выдачи
* на оценку 3 – позднее 3 недель со дня выдачи

В эти сроки должны быть пройдены и код-ревью, и очная сдача. Если код-ревью 
пройдено не позднее 2 недель со дня выдачи, а очная сдача пройдена позднее 2 
недель и не позднее 3 недель со дня выдачи, будет выставлена оценка 4.  
