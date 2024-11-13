# Лабораторная работа №6 Система контроля версий

**Цель:** изучение базовых возможностей системы управления версиями, опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием. 

### **Ход работы**

1. Создала аккаунт на сайте GitHub
2. Сделала копию в личное хранилище из (https://github.com/Kurtyanik/LR6/) (Fork)
3. Установила Git (https://git-scm.com/)
4. После установки настроила клиент git, введя имя пользователя (Фамилия И.) и email
5. Клонировал свой личный удалённый репозиторий на компьютер с помощью команды `git clone https://github.com/groshem/LR6/`

![](/image/1.png)

6. Добавила файл через интерфейс GitHub. Добавила изменения в локальный репозиторий с помощью команды `git fetch origin`

![](/image/2.png)

7. Получила историю операций для каждой из веток с помощью команды `git log`

![](/image/3.png)

8. Просмотрела последние изменения
9. Выполнила слияние в ветку master с помощью команды `git merge`

![](/image/4.png)

10. Сделала изменения и зафиксировала их, оставляя комментарии, несколько раз
```
git commit -m "Commit number 1"
git commit -m "Commit number 2"
```

![](/image/5.png)

11. Сделала откат коммита с помощью команды `git revert 2855da783eec4ffeadeadae2d7515e80c4b43b5e`

![](/image/6.png)

12. Создала ветку для отчёта и перешла в неё с помощью команд 
```
git branch report
git checkout report
```

![](/image/7.png)

14. Начала оформлять отчёт в файле README.md 

![](/image/8.png)

15. Получила историю операций в форматированном виде (сокращённый
хэш + дата + имя автора + комментарий) с помощью команды `git log --all`

![](/image/9.png)

16. Сделала финальную фиксацию изменений с помощью команды `git commit -m "Finally commit"`
17. Отправила локальные изменения в сетевое хранилище GitHub с помощью команды `git push`
### **Вывод**

В ходе выполнения данной лабораторной работы были получены навыки работы с системой контроля версий Git. 