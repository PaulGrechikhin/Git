# Ссылки

Это [cылка](https://www.google.ru/ "Google") с тайтлом

[Ссылка](https://www.google.ru/) без заголовка

https://www.google.ru/ - безанкорная ссылка

---

![Кит](CDxrVzLKuusf8ftqS44iad1OIm2_nHqitOqoG9iCyBEBPFLcMccR5-ZdiyIQX7q-PbhnxpFPir_kMmAhTFYJIf07.jpg)

---

# Git instruction

>- **git init** - создание реопзитория в текущей папке
>- **git add** - добавление файлов 
>   - **git add .** - добавление всех файлов в текущем каталоге
>   - **git add nameoffile** - добавление файла с именем nameoffile
>- **git commit -m 'Комментарий'** - сохранение версии
>   - **git commit --amend -m 'комментарий'** - перезаписать последний коммит
>- **git log** - показать сохраненные версии
>- **git diff** - показать различия между текушей и мастер версиями
>- **cls** или **clear** - очистить терминал
>- **git checkout 62f1** - переход к версии по номеру
>   - **git checkout master** - переход к мастер версии файла

>- **git merge second** - сливает ветку second с текущей.

>- **gib clone** - копировать внешний репозиторий на свой ПК. Также, она загружает все измениния и пытается слить все ветки на локальном компьютере и в удаленном репозитории.

>- **git pull** - скачивает все из удаленного репозитория и автоматически сделает merge с нашей версией.

>- **git push** - это команда отправляет локальный репозиторий в удаленны.

>- **pull request** - команда для предложения изменения. Запрос на вливание зменений в репозиторий. Сначала нужно отправить push на свой аккаунт в GitHub, а потом редложить pull request на другой аккаунт.

Как сделать pull request
* Делаем   (ответвление) репозитория fork
* Делаем git clone   версии репозитория СВОЕЙ
* Создаем новую ветку и в НЕЕ вносим свои изменения
* Фиксируем изменения (делаем коммиты)
* Отправляем свою версию в свой GitHub
* На сайте GitHub нажимаем кнопку pull request

Ветка мастер
Ветка one
Ветка two
Ветка Three
Ветка four

**Удалены**

*В процессе выполнения домашнего задания понял, что конфликт возник на каждой ветке. Как я понял, это связано с тем, что не было заголовков как на лекции и для гита пустая строка считается как заполненная*