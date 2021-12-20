# DIO desafio-GitHub Raquel
Desafio de projeto sobre Git/GitHub da plataforma DIO.<br>
Link de dicas para markdown https://www.markdownguide.org/basic-syntax/ .
## Comandos no terminal GIT
- cd + nome da pasta : entra na pasta
- ctrl+L limpa terminal
- git init : cria repositório
- ls: lista conteúdo da pasta
- -a : pastas ocultas
- cd .. : volta um nível de pasta
- mkdir : cria pasta nova
- mv nome do arquivo ./nome da pasta/ : para mudar arquivo de pasta
- git add nome do arquivo nome da pasta/ : para adicionar essa mudança no commit
- git add * : passa tudo para staged
- git status : mostra o arquivo e o estado staged
- git commit -m : cria pasta x move arquivo para x
- echo > readme : cria arquivo
- git config --list : mostra informações do usuário
- git config --global -- user.name(ou email)  
- git config --global --unset user.name(ou email) : reseta dados
## Linkando o Git com repositório no Github
- git remote add origin endereço https:// do repositório no github
- git remote -v
- git status
- git push origin master ou main (precisa de senha)
- git clone : copia repositórios
## Para atualizar repositórios 
- git add .
- git commit -m "comentário sobre as mudanças"
- git push origin main
