🛡️ Détection d’Anomalies dans le Trafic Réseau avec PCA
📌 Description
Ce projet analyse le trafic réseau à partir du CTU-13 Dataset pour identifier les anomalies et activités malveillantes (botnets). Il utilise des méthodes statistiques et l'analyse en composantes principales (PCA) pour détecter les flux suspects.

🚀 Fonctionnalités
✅ Chargement et traitement des données réseau 📊
✅ Extraction des entropies des ports, adresses IP et drapeaux TCP
✅ Application du PCA pour la réduction de dimensionnalité
✅ Détection des anomalies avec un seuil basé sur les valeurs propres
✅ Évaluation des performances avec des métriques comme la précision, le recall et le f-mesure

🔧 Technologies utilisées
Python 🐍
Pandas, NumPy (traitement des données)
Scapy (analyse du trafic réseau)
Matplotlib (visualisation)
Scikit-learn (PCA)
📂 Structure du projet
📁 data/ → Jeu de données réseau (CTU-13)
📁 scripts/ → Scripts de prétraitement et d’analyse
📁 results/ → Fichiers de sortie et métriques

🚀 Installation et Exécution
bash
Copy
Edit
git clone https://github.com/votre-repo.git
cd votre-repo
pip install -r requirements.txt
python main.py
📊 Résultats & Performances
🔹 FPR (False Positive Rate) : 1.0
🔹 TPR (True Positive Rate) : 0.0546
🔹 Précision : 0.0194
🔹 F-mesure : 0.0286

🎯 Objectif : Améliorer la précision et réduire le taux de faux positifs via des optimisations du modèle.
