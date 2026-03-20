# 💈 Barber Shop César — Sitio Web

Sitio web completo para Barber Shop César, Nuevo Ixcatlán, Oaxaca.

## 📁 Estructura del proyecto

```
barber-cesar-project/
├── index.html          ← Archivo principal del sitio
├── README.md           ← Este archivo
└── assets/
    └── images/         ← Aquí sube tus fotos
        ├── foto-cesar.jpg      (foto del barbero)
        ├── sobre-cesar.jpg     (foto sección "Sobre")
        └── hero-bg.jpg         (foto hero principal)
```

## 🚀 Cómo usar

1. Abre la carpeta en Visual Studio Code
2. Instala la extensión **Live Server** (si no la tienes)
3. Click derecho en `index.html` → **Open with Live Server**

## ✏️ Cosas que debes personalizar

### 1. Número de WhatsApp
Busca y reemplaza `5215200000000` por tu número real (con código de país, sin +)
Ejemplo: si tu número es 951 234 5678 → escribe `529512345678`

### 2. Links de redes sociales
Busca los siguientes IDs y cambia el `href="#"` por tu link real:
- `id="fb-hero"` → link de Facebook
- `id="ig-hero"` → link de Instagram
- `id="fb-vid"` → botón Facebook en sección Videos
- `id="ig-vid"` → botón Instagram en sección Videos
- `id="fb-footer"` → Facebook en footer
- `id="ig-footer"` → Instagram en footer

### 3. Videos
En la sección de videos, cada `.video-card` tiene un espacio para tu video.
Puedes incrustar videos de YouTube así:
```html
<iframe width="100%" height="100%" 
  src="https://www.youtube.com/embed/TU_VIDEO_ID" 
  frameborder="0" allowfullscreen>
</iframe>
```

### 4. Fotos
Reemplaza los bloques con clase `.img-ph-icon` por etiquetas `<img>`:
```html
<img src="assets/images/foto-cesar.jpg" alt="César Barbero" style="width:100%;height:100%;object-fit:cover">
```

### 5. Precios
Los precios están en la sección `#servicios`. Busca `$80`, `$100`, etc. y cámbialos.

## 🌐 Publicar el sitio (gratis)

Opciones gratuitas para publicar:
- **Netlify**: arrastra la carpeta a netlify.com/drop
- **GitHub Pages**: sube a GitHub y activa Pages
- **Vercel**: conecta tu repositorio

