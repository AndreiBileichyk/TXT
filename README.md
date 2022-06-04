# TXT
1. Создать внешний репозиторий c названием TXT.
Создаем репозиторий TXT на гитхабе.
 2. Клонировать репозиторий TXT на локальный компьютер.
git clone git@github.com:AndreiBileichyk/TXT.git
 3. Внутри локального TXT создать файл “new.txt”.
cd TXT
touch new.txt
 4. Добавить файл под гит
git add new.txt
 5. Закоммитить файл.
git commit -m "creat new.txt"
 6. Отправить файл на внешний GitHub репозиторий.
git push
 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.
Vim new.txt
ФИО: Билейчик Андрей Валентинович
Возраст: 36
Количество домашних животных: 1
Будущая желаемая зарплата : 500
:wq
 8. Отправить изменения на внешний репозиторий.
git add 
git commit -m "filling in the file"
git push
 9. Создать файл preferences.txt
touch preferences.txt
 10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.
cat>> new.txt
Любимый фильм: Легенда №17
Любимый сериал: Молодежка
Любимая еда: пицца
Любимое время года: зима
Страна которую хотел бы посетить: Сингапур
ctrl +C
 11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
cat>> sklls.txt
 Git, 
 github,
 git bash,
 Jmeter,
 mobile and web testing,
 API,
 sql,
 data transfer protocols.
ctrl+C
 12. Сделать коммит в одну строку.
git add . ; git commit -m "creat two file"
 13. Отправить сразу 2 файла на внешний репозиторий.
git push
 14. На веб интерфейсе создать файл bug_report.txt.
на гитхабе создать файл
 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Зайти в редактирование
В Commit changes написать : Изминение 1 и нажать Commit changes
 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
Зайти в редактирование файла на вебхабе
Summary: Что? Где? При каких условиях?
Description: STR, result, expected result
Priority": Low
Environment: windows 10, google chrom ver..
Attachment: scrin
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
В Commit changes написать : Изминение 2 и нажать Commit changes
 18. Синхронизировать внешний и локальный репозиторий TXT
git fetch
git pull
