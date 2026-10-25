# mate-retos

Juego de mate para jugar en la tele con el control (flechas, OK y Back). Es un proyecto de la casa: el código vive aquí y sus pendientes van al `TASKS.md` de Shared-Family con el prefijo `MAT`, nunca a SyntetIA.

## Cómo se trabaja
- Es un solo `index.html`, sin build ni dependencias. Se prueba abriéndolo en Chrome y moviéndose solo con las flechas y Enter.
- Se publica en GitHub Pages desde `main`. Cada merge a `main` actualiza https://mauai9.github.io/mate-retos/ en uno o dos minutos.
- El repo es público. No se suben nombres, fotos ni datos de la familia.
- El avance vive en el localStorage del navegador (`mate-retos`). Un cambio al estado tiene que seguir leyendo lo que ya está guardado.
- `config.xml` e `icon.png` son para instalarlo como app de Tizen en la tele Samsung. En el navegador no se usan.
