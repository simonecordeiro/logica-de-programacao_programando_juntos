# Lógica de Programação - Programando Juntos

Youtube - https://youtu.be/FzNUNvYdxds?feature=shared

Editor Visual Studio Code

## Git x GitHub

Repositório GitHub - https://github.com/simonecordeiro/logica-de-programacao_programando_juntos

Alterando credenciais para Simone x Máquina com outro usuário somente na pasta de trabalho:


```

git config user.name "simonecordeiro"
git config user.email "simonecordeiro12041979@gmail.com"


```

### Git - Comandos principais

* git init:
Inicializa um novo repositório Git em um diretório existente ou cria um novo diretório e o inicializa como um repositório Git.

* git clone:
Cria uma cópia de um repositório Git existente em um novo diretório, baixando todo o histórico e arquivos.

git clone caminho

* git status:
Exibe o status dos arquivos no diretório de trabalho, mostrando quais arquivos foram modificados, adicionados ou removidos desde o último commit.

* git add:
Adiciona arquivos ao índice (staging area) para serem incluídos no próximo commit.

git add .

* git commit:
Salva as alterações do índice no repositório local, criando um novo commit com uma mensagem descritiva. 8

git commit -m "Mensagem texto"

* git push:
Envia os commits locais para um repositório remoto, sincronizando as alterações entre o repositório local e o remoto.

* git pull:
Obtém as alterações mais recentes de um repositório remoto e as mescla com o repositório local.

* git branch:
Lista, cria, renomeia ou exclui branches.

* git checkout:
Muda para uma branch específica ou restaura arquivos do repositório.

git checkout -b feature/Simone - cria uma nova feature ou branch a partir da que esta em uso.

* git merge:
Mescla as alterações de uma branch em outra, combinando o histórico de duas branches em uma. 

git merge origin branch 

* git diff:
Mostra as diferenças entre arquivos, seja entre o diretório de trabalho e o índice, ou entre commits. 

* git log:
Exibe o histórico de commits, mostrando informações sobre cada commit, como autor, data e mensagem.
 
* git reset:
Desfaz alterações no repositório, seja movendo a branch, desfazendo commits ou desfazendo a adição de arquivos ao índice.

* git remote:
Gerencia as conexões com repositórios remotos.

* git stash:
Salva as alterações não commitadas temporariamente, permitindo que você mude de branch ou execute outras operações sem perder o trabalho.

* git tag:
Cria, lista, exclui ou verifica tags, que são marcadores usados para identificar versões específicas do projeto. 

