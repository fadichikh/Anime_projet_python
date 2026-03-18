# Anime_projet_python
Ce dépôt contient un exemple de traitement du jeu de données `animes.csv`.  
Les principales étapes sont :
Charger le fichier CSV avec `pandas`.
Nettoyer les données : convertir les colonnes en types numériques, gérer les valeurs manquantes et supprimer les doublons.
Créer un score final combinant la note (`Score`) et la popularité (`Popularity`). On inverse d'abord la popularité (un rang plus petit devient une valeur plus grande), puis on calcule `score_final = 0.6 * Score + 0.4 * pop_norm`.
Trier les animés selon `score_final` et sauvegarder le Top 10 dans `top10.csv`.
Exécutez `python scripts/analysis.py` depuis la racine du projet pour obtenir le classement.
