1. Создание веток и их отправка на GitHub

// "git branch" // * master(главная)

Развитие ветки:
master
develop
feature/main-page
feature/about-company

// "git branch develop" -> // "git checkout develop"
    (создали ветку)     ->  (переключились на ветку)

(внесли изменения, потом пишем "git add .", "git commit -m " ", "git push origin develop")

2. Слияние веток при помощи действия pull request

в гитхабе pull requests -> new  pull request ->
выбираем, из какой ветки в какую -> pull request (можем дать название) -> create pull request -> добавляем reviewers, открываем фкладку files changed, оставляем комментарии и нажимаем finish your review -> submit review ->
вносим правки и помечаем комметнарии как resolve conversation ->
потом мерджим ветки и удаляем ненужную ветку

// "git pull origin master" притянет код из ветки master из GitHub
// "git branch -d develop(удалил ветку в VSCode, тк в гитхабе её тоже удалили)

3. Слияние веток при помощи команды git merge
git branch feature/main-page
git checkout feature/main-page