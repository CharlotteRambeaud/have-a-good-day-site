# have-a-good-day-site

Le site public de l'application : politique de confidentialité et support.
Il vit dans un dépôt à part pour que le code de l'app reste privé tout en
profitant de GitHub Pages, gratuit sur les dépôts publics uniquement.

## Avant de publier

Remplacer `ADRESSE-A-COMPLETER` par une vraie adresse de contact, dans
`confidentialite.html`, `privacy.html` et `support.html`.

## Publier

    gh repo create have-a-good-day-site --public --source=. --remote=origin --push

Puis, sur GitHub : Settings → Pages → Source « Deploy from a branch »,
branche `main`, dossier `/root`.

Les adresses seront alors :

- confidentialité (fr) : `https://<compte>.github.io/have-a-good-day-site/confidentialite.html`
- privacy (en) : `https://<compte>.github.io/have-a-good-day-site/privacy.html`
- support : `https://<compte>.github.io/have-a-good-day-site/support.html`
