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
