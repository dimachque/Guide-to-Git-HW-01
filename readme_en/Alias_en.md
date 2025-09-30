[<Back](/readme_en.md)

# Alias

> ### Useful bindings that simplify the work in the terminal. Now it will not be difficult to see in detail the log in the `git graph` and do not need to copy a huge code

![](/assets/Alias/алиасы.png)

### How to add to confing:
   + open your repository folder;
   + further find the folder `.git`;
   + open the file `config`.

> [!IMPORTANT]      
> For the above method to work, you must have hidden folders/files ([__how to do it?__](https://clck.ru/3PUwid))

# Keep for yourself

```bash
[alias]
    s = status --short
    l = log --oneline --graph --decorate --all
    g = log --graph --abbrev-commit --decorate --all --format=format:'%C(bold blue)%h%C(reset) - %C(bold cyan)%aD%C(dim white) - %an%C(reset) %C(bold green)(%ar)%C(reset)%C(bold yellow)%d%C(reset)%n %C(white)%s%C(reset)'
    br = branch -M main
    co = checkout
```