# BASE — Perfil GitHub (mcherif004)

Repo especial: el README se muestra en https://github.com/mcherif004

## Contenido

| Carpeta / archivo | Qué es |
|-------------------|--------|
| `README.md` | Perfil público, proyectos, bio |
| `cv/*.pdf` | CVs para reclutadores (TECH, GLOBAL, EDITOR + EN/FR) |
| `docs/PIN-REPOS-GITHUB.md` | Cómo fijar repos |

## Regenerar CVs y subir

```powershell
cd C:\Users\mosta\Desktop\Importante\trabajo
python build_cv_pdf.py

cd C:\Users\mosta\Desktop\Work\Edit
.\sync-profile-github.ps1
```

Eso copia PDFs a `cv/` y hace push a GitHub.

## Editar texto del perfil

1. Cambia `README.md` en esta carpeta (o copia desde `Work/Edit/github-profile-README.md` — **no** uses el script push-todos para sobrescribir README sin querer).
2. `git add README.md && git commit -m "docs: update profile" && git push`

## Checklist tras actualizar proyectos

- [ ] Enlaces a repos en tabla Featured siguen siendo correctos
- [ ] CVs PDF actualizados si cambió experiencia o proyectos
- [ ] Bio en **Settings → Profile** = misma línea que README
- [ ] Pins: multistream, yt-downloader, job-tracker, mcherif004

## Qué no va aquí

- Código de aplicaciones (van en sus repos)
- jobauto (privado, sin enlace)
