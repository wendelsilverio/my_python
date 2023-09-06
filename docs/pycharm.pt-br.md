# PyCharm 2023.2.1 (Community Edition)

Estou utilizando a versão Community.

## Instalação

1. Download do [PyCHarm Windows Installer](https://www.jetbrains.com/pycharm/download/download-thanks.html?platform=windows&code=PCC)
2. Após o download, execute o instalador _pycharm-community-2023.2.1.exe_
3. Instalação padrão, _Next, Next, Next and Finish._
4. Abra o PyCharm

## Opção: Customize (Minhas preferências)

- **Color Theme:** Light with light header (Veja [Why ‘dark mode’ causes more accessibility issues than it solves](https://medium.com/@h_locke/why-dark-mode-causes-more-accessibility-issues-than-it-solves-d2f8359bb46a)) 
- **IDE font:** 12.0

## Opção: Projects

1. Selecione a opção `Get from VCS`
2. Em _Get from Version Control_, selecione esse repositório para clonar.
3. Antes de confirmar, eu mudei a pasta para `C:\>code\github`.
4. Confirme com _Trust Project_.

## Teste

1. Abra o terminal no PyCharm e digite `python --version`
```commandline
C:\code\github\my_python> python --version
Python 3.11.5
```
## Configurações Iniciais

### Ignorar a pasta .idea no Git

1. Abra o arquivo [JetBrains.gitignore](https://github.com/github/gitignore/blob/main/Global/JetBrains.gitignore)
2. Copie o conteúdo e cole no seu arquivo _.gitignore_ que deve ser criado na raiz do projeto