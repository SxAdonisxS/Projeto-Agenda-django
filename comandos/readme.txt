Iniciar o projeto Django

python -m venv venv
. venv/bin/activate
pip install django
django-admin startproject project .
Configurar o git

git config --global user.name 'Seu nome'
git config --global user.email 'seu_email@gmail.com'
git config --global init.defaultBranch main
# Configure o .gitignore
git init
git add .
git commit -m 'Mensagem'
git remote add origin URL_DO_GIT

Para fazer o push para o githup eu preciso usar o 
gitbash pode ser pelo vs code

para conseguir fazer isso pelo windwos eu preciso
usar esse comando

$ eval $(ssh-agent)

e depois 

$ ssh-add 'caminho do seu ssh'

no caso o meu fica assim -> $ ssh-add ~/.ssh/adonissantos_rsa

git push só funciona pelo bash


