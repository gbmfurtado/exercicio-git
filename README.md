

#versionando com github

##$ git init

Inicialização de um repositório em d:/exercicio-git/.git/

##$ git config --global user.name "George"
 
 Configurando um username
 
## $ git config --global user.email "gbmfurtado@hotmail.com"

Configurando um email

## $ git remote add origin https://github.com/gbmfurtado/exercicio-git.git

Adicionando remoto, acima

## $ git push -u origin master
##Username for 'https://github.com': gbmfurtado
##Password for 'https://gbmfurtado@github.com':

Counting objects: 3, done.
Writing objects: 100% (3/3), 250 bytes | 0 bytes/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/gbmfurtado/exercicio-git.git
 * [new branch]      master -> master
Branch master set up to track remote branch master from origin.

Acima, levando ao github os dados feitos localmente.

## git pull origin master

Para puxá-los do github até o repositório local, usar o comando acima
