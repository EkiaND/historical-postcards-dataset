<div align="center">

<!-- En-tête avec gradient -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=Historical%20Postcards%20Dataset&fontSize=38&fontAlignY=35&animation=twinkling&fontColor=fff" />

### **Projet d'autonomie M1 Sciences des Données**
#### **Détection & Transcription**

<p align="center">
  <img src="https://img.shields.io/badge/Détection_de_zones-3B82F6?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/OCR_/_HTR-10B981?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/Format_COCO-8B5CF6?style=for-the-badge&logoColor=white" />
</p>

<br>

<!-- Badges des technologies -->
<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/uv-DE5FE9?style=for-the-badge&logo=astral&logoColor=white" alt="uv" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter" />
  <img src="https://img.shields.io/badge/pycocotools-F7931E?style=for-the-badge&logoColor=white" alt="pycocotools" />
</p>

</div>

<br>

---

## Description du projet

Ce projet explore le **Historical Postcards Dataset**, un jeu de données de recherche
composé de scans de **cartes postales anciennes** annotés au format **COCO**. L'objectif
est double :

- **Détecter** les zones d'intérêt sur les cartes (texte imprimé, manuscrit, timbres, cachets…).
- **Transcrire** automatiquement le texte présent dans ces zones (OCR / HTR).

Le travail suit une progression allant de la prise en main des annotations jusqu'à
l'évaluation des modèles face à des **scores de référence**.

### Jalons

<div align="center">

| # | Étape | Objectif |
|:---:|:---:|:---:|
| **1** | Prise en main | Charger et explorer les annotations COCO |
| **2** | EDA & visualisation | Distributions, tailles de boîtes, affichage annoté |
| **3** | Détection | Détecter les zones et évaluer (précision, rappel, mAP@50) |
| **4** | Transcription | Reconnaître le texte et mesurer (Levenshtein, Jaccard, CER) |
| **5** | Stretch (libre) | Comparaisons de modèles, cas difficiles, NLP… |

</div>

---

## Jeu de données

> Pélingre, M. & Tabbone, S. A. (2026). *Historical Postcards Dataset (COCO), v2.0.*
> Recherche Data Gouv. DOI : [10.57745/GELGHH](https://doi.org/10.57745/GELGHH).
> Contenu sous **Licence Ouverte Etalab 2.0**.

---

## Démarrage rapide

Environnement géré avec [uv](https://docs.astral.sh/uv/) pour rester **reproductible** :

```bash
# Installer les dépendances de base
uv add jupyterlab numpy pillow matplotlib pycocotools

# Lancer Jupyter dans l'environnement du projet
uv run jupyter lab
```

Ouvrez ensuite le notebook `M1SD-ProjetAvance-sujet.ipynb` et adaptez `DATA_DIR` au
dossier où vous avez décompressé le dataset.

---

## Auteur

<div align="center">

<table>
<tr>
<td align="center" width="100%">
<a href="https://github.com/EkiaND/">
<img src="https://ui-avatars.com/api/?name=Romain+Lesueur&size=150&background=3B82F6&color=fff&bold=true&rounded=true" alt="Romain Lesueur" />
</a>
<br><br>
<h3>Romain Lesueur</h3>
<sub>M1 Sciences des Données • IDMC</sub>
</td>
</tr>
</table>

</div>

---

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" />

<div align="center">
<sub>© 2025-2026 - Projet académique - Contenu du dataset sous Licence Ouverte Etalab 2.0</sub>
</div>