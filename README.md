# Домашнее задание: Основы Git

Студент:** Chehlov M.V.  
Репозитории:**
- GitHub: [Chehlov1M/devops-netology](https://github.com/Chehlov1M/devops-netology)
- GitLab: [devops-group55731/devops-netology](https://gitlab.com/devops-group55731/devops-netology)


## Задание 1. Подключение GitHub и GitLab

Настроены два удалённых репозитория: `origin` (GitHub) и `gitlab` (GitLab). Это позволяет работать с проектом в распределённой среде и синхронизировать изменения между платформами.

- Remote: `gitlab`, `githab` добавлен через HTTPS.
- Репозиторий: Public, без начального README.
- Доступ: через Personal Access Token с правами `write_repository`.

Для работы с репозиторием в GitLab и Githab используется Personal Access Token с областью действия `write_repository`.  
Токен не хранится в коде и не коммитится.


## Задание 2: Теги

Созданы два типа тегов:
- `v0.0` — лёгковесный тег (просто указатель на коммит).
- `v0.1` — аннотированный тег с сообщением: `"Version 0.1 with .gitignore and README updates"`.
Теги запушены в оба репозитория: GitHub и GitLab.

Теги в GitLab (наглядно видны оба типа)
![Теги в GitLab](images/gitlab-tags.png)

Теги/Releases в GitHub
![Теги в GitHub](images/github-releases.png)


## Задание 3: Ветка fix

Ветка `fix` создана от коммита «Prepare to delete and move» (хеш: 2fb96c6):

Ветка в GitLab 
![Ветка в GitLab]()

Ветка в GitHub
![Ветка в GitHub]()


## Задание 4: Работа в PyCharm

Выполнены действия в интерфейсе PyCharm:
- Открыт проект `devops-netology`.
- Активная ветка: `fix`.
- Добавлено описание в `README.md`.

Git-интерфейс в PyCharm: Local Changes, Commit Message
![PyCharm Git Commit](images/pycharm-git-commit.png)



