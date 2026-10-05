<!-- ELUCENIA technical documentation · perc · fr · no clinical/professional/rights approval -->

# Critères PERC

[conditions, sources et autorisations](https://elucenia.org/fr/outils/perc)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Âge ≥ 50 ans

`idade`

### Fréquence cardiaque ≥ 100 bpm

`fc`

### Saturation en O₂ \< 95 % en air ambiant

`sat`

### Œdème unilatéral du membre inférieur

`edema`

### Hémoptysie

`hemoptise`

### Chirurgie ou traumatisme avec hospitalisation au cours des 4 dernières semaines

`cirurgia`

### Antécédent de TVP ou d’EP

`tev`

### Prise d’œstrogènes (contraception ou traitement hormonal substitutif)

`hormonio`

## Édition de la méthode

PERC/Kline 2004 : 8 critères négatifs avec faible suspicion préalable ; pas de décision automatique

## Formule documentée

Huit questions oui/non. PERC est négatif uniquement si toutes sont « non ». Appliquer seulement si le médecin juge déjà la faible probabilité clinique (gestalt \< 15%).

## Limites et population

La PERC 2004 a été développée chez des patients des urgences évalués pour une embolie pulmonaire et testée dans des groupes à risque faible et très faible. Les huit critères doivent être simultanément négatifs, dont l’âge \< 50 ans, le pouls \< 100/min et la saturation \> 94% dans l’étude originale. La règle ne détermine pas un risque nul et son applicabilité dépend de la sélection préalable de la population ; les définitions temporelles et critères d’inclusion doivent être vérifiés dans la version utilisée.

## Références

- [Kline JA et al. Clinical criteria to prevent unnecessary diagnostic testing in emergency department patients with suspected pulmonary embolism. J Thromb Haemost, 2004.](https://doi.org/10.1111/j.1538-7836.2004.00790.x)

- [Freund Y et al. Effect of the Pulmonary Embolism Rule-Out Criteria on subsequent thromboembolic events among low-risk emergency department patients: the PROPER randomized clinical trial. JAMA, 2018.](https://doi.org/10.1001/jama.2017.21904)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
