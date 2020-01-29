# GIT E GITHUB

Guia prático para iniciantes.

### Instalação

https://git-scm.com/download

# SCENES

- [1] Você deseja criar pontos na história da produção do seu projeto

   - iniciando história(inicia um repositório): git init 
   - criando um ponto na história: git add <nome do arquivo ou (.) para adicionar mais arquivos>
   - levando a alteração até o repositório: git commit -m "Comentário"
   - ver o ponto criado na história e mudanças: git log

- [2] Você deseja verificar mudanças feitas no seu projeto

   - verificando se tem alteração: git status
   - repete o [1] do segundo topico
   - verificando o ultimo ponto na história: git show

- [3] Você começa uma nova funcionalidade no seu projeto, sem estragar o que já foi feito.

   - Criando uma ramificação(branch): git branch <nome da branch> 
   - Trocando de branch: git checkout <nome da branch>
   - Verificando ramificações(branchs) existentes: git branch

- [4] Você adiciona as novas funcionalidade ao seu projeto em produção.

   - Unindo as branch: git merge feature/cart
   
- [5] Você quer deletar a branch da nova fucionalidade, depois de aplicar em seu projeto.
   - Deletando a branch da nova funcionalidade: git branch -D feature/cart

- [6] Você quer colocar seu projeto na nuvem.

   - Adicionando um repositório remoto: git remote add origin <link do repositório no git>
   - Colocando o repositório local no git: Quando for primeiro push: git push -u origin master. Depois usasse só: git push

- [7] Você vai pegar um projeto já iniciado, para trabalhar com o time.

   - Pegando um projeto(repositório) no git: git clone <link do projeto(repositório)>

- [8] Você precisa resolver um conflito.

   - Criando uma branch: git checkout -b <nome da branch>
   - Unindo a branch, vai mostrar o que está conflitando: git merge <nome da branch>

- [9] Antes de enviar a resolução, precisamos atualizar o projeto(repositório) local

   - Pegando atualizações realizadas pelo time no repositório remoto: git pull

- [10] Você precisa voltar um arquivo pra um determinado momento da linha do tempo

   - Resgatando um commit especifico: git checkout <id da linha do tempo> -- <arquivo alterado>

- [11] Você precisa recuperar algo deletado

   - Recuperando arquivo deletado no ultimo momento: git checkout -- <nome do arquivo deletado>
   - Recuperando arquivo deletado em um ponto especifico na história: git checkout <id da linha do tempo> -- <nome do arquivo deletado>


* `git init`   // Inicia a linha do tempo
* `git add`    // Adiciona ou atualiza mudanças pra irem para a linha do tempo
* `git commit` // Adiciona um ponto na linha do tempo
* `git log`    // Visualiza os pontos na linha do tempo
* `git status` // Informa o estado das alterações do nosso projeto
* `git show`   // Apresenta determinado ponto na história
* `git branch` // Gerenciar novas linhas do tempo
* `git chekout`// Manipula as linhas do tempo 
* `git merge`  // Unir linhas do tempo
* `git push`   // Envia alterações locais para o repositório remoto
* `git clone`  // Clonar um projeto(repositório)
* `git pull`   // Atualizar projeto local antes de subir pra o remoto


// Link da video aula: https://www.youtube.com/watch?v=2alg7MQ6_sI