# Тестовый репозиторий



Это тестовый репозиторий для изучения GIT

git config --global user.name "Alex Yersh"
git config --global user.email yersh.alex@gmail.com
git config --global core.editor nano
git config --list --show-origin
git config --global password <token> - установить токен

git add <file> - добавление файлов в индекс
git commit <file> -m 'message' - коммит изменений 
git log - лог коммитов
git show <hash> - показать изменения по hash
git branch -m master main - переименовать ветку "master" В "main"
git remote  add origin <URL> - добавить репо к удаленному по URL
git revert <hash> - отмена коммита по хэшу, возврат изменений

работа с ветками:
git branch <name> - создание ветки <name>
git checkout <name> - перейти на ветку
git merge --no-ff <br_name> -m '<massage>'
git log --oneline --graph - Отображение истории графиком