# Visual Studio Code
## Configuração do repositório
- sudo apt update
- sudo apt install -y curl apt-transport-https

- curl -sSL https://packages.microsoft.com/keys/microsoft.asc -o microsoft.asc
- sudo apt-key add microsoft.asc

- echo "deb [arch=amd64] https://packages.microsoft.com/repos/vscode stable main"  | sudo tee /etc/apt/sources.list.d/vscode.list

## Instalação
- sudo apt update
- sudo apt install -y code

## Iniciar o VS Code
- code

## Definir como editor padrão
- sudo update-alternatives --set editor /usr/bin/code

## Atualização
- sudo apt update
- sudo apt upgrade code

## Referências
- https://www.itzgeek.com/how-tos/linux/ubuntu-how-tos/how-to-install-visual-studio-code-on-ubuntu-18-04-linux-mint-19-debian-9.html
