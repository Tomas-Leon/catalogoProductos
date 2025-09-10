# ☕ Cafetería CRUD

¡Bienvenido a mi versión del proyecto CRUD de productos para una cafetería!

Este proyecto está basado en el repositorio original de **Arias Emilse** ([link al repo original](https://github.com/rollingcodeschool/catalogoProductos-c12)) y ha sido **modificado y adaptado por Tomas Leon** para fines de práctica y aprendizaje.

## 🚀 Tecnologías Utilizadas

* **React:** La biblioteca principal para construir la interfaz de usuario.
* **React-Bootstrap:** Componentes de UI pre-construidos y responsivos para un diseño rápido.
* **SweetAlert2:** Para alertas personalizadas y bonitas.
* **React Hook Form:** Para la gestión de formularios con validaciones.
* **React Router:** Para la navegación y el enrutamiento de las diferentes vistas de la aplicación.

## 📁 Estructura del Proyecto

La estructura principal del proyecto es la siguiente:
```text
src/
├── assets/
├── components/
│   ├── pages/
│   │   ├── producto/
│   │   │   ├── Administrador.jsx
│   │   │   ├── DetalleProducto.jsx
│   │   │   ├── Error404.jsx
│   │   │   ├── Inicio.jsx
│   │   │   └── Login.jsx
│   ├── routes/
│   │   └── ProtectorRutas.jsx
│   └── shared/
│       ├── Footer.jsx
│       └── Menu.jsx
├── data/
├── App.jsx
├── index.css
└── main.jsx
```
## ⚙️ Variables de Entorno

Este proyecto utiliza variables de entorno para almacenar información sensible o de configuración. Para que la aplicación funcione correctamente, debes crear un archivo `.env` en la raíz del proyecto (al mismo nivel que `package.json` y `vite.config.js`) con el siguiente contenido:

VITE_API_EMAIL=`mail@mail.com`

VITE_API_PASSWORD=`123456Aa$`


## 🛠️ Instalación y Ejecución

1. Clona este repositorio:
```
git clone https://github.com/Tomas-Leon/catalogoProductos.git
```


2. Navega a la carpeta del proyecto:
```
cd catalogoProductos
```

3. Crea el archivo `.env` con las variables de entorno mencionadas arriba.

4. Instala las dependencias:
```
npm install
```

5. Inicia la aplicación:
```
npm run dev
```

## 👩‍💻 Autoría

Proyecto original por **Arias Emilse**.  
Versión modificada y adaptada por **Tomas Leon**.

---

¡Disfruta desarrollando!💻
