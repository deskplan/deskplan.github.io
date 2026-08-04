# deskplan.github.io

Page d'accueil de **DeskPlan**, construite avec [Hugo](https://gohugo.io/) (sans thème externe : mise en page maison dans `layouts/`).

🌐 **En ligne : <https://deskplan.github.io/>**

## Aperçu local

```bash
hugo server        # http://localhost:1313
```

## Publication

Chaque `push` sur `main` déclenche [`.github/workflows/hugo.yml`](.github/workflows/hugo.yml) qui construit le site et le publie sur GitHub Pages.

## Structure

- `hugo.toml` — configuration + textes (`params`)
- `layouts/index.html` — la page (mise en page + styles inline)
- `content/_index.md` — titre de la page d'accueil
- `static/img/` — logo et visuels (source dans le dépôt [`brand`](https://github.com/deskplan/brand))
