# git-config
git config --list
git config --global user.name “имя”
git config --global user.email “почта”


git config --global core.safecrlf warn
git config --global core.quotepath off
git config --global init.defaultBranch main # Ветка по умолчанию

git config --global core.autocrlf true

git init # инициалицая репозитория
git add index.html # добавить файл
git add . # добавить все файлы
git commit -m "сообщение" # выгрузить
git status
git diff # посмотреть изменения
git diff --color-words # изменения подробно

git checkout index.html # Восстановть файл
git checkout .

git push # отправить в репозиторий
git clone ссылка с гитхаба -в нужную папку- # восстановление файлов 