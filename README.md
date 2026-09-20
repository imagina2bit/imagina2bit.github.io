# iMagina2:Bit — versión HTML Legacy

Web Pública del Proyecto iMagina2:Bit. La interfaz está construida con HTML3, CSS y JavaScript vanilla.

## Estructura
- `index.html`: página principal.
- `css/styles.css`: estilos.
- `js/app.js`: funcionalidad.
- `data/data.json`: datos editables del proyecto.

## Uso
Por las restricciones de seguridad de los navegadores, `fetch()` puede bloquear la lectura de `data/data.json` si se abre `index.html` directamente con `file://`. Se recomienda servir la carpeta con cualquier servidor web estático, por ejemplo:

```bash
python3 -m http.server 8000
```

Después ejecuta un navegador desde el puerto activo. Por ejemplo: `http://localhost:8000/`.
