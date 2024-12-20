# listgit


## Inicializar um repositório
bash
git init

- Inicializa um novo repositório Git no diretório atual.

## Clonar um repositório
bash
git clone <URL>

- Faz uma cópia local de um repositório remoto.

## Adicionar arquivos para controle de versão
bash
git add <arquivo>

- Adiciona arquivos especificados à área de "staging".
bash
git add .

- Adiciona todos os arquivos modificados no diretório atual.

## Verificar o status do repositório
bash
git status

- Mostra o estado atual dos arquivos (modificados, em staging, etc.).

## Criar um commit
bash
git commit -m "Mensagem do commit"

- Cria um commit com os arquivos que estão na área de staging e adiciona uma mensagem descritiva.

## Ver o histórico de commits
bash
git log

- Exibe o histórico de commits.
bash
git log --oneline

- Mostra o histórico de commits de forma compacta.

## Enviar alterações para o repositório remoto
bash
git push

- Envia os commits locais para o repositório remoto.

## Buscar alterações do repositório remoto
bash
git pull

- Baixa e integra as alterações do repositório remoto.

## Criar um novo branch
bash
git branch <nome-do-branch>

- Cria um novo branch.

## Mudar para um branch existente
bash
git checkout <nome-do-branch>

- Alterna para o branch especificado.
bash
git switch <nome-do-branch>

- Alternativa ao comando acima (mais moderno).

## Criar e mudar para um branch
bash
git checkout -b <nome-do-branch>

- Cria e muda para o novo branch em uma única etapa.
bash
git switch -c <nome-do-branch>

- Alternativa moderna ao comando acima.

## Mesclar branches
bash
git merge <nome-do-branch>

- Mescla o branch especificado no branch atual.

## Resolver conflitos
- Durante uma mesclagem, se houver conflitos, edite os arquivos conflitantes, depois:
bash
git add <arquivo>

- Para marcar os conflitos como resolvidos.

## Excluir um branch
bash
git branch -d <nome-do-branch>

- Exclui um branch que já foi mesclado.
bash
git branch -D <nome-do-branch>

- Força a exclusão de um branch, mesmo que não tenha sido mesclado.

## Reverter um commit
bash
git revert <hash-do-commit>

- Cria um novo commit que reverte as alterações de um commit anterior.

## Resetar alterações
bash
git reset <arquivo>

- Remove o arquivo da área de staging.
bash
git reset --hard

- Desfaz todas as alterações locais, incluindo as que ainda não foram commitadas.

## Ver diferenças entre arquivos
bash
git diff

- Mostra as diferenças entre os arquivos modificados e o último commit.

## Configurar um repositório remoto
bash
git remote add origin <URL>

- Adiciona um repositório remoto com o nome "origin".

## Renomear um branch local
bash
git branch -m <novo-nome>

- Renomeia o branch atual.

## Listar branches
bash
git branch

- Lista todos os branches locais.
bash
git branch -r

- Lista todos os branches remotos.
bash
git branch -a

- Lista todos os branches (locais e remotos).

## Verificar alterações em um branch remoto
bash
git fetch

- Busca as alterações do repositório remoto, mas não as integra.

## Remover arquivos rastreados
bash
git rm <arquivo>

- Remove o arquivo do repositório e do sistema de arquivos.

## Ignorar arquivos
- Adicione arquivos ou padrões ao arquivo .gitignore para que sejam ignorados pelo Git.

---