# Git

### Lista as chaves
- gpg --list-secret-key --keyid-form LONG

### Gerar a chave
- gpg --full-generate-key

### Exportar a chava para colocar no GIT
- gpg --armor --export KEY

### Deletar uma chave
- gpg --delete-secret-keys KEY

### Adicionar nas configurações do GIT
- git config --global user.signingkey KEY
- git config --global commit.gpgsign true
- git config --global tag.gpgSign true

### Verificar o log com a assinatura
- git log --show-signature -1

### Adicionar no bash
- export GPG_TTY=$(tty)
- vim ~/.bash_profile
- vim ~/.zshrc

### Abrir as configurações do GIT
- vim ~/.gitconfig

### Adicionar no gpg
- vim ~/.gnupg/gpp.conf
- gpgconf --launch gpg-agent
- use-agent

### Adicionar e-mail
- gpg --edit-key 04F2548613510C7B
- adduid
- uid NUMBER
- trust
- save
