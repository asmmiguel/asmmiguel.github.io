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

