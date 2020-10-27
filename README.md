# Courses monitoring
---
## Опис проекту:
Даний проект - це веб-додаток, який є платформою для онлайн-навчання.
Він надає можливіть студентам вивчати різноманітні онлайн-курси.
## Актуальність проекту:
## Функціональність проекту:
В даному проекті існує перелік курсів, розбитих за темами. За кожним курсом закріплений один викладач.
Студент записується на один або декілька курсів, дані про реєстрацію зберігаються. По закінченню курсу викладач виставляє студенту оцінку, яка зберігається в журналі.
Кожен користувач має особистий кабінет, в якому відображена коротка інформація про користувача.

Існує чотири типи користувачів: незареєстрований користувач, студент, викладач, адміністратор.

**Незареєстрований користувач** володіє правами:
+ сортувати курси за назвою (a-z, z-a), тривалістю, кількістю студентів(що записалися на курс);
+ робити вибірку курсів, що належать до певної теми;
+ робити вибірку курсів певного викладача.

**Студент** володіє правами:
+ всіма вищеперерахованими правами;
+ переліку курсів, на які студент зареєструвався, але які ще не почалися;
+ переліку курсів, на які студент зареєструвався і які знаходяться в прогресі;
+ переліку пройдених курсів з інформацією про успішність.

**Викладач** володіє правами:
+ всіма вищеперерахованими правами;
+ перегляду і редагування електронного журналу для закріплених за ним курсів;

**Адміністратор** володіє правами:
+ всіма вищеперерахованими правами;
+ реєстрації викладача і закріплення за ним курсу;
+ додавання, видалення, редагування курсу;
+ блокування, розблокування студента;
+ всіма вищеперерахованими правами.
## Стек технологій:
+ Java 11
+ Spring Framework 5
+ PostgreSQL 13
+ Hibernate
+ Angular 9
