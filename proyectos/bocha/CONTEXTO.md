# Bocha

## Propósito
Pendiente de describir con el dueño del proyecto. No asumir funcionalidades sin revisar el código local o confirmar con el usuario.

## Ubicación del código
El código vive en la PC del usuario, fuera de este repositorio. Pedir/usar la carpeta local de Bocha en Codex cuando haya que editarlo.

## Stack e infraestructura conocida
- Repositorio de código: https://github.com/teico2000/bocha
- Deploy: Vercel; proyecto asociado al repositorio GitHub.
- Base de datos: Neon, proyecto llamado Bocha.
- Autenticación heredada: Firebase Auth (según el estado conocido del proyecto). No migrar ni quitar autenticación sin revisar el código y confirmar el alcance.
- Existe trabajo previo en el PR #1 de `teico2000/bocha` para integrar endpoints de Vercel con Neon; revisar su estado antes de continuar.

## Configuración y secretos
- Nunca escribir credenciales en este archivo ni en GitHub.
- Configuración conocida del despliegue previo: `DATABASE_URL`, `FIREBASE_PROJECT_ID`, `BOCHA_ADMIN_UID`. Confirmar valores y necesidad contra el código antes de configurar.
- Guardar secretos en variables de entorno de Vercel y en un archivo local ignorado por Git.

## Pendiente de completar
- Qué hace Bocha y quiénes lo usan.
- Ruta de la carpeta local en la PC.
- Stack, comandos de desarrollo y pruebas.
- Esquema actual de Neon y estado de migración/despliegue.
- Funcionalidades prioritarias y decisiones vigentes.
