# Configurateur PLV 3D

Outil de simulation 3D de PLV (comptoirs, tourniquets, stop rayon, présentoirs de sol), à l'échelle réelle.

**Lien de l'outil :** https://simondelourme92.github.io/plv-configurateur/

Projet **séparé** de PLV WORLD (dépôt `plv-world`) : ne pas mélanger les deux.

## Organisation
| Dossier / fichier | Rôle |
|---|---|
| `index.html` | l'outil (code, interface, modèles de PLV) |
| `assets/` | textures bois, teintes, MDF couleurs (JPG) |
| `assets/librairie/` | (à venir) décor librairie : modèles 3D GLB, textures, sons |

## Règles
- **Jamais de base64** dans `index.html` : toute image ou modèle 3D va dans `assets/` et est chargé par son chemin.
- Assets uniquement sous licence libre (CC0 de préférence), crédités dans `CREDITS.md`.
- Rien de confidentiel dans ce dépôt (il est public) : pas de BAT, pas de créas d'éditeur. Les créas et couvertures s'importent dans l'outil et restent dans le navigateur.
- Une étape à la fois, testée sur le lien avant la suivante. Ne rien casser des modèles existants ni des sauvegardes.
- Interface en français, cotes en cm.

## Sauvegardes
Sur ce lien, les simulations sont gardées **dans le navigateur** (IndexedDB). Pour les transférer : « Mes simulations » → « Tout exporter (.json) », puis « Importer un .json » sur l'autre poste ou l'autre version.

## Feuille de route
1. ✅ Mise en ligne sur GitHub Pages, assets séparés.
2. Mise à jour de three.js (r128 → version récente) : lumière réaliste, ombres douces, matières bois plus fines.
3. Décor librairie réaliste : modèles 3D libres (meubles, tables, caisse, vitrine), parquet, éclairage, livres d'ambiance instanciés, emplacements PLV (caisse, table, allée, vitrine), vue client à 1,60 m. Chargé uniquement quand on choisit le décor Librairie.
4. Performance : modèles compressés, chargement à la demande.
