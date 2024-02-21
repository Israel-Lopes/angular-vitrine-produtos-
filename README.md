

## Instalando Angular na maquina

Para instalação foram feito os seguintes passos:

1. Instalar o nvm:

``curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash``

2. Garregar configurações

``source ~/.bashr`` ou ``source ~/.zshrc``

3. Instalar versão especifica do Node.js

``nvm install --lts``

4. Instalar Angular

``npm install -g @angular/cli``

5. Verificar instaação

``ng version``

Agora para criar projeto basta fazer:

``ng new <nome_do_projeto>``
