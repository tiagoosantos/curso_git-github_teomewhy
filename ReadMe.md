# Git e Github

nosso curso de git e github supimpa

## dia 1 - GIT

iniciar o git em uma pasta
clicar com botão direito e mostrar todas as opções, clicar em GIT BASH HERE

### comandos

git init .                      =  cria um novo repositorio git
git add <nome_arquivo>          =  manda arquivo para stage
git .                           =  manda todos os arquivos para stage
git commit -m "minha mensagem"  =  consolida o checkpoint "commit"
git status                      =  mostra o status da branch atual
git log                         =  exibe historico de commits
git reset                       =  retorna para unstage
git reset <idCommit>            =  retorna para o pos-commit
git branch                      =  exibe as branchs
git checkout <nome_branch>      =  troca para a branch mencionda
git checkout -b <nome_branch>   =  cria nova branch e muda para ela
git merge <nome_branch>         =  quando mescla da branch para master (atualiza)
git branch -D <nome_branch>     =  deleta a branch


quando troca de branch os arquivos só exibem os relacionados àquela branch, toda vez que troca de branch troca os arquivos ou seus conteúdos

quando cria uma branch da master ele carrega uma cópia de todos os commits da branch anterior junto