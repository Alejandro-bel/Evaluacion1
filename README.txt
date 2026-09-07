Alejandro Cristóbal Beltrán Riquelme  

Tener instalado Node.js(version 16 o superior)
Tener una cuenta en firebase y proyecto creado con firestore

Crear una carpera con tu nombre abrir la terminal desde la carpeta del proyecto para instalar las dependencias:
npm install (npm i)

Instalar SDk de firebase:
npm install firebase

en la consola de firebase crea un proyecto y registra una appWeb copia los datos de configuracion de firebase te entrega, en la carpeta del proyecto, crea un archivo llamado .env con el siquiente contenido:

VITE_FIREBASE_API_KEY=tu_valor_aquí
VITE_FIREBASE_AUTH_DOMAIN=tu_valor_aquí
VITE_FIREBASE_PROJECT_ID=tu_valor_aquí
VITE_FIREBASE_STORAGE_BUCKET=tu_valor_aquí
VITE_FIREBASE_MESSAGING_SENDER_ID=tu_valor_aquí
VITE_FIREBASE_APP_ID=tu_valor_aquí

el archivo .env contiene informacion privada y no deve deve subirse al repositorio, asegurarse que aparezca en .gitignore.

para poder ejecutar el proyecto en la terminal se agrega:
npm run dev
