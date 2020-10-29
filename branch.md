## S3. Манипуляции через ссылки, нет ссылки — в мусор
#### HEAD — текущая ссылка, tag — фиксированная ссылка, branch — движущаяся ссылка
#### checkout — перемещение на ветку или коммит, reset — перемещение с веткой на коммит
#### Видно то, на что есть ссылки, остальное — мусор
- `git tag` — вывести список тегов
- `git tag <tagname>` — создать тег
- `git branch` — вывести список локальных веток
- `git branch -av` — вывести список локальных и удаленных веток
- `git branch <branchname>` — создать ветку
- `git branch -d <branchname>` — удалить ветку
- `git checkout <commit>` — переместить HEAD на коммит (получится detached HEAD)
- `git checkout <branch>` — переместить HEAD на ветку
- `git checkout -b <new_branch>` — создать новую ветку и перейти на нее
- `git reset --hard <commit>` — переместить HEAD и текущую ветку на `<commit>`
### Lorem ipsum dolor sit amet, consectetur adipiscing elit