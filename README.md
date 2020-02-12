# React-in-Heroku

**Iniciando uma aplicação React Js no Heroku usando o CLI do Heroku**
#
##### Requisitos:
- Heroku
- Git
#

### Crie sua nova aplicação
> create-react-app new-app

*Onde "new-app" é o nome de sua aplicação.*
#

### Inicie o Git dentro da pasta da aplicação
>git init
#

### Faça login no Heroku
> heroku login
#

### Crie o app no Heroku
>heroku create app-name --buildpack mars/create-react-app

*Onde "app-name" é o nome que ficará na aplicação do Heroku.*
#

### Adicione os arquivos da pasta ao repositório local
>git add .
#

### Faça o commit
>git commit -m "Initial commit"
#

### Faça o push para o Heroku
>git push heroku master
#

**Caso o push seja feito com sucesso, rode o seguinte comando que será aberto uma página em seu navegador com seu novo app**
>heroku open


###### Alguns erros de push podem ocorrer se estiver fazendo o upload de uma aplicação que já possuí modificações. Se usou yarn e npm em uma mesma aplicação, terá que apagar o package.json de um dos dois pois o Heroku só permite usar um.
#

# Ações adicionais

### Renomeando uma aplicação do Heroku
> git remote rm heroku

> heroku git:remote -a newname

*Onde "newname" é o novo nome.*

