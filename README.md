# vscode-devcontainer-template

## 使用技術一覧

![visual studio code](https://img.shields.io/badge/-visual%20studio%20code-181717?style=for-the-badge&logo=visualstudiocode)
![visual studio code](https://img.shields.io/badge/-Docker-181717?style=for-the-badge&logo=docker)
![Github Codespaces](https://img.shields.io/badge/-Github%20Codespaces-181717?style=for-the-badge&logo=Github)

## 環境準備

### Github Codespaces

Github Codespaces を [Visual Studio Code](https://code.visualstudio.com/)（以降、vscode） で

#### vscode の拡張機能

- [Dev Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
- [GitHub Codespaces](https://marketplace.visualstudio.com/items?itemName=GitHub.codespaces)

#### Github codespaces を起動

<img src="https://github.com/user-attachments/assets/3dd42393-58c0-4924-840f-bb6a883314a9" width="400">

## Default の container 設定

最小構成で構成

### 使用イメージ

[mcr.microsoft.com/devcontainers/base:alpine](https://hub.docker.com/r/microsoft/vscode-devcontainers)

### Customize

#### vscode の設定

詳細な設定は、[devcontainer.json](/.devcontainer/devcontainer.json)を確認

##### todo-tree の設定は別にまとめる

#### 拡張機能

- [Docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)
- [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
- [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [Text Tables](https://marketplace.visualstudio.com/items?itemName=RomanPeshkov.vscode-text-tables)
- [indent-rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow)
- [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
- [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)
- [Git Graph](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph)
- [Git History](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory)
- [GitLens — Git supercharged](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
- [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)
