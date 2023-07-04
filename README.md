# votacionBlockchain
## Instalación de entorno
1. Descargar e instalar NodeJS: https://nodejs.org/en/download/ 
2. Abrir terminal para instalar truffle y ganache mediante node package manager (npm)
  > npm install -g truffle
> 
  > npm install -g ganache
3. Instalar la extensión de navegador de billetera metamask: https://metamask.io/download
4. Crear una cuenta en Metamask
> 

## Configuración de proyecto para desarrollo
1. Clonar el repositorio: https://github.com/wil0512/votacionBlockchain.git

2. Ejecutar en terminal:
>
 > git clone https://github.com/wil0512/votacionBlockchain.git
>
> cd dapp
3. Configurar la red en Metamask, accediendo a través de la ruta:
           > Configuración > Redes > Agregar nueva red
4. Es necesario optar por la opción: Añadir red manualmente
>A continuación se mostrará un formulario de registro donde registramos los siguientes datos:

  >Nueva URL RPC: http://127.0.0.1:8545
>
  >ID de cadena: 1337

Observación: En este paso, debemos acceder a la ubicación del proyecto, para incluir en el archivo truffle-config.js el puerto: 7545 (para ganache gui).

5. Instalación de Ganache 
La aplicación de escritorio de Ganache permite una mejor administración de la red blockchain, en el que va corriendo el servidor RPC. 
Accediendo a la dirección: https://trufflesuite.com/ganache/

En la seccion “WORKSPACE” 
  >Asignar un nombre: Votación Blockchain
>
  >Importar el archivo truffle-config.js del proyecto

En la seccion “SERVER” completar el campo 
> PORT NUMBER =8545, dar clic a Start

Adicionalente se puede ajustar la cantidad de cuentas que se quiera manejar a traves del entorno de pruebas de Ganache.

