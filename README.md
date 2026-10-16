# 🛒 Vamos al Mercadona

**Tienda online básica desarrollada con PHP** para practicar la creación de componentes reutilizables, el manejo de formularios y la manipulación de arrays.

## 📋 Descripción

En esta práctica se desarrolla una tienda online que muestra un listado de productos con sus precios y disponibilidad. Además, el usuario puede introducir sus datos personales mediante un formulario para personalizar la página principal.

El proyecto está organizado en diferentes archivos PHP para separar la lógica de los productos, las funciones y los componentes visuales.

## ✨ Funcionalidades

- 👤 **Formulario de usuario:** permite introducir el nombre, el teléfono y la URL de una foto de perfil.
- 👋 **Bienvenida personalizada:** muestra el nombre y la foto del usuario en la cabecera.
- 🛍️ **Listado de productos:** muestra los productos, sus precios y su disponibilidad.
- 💰 **Formato de precios:** utiliza `number_format()` para mostrar los precios correctamente.
- 🔴 **Control de stock:** los productos agotados aparecen con la fila en color rojo.
- 📞 **Información de contacto:** muestra los datos del usuario debajo de la tabla.
- 🧩 **Componentes reutilizables:** utiliza `include` y `require` para organizar el código.
- 🔀 **Operadores ternarios:** permiten mostrar el estado de disponibilidad de cada producto.

## 📁 Estructura del proyecto

```text
tienda/
├── includes/
│   ├── header.php
│   ├── footer.php
│   └── funciones.php
├── data/
│   └── productos.php
├── assets/
│   └── logo-mercadona.jpg
├── inicio.php
├── index.php
└── README.md
```

## 🛠️ Tecnologías utilizadas

- **PHP** — lógica de la aplicación y generación dinámica del contenido.
- **HTML5** — estructura de las páginas y formularios.
- **CSS3** — diseño y estilos visuales.
- **Arrays y funciones** — organización de los productos y reutilización del código.
- **Método POST** — envío de los datos del formulario.

## 🎯 Objetivos de aprendizaje

1. Organizar un proyecto PHP mediante archivos y componentes independientes.
2. Crear funciones propias para generar contenido dinámico.
3. Manipular arrays y cadenas de texto.
4. Utilizar operadores ternarios para comprobar la disponibilidad de los productos.
5. Procesar formularios mediante el método `POST`.
6. Mostrar información personalizada a partir de los datos introducidos por el usuario.

## 🚀 Cómo utilizar el proyecto

1. Clona o descarga el repositorio.
2. Abre la carpeta del proyecto en tu entorno de desarrollo.
3. Inicia un servidor compatible con PHP desde la terminal:

   ```bash
   php -S localhost:8000
   ```

4. Abre el navegador y accede a:

   ```text
   http://localhost:8000/inicio.php
   ```

5. Introduce tu nombre, teléfono y URL de la foto de perfil.
6. Envía el formulario para acceder a la tienda y consultar los productos.

## 📌 Resultado esperado

Al finalizar, la aplicación mostrará una tienda online con una cabecera personalizada, una tabla de productos con sus precios y disponibilidad, y un bloque con los datos de contacto del usuario.

---

**Práctica de PHP · Vamos al Mercadona** 🛒
