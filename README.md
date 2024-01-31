Comandos Git
=========

Uma lista com alguns de comandos git mais usados.


### Criar e Clonar Repositórios

| Comando | Função |
| ------- | ------ |
| `git init` | Inicializa um repositório local |
|`git clone git@github.com:[nome de usuário]/[nome do repositório].git` | Cria uma cópia local de um repositório remoto usando chave SSH como forma de autenticação do usuário


### Comandos Básicos

| Comando | Função |
| ------- | ------ |
| `git add [nome-do-arquivo.txt]` | Adiciona um arquivo para área de stage | 
| `git add .`| Adiciona todos os arquivos modificados ou novos para área de stage desde que não estejam mencionados no arquivo .gitignore |
| `git commit -m [Mensagem de Commit]` | Comita as alterações dos arquivos adicionados a área stage (arquivos staged) |

### Compartilhando e Atualizando Repositório

| Comando | Função |
| ------- | ------ |
| `git remote add origin git@github.com:[nome de usuário]/[nome do repositório].git ` | Adiciona um repositório remoto |	
| `git push origin [nome-da-branch]` | Enviar uma branch do seu repositório local para o repositório remoto |  
| `git pull` | Atualiza o repositório local para o último commit do repositório remoto |
| `git pull origin [nome-da-branch]` | Atualiza branch local específica para o último commit daquela branch do repositório remoto |

### Branches e Merge

| Comando | Função |
| ------- | ------ |
| `git branch` | Lista as branches |
| `git branch [nome-da-branch]` | Cria uma nova branch |
| `git branch -d [nome-da-branch]` | Deleta uma branch do repositório local |
| `git push origin --delete [nome-da-branch]` | Deletar uma branch do repositório remoto | 
| `git checkout -b [nome-da-branch]` | Cria uma nova branch e muda para ela |
| `git checkout [nome da branch]` | Seleciona uma branch |
| `git checkout -` | Muda para a branch anterior |
| ` git merge [nome-da-branch]` | Faz um merge de uma branch com a branch atual |


