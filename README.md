# Shared Clipboard App

La aplicación "Shared Clipboard" permite compartir el contenido del portapapeles entre un teléfono y un PC en la misma red LAN de manera segura y eficiente. Esta solución es ideal para usuarios que necesitan transferir texto y otros datos fácilmente entre dispositivos sin utilizar medios externos.

## Características

- **Sincronización en Tiempo Real**: Actualizaciones instantáneas del contenido del portapapeles entre dispositivos conectados.
- **Soporte Multiplataforma**: Compatible con Windows, MacOS, Linux, Android e iOS.
- **Seguridad**: Comunicación cifrada y autenticación de dispositivos para garantizar que solo dispositivos autorizados puedan compartir el portapapeles.
- **Interfaz Sencilla**: Interfaz de usuario amigable y fácil de usar tanto en el PC como en el teléfono móvil.
- **Configuración de Dispositivos**: Permite seleccionar con qué dispositivos compartir el portapapeles.

## Tecnologías Utilizadas

- **[Electron](https://www.electronjs.org/)**: para la creación de la aplicación de escritorio que funciona en Windows, MacOS y Linux.
- **[React Native](https://reactnative.dev/)**: para desarrollar la aplicación móvil compatible con Android e iOS.
- **[Node.js](https://nodejs.org/)**: para el servidor backend que maneja la lógica de negocio y las conexiones de red.
- **[Socket.IO](https://socket.io/)**: para la comunicación en tiempo real entre el cliente y el servidor.
- **[SQLite](https://www.sqlite.org/index.html)**: para la gestión opcional de datos y configuraciones.

## Configuración del Proyecto

### Requisitos Previos

- Node.js instalado en el servidor.
- React Native y Electron instalados en el entorno de desarrollo.
