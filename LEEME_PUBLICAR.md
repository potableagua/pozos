# Publicar la App de Pozos en GitHub Pages

Cuenta: `potableagua` (la misma de la App Padrón). Repositorio: `pozos`.
Dirección final: **https://potableagua.github.io/pozos/**

## Primera vez (desde la computadora, en Chrome o Edge)

1. Descomprime el .zip. Debe quedar una carpeta con: `index.html`, `datos.js`, `jspdf.umd.min.js`, `manifest.webmanifest`, `sw.js`, tres íconos `.png` y la carpeta `fotos` (79 fotos).
2. Entra a github.com con la cuenta `potableagua` → botón **New** (repositorio nuevo).
   - Repository name: `pozos`
   - Público (**Public**). GitHub Pages gratis solo funciona con repositorios públicos.
   - Marca **Add a README file** y dale **Create repository**.
3. Dentro del repositorio: **Add file → Upload files**. Arrastra **todo el contenido** de la carpeta, incluida la carpeta `fotos` (no la carpeta que la contiene). Son 89 archivos; GitHub acepta hasta 100 por subida.
4. Abajo, **Commit changes**.
5. **Settings → Pages**. En "Build and deployment": Source = **Deploy from a branch**, Branch = **main** y carpeta **/ (root)** → **Save**.
6. Espera 1 a 3 minutos y abre https://potableagua.github.io/pozos/

## Instalarla en el celular

- **iPhone:** abrir la dirección en **Safari** → botón Compartir → **Agregar a pantalla de inicio**.
- **Android:** abrir en Chrome → menú ⋮ → **Instalar app** o **Agregar a la pantalla principal**.

Una vez abierta con internet, también funciona sin señal: guarda una copia de la app, y de cada foto que ya se haya visto.

## Cuando haya datos nuevos

1. Sube el `datos.js` nuevo, y las fotos nuevas en la carpeta `fotos` si las hay (Add file → Upload files; reemplaza el que tiene el mismo nombre).
2. Edita `sw.js` en GitHub (ícono de lápiz) y cambia la fecha de la línea `const VERSION = 'pozos-2026-11-20';` por la del día. Así los celulares descargan la versión nueva.
3. Commit changes. En 1 a 3 minutos queda publicada.

Nota: el repositorio es público. Cualquier persona con la dirección puede ver los datos, las coordenadas y las fotos.
