# GitHub. HW_2

      Создать репозиторий Branch

      mkdir Branch
      cd Branch
      touch README.md
      git init
      git add . && git commit -m "init repository and add README.md"
      git push --set-upstream https://github.com/yuliakondratsiuk/Branch.git master

1. На локальном репозитории сделать ветки для:

      >  Postman
      >> git branch Postman
 
      > Jmeter
      >> git branch Jmeter
  
      > CheckLists
      >> git branch CheckLists

      > Bag Reports
      >> git branch BugReports
 
      > SQL
      >> git branch SQL
 
      > Charles
      >> git branch Charles
 
      > Mobile testing
      >> git branch MobileTesting

2.  Запушить все ветки на внешний репозиторий
    > git push --all
3.  В ветке Bag Reports сделать текстовый документ со структурой баг репорта

    >     git checkout BugReports
    >      cat > bugreports.txt (+add content)

4.  Запушить структуру багрепорта на внешний репозиторий
    > git add bugreports.txt && git commit -m "add bugreport" && git push --set-upstream origin BugReports
5.  Вмержить ветку Bag Reports в Main
    >     git checkout main
    >     git merge BugReports
6.  Запушить main на внешний репозиторий.
    > git push -u origin master
7.  В ветке CheckLists набросать структуру чек листа.

    >     git checkout CheckLists
    >     touch CheckLists.txt
    >     add CheckList
    >     git add CheckLists && git commit -m  "add CheckLists.txt"

8.  Запушить структуру на внешний репозиторий
    > git push --set-upstream origin CheckLists
9.  На внешнем репозитории сделать Pull Request ветки CheckLists в main
    > go to Pull Request - click new pull request - base:master compare:CheckLists - click create pull request - click Marge pull request - click Confirm merge
10. Синхронизировать Внешнюю и Локальную ветки Main
    > git pull

[Back to page Course_V_Ksendzov](https://yuliakondratsiuk.github.io/Course_V_Ksendzov/) 
