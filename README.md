# 🍽️ SABOREA - Food Tours App

> Prototipo de aplicación móvil para reservar tours gastronómicos

![SABOREA Preview](https://images.unsplash.com/photo-1504674900247-0877df9cc836?w=800&h=400&fit=crop)

## 📱 Demo en Vivo

Visita la demo: **[tu-usuario.github.io/saborea](https://tu-usuario.github.io/saborea)**

## 🎯 Descripción

SABOREA es un prototipo funcional de aplicación móvil para reservar tours gastronómicos. La aplicación permite a los usuarios:

- 🔍 **Descubrir** tours gastronómicos por categorías
- 📍 **Explorar** rutas en un mapa interactivo
- 🎨 **Personalizar** su experiencia (dieta, grupo, horario)
- 💳 **Reservar** y pagar de forma segura
- 📲 **Recibir** confirmación con detalles del tour

## 🖼️ Pantallas

| Home | Detalle | Personaliza |
|:---:|:---:|:---:|
| Descubrimiento de tours | Info del tour y reseñas | Opciones de personalización |

| Mapa | Resumen | Confirmación |
|:---:|:---:|:---:|
| Ruta interactiva | Pago y resumen | Confirmación de reserva |

## 🛠️ Tecnologías

- **HTML5** - Estructura semántica
- **TailwindCSS** - Estilos utility-first (CDN)
- **JavaScript** - Interactividad
- **Leaflet.js** - Mapas interactivos
- **Material Symbols** - Iconografía
- **Plus Jakarta Sans** - Tipografía

## 📁 Estructura del Proyecto

```
saborea/
├── index.html          # Página de entrada (redirect)
├── home.html           # Home - Descubrimiento de tours
├── detalle.html        # Detalle del tour
├── personaliza.html    # Personalización del tour
├── mapa.html           # Mapa interactivo
├── resumen.html        # Resumen y pago
├── confirmacion.html   # Confirmación de reserva
└── README.md           # Documentación
```

## 🚀 Despliegue en GitHub Pages

### Opción 1: Desde la interfaz de GitHub

1. Sube los archivos a un repositorio de GitHub
2. Ve a **Settings** → **Pages**
3. En "Source", selecciona **Deploy from a branch**
4. Selecciona la rama `main` y la carpeta `/ (root)`
5. Haz clic en **Save**
6. ¡Tu sitio estará disponible en `https://tu-usuario.github.io/saborea`!

### Opción 2: Usando Git

```bash
# Inicializa el repositorio
git init

# Añade todos los archivos
git add .

# Haz el primer commit
git commit -m "🍽️ Initial commit - SABOREA Food Tours App"

# Añade el repositorio remoto
git remote add origin https://github.com/tu-usuario/saborea.git

# Sube los cambios
git push -u origin main
```

## 🎨 Paleta de Colores

| Color | Hex | Uso |
|-------|-----|-----|
| 🟠 Primary | `#f27f0d` | Acciones principales, acentos |
| ⬜ Background Light | `#f8f7f5` | Fondo claro |
| ⬛ Background Dark | `#221910` | Fondo oscuro, textos |

## 📱 Características

- ✅ Diseño mobile-first
- ✅ Soporte para dark mode
- ✅ Mapa interactivo con Leaflet.js
- ✅ Navegación fluida entre pantallas
- ✅ Formularios interactivos
- ✅ Animaciones y transiciones suaves
- ✅ Iconografía Material Symbols
- ✅ Imágenes optimizadas de Unsplash

## 🔗 Flujo de Navegación

```
Home → Detalle → Personaliza → Mapa ↔ Resumen → Confirmación
  ↑                              ↓
  └──────────────────────────────┘
```

## 📄 Licencia

Este proyecto es un prototipo de demostración con fines educativos.

---

Hecho con ❤️ y 🍽️
