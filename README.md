# Comandos do GIT

#### INICIAR O REPOSITÓRIO GIT NO PROJETO
* `git init`

#### ADICIONA TODOS OS ARQUIVOS PARA SEREM COMMITADOS
* `git add .`

#### FAZ COMMIT COM UMA MENSAGEM
* `git commit -m "Mensagem"`

#### ADICIONA E FAZ COMMIT COM UMA MENSAGEM
* `git commit -am "Mensagem"`

#### VER STATUS DOS ARQUIVOS
* `git status`

#### VER AS ULTIMAS MODIFICACOES NOS ARQUIVOS STAGED
* `git diff --staged`

#### DAR UNSTAGE NO ARQUIVO
* `git reset <arquivo>`

#### VERIFICA LOG DOS ULTIMOS COMMITS
* `git log`
  
#### LISTA DE ARQUIVOS ALTERADOS EM DETERMINADO COMMIT:
* `git show --stat COMMIT_ID`

#### ADICIONANDO REPOSITORIO REMOTO CHAMADO ORIGIN
* `git remote add origin https://github.com/rtenorioh/comandos-git.git`

#### ENVIA OS ULTIMOS COMMITS DO LOCAL MASTER PARA O REMOTO ORIGIN
* `git push -u origin master`

#### BAIXA AS ATUALIZACOES DO REMOTO ORIGIN PARA O LOCAL MASTER
* `git pull origin master`

#### VERIFICA AS ULTIMAS DIFERENÇAS NOS ARQUIVOS
* `git diff HEAD`

#### VOLTA O ARQUIVO COMO ESTAVA NO ULTIMO COMMIT
* `git checkout -- <arquivo>`

#### CRIA UMA NOVA BRANCH
* `git branch <branch>`

#### MUDAR PARA O SEGUINTE BRANCH
* `git checkout <branch>`

#### REMOVE O ARQUIVO E DA STAGE NESSA REMOCAO
* `git rm '<arquivo>'`

#### APAGAR BRANCH
* `git branch -d <branch>`

#### ADICIONA TAG
* `git tag -a v1.4 -m 'my version 1.4'`
