# Desarrollo Web Estático

**Autor:** Álvaro Vargas  
**Stack:** HTML · CSS (Bootstrap Grid/Reboot) · JavaScript

Sitio web **estático multipágina** con estructura clara y listo para publicar en **GitHub Pages**, **Vercel** o **Netlify**.

---

## 📦 Contenidos
- **HTML principal:** `index.html`
- **Hojas de estilo / scripts:** en `src/`
- **Imágenes y recursos:** en `assets/`

---

## 🗂️ Estructura del repositorio
```
.
├─ index.html
├─ pages/
│  ├─ quienes-somos.html
│  ├─ servicios.html
│  ├─ casos-de-exito.html
│  └─ contacto.html
├─ src/
│  ├─ bootstrap-grid.css
│  ├─ bootstrap-grid.min.css
│  ├─ bootstrap-reboot.css
│  └─ bootstrap-reboot.min.css
├─ assets/
│  └─ (imágenes y otros recursos)
├─ .gitignore
├─ LICENSE
└─ README.md
```

> Si tu proyecto no usa la carpeta `pages/`, simplemente ignórala o elimínala.

---

## ▶️ Ejecución en local
Abrí `index.html` directamente en el navegador **o** levantá un servidor estático para recarga en vivo:

**Con Python**
```bash
python -m http.server 5500
```
**Con Node (npx)**
```bash
npx serve . -l 5500
```
Luego visitá: **http://localhost:5500**

---

## 🚀 Despliegue
**GitHub Pages**
1. Subí el repositorio.
2. En GitHub: *Settings → Pages → Build and deployment → Deploy from a branch*.
3. Elegí la rama `main` y la carpeta `/root`. Guardá los cambios.

**Vercel / Netlify**
- Importá el repositorio y seleccioná la carpeta raíz (no requiere build).

---

## ✅ Notas
- El proyecto usa **Bootstrap Grid/Reboot** local (no requiere `npm`).
- Estructura pensada para mantener *CSS/JS* en `src/` y *assets* en `assets/`.
- Podés agregar compresión de imágenes o minificación si lo necesitás.

---

## 🧾 Licencia
Este proyecto se distribuye bajo la licencia **MIT**.
