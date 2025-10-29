# Proyecto — Desarrollo Web Estático

**Autor:** Álvaro Vargas  
**Stack:** HTML · CSS · JavaScript

Repositorio del proyecto de **desarrollo web** con estructura de archivos ordenada y lista para deploy estático.

## 📦 Contenidos
- **HTML principal:** `index.html`  
- **CSS/JS:** en `src/`  
- **Imágenes y assets:** en `assets/`

## 🗂 Estructura del repositorio
```
.
├─ index.html
├─ src/
│  ├─ *.css
│  └─ *.js
├─ assets/
│  └─ imágenes y otros recursos
├─ .gitignore
├─ LICENSE
└─ README.md
```

## ▶️ Ejecución
Abrí `index.html` en tu navegador.  
Para desarrollo con recarga en vivo:
```bash
python -m http.server 5500
# o
npx serve . -l 5500
```
Luego visitá: http://localhost:5500

## 🚀 Deploy
- **GitHub Pages:** Settings → Pages → Deploy from branch (raíz)
- **Vercel / Netlify:** Importar el repo y seleccionar carpeta raíz
