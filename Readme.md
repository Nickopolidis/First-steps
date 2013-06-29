touch 'file'
git init
git add 'file'
git commit -m 'first commit'
git remote add origin https://github.com/Nickopolidis/First-steps.git (или SSH)
git push -u origin master

или общая:
После этих настроек, можно заливать свои файлы в репозитарий. Переходим в каталог со своим проектом, и даем команды:
 
git init
git add .
git commit -a -m 'first commit'
git remote add origin git@github.com:username/reponame.git
git push -u origin master

После этих команд на сервере GitHub образуется копии файлов того каталога, в котором были выполнены данные команды. Далее можно уже делать коммиты, заливки на сервер GitHub изменений, считывания изменений с сервера. Но это уже совсем другая история.
