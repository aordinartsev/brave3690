## Подсказка по GIT

Инициализация репозитория:
```sh
git init
```

Добавление файла в GIT
```sh
git add
```

Принять изменения в файле
```sh
git commit -m "Message text"
```

### Журналирование операций в GIT

Подробное журналирование
```sh
git log
```
Краткое журналирование в одну строку
```sh
git log --oneline
```

Краткое журналирование в одну строку с графом по истории изменения веток
```sh
git log --oneline --graph
```

Смена commit в ветке репозитория
```sh
git checkout <branch_name>
```

Смена commit на последнее зафиксированное состояние
```sh
git checkout master
```

Текущий статус репозитория
```sh
git status
```

Удаление не принятых изменений в GIT
```sh
git restore <filename>
```

Различия между последним состоянием и принятым
```sh
git diff
```

Различия между двумя commit
```sh
git diff <commit> <commit>
```

Отображение всех веток
```sh
git branch
```

Созание новой ветки
```sh
git branch <branch_name>
```