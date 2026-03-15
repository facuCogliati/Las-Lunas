# 🌙 Las Lunas — Sitio Web

Proyecto Astro.js para el sitio web de Las Lunas Hospedaje para Mascotas.

## Requisitos

- Node.js 18+
- npm o pnpm

## Instalación

```bash
npm install
```

## Desarrollo

```bash
npm run dev
# Abre http://localhost:4321
```

## Producción

```bash
npm run build
npm run preview
```

## Estructura

```
src/
├── components/
│   ├── Header.astro       # Preheader + Nav sticky
│   ├── Hero.astro         # Hero con video de fondo
│   ├── Conocenos.astro    # Sección quiénes somos
│   ├── Instalaciones.astro# Fotos y features del predio
│   ├── Servicios.astro    # Cards de todos los servicios
│   ├── Testimonios.astro  # Carrusel de testimonios
│   ├── Contacto.astro     # Formulario + métodos de contacto
│   └── Footer.astro       # Footer + botón WhatsApp flotante
├── layouts/
│   └── Layout.astro       # Layout base con scripts globales
├── pages/
│   ├── index.astro        # Página principal
│   └── galeria.astro      # Galería de fotos
└── styles/
    └── global.css         # Variables, botones, utilidades
```

## Personalización pendiente

### Imágenes y video
Reemplazar las imágenes de placeholder por las reales:

1. **Video hero** — subir a `/public/video/institucional.mp4`  
   O actualizar la `src` en `Hero.astro` con la URL de tu servidor.

2. **Fotos Conocenos** — Las del Google Drive:  
   `https://drive.google.com/drive/folders/1cncRRFHyKil3Czw4UODAIWdFAuyl5Zeo`  
   Descargarlas y subirlas a `/public/images/conocenos/`.

3. **Fotos Instalaciones** — Las del Google Drive:  
   `https://drive.google.com/drive/folders/1vSqgVBtCkioSBiVIXGaYtdQF9kusdRnn`  
   Subirlas a `/public/images/instalaciones/`.

4. **Foto adiestramiento** (Card D):  
   `https://drive.google.com/file/d/1PuD3h2bmSUsGT3GxdfnZfLG7OH6izvJp`

5. **Fotos traslado internacional** (Card E):  
   `https://drive.google.com/drive/folders/1jSmyq_7MLg0hIFu56H2gyl11mFLoaUmS`

6. **Logo Las Lunas** — reemplazar el emoji 🌙 con el logo real en `Header.astro` y `Footer.astro`.

### Video institucional
El YouTube embed ya está integrado con el link `https://youtu.be/uVR_vt05V0`.

### Deploy recomendado
- **Vercel** o **Netlify** — soporte nativo de Astro, deploy automático desde GitHub.

## Paleta de colores

| Variable | Valor |
|---|---|
| `--green` | `#2d6a4f` |
| `--green-light` | `#40916c` |
| `--green-pale` | `#d8f3dc` |
| `--green-dark` | `#1b4332` |
| `--accent` | `#52b788` |

## Links importantes

- Instagram: https://www.instagram.com/hospedaje.laslunas/
- WhatsApp: https://api.whatsapp.com/send?phone=5491150968576
- Mail: info@las-lunas.com.ar
- Requisitos sanitarios: https://docs.google.com/document/d/1nPaS-Ibv_P7T9CQX2_zNQY6iKw26Yw7o2Eo9KqxqQtQ/edit
- LATAM Pet Transport: https://www.latampettransport.com/es/
