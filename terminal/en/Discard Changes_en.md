[<Back](/readme_en.md)

# Discard Changes

> [!IMPORTANT]      
> #### More about abbreviated commands  — [**HERE**](/readme_en/Alias_en.md)

---

### Undo local changes.
> `name file` — undo the last local changes in the file

```bash
git checkout -- `name file`
```
> #### _Example: `git checkout index.html`_

---

### Undo local changes. 
> `Dot` — Undo all recent local changes. After rolling back, it returns to the previous commit version.

```bash
git checkout .
```

---

### Extract modified files from `Staged Changes` to `Changes`.
> `name file` — extract one file

```bash
git reset -- `name file`
```
> #### _Example: `git reset index.html`_

---

### Extract modified files from `Staged Changes` to `Changes`.
> `Dot` — extract all files

```bash
git reset .
```

---

### Hard reset to `1 commit` back. Deletes the new commit and reverts to the previous one.

```bash
git reset --hard HEAD^1
```

---

### Soft reset to the previous commit. Removes the new commit and returns to the previous commit, but uncommitted changes remain and the file(s) are sent to the staging area.

```bash
git reset --soft HEAD^1
```

---

### An alternative to a hard reset (reboot):
1) `git reset .` — extract data from the stage;
2) `git checkout -- .` — We are reverting from the stage to the previous commit.