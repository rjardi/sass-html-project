# Conquerblocks - Academia de Programación

Sitio web estático de la academia Conquerblocks, donde se ofrecen cursos de desarrollo de software (Python, MQL5, entre otros) junto con un blog de noticias tecnológicas.

## Estructura del proyecto

```
├── index.html          # Página principal
├── quienes-somos.html  # Sobre la academia
├── cursos.html         # Listado de cursos
├── cursos/             # Páginas individuales de cursos
├── blog.html           # Blog de noticias
├── noticias/           # Páginas individuales de noticias
├── contacto.html       # Formulario de contacto
├── registro.html       # Registro de usuarios
├── login.html          # Inicio de sesión
├── aviso-legal.html    # Aviso legal
├── img/                # Imágenes del sitio
├── js/                 # JavaScript
└── css/                # Estilos (pendiente)
```

## Instalación

```bash
git clone https://github.com/rjardi/sass-html-project
cd sass-html-project
npm install
```

## Levantar el proyecto

```bash
npx live-server --port=8080
```

Se abrirá automáticamente en el navegador en `http://localhost:8080`. El servidor incluye live-reload, por lo que los cambios se reflejan al instante.

## Requisitos

- Node.js (v16 o superior)
- npm
