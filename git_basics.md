        // ОТПРАВКА ИЗМЕНЕНИЙ

// в терминале "git status" - покажет красным, что надо добавить

// "git add [files]" (git add index.js index.html readme.md) Но запись большая, поэтому: "git add ." (добавит все файлы в stage)

// "git commit (дальше комментарий) -m 'comment'"(можно написать init project)

// "git log" (покажет дату, автора записи, айди коммита и комментарий)
// "git log --oneline" (покажет только последний комментарий)

// "git push" [rep_line] [branch_name]
// "git remote -v" (Покажет репозиторий: в нашем случае 'https://github.com/zeniukov/test-git-2.git', но можно написать 'origin')
// "git branch" (покажет ветку) (в нашем случае 'master')


        // git reset, git diff и git reset --hard


// "git reset [file]" удаляет некоторые файлы из промежуточной области 

// "git diff" (показывает удаленные или измененные строки) (можно уточнить файл: например, "git diff index.js")

// "git reset --hard" (сносит все изменения во всех файлах)


// ФАЙЛ .gitignore (указывает папки и файлы, которые должны игнорироватсья при отправке на гитхаб)