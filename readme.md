1. git status
2. git add file1 file2 file3 или git status add . - для всех файлов (git add добавляет файлы в stage)
3. git commit -m "комментарий" например  git commit -m "init project"
4. git log получение информации о commit, git log --oneline краткая информация о commit
5. git push [rep_link] [branch_name] git push origin master
6. git remote -v просмотр link
7. git branch просмотр веткипше
8. git reset (file) или git reset . удаление файлов или файла из stage
9. git diff или git diff (file) просмотр изменений в файле или файлах
10. git reset --hard убереть
11. файл .gitignore в нем мы указываем файлы которые не отправляются на репозиторий и не отслеживабтся git

ветки

master

develop

feature/main-page

feature/about-company

git branch name например git branch develop сoplfybt ветки develop

git checkout develop переключение на ветку develop