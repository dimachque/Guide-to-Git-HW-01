[<Back](/readme_en.md)

# How to understand the current branch

>### `main` branch on the right in `git graph`

![](/assets/7.%20Сменить%20название%20ветки/main%20ветка%20до%20смены.png)

>### Main branch in lower left corner of IDE

![](/assets/7.%20Сменить%20название%20ветки/ветка%20main.png)

# Rename branch

> [!IMPORTANT]      
> When changing branches, the case plays an important role. If before the branch was named "main", and after the return of "Main", then there will be two different branches.

>### In version control, we select a cross-reference and then the `Branch >> Rename Branch...`.

![](/assets/7.%20Сменить%20название%20ветки/сменить%20название%20ветки.png)

>### Enter a new name in the line

![](/assets/7.%20Сменить%20название%20ветки/в%20строке%20меняем%20название%20ветки.png)

>### Similarly, you can rename to git graph via `MB2` (_right mouse button_)

![](/assets/7.%20Сменить%20название%20ветки/2088.png)

>### Check the status of branches

![](/assets/7.%20Сменить%20название%20ветки/новое%20название%20ветки.png)       
![](/assets/7.%20Сменить%20название%20ветки/новое%20название%20ветки%202.png)

# Create new branch

>### In version control, we select a cross-reference, then `Branch >> Create Branch...`.

![](/assets/7.%20Сменить%20название%20ветки/2089.png)       
![](/assets/7.%20Сменить%20название%20ветки/в%20строке%20меняем%20название%20ветки.png)

>### Check that the branch is actually created

![](/assets/7.%20Сменить%20название%20ветки/новое%20название%20ветки.png)

# Switching from branch to commit

>### If we want to work not in the branch, but in a certain commet, then at the bottom left click on the current branch

![](/assets/7.%20Сменить%20название%20ветки/ветка%20main.png)

>### Next in the line select `Checkout detached...`

![](/assets/7.%20Сменить%20название%20ветки/чекаут.png)

>### Check that we have a header pointer now attached to the comment, not the branch

![](/assets/7.%20Сменить%20название%20ветки/смена%20коммита%20на%20ветку.png)

>### To make a change back from Kommitta to our branch, it is enough to do the same manipulations, but now in line you have to choose the branch

![](/assets/7.%20Сменить%20название%20ветки/выбрать%20ветку.png)