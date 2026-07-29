# devops-netology

Репозиторий для курса по системам контроля версий.  
Автор: Misha Chehlov

## История коммитов

| Коммит | Описание |
|--------|----------|
| Initial commit | Создан GitHub при инициализации репозитория |
| First commit | Правки в README.md (добавлена история коммитов) |
| Added gitignore | Добавлены .gitignore и описание в README |
| Prepare to delete and move | Созданы will_be_deleted.txt и will_be_moved.txt |
| Moved and deleted | Удален will_be_deleted.txt, переименован will_be_moved.txt → has_been_moved.txt |

## Зачем нужен .gitignore

Файл `.gitignore` нужен, чтобы не хранить в репозитории временные и автоматически генерируемые файлы.  
Например, для Terraform мы игнорируем файлы состояния (`*.tfstate`), кэш и логи, чтобы:
- не засорять историю коммитов;
- не выкладывать чувствительные данные;
- избежать конфликтов при совместной работе.

