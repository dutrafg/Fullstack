# Comandos Git Básicos

## Inicialização e Clonagem

- `git init` – Inicializa um novo repositório Git.
- `git clone <URL>` – Clona um repositório remoto para o seu computador.

## Status e Alterações

- `git status` – Exibe o status dos arquivos no repositório.
- `git add <arquivo>` – Adiciona um arquivo à área de preparação.
- `git add .` – Adiciona todos os arquivos modificados à área de preparação.
- `git commit -m "mensagem"` – Salva as alterações no repositório local com uma mensagem descritiva.

## Restauração de Arquivos

- `git restore <arquivo>` – Restaura um arquivo para o estado do último commit.
- `git restore --staged <arquivo>` – Remove um arquivo da área de preparação.
- `git restore --source=<commit> <arquivo>` – Restaura um arquivo a partir de um commit específico.

## Trabalhando com Repositórios Remotos

- `git remote add origin <URL>` – Adiciona um repositório remoto.
- `git push origin <branch>` – Envia as alterações para o repositório remoto.
- `git pull origin <branch>` – Baixa as alterações do repositório remoto.

## Gerenciamento de Branches

- `git branch` – Lista todas as branches no repositório.
- `git checkout -b <nome>` – Cria e muda para uma nova branch.
- `git merge <branch>` – Mescla uma branch ao branch atual.

## Desfazendo Alterações

- `git reset --soft <commit>` – Reverte um commit, mantendo as alterações.
- `git reset --hard <commit>` – Reverte um commit e descarta as alterações.
- `git revert <commit>` – Cria um novo commit que desfaz as alterações do commit especificado.

## Visualização e Histórico

- `git log` – Exibe o histórico de commits.
- `git log --oneline` – Mostra o histórico de commits de forma compacta.
- `git log --graph` – Exibe um gráfico do histórico de commits.

## Manipulação de Arquivos

- `git rm <arquivo>` – Remove um arquivo do repositório.
- `git mv <arquivo_antigo> <arquivo_novo>` – Renomeia ou move um arquivo.

## Trabalhando com Tags

- `git tag <nome>` – Cria uma tag para marcar um commit.
- `git tag` – Lista todas as tags do repositório.
- `git push origin <tag>` – Envia uma tag para o repositório remoto.

## Sincronização e Colaboração

- `git fetch` – Baixa as alterações do repositório remoto sem aplicá-las.
- `git rebase <branch>` – Reaplica commits em cima de outra branch.
- `git cherry-pick <commit>` – Aplica um commit específico em outra branch.

## Correção de Erros

- `git stash` – Salva temporariamente alterações não commitadas.
- `git stash pop` – Recupera as alterações salvas com `git stash`.
- `git bisect` – Ajuda a encontrar um commit que introduziu um bug.

---

Se precisar de mais detalhes ou exemplos sobre algum desses comandos, é só me chamar!
