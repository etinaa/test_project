### Шаги создания проекта в Git
```bash
cd ~/dev
mkdir test_project
cd test_project
touch readme.md
nano readme.md
git init
git add readme.md
git commit -m 'init commit'
```
### Шаги привязки проекта к GitHub
```bash
git remote add origin git@github.com:etinaa/test_project.git
git push -u origin main
```

### Внесение изменений в проект
```bash
nano readme.md
git add readme.md
git commit -m 'new changes'
git push
```