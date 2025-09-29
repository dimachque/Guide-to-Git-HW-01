[<Назад](/readme.md)

> ### [Перейти к файлу "ALIAS](/readme_ru/Alias.md)

# Статусы

### Посмотреть краткую информацию.

```bash
git status --short
```
> `git s` — если читали файл про Alias

* #### Подробно про модификации:
    + M *(красного цвета)* — находится в измененных файлах `Changes`.
    + M *(зеленого цвета)* — находится в промежуточном изменении `Staged Changes`.

![](/assets/Status%20'n'%20Logs/git%20status.png)

---

# Логи

### Посмотреть историю изменений (коммитов). Показывает автора, дату, хэш коммита в хронологичном порядке. Чтобы выйти из журнала, нажимаем клавишу `[Q | q]`

```bash
git log
```

---

### Выводит информацию коммитов в виде компактного графа.

```bash
git log --oneline --graph --decorate --all
```
> `git l` — если читали файл про Alias

![](/assets/Status%20'n'%20Logs/git%20log.png)

---

### Выводит подробную информацию коммитов, хэшев, авторов в хронологичном порядке в виде графа.

```bash
git log --graph --abbrev-commit --decorate --all --format=format:'%C(bold blue)%h%C(reset) - %C(bold cyan)%aD%C(dim white) - %an%C(reset) %C(bold green)(%ar)%C(reset)%C(bold yellow)%d%C(reset)%n %C(white)%s%C(reset)'
```
> `git g` — если читали файл про Alias

![](/assets/Status%20'n'%20Logs/git%20log%20подробный.png)