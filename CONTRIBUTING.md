# Cómo contribuir

Gracias por dedicar tiempo a mejorar estos proyectos. Esta guía resume el flujo de trabajo común a todos los repositorios de la cuenta.

## Antes de empezar

- Busca en los issues abiertos y cerrados si el tema ya está tratado.
- Para cambios pequeños (erratas, documentación, un bug claro) abre directamente un pull request.
- Para cambios grandes, nuevas funciones o decisiones de diseño, abre antes un issue para acordar el enfoque.

## Issues

Usa las plantillas disponibles. Un buen reporte incluye:

- Qué esperabas que ocurriera y qué ocurrió.
- Pasos exactos para reproducirlo.
- Versión, sistema operativo o navegador y cualquier configuración relevante.
- Capturas, trazas o mensajes de error, si ayudan.

No incluyas datos personales, credenciales ni información sensible en un issue. Para vulnerabilidades, sigue [`SECURITY.md`](SECURITY.md).

## Pull requests

1. Haz un fork del repositorio o crea una rama si tienes permisos.
2. Crea una rama descriptiva: `feat/nombre-corto`, `fix/nombre-corto`, `docs/nombre-corto`.
3. Mantén el cambio centrado: un PR, un objetivo.
4. Actualiza la documentación y los tests que correspondan.
5. Comprueba que el proyecto arranca y que las pruebas pasan antes de enviarlo.
6. Rellena la plantilla del pull request explicando el qué y el porqué.

### Commits

Se agradece un mensaje claro y en imperativo. Se acepta el formato de *Conventional Commits*:

```text
feat: añade exportación a PDF
fix: corrige el cálculo de la longitud mínima
docs: actualiza la sección de instalación
```

No hace falta un formato estricto, pero evita mensajes como `cambios`, `update` o `fix`.

## Estilo y pruebas

- Respeta el estilo y la estructura del código que ya existe.
- No reformatees archivos completos en un cambio funcional: dificulta la revisión.
- Añade o actualiza pruebas cuando el repositorio las tenga; indica cómo ejecutarlas en el PR.
- No subas binarios, dependencias instaladas (`node_modules`, `.venv`), archivos de entorno reales ni credenciales.
- Los READMEs bilingües mantienen las dos versiones sincronizadas cuando el cambio afecta a la documentación.

## Licencia

Al contribuir aceptas que tu aportación se publique bajo la licencia del repositorio correspondiente (MIT, GPL-3.0 o Apache-2.0, según el caso). Consulta el archivo `LICENSE` de cada proyecto.
