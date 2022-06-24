# Projetos
Projetos Html e Css

para mudar a branch:
git checkout (branch)

Para mudar o repositorio:
git remote set-url origin

para iniciar e ultilizar o git:
0-git remote add origin (url)
1-git init
2-git add .
3-git commit -m "nome"
4-git push origin (branch)

para resolver problema de no-fast-forward:
1-git fetch origin master:tmp
2-git rebase tmp
3-git push origin head:master
4-git branch -d tmp.
