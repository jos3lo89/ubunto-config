
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
### instalar docker
```bash
# Agregue la clave GPG oficial de Docker:
sudo apt-get update

sudo apt-get install ca-certificates curl

sudo install -m 0755 -d /etc/apt/keyrings

sudo curl -fsSL https://download.docker.com/linux/ubuntu/gpg -o /etc/apt/keyrings/docker.asc

sudo chmod a+r /etc/apt/keyrings/docker.asc

# Agregue el repositorio a las fuentes Apt:
echo \
  "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.asc] https://download.docker.com/linux/ubuntu \
  $(. /etc/os-release && echo "$VERSION_CODENAME") stable" | \
  sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
  
sudo apt-get update
```

```bash
sudo apt-get install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin

sudo docker version
```
### install postmanaaa
- descargar el archivo de linux
```bash
cd ~/Descargas
```
- Extrae el contenido del archivo `postman-linux-x64.tar.gz`:
```bash
tar -xvzf postman-linux-x64.tar.gz
```
- Mueve el directorio extraído a `/opt` (esto generalmente requiere privilegios de superusuario):
```bash
sudo mv Postman /opt/Postman
```
- Crea un enlace simbólico para que sea fácil ejecutar Postman desde cualquier lugar:
```bash
sudo ln -s /opt/Postman/Postman /usr/bin/postman
```
- Para abrir Postman, simplemente escribe `postman` en la terminal:
```bash
postman
```
- Crea un archivo de acceso directo:
```bash
sudo nano /usr/share/applications/postman.desktop
```
- Agrega el siguiente contenido al archivo:
```bash
[Desktop Entry]
Encoding=UTF-8
Name=Postman
Exec=/opt/Postman/Postman
Icon=/opt/Postman/app/resources/app/assets/icon.png
Terminal=false
Type=Application
Categories=Development;
```
- Guarda el archivo y cierra el editor (`Ctrl+O` para guardar y `Ctrl+X` para salir).
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
