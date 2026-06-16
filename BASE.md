# BASE — Perfil GitHub (local)

Repo público: https://github.com/mcherif004/mcherif004

## Contenido en GitHub

| Archivo | Uso público |
|---------|-------------|
| `README.md` | Perfil, proyectos, contacto |
| `cv/CV_ES.pdf` · `cv/CV_EN.pdf` | CVs para reclutadores |

**No subir a GitHub:** `BASE.md` (este archivo), rutas locales, instrucciones de mantenimiento.

## Regenerar CVs y sincronizar

```powershell
cd C:\Users\mosta\Desktop\Importante\trabajo\cv
python build_cv_pdf.py

cd C:\Users\mosta\Desktop\Work\Edit
.\sync-profile-github.ps1
```

## Editar perfil

1. Cambia `README.md` en esta carpeta.
2. `git add README.md cv/*.pdf && git commit -m "docs: update profile" && git push`

## Checklist

- [ ] Enlaces de proyectos correctos en README
- [ ] CVs PDF actualizados
- [ ] Bio en GitHub Settings = misma línea que README
- [ ] Pins: `multistream-upload`, `yt-downloader`, `job-tracker`, `mcherif004`
