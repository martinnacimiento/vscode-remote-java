# vscode-remote-java
# Visión
Esta configuración te permite armar un entorno de desarrollo remoto en un contenedor de docker que se ejecuta localmente en tu computadora. Es remoto porque tanto Java, Maven y todas las extensiones de vscode para Java se instalan en el Contenedor y en tu máquina local no tendrás señales de tener instalado ninguno de ellos.
## Qué tiene dentro?
- Openjdk-15
- Maven 3.6.3
- Extensión de vscode: vscjava.vscode-java-pack
## Requisitos 
- Docker

## Pasos
1. Dale una estrellita⭐ al repo (si no no te va a funcionar).
2. Clona el repositorio.
3. Abrí el directorio con vscode.
4. Vscode te pedirá que instales un pack de [extensiones](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack).
5. Ejecuta el comando re-abrir en el contenedor.
6. La primera vez tarda un poco en levantar el contenedor, por tener que bajar la imagen del openjdk, preparar la imagen del contenedor, instalar el servidor remoto de vscode y levantar el contenedor. Las próximas veces será muchísimo mas rápido.

## Más info
Me inspiré y modifiqué del repo de microsoft asi que para más info podes consultar su [repo](https://github.com/microsoft/vscode-remote-try-java).