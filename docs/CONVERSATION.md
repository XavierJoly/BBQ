# Historique de conception — BBQ Pod

Ce document migre les décisions structurantes prises pendant la conversation de conception du projet.

## 1. Point de départ

Le projet est inspiré des BBQ Pods / outdoor kitchens à grande façade relevable, notamment AFA Stainless et un modèle de cuisine extérieure préfabriquée vu sur Instagram / Alibaba.

L'objectif est de fabriquer soi-même une cuisine extérieure premium, robuste, maintenable et nettement moins chère qu'un produit industriel complet.

## 2. Besoins fonctionnels retenus

Implantation de gauche à droite :

1. petite desserte — 600 mm ;
2. Kamado XXL ;
3. planche / zone de découpe — 600 mm ;
4. plancha gaz déjà possédée ;
5. friteuse ;
6. four à pizza Ooni Koda déjà possédé.

L'évier, envisagé initialement, est abandonné pour la version actuelle.

## 3. Profondeur

Une première hypothèse de plan de travail à 700–800 mm a été rejetée comme trop faible pour les appareils.

Décision :

- profondeur extérieure cible : ~1 050 mm ;
- profondeur utile de plan de travail : ~900–950 mm ;
- vide technique arrière : ~100–150 mm selon les zones ;
- hauteur de plan cible : ~900 mm.

Cette profondeur est notamment justifiée par le Kamado XXL, la plancha, la friteuse et le four Ooni.

## 4. Largeur

Le pod de 4 m envisagé initialement devenait trop contraint avec tous les équipements.

Base de conception retenue : **environ 4,50 m de largeur**.

Une répartition de travail utilisée dans le premier dossier détaillé est :

`600 desserte | 950 Kamado | 600 découpe | 850 plancha | 600 friteuse | 900 Ooni`

Cette répartition devra être ajustée après relevé des dimensions réelles des appareils.

## 5. Façade / toiture — décision majeure

Le concept initial utilisait un auvent plus classique. Il a été remplacé après analyse des références visuelles.

Architecture désormais retenue :

- une **grande façade pleine sur toute la largeur** ferme complètement le pod ;
- cette façade pivote autour de son axe supérieur ;
- une fois ouverte à environ 90°, elle devient un **toit / auvent complet** ;
- hauteur de façade / profondeur d'auvent cible : environ 2,20 m ;
- surface exposée au vent : proche de 10 m² pour une façade de 4,5 × 2,2 m.

C'est l'architecture de référence définitive du projet.

## 6. Référence industrielle analysée

Le modèle Outdoor Party Kitchen Plus du fabricant prefabhousemanufacturer.com indique notamment :

- châssis en tube carré acier galvanisé Q235 ;
- panneaux aluminium ;
- « electric push-rod flip cover » ;
- ouverture motorisée de la grande façade à environ 90°.

Cela confirme le principe : structure acier + façade légère + actionneurs linéaires électriques.

## 7. Mécanisme de façade

Les petits vérins IP44 initialement envisagés ne sont plus considérés comme une solution finale acceptable.

Architecture cible :

- actionneurs linéaires IP65 minimum, idéalement IP66/IP67 ;
- fins de course intégrées ;
- synchronisation des deux côtés ;
- butées mécaniques ;
- bras mécaniques de sécurité indépendants des moteurs en position ouverte ;
- verrouillage mécanique en position fermée ;
- goupilles de désaccouplement permettant une manœuvre de secours ;
- charnière/axe supérieur dimensionné pour la largeur de 4,5 m.

Les actionneurs doivent **ouvrir et fermer**, mais ne doivent pas être l'unique sécurité maintenant le toit ouvert.

## 8. Vent — point critique

La façade ouverte représente environ 10 m² de prise au vent. Le vent est probablement plus dimensionnant que le poids propre de la façade.

Conséquences :

- ancrage mécanique sérieux du pod dans une dalle béton ;
- dimensionnement structurel de la poutre supérieure et des montants ;
- verrouillage mécanique du toit ouvert ;
- règle d'exploitation imposant la fermeture en cas de vent significatif ;
- possibilité future d'un anémomètre pour interdire l'ouverture lorsque les conditions sont défavorables.

Une fermeture automatique par vent fort ne doit pas être mise en œuvre sans système de détection d'obstacle adapté.

## 9. Gaz

Des bouteilles de gaz doivent être stockées sous la plancha et sous le four Ooni.

Décisions :

- compartiments dédiés ;
- bouteille verticale et sanglée ;
- ventilation permanente directement vers l'extérieur ;
- séparation thermique avec l'appareil chaud situé au-dessus ;
- aucun relais, alimentation ou appareillage électrique susceptible de produire une étincelle dans le volume bouteille ;
- détendeur et flexible homologués et accessibles.

## 10. Matériaux

La solution tout inox a été rejetée comme trop chère.

Philosophie retenue :

- structure principale en acier S235/Q235 protégé contre la corrosion ;
- façade aussi légère que possible ;
- aluminium / composite aluminium pour l'enveloppe lorsque pertinent ;
- inox et matériaux incombustibles uniquement autour des zones alimentaires et très chaudes ;
- panneaux ciment / pare-chaleur et lame d'air autour des équipements nécessitant une protection thermique.

## 11. Kamado XXL

Le premier dossier détaillé a utilisé le Big Green Egg 2XL comme enveloppe dimensionnante, notamment à cause de son diamètre et de son poids important (~170 kg).

Le Kamado doit reposer sur un sous-châssis structurel et non sur un simple panneau de meuble.

Le modèle définitif de Kamado reste à arbitrer en fonction du rapport qualité/prix : le coût d'un BGE 2XL neuf est disproportionné par rapport à l'objectif budgétaire global.

## 12. Budget — changement de cible

Une première BOM détaillée aboutissait à plus de 6 000 € pour le pod hors appareils, ce qui a été jugé beaucoup trop élevé.

**Nouvel objectif ferme : 3 000 € TTC maximum pour la construction du pod**, hors équipements déjà possédés et avec séparation claire entre :

- structure / enveloppe ;
- mécanisme de façade ;
- mobilier / plans ;
- gaz / sécurité ;
- électricité / LED ;
- appareils achetés séparément.

La BOM doit être entièrement rechallengée : supprimer le surdimensionnement, privilégier les négoces acier et composants simples, optimiser les débits matière et conserver le budget uniquement là où la sécurité l'exige.

## 13. Équipements déjà possédés

- plancha gaz ;
- four à pizza Ooni Koda.

Ils doivent être valorisés à 0 € dans le budget restant du projet.

## 14. Livrables déjà produits dans la conversation

- manuel HTML interactif de construction ;
- BOM / budget Excel ;
- plan technique PNG ;
- plusieurs rendus et infographies conceptuelles ;
- archive ZIP du manuel.

Le dépôt GitHub devient désormais la **source de vérité** du projet. Les prochaines évolutions doivent être documentées ici plutôt que dispersées dans la conversation.

## 15. Prochaines étapes recommandées

1. Relever les dimensions exactes de la plancha, du modèle Ooni et de la friteuse.
2. Choisir le Kamado XXL réel.
3. Recalculer la largeur exacte des six modules.
4. Refaire la BOM pour tenir l'objectif 3 000 €.
5. Calculer la masse de la façade optimisée.
6. Dimensionner la cinématique des actionneurs à partir du centre de gravité réel.
7. Valider poutre haute, charnières, bras de sécurité et ancrages au vent.
8. Produire les plans de débit définitifs.
9. Produire une version 2 du manuel IKEA avec illustrations de chaque étape.
