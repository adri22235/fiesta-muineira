# Fiesta Muiñeira

Mini web estática (HTML + Tailwind CDN). Incluye:
- Tema claro/oscuro con persistencia
- Botones Play/Stop para un audio local (`music/muineira.mp3`)
- Confeti en canvas y mini ecualizador animado

## Estructura
```
.
├── index.html
└── music/
    └── muineira.mp3    # (pon tu archivo aquí)
```

## Deploy rápido

### Opción A: GitHub Pages
1. Crea un repositorio nuevo (por ejemplo `fiesta-muineira`).
2. Sube `index.html` y la carpeta `music/` (con tu `muineira.mp3`).
3. En **Settings → Pages**:
   - **Source**: *Deploy from a branch*
   - **Branch**: `main` y carpeta `/ (root)`
4. La web quedará en: `https://TU_USUARIO.github.io/fiesta-muineira/`.

### Opción B: Vercel
1. Importa el repositorio en https://vercel.com/new.
2. Framework: *Other* (estático).
3. Build & Output: (vacío), **Output Directory**: `.` (raíz).

### Opción C: Netlify
1. Arrastra la carpeta al panel de https://app.netlify.com/drop.
2. O conecta tu repo y despliega como sitio estático.
