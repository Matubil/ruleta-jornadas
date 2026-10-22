# Ruleta

Ruleta de escritorio para sortear opciones. Funciona sin internet.

## Qué hace

- **Opciones:** una por línea, o cargadas desde un `.txt` / `.csv`. Botones para mezclar, ordenar A-Z, quitar repetidos, guardar y vaciar la lista.
- **Girar:** clic en la ruleta, botón "Girar" o `Ctrl+Enter`. Sonido y confeti al terminar.
- **Qué hacer con el ganador:** preguntar si se elimina, eliminarlo siempre o no eliminarlo nunca.
- **Resultados:** historial de ganadores, se puede copiar o guardar.
- **Personalizar:** colores de los gajos (con paletas predefinidas), texto, centro (imagen, texto y colores), puntero, borde, duración del giro y fondo de la app (color o imagen).
- Todo se guarda solo. La configuración se puede exportar e importar como `.json`.
- `F11` pantalla completa.

## Usarla

Descargá `Ruleta.exe` de la última versión en [Releases](../../releases) y abrilo. Es un único archivo: no hace falta instalar nada ni tener internet. La primera vez puede tardar unos segundos en abrir.

## Desarrollo

Requiere [Node.js](https://nodejs.org).

```bash
npm install
npm start        # abre la app
npm run build    # genera dist/Ruleta.exe (un único ejecutable portable)
```

Toda la app está en `index.html`; `main.js` solo abre la ventana de Electron.
