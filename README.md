## Ubunto 

### Configuración inicial
- Actualizar repositorios

```bash
sudo apt-get update
```
```bash
sudo apt-get upgrade
```
- Instalación de HomeBrew
```bash
sudo apt-get install build-essential procps curl file git
```
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

```bash
(echo; echo 'eval "$(/home/linuxbrew/.linuxbrew/bin/brew shellenv)"') >> /home/lagarto/.bashrc
```
```bash
eval "$(/home/linuxbrew/.linuxbrew/bin/brew shellenv)"
```
```bash
brew install gcc
```
- Instalar developer tools
```bash
brew install node
```
```bash
brew install pnpm
```
```bash
brew install git
```

- instalar bun js
```bash
curl -fsSL https://bun.sh/install | bash
```
```bash
source /home/lagarto/.bashrc
```



### atajos de teclado vs code config

- bloc de notas: copiar celda inferior  `Mayús + Alt + DownArrow`
- copiar línea abajo `Mayús + Alt + DownArrow`
- bloc de notas: copiar celda superior `Mayús + Alt + UpArrow`
- copiar línea arriba `Mayús + Alt + UpArrow`
- cursorUpSelect `Ctrl + Mayús + UpArrow`
- terminal: seleccionar hasta el comando anterior `Ctrl + Mayús + UpArrow`
- terminal: seleccionar hasta el comando siguiente `Ctrl + Mayús + DownArrow`
- cursorDownSelect `Ctrl + Mayús + DownArrow`
- Aplicar formato a celda `Mayús + Alt + f`
- bloc de notas: dar formato al bloc de notas `Mayús + Alt + f`
- dar formato al documento `Mayús + Alt + f`
- filesExplorer.findInFolder `Mayús + Alt + f`
- search.action.restrictSearchToFolder `Mayús + Alt + f`
- `Ctrl + Alt + UpArrow o DowArrow` no funciona
