# testegit

# testando commit DEV
git fetch
git rebase origin/master

para atualizar a master com conteudo da DEV

git merge DEV
git status
git add .
git commit -m ""
git push

## CRiando conteudo na master e jogando na DEV"


## Renomeando 
mudar nome de origin para o novo
git remote rename origin github2

adicionar o outro repo remote com o segundo nome
https://github.com/vagnerasilva/testegit1.git

quando fizer git remote -v 

github1 https://github.com/vagnerasilva/testegit1.git (fetch)
github1 https://github.com/vagnerasilva/testegit1.git (push)
github2 https://github.com/vagnerasilva/testegit2.git (fetch)
github2 https://github.com/vagnerasilva/testegit2.git (push)

adicionando um git push somente com all
git remote add all https://github.com/vagnerasilva/testegit1.git
vc vai ver
all     https://github.com/vagnerasilva/testegit1.git (fetch)
all     https://github.com/vagnerasilva/testegit1.git (push)
github1 https://github.com/vagnerasilva/testegit1.git (fetch)
github1 https://github.com/vagnerasilva/testegit1.git (push)
github2 https://github.com/vagnerasilva/testegit2.git (fetch)
github2 https://github.com/vagnerasilva/testegit2.git (push)

git remote set-url --add --push all https://github.com/vagnerasilva/testegit1.git

all     https://github.com/vagnerasilva/testegit1.git (fetch)
all     https://github.com/vagnerasilva/testegit2.git (push) # aqui primeiro
all     https://github.com/vagnerasilva/testegit1.git (push) # aqui segundo

github1 https://github.com/vagnerasilva/testegit1.git (fetch)
github1 https://github.com/vagnerasilva/testegit1.git (push)
github2 https://github.com/vagnerasilva/testegit2.git (fetch)
github2 https://github.com/vagnerasilva/testegit2.git (push)
