Git - Михайлов Александр  
11.07.2024  
**Задание 1**  
1.Зарегистрируйте аккаунт на GitHub.
![alt text](https://github.com/AleksandrMihajlov/gitlab-hw/blob/main/1.1.png)  
2.Создайте новый отдельный публичный репозиторий. Обязательно поставьте галочку в поле «Initialize this repository with a README».
![alt text](https://github.com/AleksandrMihajlov/gitlab-hw/blob/main/1.2.png)  
3.Склонируйте репозиторий, используя https протокол git clone ....  
![alt text](https://github.com/AleksandrMihajlov/gitlab-hw/blob/main/1.3.png)
4.Перейдите в каталог с клоном репозитория.  
![alt text](https://github.com/AleksandrMihajlov/gitlab-hw/blob/main/1.4.png)
5.Произведите первоначальную настройку Git, указав своё настоящее имя и email: git config --global user.name и git config --global user.email johndoe@example.com.  
![alt text](https://github.com/AleksandrMihajlov/gitlab-hw/blob/main/1.5.png)
6.Выполните команду git status и запомните результат.  
![alt text](https://github.com/AleksandrMihajlov/gitlab-hw/blob/main/1.6.png)
7.Отредактируйте файл README.md любым удобным способом, переведя файл в состояние Modified.  
![alt text](https://github.com/AleksandrMihajlov/gitlab-hw/blob/main/1.7.png)
8.Ещё раз выполните git status и продолжайте проверять вывод этой команды после каждого следующего шага.  
![alt text](https://github.com/AleksandrMihajlov/gitlab-hw/blob/main/1.8.png)
9.Посмотрите изменения в файле README.md, выполнив команды git diff и git diff --staged.  
![alt text](https://github.com/AleksandrMihajlov/gitlab-hw/blob/main/1.9.png)
10.Переведите файл в состояние staged или, как говорят, добавьте файл в коммит, командой git add README.md.  
![alt text](https://github.com/AleksandrMihajlov/gitlab-hw/blob/main/1.10.png)
11.Ещё раз выполните команды git diff и git diff --staged.  
![alt text](https://github.com/AleksandrMihajlov/gitlab-hw/blob/main/1.11.png)
12.Теперь можно сделать коммит git commit -m 'First commit'.  
![alt text](https://github.com/AleksandrMihajlov/gitlab-hw/blob/main/1.12.png)
13.Сделайте git push origin master.  
![alt text](https://github.com/AleksandrMihajlov/gitlab-hw/blob/main/1.13.png)
[Ссылка](https://github.com/AleksandrMihajlov/gitlab-hw/commit/8c6fe3590796c8159f38536d0e671c1724220b26)  
**Задание 2**  
1.Создайте файл .gitignore (обратите внимание на точку в начале файла) и проверьте его статус сразу после создания.  
![alt text](https://github.com/AleksandrMihajlov/gitlab-hw/blob/main/2.1.png)
2.Добавьте файл .gitignore в следующий коммит git add....  
![alt text](https://github.com/AleksandrMihajlov/gitlab-hw/blob/main/2.2.png)
3.Напишите правила в этом файле, чтобы игнорировать любые файлы .pyc, а также все файлы в директории cache.  
![alt text](https://github.com/AleksandrMihajlov/gitlab-hw/blob/main/2.3.png)
4.Сделайте коммит и пуш.  
![alt text](https://github.com/AleksandrMihajlov/gitlab-hw/blob/main/2.4.png)
[Ссылка](https://github.com/AleksandrMihajlov/gitlab-hw/commit/3261b9d140546e25fddbade29c1ee215339b5184)