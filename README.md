git init                      # создаём репозиторий в этой директории
touch readme.md               # создаем файл readme.md
git add readme.md             # добавляем файл в индекс
git commit -m "Старт"         # создаем коммит
git remote add origin https://github.com:nicothin/test.git # добавляем предварительно созданный пустой удаленный репозиторий
git push -u origin master
