# Modèles 3D libres — décor librairie et silhouette

Tous les fichiers de ce dossier viennent de sources **CC0 1.0** (domaine public), à part la police utilisée pour écrire sur le tableau, qui est sous licence OFL.

## Personnages (`clients-librairie.glb`, `silhouette-175.glb`)

- **Maya, Sam, Harper, Jordan** : bibliothèque 3D d'[Innerscene](https://www.innerscene.com/tools/library). Ce sont des personnages dérivés de MakeHuman / MPFB, sous **CC0 1.0** (licence consultée le 14 novembre 2026).
  Les fichiers d'origine portent eux-mêmes la mention : « Authored by Innerscene Corp (innerscene.com). Public domain: dedicated under CC0 1.0 Universal ».
- **Modifications pour le configurateur :**
  - Poses figées : lecture, main tendue vers un rayon, client à une table, client à la caisse, marche, debout.
  - Les poses partent des animations fournies (`Idle_Standing`, `Walk_Relaxed`), retouchées articulation par articulation, puis le maillage est figé dans la pose.
  - Maillage allégé : 114 000 triangles pour les 5 clients, 29 000 pour la silhouette.
  - Couleurs de certains vêtements changées.
  - Textures réduites : 512 px pour les clients, 1024 px pour la silhouette.
  - Supprimés : dents, cils, accessoire tenu en main.
- **Silhouette :** mise à l'échelle exacte de 175 cm au chargement.

## Décor Poly Haven (`decor-librairie.glb`, `parquet-hongrie.jpg`, `platre.jpg`)

Tous ces fichiers sont sous **CC0 1.0** ([licence Poly Haven](https://polyhaven.com/license)).

| Fichier / modèle | Source | Auteur(s) |
|---|---|---|
| Fauteuil lounge | [mid_century_lounge_chair](https://polyhaven.com/a/mid_century_lounge_chair) | Kuutti Siitonen |
| Fauteuil cuir | [modern_arm_chair_01](https://polyhaven.com/a/modern_arm_chair_01) | Vibrant Nordic |
| Ficus | [potted_plant_01](https://polyhaven.com/a/potted_plant_01) | Rico Cilliers |
| Plante en pot | [potted_plant_02](https://polyhaven.com/a/potted_plant_02) | Rico Cilliers |
| Suspension globe | [modern_ceiling_lamp_01](https://polyhaven.com/a/modern_ceiling_lamp_01) | James Ray Cock |
| Tableau craie | [standing_chalkboard_01](https://polyhaven.com/a/standing_chalkboard_01) | ParzivalCG |
| Parquet point de Hongrie | [herringbone_parquet](https://polyhaven.com/a/herringbone_parquet) | Jenelle van Heerden, Sergej Majboroda |
| Enduit des murs | [painted_plaster_wall](https://polyhaven.com/a/painted_plaster_wall) | Amal Kumar |

**Modifications :**
- Version 1K téléchargée via l'API officielle (`api.polyhaven.com/files/…`).
- Seule la texture de couleur est conservée, réduite à 512 px. Le parquet est en 1024 px, éclairci de 14 %. L'enduit est réduit à 512 px et teinté crème.
- Plantes allégées : 22 % et 45 % des triangles d'origine.
- Géométrie quantifiée (`KHR_mesh_quantization`).

**Tableau craie :** le texte « Nos coups de cœur » est écrit dans la texture avec la police [Caveat](https://fonts.google.com/specimen/Caveat) (Impallari Type, SIL Open Font License 1.1). La police elle-même n'est pas distribuée.
