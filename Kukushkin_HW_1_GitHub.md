### GIT Homework 1

*Для выполнения задания у вас должен быть установлен GitBash для Windows и создан аккаунт в GitHub.*

*Все шаги сценария выполняйте в терминале GitBash, Terminal, в папке под гитом.*

*Как отправить ДЗ на проверку.*

* **1.** *Создайте текстовый файл, как в первом ДЗ по Terminal.*

* **2.** *Сценарий перенесите в этот файл.*
 
* **3.** *Напротив каждого действия напишите команду в GitBash.*

*Файл со сценарием и ссылку на свой гит хаб отправляйте менторам на проверку.*
___
## JSON - https://github.com/kukushkin42/JSON
___
**4.** Создать внешний репозиторий c названием *JSON*.
>https://github.com/new => Repository name => JSON => Add a README file => Create

 **5.** Клонировать репозиторий *JSON* на локальный компьютер.
```
$ git clone "link to the repository from GitHub"
```
 **6.** Внутри локального *JSON* создать файл “`new.json`”.
```
$ cd JSON/
$ touch new.json
```
 **7.** Добавить файл под гит.
 ```
$ git status
$ git add new.json
$ git status
```
 **8.** Закоммитить файл.
 ```
$ git commit -m "add new.json"
```
 **9.** Отправить файл на внешний GitHub репозиторий.
 ```
$ git push
```
 **10.** Отредактировать содержание файла “`new.json`” - написать информацию о себе (*ФИО, возраст, количество домашних животных, будущая желаемая зарплата*). Всё написать в формате *JSON*.
```
$ vim new.json
```   
>===> INSERT ===>
```
{
    "name": "Andrey",
    "age": 28,
    "pets": {"cat": "Marie",
             "age": 7},
    "salary": 1500
}
```
>===> Esc ===> :wq

 **11.** Отправить изменения на внешний репозиторий.
 ```
$ git commit -am "update json file"
$ git push
```
 **12.** Создать файл `preferences.json`.
 ```
$ cat > preferences.json
```
>Ctrl+C

 **13.** В файл `preferences.json` добавить информацию о своих предпочтениях (*Любимый фильм, любимый сериал, любимая еда, любимое время года, страна, которую хотели бы посетить*) в формате *JSON*.
 ```
$ vim preferences.json
```
>===> INSERT ===>
```
{
    "favorite movie": "Fight Club",
    "favorite series": "Breaking Bad",
    "favorite food": "Pizza",
    "favorite season": "Summer",
    "country to visit": "USA"
}
```
>===> Esc ===> :wq

 **14.** Создать файл `skills.json`, добавить информацию о скиллах, которые будут изучены на курсе, в формате *JSON*.
 ```
$ touch skills.json
$ vim skills.json
```
>===> INSERT ===>
```
{
    "skill": "Terminal",
    "skill": "Postman",
    "skill": "CheckList",
    "skill": "BugReport",
    "skill": "Jmeter",
    "skill": "SQL",
    "skill": "Charles",
    "skill": "DevTools",
    "skill": "Mobile testing"
}
```
>===> Esc ===> :x

 **15.** Отправить сразу 2 файла на внешний репозиторий.
 ```
$ git add .
$ git commit -m "add two files"
$ git push
```
 **16.** На веб интерфейсе создать файл `bug_report.json`.
>Add file ===> Create new file ===> bug_report.json file name

 **17.** Сделать *Commit changes* (сохранить) изменения на веб интерфейсе.
>Created bug_report file ===> Commit changes

 **18.** На веб интерфейсе модифицировать файл `bug_report.json`, добавить баг репорт в формате *JSON*.
>Open file ===> Edit file ===>
```
{
   "ID":"",
   "Summary":"",
   "Incident Description":"",
   "Pre-Conditions":"",
   "Steps to reproduce":"",
   "Actual result":"",
   "Expected result":"",
   "Environment":"",
   "Build":"",
   "Attempt to repeat":"",
   "Impact":"",
   "Severity":"",
   "Priority":"",
   "Attachment":""
}
```
 **19.** Сделать *Commit changes* (сохранить) изменения на веб интерфейсе.
>Added bug_report structure ===> Commit changes

 **20.** Синхронизировать внешний и локальный репозиторий *JSON*.
 ```
$ git fetch
$ git pull
```
___
## XML - https://github.com/kukushkin42/XML
___
 **21.** Создать внешний репозиторий c названием *XML*.
>https://github.com/new => Repository name => XML => Add a README file => Create

 **22.** Клонировать репозиторий *XML* на локальный компьютер.
 ```
$ cd ..
$ git clone "link to the repository from GitHub"
$ cd XML/
```
 **23.** Внутри локального *XML* создать файл “`new.xml`”.
 ```
$ touch new.xml
```
 **24.** Добавить файл под гит.
 ```
$ git add new.xml
```
 **25.** Закоммитить файл.
 ```
$ git commit -m "add new xml file"
```
 **26.** Отправить файл на внешний GitHub репозиторий.
 ```
$ git push
```
 **27.** Отредактировать содержание файла “`new.xml`” - написать информацию о себе (*ФИО, возраст, количество домашних животных, будущая желаемая зарплата*). Всё написать в формате *XML*.
 ```
$ vim new.xml
```
>===> INSERT ===>
```
<resume>
    <name>Andrey</name>
    <age>28</age>
    <pets>1</pets>
    <salary>1500</salary>
</resume>
```
>===> Esc ===> :x

 **28.** Отправить изменения на внешний репозиторий.
 ```
$ git add new.xml
$ git commit -am "update new xml file"
$ git push
```
 **29.** Создать файл `preferences.xml`.
 ```
$ touch preferences.xml
```
 **30.** В файл `preferences.xml` добавить информацию о своих предпочтениях (*Любимый фильм, любимый сериал, любимая еда, любимое время года, страна, которую хотели бы посетить*) в формате *XML*.
 ```
$ vim preferences.xml
```
>===> INSERT ===>
```
<preferences>
    <favorite_movie>Fight_Club</favorite_movie>
    <favorite_series>Breaking_Bad</favorite_series>
    <favorite_food>Pizza</favorite_food>
    <favorite_season>Summer</favorite_season>
    <country_to_visit>USA</country_to_visit>
</preferences>
```
>===> Esc ===> :wq

 **31.** Создать файл `skills.xml`, добавить информацию о скиллах, которые будут изучены на курсе, в формате *XML*.
 ```
$ cat > skills.xml
```
>Ctrl+C
```
$ vim skills.xml
```
>   ===> INSERT ===>
```
<skills>
    <skill>Terminal</skill>
    <skill>Postman</skill>
    <skill>CheckList</skill>
    <skill>BugReport</skill>
    <skill>Jmeter</skill>
    <skill>SQL</skill>
    <skill>Charles</skill>
    <skill>DevTools</skill>
    <skill>Mobile_testing</skill>
</skills>
```
>===> Esc ===> :x

 **32.** Сделать коммит в одну строку.
 ```
$ git add .; git commit -m "add preferences & skills files"
```
 **33.** Отправить сразу 2 файла на внешний репозиторий.
 ```
$ git push
```
 **34.** На веб интерфейсе создать файл `bug_report.xml`.
 >Add file ===> Create new file ===> bug_report.xml file name

 **35.** Сделать *Commit changes* (сохранить) изменения на веб интерфейсе.
>Created bug_report file ===> Commit changes

 **36.** На веб интерфейсе модифицировать файл `bug_report.xml`, добавить баг репорт в формате *XML*.
>Open file ===> Edit file ===>
```
<Bug_Report>
    <ID></ID>
    <Summary></Summary>
    <Incident_Description></Incident_Description>
    <Pre-Conditions></Pre-Conditions>
    <Steps_to_reproduce></Steps_to_reproduce>
    <Actual_result></Actual_result>
    <Expected_result></Expected_result>
    <Environment></Environment>
    <Build></Build>
    <Attempt_to_repeat></Attempt_to_repeat>
    <Impact></Impact>
    <Severity></Severity>
    <Priority></Priority>
    <Attachment></Attachment>
</Bug_Report>
  ```
 **37.** Сделать *Commit changes* (сохранить) изменения на веб интерфейсе.
>Added bug_report structure ===> Commit changes

 **38.** Синхронизировать внешний и локальный репозиторий *XML*.
 ```
$ git fetch
$ git pull
```
___
## TXT - https://github.com/kukushkin42/TXT
___
 **1.** Создать внешний репозиторий c названием *TXT*.
>https://github.com/new => Repository name => TXT => Add a README file => Create

 **2.** Клонировать репозиторий *TXT* на локальный компьютер.
 ```
$ cd ..
$ git clone "link to the repository from GitHub"
$ cd TXT/
```
 **3.** Внутри локального *TXT* создать файл “`new.txt`”.
 ```
$ touch new.txt
```
 **4.** Добавить файл под гит.
 ```
$ git add new.txt
```
 **5.** Закоммитить файл.
 ```
$ git commit -m "add txt file"
```
 **6.** Отправить файл на внешний GitHub репозиторий.
 ```
$ git push
```
 **7.** Отредактировать содержание файла “`new.txt`” - написать информацию о себе (*ФИО, возраст, количество домашних животных, будущая желаемая зарплата*). Всё написать в формате *TXT*.
 ```
$ vim new.txt
```
>   ===> INSERT ===>
```
name - Andrey
age - 28
pets - 1
salary - 1500
```
>===> Esc ===> :x

 **8.** Отправить изменения на внешний репозиторий.
 ```
$ git commit -am "update txt file"
$ git push
```
 **9.** Создать файл `preferences.txt`
 ```
$ touch preferences.txt
```
 **10.** В файл `preferences.txt`” добавить информацию о своих предпочтениях (*Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить*) в формате *TXT*.
 ```
$ vim preferences.txt
```
>   ===> INSERT ===>
```
favorite movie - Fight Club
favorite series - Breaking Bad
favorite food - Pizza
favorite season - Summer
country to visit - USA
```
>===> Esc ===> :wq

 **11.** Создать файл `skills.txt` добавить информацию о скиллах которые будут изучены на курсе в формате *TXT*
 ```
$ cat > skills.txt
Terminal
Postman
CheckList
BugReport
Jmeter
SQL
Charles
DevTools
Mobile_testing
```
 **12.** Сделать коммит в одну строку.
 ```
$ git add .; git commit -m "add preferences and skills files"
```
 **13.** Отправить сразу 2 файла на внешний репозиторий.
 ```
$ git push
```
 **14.** На веб интерфейсе создать файл `bug_report.txt`.
>Add file ===> Create new file ===> bug_report.txt file name

 **15.** Сделать *Commit changes* (сохранить) изменения на веб интерфейсе.
>Created bug_report file ===> Commit changes

 **16.** На веб интерфейсе модифицировать файл `bug_report.txt`, добавить баг репорт в формате *TXT*.
>Open file ===> Edit file ===>
```
1.ID
2.Summary
3.Incident Description
4.Pre-Conditions
5.Steps to reproduce
6.Actual result
7.Expected result
8.Environment
9.Build
10.Attempt to repeat
11.Impact
12.Severity
13.Priority
14.Attachment
```
 **17.** Сделать *Commit changes* (сохранить) изменения на веб интерфейсе.
>Added bug_report structure ===> Commit changes

 **18.** Синхронизировать внешний и локальный репозиторий *TXT*
 ```
$ git fetch
$ git pull
```
___
