## Иструкция по загрузки измениний в git репозиторий
1. Созадать локально проект git init
2. После это зайти в свой профиль на github и создать удаленный репозиторий
3. Привязать удаленный репозиторий к локальному git remote add origin <name_project>
4. Проверить с помощью команды git remote -v
5. Созадать файл touch file.txt
6. Добавать в файл в состояние отслеживания git add file.txt
7. Сделать коммит git commit -m "add file"
8. Залить изменения в удаленный репозиторий  git push -u origin master

## Урок HEAD
HEAD это файл в .git где храниться ссылка/хеш последнего commit

## Жизненный цикл статусов
```aidl
untracked -- git add --> staged
staged --> git commit --> tracked/commited; 
```