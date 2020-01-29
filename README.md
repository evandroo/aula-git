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