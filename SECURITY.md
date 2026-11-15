# Política de seguridad

## Versiones soportadas

Se aplican correcciones de seguridad a la rama `main` y a la última release publicada de cada repositorio. Las versiones anteriores pueden no recibir actualizaciones; si usas una versión antigua, actualiza antes de reportar un problema.

## Cómo reportar una vulnerabilidad

**No abras un issue público** para vulnerabilidades de seguridad.

Usa uno de estos canales privados:

1. **GitHub Security Advisories**: en el repositorio afectado, pestaña **Security** → **Report a vulnerability**. Es el canal preferido porque permite coordinar la corrección y la divulgación.
2. **Email**: [albertoortixsanchez@gmail.com](mailto:albertoortixsanchez@gmail.com) con el asunto `[SECURITY] <repositorio>`, si no puedes usar el anterior.

Incluye, en la medida de lo posible:

- Repositorio y versión, release o commit afectado.
- Tipo de vulnerabilidad e impacto esperado.
- Pasos para reproducirla o una prueba de concepto mínima.
- Configuración necesaria (sistema operativo, navegador, permisos, variables de entorno).
- Mitigación o corrección que propongas, si la tienes.

## Qué está dentro del alcance

- Código fuente propio de los repositorios de esta cuenta.
- Configuración de GitHub Actions y flujos de publicación.
- Contraseñas, claves o tokens expuestos en el código o en el historial.

## Qué queda fuera del alcance

- Vulnerabilidades en dependencias, librerías o servicios de terceros. Repórtalas al proyecto original.
- Ataques de denegación de servicio, spam, ingeniería social o acceso físico.
- Problemas que requieran una configuración deliberadamente insegura o credenciales ya comprometidas por terceros.
- Buenas prácticas sin impacto real demostrable.

## Plazos orientativos

- **Acuse de recibo**: 72 horas laborables.
- **Evaluación inicial**: 7 días.
- **Corrección**: según la gravedad y la complejidad; se acordará contigo.
- **Divulgación**: coordinada, por defecto a los 90 días o antes si hay una corrección publicada.

Este es un proyecto personal mantenido en la medida de lo posible; estos plazos son un compromiso de buena fe, no un contrato de nivel de servicio.

## Reconocimiento

Si lo deseas, puedes ser acreditado en la release o en el aviso de seguridad. Indícalo en el reporte y con qué nombre o enlace quieres aparecer. No hay programa de recompensas económicas.
