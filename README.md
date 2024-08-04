# Systèmes d’information et programmation

L'objectif de ce repository est de répertorier les différents tutoriels que je met à disposition de mes élèves afin de comprendre et de maîtriser les concepts de programmation et de systèmes d'information.

# Installation des outils

Vous aurez besoin de deux outils, **Python 3.12** et **Visual Studio Code**. Pour installer ces différents outils, CentraleSupélec vous propose des tutoriels que je ne trouve pas forcément très simple à suivre et à debugger.

Je vous propose donc des méthodes qui me seront faciles à débugger pour vous aider au mieux.

## Installation de Python

L'installation d'un beau Python3.12 se fait en plusieurs étapes, et cela diffère entre les OS. Merci de suivre la prochaine section qui correspond à votre situation.

### Mac OS

Sur MacOS je vous propose d'installer Python3.12 via Homebrew. Pour ce qui ne connaissent pas, Homebrew est un installateur de logiciel très sympathique à utiliser, qui vous permettra d'installer la bonne version de python.

D'abord, il faut lancer un `terminal` ou un `cmd` et taper la commande suivante :

```bash
brew --version
```

Si vous n'obtenez pas d'erreur c'est que Homebrew est installé. Sinon il faut l'installer via la commande :

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Suivez les indications.

Ensuite, il faut installer Python3.12 via la commande suivante :

```bash
brew install python@3.12
```

Maintenant que vous avez installé un Python3.12 de base nous allons créer ce qu'il faut pour travailler cette année.
Créons les dossiers suivant et initialisons un environnement python pour ces dossiers:

```bash
cd ~/Documents
mkdir td-sip
cd td-sip
/opt/homebrew/bin/python3.12 -m venv venv
```

Et voilà vous en avez fini pour Python!

### Linux

Sur Linux je vous propose d'installer Python3.12 via Linuxbrew. Pour ce qui ne connaissent pas, Linuxbrew est un installateur de logiciel très sympathique à utiliser, qui vous permettra d'installer la bonne version de python.

D'abord, il faut lancer un `terminal` ou un `cmd` et taper la commande suivante :

```bash
brew --version
```

Si vous n'obtenez pas d'erreur c'est que Linuxbrew est installé. Sinon il faut l'installer via la commande :

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Suivez les indications.

Ensuite, il faut installer Python3.12 via la commande suivante :

```bash
brew install python@3.12
```

Maintenant que vous avez installé un Python3.12 de base nous allons créer ce qu'il faut pour travailler cette année.
Créons les dossiers suivant et initialisons un environnement python pour ces dossiers:

```bash
cd ~/Documents
mkdir td-sip
cd td-sip
/home/linuxbrew/.linuxbrew/bin/python3.12 -m venv venv
```

Et voilà vous en avez fini pour Python!

### Windows

Sur Windows je vous propose d'installer Python3.12 via Chocolatey. Pour ce qui ne connaissent pas, Chocolatey est un installateur de logiciel très sympathique à utiliser, qui vous permettra d'installer la bonne version de python.

D'abord, il faut lancer un `cmd` et taper la commande suivante :

```bash
choco --version
```

Si vous n'obtenez pas d'erreur c'est que Chocolatey est installé. Sinon il faut l'installer via la commande :

```bash
@"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "[System.Net.ServicePointManager]::SecurityProtocol = 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"
```

Suivez les indications.

Ensuite, il faut installer Python3.12 via la commande suivante :

```bash
choco install python312
```

Maintenant que vous avez installé un Python3.12 de base nous allons créer ce qu'il faut pour travailler cette année.
Créons les dossiers suivant et initialisons un environnement python pour ces dossiers:

```bash
cd ~/Documents
mkdir td-sip
cd td-sip
C:\Python312\python.exe -m venv venv
```

Et voilà vous en avez fini pour Python!

## Installation de vscode
