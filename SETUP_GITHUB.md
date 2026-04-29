# 📝 Cómo crear el repo en GitHub desde el navegador

## Paso 1: Crear el repositorio
1. Ve a [github.com/new](https://github.com/new)
2. Repository name: `iker-repo`
3. Public ✓
4. Create repository

## Paso 2: Crear manifest.json
1. Click en "Add file" → "Create new file"
2. Nombre: `manifest.json`
3. Pega esto:
```json
{
  "name": "Iker Repo",
  "description": "Apps web completas estilo marketplace oficial",
  "maintainer": {
    "name": "Iker",
    "website": "https://github.com/iker"
  },
  "version": "1.0.0"
}
```
4. Commit

## Paso 3: Crear list.json
1. Add file → Create new file
2. Nombre: `list.json`
3. Pega el contenido de list.json (abajo)
4. Commit

## Paso 4: Crear carpetas de apps
Para cada app, haz esto:
1. Add file → Create new file
2. Escribe en el nombre: `apps/social.discord/app.zip` (nota: GitHub crea la carpeta automáticamente)
3. Si no te deja, añade un archivo temporal: `apps/social.discord/.gitkeep`

## Paso 5: Subir los ZIP
1. Ve a tu repo → Upload files
2. Arrastra los ZIP desde: `iker-repo/apps/*/app.zip`

O más fácil: desde Replit (ver Opción A arriba)
