# XML
**1. Создать внешний репозиторий c названием XML**

**2. Клонировать репозиторий XML на локальный компьютер**
> git clone https://github.com/Evgeniatest/JSON.git

**3. Внутри локального XML создать файл “new.json”**
>touch new.xml

**4. Добавить файл под гит**
>git add new.xml

**5. Закоммитить файл**
>git commit -m "add new.xml"

**6. Отправить файл на внешний GitHub репозиторий**
>git push

**7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML**
>vim new.xml    ---> input data ---> esc ---> enter ":wq"

**8. Отправить изменения на внешний репозиторий**
>git commit -am "add name, age, salary" && git push

**9. Создать файл preferences.xml**
>touch preferences.xml

**10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML**
>vim preferences.xml ---> insert data ---> esc ---> enter ":wq"

**11. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML**
>touch skills.xml

>vim skills.xml ---> insert data ---> esc ---> enter ":wq"

**12. Отправить сразу 2 файла на внешний репозиторий**
>git add . && git commit -m "add new information" && git push

**13. На веб интерфейсе создать файл bug_report.xml**
>Add file --> Create new file --> Name: bug_report.xml

**14.Сделать Commit changes (сохранить) изменения на веб интерфейсе**
>Commit New File

**15. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML**

**16. Сделать Commit changes (сохранить) изменения на веб интерфейсе**
>Commit changes

**17. Синхронизировать внешний и локальный репозиторий XML**
>git pull
