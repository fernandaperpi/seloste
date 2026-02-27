# Seloste – Servicios Logísticos del Sureste

Sitio web oficial de **Seloste**, empresa de mensajería, paquetería y distribución logística con cobertura en el Sureste de México. Fundada en Mérida, Yucatán en 2001.

## 🚀 Deploy en Netlify desde GitHub

### Paso 1 – Subir a GitHub
```bash
git init
git add .
git commit -m "Initial commit - Seloste website"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/seloste.git
git push -u origin main
```

### Paso 2 – Conectar con Netlify
1. Ve a [app.netlify.com](https://app.netlify.com) → **Add new site** → **Import an existing project**
2. Selecciona **GitHub** y autoriza el acceso
3. Elige el repositorio `seloste`
4. Configuración de build:
   - **Base directory**: *(dejar vacío)*
   - **Build command**: *(dejar vacío)*
   - **Publish directory**: `.`
5. Clic en **Deploy site** ✅

Netlify detectará automáticamente el `netlify.toml` y aplicará la configuración.

### Opción alternativa – Drag & Drop
1. Ve a [app.netlify.com](https://app.netlify.com)
2. Arrastra esta carpeta directamente al área de deploy

---

## 📁 Estructura del proyecto

```
seloste/
├── index.html       # Página principal completa
├── netlify.toml     # Configuración Netlify (redirects, headers, cache)
├── .gitignore       # Archivos ignorados por Git
└── README.md        # Este archivo
```

## ✨ Características del sitio

- ✅ HTML5 + CSS3 + JS vanilla — sin frameworks ni build steps
- ✅ Tipografía: Mulish (títulos) + Plus Jakarta Sans (cuerpo)
- ✅ Mapa interactivo del Sureste con Leaflet.js
- ✅ Acordeón de cobertura por estado
- ✅ Menú responsive con hamburger mobile
- ✅ Animaciones de scroll reveal
- ✅ Ticker animado de servicios
- ✅ Secciones: Hero · Nosotros · Misión/Visión/Valores · Servicios · Proceso · Cobertura+Mapa · Ventajas · Clientes · Flota · Contacto
- ✅ Listo para Netlify y GitHub Pages

## 📞 Contacto Seloste

| Canal | Datos |
|-------|-------|
| Teléfono | 999 947 8642 / 999 494 8187 |
| Email | mensajeria@seloste.net |
| Web | [seloste.net](https://seloste.net) |
| Facebook | [/SELOSTE](https://www.facebook.com/SELOSTE) |
| Dirección | C. 39 530a, Centro, 97000 Mérida, Yucatán |
