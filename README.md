# NOIR — Digital Agency

Copia estática importable en GitHub de la plantilla pública:

<https://template-noir-agency-dyl3.bolt.host>

## Contenido

- `index.html`: punto de entrada.
- `assets/index.js`: bundle JavaScript compilado de la aplicación.
- `assets/index.css`: estilos compilados.

## Ejecutar localmente

Se recomienda servirla mediante un servidor HTTP para que los módulos JavaScript funcionen correctamente:

```bash
python3 -m http.server 8080
```

Después abre <http://localhost:8080>.

## Publicar en GitHub Pages

1. Sube estos archivos a la raíz de un repositorio.
2. En GitHub, abre **Settings → Pages**.
3. En **Build and deployment**, selecciona **Deploy from a branch**.
4. Elige la rama principal y la carpeta `/ (root)`.

## Nota técnica

Esta es una exportación estática del sitio publicado. El servidor no expone el proyecto fuente original (componentes, configuración de build ni archivos editables), por lo que el JavaScript se conserva como bundle compilado. El badge de Bolt se retiró para que la copia sea independiente.

Verifica los derechos de uso de la plantilla antes de redistribuirla públicamente.
