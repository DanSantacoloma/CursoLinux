Curso de Linux Clonado
git config --global user.name
git config --global user.email
git config --global credential.helper cache
git config --global credential.helper 'cache --timeout=3600'

git fetch origin master
git pull origin master

git commit -a
git commit -m "mensaje"

