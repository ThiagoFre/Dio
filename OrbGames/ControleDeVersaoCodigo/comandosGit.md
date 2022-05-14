# Comandos do Git !

+ git init (cria um repositório no git)
+ git add (adiciona os arquivos na fila de espera do repositório local)
+ git commit -m "nome do commit" (adiciona os arquivos na fila de espera do repositório remoto)

  
+ rm -rf .git (excluí o repositório remoto)
+ ls (lista todos arquivos pastas do local que você está no HD)
+ git remote -v (mostra o caminho para o repositório no GitHub)

+ git config --list (entrega as informação do repositório)

(adiciona um nome e email autoral do repositório)
+ git config --global user.name "seu nome" (Receomendação pessoal: uso meu "@" do Github)
+ git config --global user.email "seu e-mail" (Boa prática usar seu email GitHub)

(remove as informações autorais do repositório, depois você precisa adicionar de novo com " git config --global user.name 'seu nome/email' " )
+ git config --global --unset user.name
+ git config --global --unset user.email

+ git remote add origin "link do repositório"
+ git push origin "branch" 