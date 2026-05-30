# PremiumPlus / Billar tres bandas - MSI

Este proyecto genera un instalador Windows MSI de la app local de billar.

## Estructura esperada en GitHub

En la raíz del repositorio deben quedar:

- `.github/workflows/build-windows-msi.yml`
- `app/index.html`
- `src-tauri/`
- `package.json`
- `README_INSTRUCCIONES.md`

## Generar el MSI

1. Suba el contenido de esta carpeta al repositorio, no el ZIP.
2. Entre a la pestaña **Actions**.
3. Abra **Construir instalador Windows MSI**.
4. Pulse **Run workflow**.
5. Espere el chulo verde.
6. En **Summary**, descargue el artefacto **PremiumPlus-Billar-MSI**.
7. Descomprima el artefacto: adentro estará el `.msi`.

## Nota

El programa no está firmado digitalmente. Windows puede mostrar advertencias al instalar.
