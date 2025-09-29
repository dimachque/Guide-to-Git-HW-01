[<Back](/readme_en.md)

# Git config

### After initializing the repository, an error may occur. Most likely, this is because you have not configured your browser. To continue working with GitHub in the terminal, you need to specify a `username` and `email address`.

> #### User name in quotation marks:

```bash
git config --global  user.name "Your Name"
```

> #### Email in quortation marks:

```bash
git config --global  user.email "your@example.com"
```

> #### Make sure everything works:

```bash
git config --list
```