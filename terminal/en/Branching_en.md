[<Back](/readme_en.md)

# Branching

### View the current branch.

```bash
git branch
```

---

### View additional information about the current branch.

```bash
git branch -v
```

+ **HEAD** The header pointer is located at a specific commit, and the terminal will display the abbreviated commit hash from the first `7 digits`.

![](/assets/Работа%20с%20ветками/git%20branch.png)      

+ **Checkout detached** — A state in which we are not on a specific branch, such as `main`, but on a specific commit.

![](/assets/Работа%20с%20ветками/detached%20на%20коммите.png)

# How to switch from a branch to a commit and back

![](/assets/7.%20Сменить%20название%20ветки/ветка%20main.png)       
![](/assets/Работа%20с%20ветками/чекаут.png)        
![](/assets/Работа%20с%20ветками/смена%20коммита%20на%20ветку.png)      
![](/assets/Работа%20с%20ветками/вернуться%20на%20ветку.png)             

### Go to a specific commit (even if the branch changes). The hash can be specified as `7`, `8`, or `full characters`; it can be found, for example, with the `git log` command.

```bash
git checkout "git commit hash"
```

* #### If you need to simply move to the commit without changing branches, then after these manipulations you need to change the branch. Example:
    1. `git checkout commit`
    2. `git checkout name branch`

# Add / Rename / Delete branch

### Create a new branch.

```bash
git branch "name"
```

---

### Delete the inactive branch; you cannot delete the active branch.

```bash
git branch -d "name"
```

---

### Go to the branch.

```bash
git checkout "name"
```

---

### Create a new branch and switch to it.
> The `-b` flag creates a new branch; if you specify checkout without the flag, it will return an error.

```bash
git checkout -b "name"
```

---

### Rename the current branch. For example, from `master` to `main`.
> [!IMPORTANT]      
> The register is significant, i.e., if **`main`** was lowercase **`m`** and after renaming became uppercase **`M`**, then this will be a different branch.

```bash
git branch -m "name"
```

# Merging of branches

### Merge branches. Merge the current branch we are on with the branch specified in the command.

```bash
git merge "name branch"
```