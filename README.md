# Hub de proyectos

Este repositorio guarda **contexto e instrucciones**, no el código fuente de las aplicaciones.

## Proyectos

- [Bocha](proyectos/bocha/CONTEXTO.md)
- [Bot](proyectos/bot/CONTEXTO.md)
- [Fabri](proyectos/fabri/CONTEXTO.md)

## Flujo de trabajo con Codex

Cuando pidas un cambio:

1. Identificar el proyecto por nombre o preguntarte si no está claro.
2. Leer su `CONTEXTO.md` y revisar las instrucciones del repositorio local.
3. Usar la skill `find-skills` para buscar skills relevantes al pedido, revisar las candidatas y aplicar las que encajen.
4. Trabajar sobre la carpeta local del proyecto, manteniendo el código fuera de este hub.
5. Ejecutar las verificaciones apropiadas y explicar los cambios.
6. Para publicar, usar Vercel. Para persistencia, usar Neon cuando el proyecto lo requiera.
7. No copiar secretos ni valores de conexión a GitHub. Guardarlos en variables de entorno del entorno correspondiente.

## Cómo pedirme trabajo

Ejemplos:

- “En Bocha, agregá una página de contacto.”
- “En Bot, revisá el error de inicio.”
- “En Fabri, buscá skills para implementar autenticación y después armá el plan.”

Si Codex no tiene abierta la carpeta local del proyecto, indicá su ubicación o abrí esa carpeta en Codex. Este repositorio da el contexto, pero no contiene el código para editar.

## Ubicaciones conocidas en esta PC

- Bocha: `C:\Users\matte\Desktop\bocha`
- Bot: `C:\Users\matte\Desktop\Bot`
- Fabri: `C:\Users\matte\Desktop\fabri`
