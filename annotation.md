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