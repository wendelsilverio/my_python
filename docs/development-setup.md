# My development setup

## My computer
- **Processor:** Intel(R) Core(TM) i7-8565U
- **RAM:**	8 GB
- **SSD:** 250 GB
- **O.S.:** Microsoft Windows 11 Home

## Python 3.11.5

### Installation

1. Download the [Python Windows Installer](https://www.python.org/ftp/python/3.11.5/python-3.11.5-amd64.exe)
2. After download, execute the installer python-3.11.5-amd64.exe
3. In _Install Python_, select this options:
   - [x] Use admin privileges when installing py.exe
   - [x] Add python.exe to PATH
4. Click on _Install Now_
5. After finished, click on Close button.

### Test

1. Open a _Command Prompt_ and type `python --version`:

```commandline
C:\> python --version
Python 3.11.5
```

# PyCharm 2023.2.1 (Community Edition)

### Installation

1. Download the [PyCHarm Windows Installer](https://www.jetbrains.com/pycharm/download/download-thanks.html?platform=windows&code=PCC)
2. After download, execute the installer pycharm-community-2023.2.1.exe
3. Next, Next, Next and Finish.
4. Open the PyCharm

### Customize (by my preferences)

- **Color Theme:** Light with light header (See [Why ‘dark mode’ causes more accessibility issues than it solves](https://medium.com/@h_locke/why-dark-mode-causes-more-accessibility-issues-than-it-solves-d2f8359bb46a)) 
- **IDE font:** 12.0 (I'm superstitious with 13)
- **Keymap:** Eclipse (Need install _Eclipse Keymap_ plugin. I used Eclipse to Java programming a long time ago)

### Projects

1. Select `Get from VCS` option
2. In _Get from Version Control_, select this repository to clone.
3. Before clone, I changed the Directory folder to `C:\>code\github`.
4. Confirm with _Trust Project_.

### Test

1. Open the PyCharm Terminal and type `python --version`
```commandline
C:\code\github\my_python> python --version
Python 3.11.5
```