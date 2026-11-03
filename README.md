# MUN.MARKET — dossier fournisseur

Formulaire en ligne qui permet aux **fournisseurs de MUN.MARKET** de constituer leur dossier : informations sur l'entreprise, pièces à transmettre, produits proposés et engagement.

## Contenu

- `index.html` : formulaire (HTML, CSS et JavaScript intégrés), envoyé en `POST` vers l'endpoint configuré dans `API_ENDPOINT`.
- `netlify.toml` : publication sur Netlify avec en-têtes de sécurité (CSP, `X-Frame-Options`, `nosniff`, `Permissions-Policy`).

## Lancer

Ouvrir `index.html` localement, ou déployer sur Netlify (publication du dossier racine). L'endpoint de réception des formulaires doit être configuré (par exemple Netlify Forms ou une fonction).

> Licence : aucune licence n'est déclarée dans ce dépôt (tous droits réservés par défaut).
