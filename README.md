# Mon Quartier Bouge — nouveau site

Refonte du site de l'association **Mon Quartier Bouge** (Paris 19e), réalisée dans le cadre du projet inter-spécialités **Digital Builders 2026-2027** à Digital Campus Paris, groupe GROUPE_5.

L'association valorise les quartiers populaires par la musique, le sport, l'audiovisuel et la culture. Son site actuel est un Wix dont le contenu tient presque entièrement sur la page d'accueil. Le nouveau site doit être modifiable par l'association elle-même, sans développeur.

## Équipe

| Spécialité | Prénom |
| --- | --- |
| DEV | Anouar |
| PTD | Léandro |
| MKTI | Rayan, Aurelie |
| AIA | Vadim, Raphael |
| WD | Yoann, Soraya, Hoài |
| MD | Maël, Karifala |

## Dates clés

| Date | Événement |
| --- | --- |
| 17/11/2026 | Coaching 1, dépôt partagé avec l'équipe pédagogique |
| 02/02/2027 à 23h59 | Remise du dossier |
| Avant le 22/02/2027 | Gel du code, date exacte à confirmer |
| 22/02/2027 | Soutenance |

## Stack

- **WordPress**, thème et extension développés pour ce projet.
- Le noyau WordPress, les uploads et les extensions tierces ne sont pas versionnés. Seuls le thème `mqb-theme` et l'extension `mqb-features` le sont.
- Hébergement : à définir, le coût doit être validé par le client.

## Contraintes du sujet à respecter

- Le client modifie ses contenus lui-même, avec un compte éditeur aux droits limités et aucun contenu écrit en dur dans le code.
- Au moins une fonctionnalité sur mesure développée pour ce client, dans `mqb-features`.
- Référencement soigné, en lien avec l'équipe MKTI.
- Interopérabilité avec les automatisations de l'équipe AIA, par webhooks ou API REST.
- Accessibilité WCAG niveau AA.
- Aucune vente en ligne et aucune transaction bancaire sur le site.
- Un README à jour et un guide du back-office remis à la livraison.

## Structure du dépôt

```
.
├── README.md                  ce fichier
├── CONTRIBUTING.md           règles de branches et de commits
├── .env.example              variables locales fictives
├── .gitignore
├── docs/
│   ├── guide-back-office.md  guide remis au client, à rédiger
│   └── reunions/             un compte rendu par rendez-vous client
└── wp-content/
    ├── themes/mqb-theme/     thème du site
    └── plugins/mqb-features/ fonctionnalités sur mesure
```


## Extensions tierces

Elles ne sont pas dans le dépôt, donc chaque ajout doit être noté ici.

| Extension | Rôle | Version |
| --- | --- | --- |
| Aucune Extention pour l'instant | | |

## Fonctionnalité sur mesure

À définir avec le client après le premier rendez-vous. Noter le choix et ses raisons dans le compte rendu de la réunion, dans `docs/reunions/`.

## Livrables

- [ ] README à jour
- [ ] Guide du back-office dans `docs/guide-back-office.md`
- [ ] Dépôt partagé avec l'équipe pédagogique
- [ ] Coût d'hébergement validé par le client
- [ ] Dossier remis le 02/02/2027 avant 23h59
- [ ] Code gelé avant la soutenance du 22/02/2027
