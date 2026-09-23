# Enanos Mobile

Aplicación móvil desarrollada con React Native y Expo.

La aplicación permite:

- Ver los enanos registrados en la base de datos.
- Agregar un nuevo enano indicando nombre, apellido, edad y fecha de llegada.
- Cambiar su estado de trabajo.
- Eliminar un enano de la base de datos.

## Instalación

Instalar las dependencias:

npm install

## Configuración del backend

Crear un archivo `.env` en la raíz del proyecto.

Usar como referencia el archivo `.env.example`.

Configurar la URL del backend:

EXPO_PUBLIC_API_URL=http://TU_IP_LOCAL:3000

Por ejemplo:

EXPO_PUBLIC_API_URL=http://192.168.1.100:3000

Si se utiliza Expo Go en un celular físico, el celular y la computadora deben estar conectados a la misma red Wi-Fi.

## Ejecutar la aplicación

npm start

Luego abrir el proyecto utilizando Expo Go.