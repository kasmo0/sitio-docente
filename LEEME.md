# Sitio docente · Aldo Villanueva (GitHub Pages)

## Archivos
- index.html — página de inicio con las 4 secciones
- ies1sv.html — sección 1: grupo, horario y accesos
- profesores.html / alumnos.html / personal.html — páginas protegidas (contenido cifrado)
- material.html, anexos.html — catálogos públicos de recursos
- bitacora.html — bitácora de seguimiento (versión local, datos en el navegador)
- generar.html — herramienta para cambiar contraseñas o el contenido de las páginas protegidas
- estilo.css — estilos compartidos

## Contraseñas iniciales (cámbialas antes de compartir)
- Profesores: Academia2026
- Alumnos: IES1SV2026
- Uso Personal: Tutoria2026

## Cómo cambiar una contraseña o actualizar una página protegida
1. Abre generar.html en tu navegador (funciona sin internet, todo ocurre en tu equipo).
2. Elige la página, edita el contenido (HTML) y escribe la contraseña nueva.
3. Descarga el archivo generado y súbelo al repositorio reemplazando al anterior.
El contenido se cifra con AES-256-GCM (clave derivada con PBKDF2, 250 000 iteraciones): sin la contraseña no puede leerse ni desde el código fuente.

## Publicar en GitHub Pages
1. Sube todos los archivos de esta carpeta a la raíz del repositorio (o a la carpeta que uses).
2. En Settings → Pages elige la rama y la carpeta. El sitio quedará en https://TU-USUARIO.github.io/TU-REPO/
3. Comparte la contraseña de alumnos con el grupo y la de profesores con la academia; nunca la de Uso Personal.

## Límites que conviene conocer
- El login es una contraseña compartida por perfil; no hay cuentas individuales.
- Quien tenga la contraseña ve todo el contenido de esa página; no publiques datos individuales de alumnos (calificaciones, faltas, seguimiento) en las páginas protegidas. Esos datos viven en la Bitácora, que solo abre el administrador.
