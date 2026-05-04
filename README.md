# [ MODO ANALISTA ]

Centro de mando personal para @modoanalista — app de organización de contenido, ideas, calendario y seguimiento de LeadRadar.

## Stack
- HTML + CSS + JS vanilla (single file)
- Firebase Firestore (persistencia de datos)
- Deployed en Vercel

## Estructura
```
/
├── index.html      # App completa
├── favicon.svg     # Ícono de la app
├── vercel.json     # Configuración de Vercel
└── README.md
```

## Deploy

### 1. Subir a GitHub
```bash
git init
git add .
git commit -m "feat: modoanalista app v1"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/modoanalista.git
git push -u origin main
```

### 2. Importar en Vercel
1. Ir a [vercel.com](https://vercel.com)
2. New Project → Import Git Repository
3. Seleccionar el repo `modoanalista`
4. Framework Preset: **Other**
5. Deploy

### 3. Firebase
El proyecto ya está conectado a Firebase proyecto `modo-analista`.
Asegúrate de que las reglas de Firestore permitan lectura/escritura.

## Funcionalidades
- 📊 Dashboard con protocolo del día dinámico
- 📅 Calendario de contenido con eventos editables
- 🎬 Cola de videos con guiones listos
- 💡 Banco de ideas por categoría
- 📡 Tracker de LeadRadar por fases
- 🎨 Branding editable (colores, tipografía, logo)
- 🌙 Tema claro / oscuro
- 💾 Sincronización con Firebase Firestore
