####################
## PROJETO FASE 1 ##
####################

# Iniciando o Git

Usuario@Usuario-PC MINGW32 ~
$ git config --global user.name "Átila de Freitas"

Usuario@Usuario-PC MINGW32 ~
$ git config --global user.email "atilafreitasjr@gmail.com"

Usuario@Usuario-PC MINGW32 ~
$ git config --global color.ui true

# Criando repositório

Usuario@Usuario-PC MINGW32 /d/aulagit
$ git init

Initialized empty Git repository in D:/aulagit/.git/

# adicinando arquivo

$ git add arquivo.txt

warning: LF will be replaced by CRLF in arquivo.txt.
The file will have its original line endings in your working directory.

Usuario@Usuario-PC MINGW32 /d/aulagit (master)
$ git status
On branch master

Initial commit

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   arquivo.txt

# Commitando arquivos

$ git commit -m "Meu primeiro commit"
[master (root-commit) 8c7f7c1] Meu primeiro commit
warning: LF will be replaced by CRLF in arquivo.txt.
The file will have its original line endings in your working directory.
 1 file changed, 4 insertions(+)
 create mode 100644 arquivo.txt

# Adicionando

Usuario@Usuario-PC MINGW32 /d/aulagit (master)

$ git add README.md



