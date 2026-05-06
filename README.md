# meu-projeto

git init
- iniciar um novo projeto com Git

git add <nome-arquivo>/.
- adiciona os arquivos que estão prontos para serem commitados

git commit -m "mensagem commit"
- registra os arquivos no histórico

git log
- mostra os últimos commits, o log de alterações

git status
- mostra como está o estado das nossas ramificações

git diff
- mostra o que foi alterado
- mostra o que tem de alteração na ramificação

git merge
- faz o merge de ramificações, ou seja, mescla ramificações

git branch
- mostra a branch atual

git branch -b <nome-da-branch>
- cria uma nova branch a partir do histórico da branch atual em que estamos

git checkout <nome-da-branch>
- muda para esta branch

git checkout -b <nome-da-branch>
- cria uma nova branch a partir da branch atual em que estamos

git remote add <nome> <url>
- adiciona um novo repositório remoto

git push <nome> <nome-da-branch>
- manda nossas alterações locais para o repositório remoto, para cada branch

git pull <nome> <nome-da-branch>
- pega as alterações do repositório remoto e joga para a nossa máquina

git fetch
- atualiza o nosso histórico local de acordo com o histórico salvo lá no repositório remoto
- sincronização do local com o remoto