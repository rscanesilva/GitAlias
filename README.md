# GitAlias

#### 1. Git FPG (Fist Remote Push)
```
$ git config --global alias.frp '!git init && git add . && git commit -m "first commit"  && git remote add origin $1 && git push -u origin master && :'
```
Recebe como parâmetro a url do repositório remoto. 
Utilizar quando criar um novo repositório no git e precisar enviar um código fonte existente para esse novo repositório
Exemplo:
```
$ git frp https://github.com/rscanesilva/GitAlias.git
```
