# Setup

- [Install Elm](https://github.com/elm/compiler/blob/master/installers/linux/README.md)

curl -L -o elm.gz https://github.com/elm/compiler/releases/download/0.19.1/binary-for-linux-64-bit.gz

gunzip elm.gz

chmod +x elm

sudo mv elm /usr/local/bin/

- Install [Visual Studio Code](https://code.visualstudio.com/)

sudo snap install code --classic

Enable the elmtooling.elm-ls-vscode extension

sudo apt install npm

sudo npm install -g elm-test elm-format elm-review

# Running

elm reactor

# CI & tests

GitHub Actions

# Deployment

Hosting: GitHub Pages
Backend: Supabase

Secrets are stored on GitHub

# Bug Reports

Use the template

# Feature Request

Use the template

# Security Vulnerabilities

E-Mail

# Support

