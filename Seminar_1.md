# Руководство по GIT
 Обычный текст

 *курсив*
 **полужирный**
 
 ## Команды GIT общие
1. version - узнать установленную версию Git
2. config --global user.name "NAME" - указать в системе свое имя для последующей идентификации
3. config --global user.email - указать в системе адрес эл. почты для последующей идентификации
4. init - инициализирует репозиторий
5. status - показывает состояние репозитория
6. commit - сделать коммит
7. log - журнал версий
8. checkout - перейти к одной из версий файла
9. diff - показать изменения, внесенные в 
## Команды Git ветки
1. branch - показать все ветки
2. branch branch.name - создать новую ветку
3. checkout branch.name - перейти на ветку branch.name
4. branch -d branch.name - удалить ветку
5. checkout -b branch.name - создать новую ветку и сразу перейти на нее
6. branch -D branch.name - удалить ветку независимо от того, слита она или нет
