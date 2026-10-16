# 🏫 Sistema Escolar

Sistema web para la organización y administración visual de información escolar.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![Status](https://img.shields.io/badge/status-en%20desarrollo-yellow)

---

## 📌 Descripción

El **Sistema Escolar** es un proyecto desarrollado en **HTML5** y **CSS3** que presenta una interfaz visual para gestionar la información de los alumnos de una institución educativa.

Incluye un formulario de registro, una tabla de alumnos, un panel de resumen y un diseño moderno con sidebar, tarjetas y botones.

---

## ✨ Características

- 🏠 **Encabezado:** logotipo y nombre del sistema.
- 🧭 **Menú de navegación:** accesos a las diferentes secciones.
- 📂 **Panel lateral:** enlaces a alumnos, maestros y administradores.
- 📝 **Registro de alumnos:** formulario para capturar datos personales.
- 📋 **Lista de alumnos:** tabla con matrícula, nombre, edad, correo y acciones.
- 📊 **Resumen:** indicadores de total de alumnos, promedio general y último alumno registrado.
- 🎨 **Diseño con CSS:** colores, layout, tipografía y responsive.

---

## 🛠️ Tecnologías

| Tecnología | Uso |
|------------|-----|
| HTML5 | Estructura de la página web |
| Formularios HTML | Captura de información |
| Tablas HTML | Presentación de datos |
| Enlaces HTML | Navegación entre secciones |
| CSS3 | Estilos, layout y colores |
| CSS Grid | Distribución del layout principal |
| CSS Flexbox | Alineación de menús, formularios y tarjetas |
| Variables CSS | Paleta de colores reutilizable |
| Media Queries | Diseño responsive básico |

---


---

## 🚀 Instalación y ejecución

1. Descarga el proyecto o clona el repositorio.
2. Abre la carpeta `Sistema-Escolar`.
3. Comprueba que el logotipo esté en `public/img/logo.png`.
4. Abre `public/index.html` en tu navegador.

**Requisitos:** un navegador web moderno. No es necesario instalar dependencias para visualizar la estructura HTML y CSS.

---

## 🎨 Vista previa

El diseño incluye:

- **Header** con logo redondo y título azul.
- **Menú horizontal** con hover azul.
- **Sidebar** oscuro a la izquierda con enlaces.
- **Formulario** con campos alineados, bordes suaves y foco azul.
- **Botones:** primario (azul), secundario (gris), peligro (rojo).
- **Tabla** con encabezado azul, filas alternas y hover.
- **Tarjetas** blancas con sombra que se elevan al pasar el mouse.
- **Footer** centrado en gris.
- **Responsive:** al reducir la ventana, el sidebar se va arriba.

---

## 📌 Estado del proyecto

| Actividad | Estado |
|-----------|--------|
| Actividad 16 — Estructura HTML | ✅ Completada |
| Actividad 17 — Estilos CSS | ✅ Completada |
| Actividad 18 — JavaScript | ⏳ Pendiente |
| Actividad 19 — Tabla dinámica | ⏳ Pendiente |
| Actividad 20 — Conexión con backend | ⏳ Pendiente |

En esta etapa el formulario **no funciona todavía**, solo se muestra la interfaz visual con estilos aplicados.

---

## 🧠 Conceptos aplicados

### HTML
- Estructura básica: `<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`.
- Etiquetas semánticas: `<header>`, `<nav>`, `<main>`, `<section>`, `<aside>`, `<footer>`.
- Formularios: `<form>`, `<input>`, `<label>`, `<button>`.
- Tablas: `<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>`, `<td>`.
- Atributos: `id`, `name`, `for`, `placeholder`, `required`, `min`, `max`, `type`.

### CSS
- Selectores: etiqueta, clase, id, atributo, pseudo-clases.
- Variables CSS (`:root` y `var(--...)`).
- Box model: `box-sizing: border-box`.
- Layout con **CSS Grid** (`grid-template-columns: 240px 1fr`).
- Layout con **Flexbox** (`display: flex`, `gap`, `justify-content`).
- Colores con **HEX** y **RGBA**.
- Transiciones y hovers.
- **Media queries** para responsive básico.

### Buenas prácticas
- `alt` en imágenes (accesibilidad).
- `for` en labels asociados a `id` de inputs.
- Un solo `<h1>` por página.
- Codificación **UTF-8**.
- CSS externo enlazado desde el `<head>`.
- Nombres de clases en kebab-case.

---

## 🧪 Cómo probarlo

1. Abre `public/index.html` en el navegador.
2. Pasa el mouse sobre el menú → cambia a fondo azul.
3. Pasa el mouse sobre el sidebar → los enlaces se iluminan.
4. Haz clic en un input → aparece borde azul con sombra.
5. Pasa el mouse sobre un botón → cambia de color.
6. Pasa el mouse sobre una tarjeta → se eleva un poco.
7. Reduce la ventana a menos de **768px** → el sidebar se va arriba.

---

## 🎯 Próximas mejoras

- [ ] Agregar JavaScript para hacer funcional el formulario.
- [ ] Llenar la tabla dinámicamente al registrar alumnos.
- [ ] Actualizar las tarjetas de resumen automáticamente.
- [ ] Conectar con el backend en C++.
- [ ] Validaciones del lado del cliente.
- [ ] Modo oscuro.

---

## 📄 Licencia

MIT License
