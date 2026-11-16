# Contributing

**[English](#english)** | **[Español](#español)**

---

## English

Thanks for taking the time to improve these projects. This guide summarises the workflow shared by every repository on this account.

### Before you start

- Search open and closed issues to check whether the topic is already covered.
- For small changes (typos, documentation, a clear bug) open a pull request directly.
- For large changes, new features or design decisions, open an issue first to agree on the approach.

### Issues

Use the available templates. A good report includes:

- What you expected to happen and what actually happened.
- Exact steps to reproduce it.
- Version, operating system or browser, and any relevant configuration.
- Screenshots, stack traces or error messages, if they help.

Do not include personal data, credentials or sensitive information in an issue. For vulnerabilities, follow [`SECURITY.md`](SECURITY.md).

### Pull requests

1. Fork the repository, or create a branch if you have write access.
2. Use a descriptive branch name: `feat/short-name`, `fix/short-name`, `docs/short-name`.
3. Keep the change focused: one PR, one goal.
4. Update the documentation and tests that apply.
5. Check that the project starts and the tests pass before submitting.
6. Fill in the pull request template explaining the what and the why.

### Commits

A clear message in the imperative mood is appreciated. *Conventional Commits* is accepted:

```text
feat: add PDF export
fix: correct minimum length calculation
docs: update the installation section
```

Strict formatting is not required, but avoid messages such as `changes`, `update` or `fix`.

### Style and tests

- Respect the style and structure of the existing code.
- Do not reformat entire files in a functional change: it makes review harder.
- Add or update tests when the repository has them; explain how to run them in the PR.
- Do not commit binaries, installed dependencies (`node_modules`, `.venv`), real environment files or credentials.
- Bilingual READMEs keep both versions in sync when a change affects the documentation.

### License

By contributing you agree that your contribution will be published under the license of the corresponding repository (MIT, GPL-3.0 or Apache-2.0, as applicable). See the `LICENSE` file of each project.

---

## Español

Gracias por dedicar tiempo a mejorar estos proyectos. Esta guía resume el flujo de trabajo común a todos los repositorios de la cuenta.

### Antes de empezar

- Busca en los issues abiertos y cerrados si el tema ya está tratado.
- Para cambios pequeños (erratas, documentación, un bug claro) abre directamente un pull request.
- Para cambios grandes, nuevas funciones o decisiones de diseño, abre antes un issue para acordar el enfoque.

### Issues

Usa las plantillas disponibles. Un buen reporte incluye:

- Qué esperabas que ocurriera y qué ocurrió.
- Pasos exactos para reproducirlo.
- Versión, sistema operativo o navegador y cualquier configuración relevante.
- Capturas, trazas o mensajes de error, si ayudan.

No incluyas datos personales, credenciales ni información sensible en un issue. Para vulnerabilidades, sigue [`SECURITY.md`](SECURITY.md).

### Pull requests

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

### Estilo y pruebas

- Respeta el estilo y la estructura del código que ya existe.
- No reformatees archivos completos en un cambio funcional: dificulta la revisión.
- Añade o actualiza pruebas cuando el repositorio las tenga; indica cómo ejecutarlas en el PR.
- No subas binarios, dependencias instaladas (`node_modules`, `.venv`), archivos de entorno reales ni credenciales.
- Los READMEs bilingües mantienen las dos versiones sincronizadas cuando el cambio afecta a la documentación.

### Licencia

Al contribuir aceptas que tu aportación se publique bajo la licencia del repositorio correspondiente (MIT, GPL-3.0 o Apache-2.0, según el caso). Consulta el archivo `LICENSE` de cada proyecto.
