# Règles de travail

Même si le dépôt est surtout alimenté par une seule personne, un historique lisible permet à l'équipe pédagogique de suivre l'avancement et de comprendre chaque choix.

## Branches

- `main` contient toujours une version qui fonctionne. On ne commit pas directement dessus.
- Une branche par tâche, nommée `type/sujet-court` : `feat/agenda-evenements`, `fix/menu-mobile`, `docs/guide-back-office`.
- On fusionne dans `main` par pull request, même seul : relire sa propre PR avant de fusionner évite beaucoup d'erreurs.

## Messages de commit

Format `type: ce qui change`, au présent, en français.

| Type | Quand l'utiliser |
| --- | --- |
| `feat` | nouvelle fonctionnalité |
| `fix` | correction d'un bug |
| `docs` | README, guides, commentaires |
| `style` | mise en forme sans changement de comportement |
| `refactor` | réorganisation du code sans changement visible |
| `chore` | configuration, dépendances, outils |

Exemple : `feat: ajoute le formulaire de candidature des talents`.

## À ne jamais commiter

- `wp-config.php`, `.env` et tout mot de passe ou clé d'API.
- Les exports de base de données, qui contiennent des données personnelles.
- Le noyau WordPress, les uploads et les extensions tierces.
- Les photos ou vidéos du client sans autorisation de droit à l'image.

## Avant d'ouvrir une pull request

- Le site se charge sans erreur PHP avec `WP_DEBUG` activé.
- Aucun contenu du client n'est écrit en dur dans le code.
- Les nouveaux éléments restent accessibles au clavier et avec des contrastes suffisants.
- Le README est mis à jour si l'installation ou la structure a changé.
