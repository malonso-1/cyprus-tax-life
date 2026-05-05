## Git Push Rules

- **Push al branch siempre**: después de cada commit, pushear el branch a origin (`git push -u origin <branch>`) para tener backup en GitHub. No cuesta nada — Vercel solo se dispara en push a `master`.
- **PR a master**: acumular 20+ commits antes de abrir PR. Cada merge a master = 1 build Vercel.
- **No hacer PR solo con docs**: si todos los commits del branch son exclusivamente de `docs/` u otros directorios fuera del código fuente principal, no abrir PR solo — acumular junto con el próximo bloque de commits de código.
