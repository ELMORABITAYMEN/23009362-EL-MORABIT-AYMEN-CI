# [23009362-EL MORABIT AYMEN-CI] : Prévision du prix du phosphate de roche

**Étudiant** : [EL MORABIT AYMEN] · **Code Apogée** : [23009362] · **Groupe** : [CI]
**Sujet attribué** : CI05, Prévision des prix de matières premières
**Cours** : BD & DS, S7 Commerce international, ENCG Settat, 2026-2027
**Enseignant** : A. Larhlimi

## Problématique
Peut-on prévoir le prix mensuel du phosphate de roche à un mois mieux
qu'en supposant qu'il reste identique au mois précédent ?

Intérêt économique : le Maroc détient l'essentiel des réserves mondiales de
phosphate, et la volatilité de son prix influence les recettes d'exportation.

## Données
- Série mensuelle du prix du phosphate de roche (repère FOB Afrique du Nord), en USD/tonne, prix nominal
- Plateforme de téléchargement : agri.markets (https://agri.markets/phosphate-rock), données issues de la Banque mondiale
- Période : 2016-10 à 2026-10 (120 observations mensuelles)
- Détails (URL, date d'extraction, licence, accord de l'enseignant) : voir `data/raw/SOURCE.md`

## Structure du dépôt
- `data/raw/` : données brutes non modifiées + notice de source
- `docs/` : fiche du sujet, références
- `notebooks/projet_CI05.ipynb` : notebook exécuté
- `figures/` : graphiques utilisés dans la présentation
- `rapport/rapport.pdf` : export du notebook
- `presentation/` : 6 diapositives (PDF + source)
- `video/` : vidéo de démonstration (ou lien ci-dessous)
- `DECLARATION_IA.md` : déclaration d'usage des outils d'IA
- `requirements.txt` : dépendances Python

## Exécution
1. Ouvrir `notebooks/projet_CI05.ipynb` dans Google Colab ou Jupyter
2. Installer les dépendances : `pip install -r requirements.txt`
3. Exécuter toutes les cellules (graine aléatoire fixée à 42, chemins relatifs)

## Vidéo
[Lien de lecture accessible sans autorisation, ou « Voir `video/demonstration.mp4` »]

## Livrables
Notebook, rapport PDF, présentation (6 diapositives), vidéo, déclaration d'usage de l'IA.
