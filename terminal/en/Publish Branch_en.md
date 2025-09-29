[<Back](/readme_en.md)

# Publish Branch on GitHub

![](/assets/Создаем%20репозиторий/2091.png)

### Adds the modified file from the working directory to the index in preparation for the next commit

```bash
git add 'name file'
```
> #### _Example: `git add index.html`_

---

### It adds all files from the working directory to the index in preparation for the next commit

```bash
git add .
```
---

### This command creates a project status commit that records all changes added to the index

```bash
git commit -m “name commit”
```
> #### _Example: `git commit -m "first commit"`_
> ##### ⚠️ _An error may occur at this point. Read the recommendations for how to fix it_ [**HERE**](/readme_en/Author%20not%20confirmed_en.md)

---

### Link the project to the remote repository path

```bash
git remote add origin “link”
```

---

### It sends recent commits from the local repository computer to the server with the remote repository

```bash
git push -u origin main
```

---

### Push local changes to a remote repository

```bash
git push
```

---