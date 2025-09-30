[<Назад](/readme.md)

# Alias

> ### Полезные бинды, которые упрощают работу в терминале. Теперь не составит труда подробно посмотреть лог в `git graph` и не нужно по кд копипастить огромный код

![](/assets/Alias/алиасы.png)

### Как добавить в конфинг:
   + открыть вашу папку с репозиторием;
   + далее находим папку `.git`;
   + открываем файл `config`.

> [!IMPORTANT]      
> Для того чтобы сработал метод выше, у вас должны отображаться скрытые папки/файлы ([__Как это сделать?__](https://clck.ru/3PUweq))

# Сохраняем себе

```bash
[alias]
    s = status --short
    l = log --oneline --graph --decorate --all
    g = log --graph --abbrev-commit --decorate --all --format=format:'%C(bold blue)%h%C(reset) - %C(bold cyan)%aD%C(dim white) - %an%C(reset) %C(bold green)(%ar)%C(reset)%C(bold yellow)%d%C(reset)%n %C(white)%s%C(reset)'
    br = branch -M main
    co = checkout
```