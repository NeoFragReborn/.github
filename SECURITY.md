# Politique de sécurité

Elle vaut pour tous les dépôts de l'organisation NeoFragReborn : le CMS
([neofrag](https://github.com/NeoFragReborn/neofrag)), ses addons à la carte
([extensions](https://github.com/NeoFragReborn/extensions)) et le
[bot Discord](https://github.com/NeoFragReborn/bot-discord).

## Versions qui reçoivent des correctifs

| Version | Correctifs de sécurité |
|---------|------------------------|
| la dernière version publiée | ✅ |
| toute version antérieure | ❌ — mettre à jour : *Administration → Monitoring* le fait en un clic, avec une sauvegarde avant d'écrire et un retour arrière si une étape échoue |
| < 1.0 (NeoFrag d'origine, alpha) | ❌ |

Un correctif de sécurité paraît dans une nouvelle version ; ses notes le signalent dans une section
**Sécurité**.

## Signaler une vulnérabilité

**N'ouvre pas d'issue publique** pour une faille de sécurité.

Privilégie le **signalement privé de GitHub** : onglet *Security* du dépôt concerné → *Report a
vulnerability*. À défaut, écris à **contact@neofrag-reborn.xyz**.

Merci d'inclure : la version, une description, les étapes de reproduction, l'impact estimé, et si
possible un correctif proposé. Nous accusons réception sous quelques jours et te tenons informé du
correctif. Merci de laisser un délai raisonnable de correction avant toute divulgation publique.

## Ce que fait le CMS pour se protéger

La posture de sécurité de NeoFrag Reborn — injection, sessions, jetons, en-têtes, mise à jour
vérifiée, limites connues — et ce qu'elle attend de l'hébergement sont décrits dans
[docs/securite.md](https://github.com/NeoFragReborn/neofrag/blob/main/docs/securite.md).
