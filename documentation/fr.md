<!-- ELUCENIA technical documentation · peso-ideal-e-ajustado · fr · no clinical/professional/rights approval -->

# Poids idéal et poids ajusté

[conditions, sources et autorisations](https://elucenia.org/fr/outils/peso-ideal-e-ajustado)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Sexe

`sexo`

- `F` — Féminin
- `M` — Masculin

### Taille

`altura`

cm · intervalle: 120–230

### Poids réel (pour le poids ajusté)

`peso`

kg · facultatif · intervalle: 25–350

## Édition de la méthode

Devine 1974/Robinson 1983/Miller 1983 ; revue Pai–Paloucek 2000 ; facteur local du poids ajusté 0,4

## Formule documentée

Poids idéal (Devine): hommes 50 kg + 2,3 kg par pouce au-delà de 5 pieds; femmes 45,5 kg + 2,3 kg par pouce au-delà de 5 pieds. En centimètres: 50 (45,5) + 2,3 × (taille − 152,4) ÷ 2,54.

Poids ajusté = Poids idéal + 0,4 × (poids réel − Poids idéal).

## Limites et population

Le poids idéal est une estimation issue de tables taille/poids, pas une mesure de masse maigre. La relation pharmacocinétique varie selon le médicament ; ce résumé ne confirme pas un facteur d’ajustement universel de 0,4. Le choix du poids pour la posologie doit suivre la source du médicament et la population correspondante.

## Références

- [Pai MP, Paloucek FP. The origin of the "ideal" body weight equations. Ann Pharmacother, 2000.](https://doi.org/10.1345/aph.19381)

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

## Résultats documentés

Les informations ci-dessous conservent les sorties de la méthode pour des exemples synthétiques. Elles ne constituent pas une validation clinique indépendante.

### 1

Poids idéal selon la formule de Devine


### 2

Poids réel > 120 % du poids idéal : pour les médicaments hydrophiles et les aminosides, utiliser le poids ajusté

| Détails du résultat | |
| --- | --- |
| Poids réel par rapport au poids idéal | 160% |
| Poids ajusté (IBW + 0,4 × excès) | 93,0 kg |


### 3

Poids idéal selon la formule de Devine


### 4

Poids idéal selon la formule de Devine

