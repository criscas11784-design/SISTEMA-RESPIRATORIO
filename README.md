# 🫁 Sistema Respiratorio Interactivo — PWA

Recurso educativo interactivo para Ciencia y Tecnología, Ciclo V (CNEB).
Funciona **offline** una vez instalado. Compatible con celulares Android y PC.

---

## 📁 Archivos incluidos

```
pwa_respiratorio/
├── index.html       ← Recurso principal (todo el juego)
├── manifest.json    ← Configuración de la app instalable
├── sw.js            ← Service worker (modo offline)
└── icons/
    ├── icon-192.png ← Ícono para pantalla de inicio
    └── icon-512.png ← Ícono splash screen
```

---

## 🚀 Cómo publicar en GitHub Pages (GRATIS)

1. Crea una cuenta en https://github.com (si no tienes)
2. Haz clic en **New repository** → ponle el nombre `respiratorio`
3. Marca la opción **Public** → clic en **Create repository**
4. Sube los 4 archivos (index.html, manifest.json, sw.js) y la carpeta icons/
5. Ve a **Settings → Pages → Branch: main → Save**
6. En 1-2 minutos tu URL será:
   `https://TU_USUARIO.github.io/respiratorio/`

---

## 📱 Cómo instalar la app en el celular (Android)

1. Abre la URL en Chrome
2. Aparecerá un banner "Añadir a pantalla de inicio" → toca **Instalar**
3. Si no aparece el banner: menú ⋮ → "Añadir a pantalla de inicio"
4. ¡La app aparecerá como ícono en el celular!
5. Funciona **sin internet** después de la primera carga ✅

---

## 💡 Para probar localmente (sin subir a internet)

```bash
# Opción 1 — Python (si tienes Python instalado)
cd pwa_respiratorio
python3 -m http.server 8000
# Abre: http://localhost:8000

# Opción 2 — VS Code
# Instala la extensión "Live Server" y abre index.html
```

> ⚠️ El service worker solo funciona con HTTPS o localhost.
> Abrir index.html directo como archivo NO activa el modo offline.

---

## 👨‍🏫 Datos del recurso

- **Área:** Ciencia y Tecnología
- **Ciclo:** V (5.° y 6.° grado)
- **Tema:** Sistema Respiratorio
- **Actividades:** 6 (Completar oraciones, Relacionar columnas, V/F, Selección múltiple, Ordenar recorrido, Datos curiosos)
- **Sistema de puntos:** Sí (con feedback inmediato)
- **Modo offline:** Sí ✅
