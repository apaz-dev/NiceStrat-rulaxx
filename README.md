
# NiceStrat

Aplicación Android desarrollada en *Java* con *Android Studio* como parte de un proyecto académico.  
El objetivo principal es practicar el flujo de autenticación de un usuario (login / registro) y la navegación entre pantallas.

---

## Capturas de Pantalla

A continuación, se presentan algunas capturas de pantalla de como se verian las pantallas principales de la aplicación:

### Registro
Esta es nuestra pantalla de registro
![Registrar](img/foto1.png)

### Inicio de Sesión
Esta es la pantalla en la cual realizamos el login a la aplicaion
![Login](img/foto2.png)

### Vista Principal
Este seria el main de nuestra aplicacion
![Main](img/foto3.png)

### Pantalla de Carga
Esta es la pantalla de carga de la aplicacion al inicializarla
![Splash](img/foto4.png)

## 📱 Funcionalidades

- *Pantalla de inicio de sesión (Login)*
    - Campos de usuario y contraseña.
    - Botón para iniciar sesión.
    - Acceso directo a la pantalla de registro.

- *Pantalla de registro (Sign Up)*
    - Campos de usuario, email, contraseña y repetición de contraseña.
    - Botón para crear la cuenta.
    - Botón de cancelar para volver a la pantalla de login.

- *Pantalla principal*
    - Vista sencilla con el texto de prueba *“Hello World!”*, que actúa como pantalla de inicio tras el login.

---

## 🛠 Tecnologías utilizadas

- *Lenguaje:* Java
- *Entorno de desarrollo:* Android Studio
- *SDK:* Android SDK
- *Sistema de construcción:* Gradle

---

## ✅ Requisitos del programa

Para compilar y ejecutar el proyecto necesitas:

- *JDK 11 o superior* (según la configuración del proyecto).
- *Android Studio* (obligatorio).
- Emulador de Android o dispositivo físico para ejecutar la app.

---

## 📂 Estructura del proyecto

Las rutas pueden variar ligeramente según el paquete configurado en Android Studio, pero la estructura principal es:

- app/src/main/java/
    - Login.java – Lógica de la ventana de *inicio de sesión*.
    - MainActivity.java – Lógica de la *pantalla principal* de la app.
    - SingUp.java – Lógica de la ventana de *registro de nueva cuenta*.

- app/src/main/res/layout/
    - activity_login.xml – Diseño (frontend) de la pantalla de *login*.
    - activity_main.xml – Diseño de la *vista principal*.
    - activity_sing_up.xml – Diseño de la pantalla de *registro*.

- app/src/main/AndroidManifest.xml – *Manifest* del módulo con la configuración de actividades y permisos.

- img/
    - foto1.png – Screenshot de la pantalla de *login*.
    - foto2.png – Screenshot de la pantalla de *registro*.
    - foto3.png – Screenshot de la *pantalla principal* (Hello World).

---

## 🚀 Cómo ejecutar el proyecto



