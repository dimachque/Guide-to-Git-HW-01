[<Back](/readme_en.md)

> ### [Перейти к файлу "ALIAS](/readme_en/Alias_en.md)

# Status

### View short information.

```bash
git status --short
```
> `git s` — if you read the file about Alias

* #### Details about modifications:
    + M *(red)* — found in modified files `Changes`.
    + M *(green)* — found in intermediate changes `Staged Changes`.

![](/assets/Status%20'n'%20Logs/git%20status.png)

# Logs

### View the history of changes (commits). Shows the author, date, and commit hash in chronological order. To exit the log, press the `[Q | q]`

```bash
git log
```

---

### Displays commit information in the form of a compact graph.

```bash
git log --oneline --graph --decorate --all
```
> `git l` — if you read the file about Alias

![](/assets/Status%20'n'%20Logs/git%20log.png)

---

### Displays detailed information about commits, hashes, and authors in chronological order in the form of a graph.

```bash
git log --graph --abbrev-commit --decorate --all --format=format:'%C(bold blue)%h%C(reset) - %C(bold cyan)%aD%C(dim white) - %an%C(reset) %C(bold green)(%ar)%C(reset)%C(bold yellow)%d%C(reset)%n %C(white)%s%C(reset)'
```
> `git g` — if you read the file about Alias

![](/assets/Status%20'n'%20Logs/git%20log%20подробный.png)