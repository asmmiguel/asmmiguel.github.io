# Memórias de estudo em programação

## Um simples repositório de algumas memórias/lembretes de estudos em programação

### Criando chave ssh

#### Passos:

1. ssh-keygen -t ed25519 -C "your_email@example.com"
2. Copnfigure passphase
3. start ssh-agent
4. eval `` `ssh-agent -s` ``
5. ssh-add ~/.ssh/id_ed25519
6. clip < ~/.ssh/id_ed25519.pub
7. Paste key into Github's Key field

### Alguns comandos Git

1. git init - cria repositório local
2. git clone - clona repositório
3. git status - estado atual do repositório
4. git add "file" - inicia rastreamento de um arquivo específico
5. git add . - inicia rastreamento de todos os todos os arquivos não rastreados
6. .gitignore - extensões que não devem ser rastreadas
7. git diff - exibe alterações feitas na área de preparação para o próximo commit
8. git commit -m "mensagem" - realiza commit e cria mensagem
9. git rm "file" - remove arquivo do rastreamento
10. git clean - remove arquivos da árvore de trabalho permanentemete
11. git log -  lista todos os commits
12. git commit --amend - permite correção do último commit
13. git reset HEAD "file" - Redefine o HEAD atual para a condição especificada, ou seja, desfaz alterações não fonfirmadas
14. git restore - restaura árvore de trabalho
15. git tag -  exibs tags; (-a) cria tags
16. git branch "name" - cria uma ramificação
17. gir checkout "name" - checkout para o ramo
18. git checkout master - retorna para a origem, o principal
19. git checkout -b "mensagem" - checout no ramo especificado pela mensagem
20. git branch -d "mensagem" - deleta o ramos especificado pela mensagem
21. git log --oneline --decorate --graph --all - visualização amigável dos commmits na linha do tempo
