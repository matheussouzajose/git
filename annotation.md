git config --global user.name "Matheus Souza Jose"
git config --global user.email "matheus.jose@aluno.faculdadeimpacta.com.br"
git config --list

git init
git status

git add name-file
git add .
git add --all
git add -A

git commit -m "message"

git diff
git giff --cached
git giff --staged

git log
git log --oneline

git checkout HASH
git checkout name-branch

git checkout name-file
git reset --hard

git clean -f

git clone url

git push origin branch-name

git branch
git branch branch-name

git checkout -b task-1
git push --set-upstream origin develop
git push -u origin develop

git branch -d branch-name
git push --delete origin branch-name

git branch -m branch-name

resolvendo conflitos