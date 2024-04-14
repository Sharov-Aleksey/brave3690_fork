* Настройка гита, глобальное представление почты
```sh
git config --global user.email "sha.ala@yandex.ru"
```

* Настройка гита, глобальное представление автора
```sh
git config --global user.name "Sharov Aleksey"  
```

* команда инициальзации гита
```sh
git init
```

* команда просмотра состояния файлов
```sh
git status
```

* команда добавления определенного файла для коммита
```sh
git add "file"
```

* команда сохранения изменений файла с комментарием что было изменено и тд
```sh
git commit -m "message"
```

* общий просмотр журнала
```sh
git log
```

* вывод журнала компакнее, одной строкой за коммит
```sh
git log --oneline
```

* просмотр разницы файла
```sh
git diff
```

* просмотр изменений с указанием хеша коммита
```sh
git diff hash1 hash2
```

* просмотр количества веток и отображение активной 
```sh
git branch
```

* создание ветки
```sh
git branch "name"
```

* 
```sh
git checkout "branch_name"
```

* удаление ветки
```sh
git lession2>git branch -d "text_formatting"
```

* отображение лога с ветвлениями и коммитами
```sh
git log --graph
```

* возврат на главную ветку
```sh
git checkout master
```
