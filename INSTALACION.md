# 📦 Guía de Instalación del Repositorio en GitHub

## Opción 1: Interfaz Web de GitHub (Más Fácil) ⭐

### Paso 1: Crear el repositorio

1. Ve a https://github.com/new
2. Rellena los campos:
   - **Repository name**: `propuesta-vivienda-espana`
   - **Description**: `Propuesta para convertir 35.000M€ de deuda del FROB en 400.000 viviendas sociales con coste neto cero`
   - **Public** (marcado)
   - ❌ NO marques "Add README" (ya lo tenemos)
3. Click en **"Create repository"**

### Paso 2: Descargar todos los archivos

Yo te he generado todos los archivos. Tienes dos opciones:

**A) Descargar archivos uno por uno desde esta conversación:**
- README.md
- LICENSE
- Todos los archivos en `docs/`
- Todos los archivos en `datos/`
- Todas las imágenes en `graficos/`

**B) Pedir que te los empaquete en un ZIP** (más rápido)

### Paso 3: Subir archivos a GitHub

1. En tu nuevo repositorio vacío, click en **"uploading an existing file"**
2. Arrastra todos los archivos y carpetas
3. Escribe un commit message: `📦 Primera versión completa de la propuesta`
4. Click en **"Commit changes"**

¡Listo! Tu repositorio estará público en: `https://github.com/TU_USUARIO/propuesta-vivienda-espana`

---

## Opción 2: Línea de Comandos (Git) 💻

### Paso 1: Instalar Git (si no lo tienes)

**macOS:**
```bash
brew install git
```

**Linux (Ubuntu/Debian):**
```bash
sudo apt-get install git
```

**Windows:**
Descarga desde https://git-scm.com/download/win

### Paso 2: Configurar Git (primera vez)

```bash
git config --global user.name "Tu Nombre"
git config --global user.email "tu@email.com"
```

### Paso 3: Crear repositorio en GitHub

1. Ve a https://github.com/new
2. Nombre: `propuesta-vivienda-espana`
3. Click "Create repository"
4. **Copia la URL** que aparece (ej: `https://github.com/TU_USUARIO/propuesta-vivienda-espana.git`)

### Paso 4: Subir archivos desde tu ordenador

```bash
# 1. Ir a la carpeta donde descargaste todos los archivos
cd /ruta/donde/descargaste/archivos

# 2. Inicializar Git
git init

# 3. Añadir todos los archivos
git add .

# 4. Hacer el primer commit
git commit -m "📦 Primera versión completa de la propuesta"

# 5. Conectar con tu repositorio de GitHub
git remote add origin https://github.com/TU_USUARIO/propuesta-vivienda-espana.git

# 6. Subir todo a GitHub
git branch -M main
git push -u origin main
```

¡Listo!

---

## Opción 3: GitHub Desktop (Interfaz Gráfica) 🖱️

### Paso 1: Instalar GitHub Desktop

Descarga desde: https://desktop.github.com/

### Paso 2: Crear el repositorio

1. Abre GitHub Desktop
2. File → New Repository
3. Name: `propuesta-vivienda-espana`
4. Local Path: Donde quieres guardar los archivos
5. Click "Create Repository"

### Paso 3: Añadir archivos

1. Copia todos los archivos descargados a la carpeta del repositorio
2. GitHub Desktop detectará automáticamente los cambios
3. Escribe commit message: `📦 Primera versión completa`
4. Click "Commit to main"
5. Click "Publish repository"
6. Marca "Public"
7. Click "Publish repository"

¡Listo!

---

## 🌐 Activar GitHub Pages (Opcional pero Recomendado)

Convierte tu repositorio en una web pública:

1. Ve a tu repositorio en GitHub
2. Click en **Settings** (arriba derecha)
3. Scroll hasta **"Pages"** (menú izquierda)
4. En "Source" selecciona: **main branch**
5. Click **Save**

En 2-3 minutos tu propuesta estará en:
```
https://TU_USUARIO.github.io/propuesta-vivienda-espana/
```

El README.md se convierte automáticamente en la página principal.

---

## 📊 Estructura del Repositorio

Después de subirlo todo, tu repositorio tendrá esta estructura:

```
propuesta-vivienda-espana/
├── README.md                  ← Página principal
├── LICENSE                    ← Licencia CC BY-SA 4.0
├── docs/                      ← Documentación detallada
│   ├── 01-diagnostico-crisis.md
│   ├── 02-deuda-frob-sareb.md
│   ├── 03-analisis-financiero.md
│   ├── 04-gestion-externalizada.md
│   ├── 05-prevencion-corrupcion.md
│   ├── 06-marco-juridico.md
│   ├── 07-cronograma.md
│   ├── 08-referentes-internacionales.md
│   └── propuesta-completa.pdf
├── graficos/                  ← Todos los gráficos PNG
│   ├── cronograma-implementacion.png
│   ├── comparacion-vivienda-social-europa.png
│   ├── deficit-vivienda-provincias.png
│   ├── lotes-territoriales.png
│   ├── costes-frob-sareb-vs-nueva-estructura.png
│   └── beneficios-banca-2024.png
└── datos/                     ← Datos abiertos CSV
    ├── lotes_territoriales.csv
    ├── costes_detalle_frob_sareb.csv
    ├── beneficios_banca_2024.csv
    └── fuentes.md
```

---

## 🔄 Actualizar el Repositorio (después)

Cuando quieras añadir cambios:

```bash
# 1. Añadir archivos modificados
git add .

# 2. Hacer commit
git commit -m "✨ Descripción de los cambios"

# 3. Subir a GitHub
git push
```

O simplemente usa GitHub Desktop y haz click en "Push origin".

---

## ⚡ Consejos

1. **Activa las "Issues"** para que la gente pueda comentar
2. **Añade topics** al repositorio: `vivienda`, `espana`, `politica-publica`, `frob`, `sareb`
3. **Pin el repositorio** en tu perfil para darle visibilidad
4. **Comparte el enlace** en redes sociales con el hashtag #ViviendaDigna

---

## 🆘 ¿Problemas?

- **Error de permisos**: Asegúrate de estar autenticado en GitHub
- **Archivos grandes**: GitHub tiene límite de 100MB por archivo (no aplica a estos archivos)
- **Conflictos**: Si alguien más está editando, haz `git pull` antes de `push`

---

## 📞 Ayuda

Si necesitas ayuda:
1. **GitHub Docs**: https://docs.github.com/
2. **Video tutorial**: Busca "cómo subir proyecto a github" en YouTube
3. **Soporte GitHub**: https://support.github.com/

---

¡Éxito con tu repositorio! 🚀
