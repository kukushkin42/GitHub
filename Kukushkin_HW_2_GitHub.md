### GitHub. HW_2
**1.** На локальном репозитории сделать ветки для:
- `Postman`
- `Jmeter`
- `CheckLists`
- `Bag Reports`
- `SQL`
- `Charles`
- `Mobile testing`
```
$ git branch Postman
$ git branch Jmeter
$ git branch CheckLists
$ git branch BugReports
$ git branch SQL
$ git branch Charles
$ git branch MobileTesting
```
**2.** Запушить все ветки на внешний репозиторий
```
$ git push -u origin Postman
$ git push -u origin Jmeter
$ git push -u origin CheckLists
$ git push -u origin BugReports
$ git push -u origin SQL
$ git push -u origin Charles
$ git push -u origin MobileTesting
```
**3.** В ветке **Bug Reports** сделать текстовый документ со структурой баг репорта
```
$ git checkout BugReports
$ touch BugReportStructure.txt
$ vim BugReportStructure.txt
```
>=> INSERT =>
```
1) Unique ID
2) Priority / Severity, Priority
3) Title
4) Environment
5) Preconditions
6) Steps to reproduce
7) Actual result
8) Expected result
9) Attachments
10) Affected versions
11) Fix versions
12) Found by
13) Assignee to
14) Tags
```
> => Esc => :x => Enter

**4.** Запушить структуру багрепорта на внешний репозиторий
```
$ git add BugReportStructure.txt
$ git commit -m "add BugReportStructure.txt"
$ git push
```
**5.** Вмержить ветку **Bug Reports** в `Main`
```
$ git merge main
$ git checkout main
```
**6.** Запушить `main` на внешний репозиторий.
```
$ git push
```
**7.** В ветке **CheckLists** набросать структуру чек листа.
```
$ git checkout CheckLists
$ touch CheckListStructure.txt
$ vim CheckListStructure.txt
```
>=> INSERT =>
```
1) Number
2) Priority
3) Preconditions
3) Check name (description)
4) Actual result
5) Expected result
6) Status
7) Comments
```
> => Esc => :x => Enter

**8.** Запушить структуру на внешний репозиторий
```
$ git add CheckListStructure.txt
$ git commit -m "add CheckListStructure.txt"
$ git push
```
**9.** На внешнем репозитории сделать *Pull Request* ветки **CheckLists** в `main`
>Pull requests => New pull request => base: `main` <- compare: `CheckLists` => Create pull request => Create pull request => Merge pull request => Confirm merge

**10.** Синхронизировать Внешнюю и Локальную ветки `Main`
```
$ git checkout main
$ git pull
```
