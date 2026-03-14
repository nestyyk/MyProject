# Отчет по практической работе "Введение в Git"

## Выполненные действия

### 1. Инициализация репозитория
- Создана папка MyProject
- Выполнена команда: `git init`
- Настроены имя и email: `git config user.name "..."`

### 2. Первый коммит
- Создан файл index.html
- Добавлен в индекс: `git add index.html`
- Создан коммит: `git commit -m "feat: create index page"`

### 3. Внесение изменений
- Добавлен параграф в index.html
- Создан коммит: `git commit -m "feat: add description"`

### 4. Работа с ветками
- Создана ветка develop: `git checkout -b develop`
- Добавлен файл styles.css
- Выполнено слияние: `git merge develop`

### 5. Разрешение конфликта
- Создан конфликт в двух ветках
- Вручную разрешен конфликт в index.html
- Создан коммит слияния

### 6. Публикация на GitHub
- Создан репозиторий на GitHub
- Добавлен remote: `git remote add origin ...`
- Отправлен код: `git push -u origin main`

### 7. Клонирование проекта
- Склонирован репозиторий в FriendProject
- Создана ветка feature/contact
- Добавлен файл contact.html

### 8. Pull Request
- Создан Pull Request на GitHub
- Выполнено слияние через интерфейс
- Получены изменения: `git pull origin main`


## Использованные команды

```bash
git init
git add .
git commit -m "сообщение"
git status
git log --oneline
git checkout -b имя_ветки
git branch
git merge ветка
git remote add origin ссылка
git push -u origin main
git clone ссылка
git pull origin main
