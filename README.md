# 📚 Flash Cards

Aplicación web de tarjetas de estudio para preparar el coloquio de Matemática.

Al ser un sitio completamente estático (HTML, CSS y JavaScript embebidos en un único archivo `index.html`), puede publicarse fácilmente utilizando **GitHub Pages** sin necesidad de instalar dependencias ni ejecutar un proceso de compilación.

---

## 🚀 Ejecutar localmente

Simplemente abrí el archivo:

```
index.html
```

en cualquier navegador moderno.

También podés utilizar un servidor local, por ejemplo con VS Code utilizando la extensión **Live Server**.

---

# 🌐 Publicar en GitHub Pages

## 1. Crear un repositorio

Crear un nuevo repositorio en GitHub, por ejemplo:

```
flash-cards
```

---

## 2. Subir el proyecto

Subí el contenido del proyecto al repositorio.

La estructura debe quedar así:

```
flash-cards/
│
├── index.html
└── README.md
```

---

## 3. Hacer el primer commit

```bash
git init

git add .

git commit -m "Initial commit"

git branch -M main

git remote add origin https://github.com/TU_USUARIO/flash-cards.git

git push -u origin main
```

Reemplazá `TU_USUARIO` por tu usuario de GitHub.

---

## 4. Activar GitHub Pages

Entrá al repositorio en GitHub y seguí estos pasos:

```
Settings
    ↓
Pages
```

En **Build and deployment** seleccionar:

```
Source:
Deploy from a branch
```

Luego configurar:

```
Branch:
main

Folder:
/ (root)
```

Guardar los cambios.

---

## 5. Esperar el despliegue

GitHub tardará aproximadamente entre 30 segundos y 2 minutos en publicar el sitio.

Cuando finalice, aparecerá una URL similar a:

```
https://TU_USUARIO.github.io/flash-cards/
```

---

# 🔄 Actualizar el sitio

Cada vez que hagas cambios:

```bash
git add .

git commit -m "Actualizar contenido"

git push
```

GitHub Pages volverá a publicar automáticamente la nueva versión.

---

# 📁 Estructura del proyecto

```
flash-cards/
│
├── index.html     # Aplicación completa
└── README.md
```

Todo el proyecto está contenido dentro de `index.html`:

* HTML
* CSS
* JavaScript

No requiere:

* Node.js
* npm
* Vite
* React
* Dependencias externas
* Proceso de build

---

# ✅ Tecnologías utilizadas

* HTML5
* CSS3
* JavaScript (Vanilla)

---

# 📄 Licencia

Este proyecto puede utilizarse libremente con fines educativos.
