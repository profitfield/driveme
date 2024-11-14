# Git Workflow Guidelines

## Branch Naming Convention

- `feature/` - для новых функций (например, feature/auth-system)
- `bugfix/` - для исправления багов (например, bugfix/login-validation)
- `hotfix/` - для срочных исправлений в production
- `release/` - для подготовки релиза
- `refactor/` - для рефакторинга кода

## Commit Message Format

```
<type>(<scope>): <subject>

<body>
```

### Types

- `feat`: новая функциональность
- `fix`: исправление бага
- `refactor`: рефакторинг кода
- `docs`: изменения в документации
- `style`: форматирование, отступы и т.д.
- `test`: добавление тестов
- `chore`: обновление зависимостей, конфигурации и т.д.

### Example

```
feat(auth): add telegram authentication

- Add Telegram OAuth integration
- Create authentication middleware
- Add user session handling
```

## Pull Request Process

1. Создавайте PR из своей ветки в main
2. Добавьте описание изменений
3. Убедитесь, что все тесты проходят
4. Получите минимум один апрув
5. Используйте squash and merge при слиянии
