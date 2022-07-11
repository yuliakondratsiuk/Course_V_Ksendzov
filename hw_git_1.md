# GIT Homework 1

Для выполнения задания у вас должен быть установлен для Windows - GitBash.
Создан аккаунт в GitHub

Все шаги сценария выполняйте в терминале GitBush, Terminal, в папке под гитом.

Как отправить ДЗ на проверку.

1.  Создайте текстоовый файл как в первом ДЗ по Terminal.
2.  Сценарий перенесите в этот файл.
3.  На против каждого действия - напишите команду в GitBash

Файл со сценарием и ссылку на свой гит хаб отправляйте менторам на проверку.

## [JSON](https://github.com/yuliakondratsiuk/JSON) 

4. Создать внешний репозиторий c названием JSON.
   > в github.com нажать new - ввести имя репозитория JSON - выбрать public - нажать Create repository
5. Клонировать репозиторий JSON на локальный компьютер.
   > git clone https://github.com/yuliakondratsiuk/JSON.git
6. Внутри локального JSON создать файл “new.json”.
   > cd JSON/ && touch new.json
7. Добавить файл под гит.
   > git add new.json
8. Закоммитить файл.
   > git commit -m "create new.json"
9. Отправить файл на внешний GitHub репозиторий.
   > git push
10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата).Всё написать в формате JSON.
    > vim new.json - i ввести информацию, esc :wq
11. Отправить изменения на внешний репозиторий.
    > git commit -am "add information in new.json" && git push
12. Создать файл preferences.json
    > touch preferences.json
13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, страна которую хотели бы посетить) в формате JSON.
    > vim preferences.json - i ввести информацию - esc :wq
14. Создать файл skills.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
    > cat > skills.json - ввести информацию - enter - ctrl + D
15. Отправить сразу 2 файла на внешний репозиторий.
    > git add . && git commit -m "add preferences.json and skills.json" && git push
16. На веб интерфейсе создать файл bug_report.json.
    > в веб интерфейсе нажать add file - create new file - ввести имя файла bug_report.json
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
    > написать комментарий - нажать commit new file
18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
    > зайти в файл bug_report.json - нажать edit this file - внести баг репорт в формате JSON
19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
    > вписать комментарий - нажать commit new file
20. Синхронизировать внешний и локальный репозиторий JSON.
    > git pull

## [XML](https://github.com/yuliakondratsiuk/XML) 

21. Создать внешний репозиторий c названием XML.
    > в github.com нажать new - ввести имя репозитория XML - выбрать public - нажать Create repository
22. Клонировать репозиторий XML на локальный компьютер.
    > git clone https://github.com/yuliakondratsiuk/XML.git
23. Внутри локального XML создать файл “new.xml”.
    > cd XML/ && touch new.xml
24. Добавить файл под гит.
    > git add new.xml
25. Закоммитить файл.
    > git commit -m "create new.xml"
26. Отправить файл на внешний GitHub репозиторий.
    > git push
27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
    > vim new.xml - i вносим информацию в формате XML - esc :wq
28. Отправить изменения на внешний репозиторий.
    > git commit -am "update new.xml" && git push
29. Создать файл preferences.xml
    > touch preferences.xml
30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
    > vim preferences.xml - i ввести информацию - esc :wq
31. Создать файл skills.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
    > cat > skills.xml - i ввести информацию - enter - ctrl + D
32. Сделать коммит в одну строку.
    > git add preferences.xml && git add skills.xml && git commit -m "add preferences.xml and skills.xml"
33. Отправить сразу 2 файла на внешний репозиторий.
    > git push
34. На веб интерфейсе создать файл bug_report.xml
    > в веб интерфейсе нажать add file - create new file - ввести имя файла bug_report.xml
35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
    > вписать комментарий - нажать commit new file
36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
    > зайти в файл bug_report.xml - edit this file - ввести баг репорт в формате xml
37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
    > вписать комментарий - нажать commit new file
38. Синхронизировать внешний и локальный репозиторий XML
    > git pull

## [TXT](https://github.com/yuliakondratsiuk/TXT)

1.  Создать внешний репозиторий c названием TXT.
    > в github.com нажать new - ввести имя репозитория TXT - выбрать public - нажать Create repository
2.  Клонировать репозиторий TXT на локальный компьютер.
    > git clone https://github.com/yuliakondratsiuk/TXT.git
3.  Внутри локального TXT создать файл “new.txt”.
    > cd TXT/ && touch new.txt
4.  Добавить файл под гит.
    > git add new.txt
5.  Закоммитить файл.
    > git commit -m "create new.txt"
6.  Отправить файл на внешний GitHub репозиторий.
    > git push
7.  Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.
    > vim new.txt - i ввести информацию, esc :wq
8.  Отправить изменения на внешний репозиторий.
    > git commit -am "add information in new.txt" && git push
9.  Создать файл preferences.txt
    > touch preferences.txt
10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.
    > vim preferences.txt - i ввести информацию - esc :wq
11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
    > cat > sklls.txt - ввести информацию - enter - ctrl + D
12. Сделать коммит в одну строку.
    > git add . && git commit -m "add preferences.txt and sklls.txt"
13. Отправить сразу 2 файла на внешний репозиторий.
    > git push
14. На веб интерфейсе создать файл bug_report.txt.
    > в веб интерфейсе нажать add file - create new file - ввести имя файла bug_report.txt
15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
    > вписать комментарий - нажать commit new file
16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
    > зайти в файл bug_report.txt - edit this file - ввести баг репорт в формате TXT
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
    > вписать комментарий - нажать commit new file
18. Синхронизировать внешний и локальный репозиторий TXT
    > git pull

[Back to page Course_V_Ksendzov](https://yuliakondratsiuk.github.io/Course_V_Ksendzov/) 
