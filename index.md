# Como utilizar o **git**


* Baixe o git e inicie o git-bash na pasta do download

* Crie um diretório
 >_mkdir nome.do.diretorio_
 
* Entre no diretório
 >_cd nome.do.diretorio_

* Inicie o git
 >_git init_

* Configure um user e e um email.
 >_git config --global user.name "nome"_  
 >_git config --global user.email "email"_

* Utilize o "vim"(ou não) para criar ou editar um arquivo
 >_vim index.html_. Se for criar um html.

* Já dentro do vim aperte **I** para entrar no modo de INSERT, vc deverá criar um html basico, pesquise.
 >Precione ESC para sair do modo INSERT e escreva _:w_ para salvar e então _:q_ para sair
 
* Para adicionar arquivos ao seu commit
 >_git add 'arquivo'_
 
* Para salvar o commit
 >_git commit -m 'explicaçao do commit'_
 
* Para solicitar o envio do commit para o repositório
 >_git remote add "normalmente **ORIGIN**" "endereço do repositório do github"_  
 Se já existir arquivos no repositorio utilizar "_git pull origin master_" para pegar os mesmos.
 
* Para concluir o envio
 >_git push -u origin master_
