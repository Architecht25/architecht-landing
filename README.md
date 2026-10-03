# Architecht · Landing page

Page d'accueil statique de la société **Architecht**, qui édite des logiciels pour la
rénovation et la construction.

Présente les produits du portefeuille :

- **Ren0vate** : primes à la rénovation énergétique en Belgique et suivi des travaux
- **Cairn** : cockpit de l'architecte, du programme à la réception du chantier
- **urbanIA** : aide à la compréhension du cadre urbanistique d'un bien
- un outil à venir : métré vers liste de courses pour les entrepreneurs

## Structure

Un seul fichier, [`index.html`](index.html), avec CSS et HTML inline. Aucune
dépendance, aucun build.

- thème clair par défaut, thème sombre via `prefers-color-scheme` ou
  `data-theme="dark"` sur `<html>`
- mise en page responsive

## Utilisation

Ouvrir `index.html` dans un navigateur, ou le servir avec n'importe quel serveur
statique :

```bash
python3 -m http.server 8000
```

## Modifier le contenu

Tout le texte est directement dans `index.html`. Les couleurs de marque sont des
variables CSS définies dans `:root` (`--brand`, `--ren0vate`, `--carin`, `--urbania`,
etc.).
