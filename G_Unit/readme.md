# Proyecto Ansible - Guillermo Alberto Martin Palacios

## Información Personal
- **Nombre:** Guillermo Alberto Martin Palacios
- **Cargo:** INGENIERO INFRAESTRUCTURA TI
- **Ubicación:** Panamá

## Propósito
Este proyecto está orientado a la automatización de tareas en servidores Linux y Windows utilizando Ansible, con enfoque en cumplimiento normativo, seguridad y gestión de configuraciones.

## Módulos Usados

### Linux
- `ansible.builtin.lineinfile`: Para asegurar que líneas específicas estén presentes en archivos de configuración.

## Consideraciones para Linux
- Verificar que los archivos de configuración existan antes de aplicar cambios.
- Usar rutas absolutas en formato Linux (`/etc/archivo.conf`).
- Validar permisos de escritura del usuario remoto.
- Utilizar expresiones regulares con cuidado para evitar reemplazos no deseados.
- Confirmar que el archivo no esté siendo gestionado por otro sistema (como `cloud-init` o herramientas de configuración externas).
- Realizar pruebas en entornos de desarrollo antes de aplicar en producción.

## Seguridad y Cumplimiento
Este proyecto se alinea con los esfuerzos de Banistmo en la lucha contra el lavado de activos, financiación del terrorismo y proliferación de armas de destrucción masiva.

## Contacto
- **Correo:** guillermo.martin@banistmo.com
