# Portal de Herramientas — DuocUC Educación Continua

Portal centralizado con las herramientas de automatización y procesamiento de datos de Coordinación Académica.

---

## 🔗 Acceso

Una vez desplegado en GitHub Pages, el portal estará disponible en:
```
https://TU_USUARIO.github.io/portal-ec-duocuc/
```

---

## 🛠️ Herramientas incluidas

| Herramienta | Archivo | Descripción |
|---|---|---|
| Sistema de Gestión de Asistencia | `SistemaGC.html` | Procesa CSVs de Blackboard y genera archivos GC con % asistencia |
| Cruzador de Datos | `cruzador.html` | BUSCARV visual entre dos archivos Excel |
| Generador de Declaraciones Juradas | `generador_dj.html` | Extrae datos de PDFs y genera documentos Word |

---

## 📁 Estructura del repositorio

```
portal-ec-duocuc/
│
├── index.html                ← Portal principal (este archivo es la entrada)
├── SistemaGC.html
├── cruzador_datos.html
├── generador_dj.html
└── README.md
```

---

## 🚀 Cómo publicar en GitHub Pages

### Paso 1 — Crear el repositorio
1. Ve a [github.com](https://github.com) e inicia sesión
2. Haz clic en **New repository**
3. Nómbralo: `portal-ec-duocuc`
4. Déjalo en **Public** (necesario para GitHub Pages gratuito)
5. Haz clic en **Create repository**

### Paso 2 — Subir los archivos
1. En la página del repositorio, haz clic en **Add file → Upload files**
2. Arrastra todos los archivos HTML + este README
3. Escribe un mensaje como `"Versión inicial del portal"` y haz clic en **Commit changes**

### Paso 3 — Activar GitHub Pages
1. Ve a **Settings** (en el menú del repositorio)
2. En el panel izquierdo, haz clic en **Pages**
3. En "Source", selecciona **Deploy from a branch**
4. En "Branch", selecciona `main` y la carpeta `/ (root)`
5. Haz clic en **Save**

GitHub tardará 1–2 minutos en publicar. Luego verás el link en esa misma página.

---

## 🔄 Cómo actualizar una herramienta

1. Ve al repositorio en GitHub
2. Haz clic en el archivo que quieres actualizar (ej: `SistemaGC.html`)
3. Haz clic en el ícono del lápiz (✏️ Edit)
4. Pega el contenido nuevo
5. Haz clic en **Commit changes**

En menos de 1 minuto el portal ya tiene la versión actualizada para todo el equipo.

---

## 🔒 Privacidad

Ninguna herramienta sube archivos a internet. Todo el procesamiento ocurre en el navegador del usuario.

---

*Desarrollado por Coordinación Académica — DuocUC Educación Continua · 2026*
