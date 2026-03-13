# ☕ Alimenta Almacén y Café — Landing Page

Landing page mobile-first para **Alimenta Almacén y Café**, diseñada para visitantes que llegan desde Instagram. Construida con HTML, CSS y JavaScript vanilla — sin dependencias ni frameworks.

[![Instagram](https://img.shields.io/badge/Instagram-%40alimentaalmacenycafe-E4405F?logo=instagram&logoColor=white)](https://www.instagram.com/alimentaalmacenycafe)

---
## 🚀 Uso

Este proyecto es un **único archivo HTML** autocontenido. No requiere instalación.

```bash
# Clonar el repositorio
git clone https://github.com/tu-usuario/alimenta-cafe.git

# Abrir en el navegador
open alimenta-cafe.html
```

Para publicar, simplemente subí `alimenta-cafe.html` a cualquier servicio de hosting estático.

---

## ✏️ Personalización

Antes de publicar, actualizá estos valores en el archivo `alimenta-cafe.html`:

### 1. Número de WhatsApp
Buscá todas las apariciones de `549XXXXXXXXXX` y reemplazalas con el número real (código de país + área + número, sin espacios ni guiones):

```html
<!-- Ejemplo para Argentina, Buenos Aires -->
href="https://wa.me/5491123456789"
```

### 2. Link de Google Maps
Reemplazá el `href` del botón "Cómo llegar":

```html
href="https://maps.app.goo.gl/TU-LINK-REAL"
```

### 3. Dirección y horarios
En la sección `#location`, actualizá el texto de los `.location-item` con la dirección y horarios reales.

### 4. Fotos propias
Las imágenes actuales son placeholders de Unsplash. Para usar fotos propias:

```html
<!-- Reemplazá la URL por la ruta a tu imagen -->
<img src="./fotos/hero.jpg" alt="Interior del café">
```

> Recomendamos usar imágenes en formato `.webp` para mejor rendimiento.

---

## 🎨 Diseño

### Paleta de colores

| Variable | Color | Uso |
|----------|-------|-----|
| `--cream` | `#FAF6F0` | Fondo principal |
| `--beige` | `#F2EAD8` | Fondo secciones alternas |
| `--coffee-light` | `#C4986A` | Acentos y highlights |
| `--coffee` | `#8B5E3C` | Color principal café |
| `--coffee-dark` | `#5C3D2E` | Títulos y elementos fuertes |
| `--espresso` | `#2C1810` | Fondos oscuros (footer, galería) |

### Tipografía
- **Playfair Display** — Títulos y display (Google Fonts)
- **Lato** — Cuerpo de texto y UI (Google Fonts)

### Características técnicas
- ✅ Mobile-first (optimizado para 375px en adelante)
- ✅ Scroll suave con `scroll-behavior: smooth`
- ✅ Animaciones de aparición al hacer scroll (Intersection Observer)
- ✅ Efecto parallax/zoom en el hero
- ✅ Navbar con efecto blur al hacer scroll
- ✅ Sin dependencias externas (solo Google Fonts)
- ✅ Compatible con todos los navegadores modernos

---

## 🌐 Deploy

### GitHub Pages
1. Subí el repositorio a GitHub
2. Ir a **Settings → Pages**
3. Source: `Deploy from a branch` → `main` → `/ (root)`
4. La página quedará disponible en `https://tu-usuario.github.io/alimenta-cafe/alimenta-cafe.html`

> 💡 Para que abra directo como `/`, renombrá el archivo a `index.html`.

### Netlify / Vercel
Arrastrá la carpeta del proyecto al dashboard de [Netlify Drop](https://app.netlify.com/drop) y listo.

---

## 📬 Contacto

- Instagram: [@alimentaalmacenycafe](https://www.instagram.com/alimentaalmacenycafe)
- WhatsApp: _(actualizar con número real)_

---

*Hecho con ♥ para Alimenta Almacén y Café*