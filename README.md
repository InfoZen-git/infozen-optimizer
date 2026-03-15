# InfoZen

Optimiseur PC  
Boost FPS • Nettoyage système • Allègement vieux PC • Optimisations réseau

**InfoZen** est un outil simple et visuel qui applique des tweaks classiques de performance, de confidentialité et de nettoyage sous Windows 10 et 11.

https://github.com/InfoZen-git/infozen-optimizer

## ✨ Fonctionnalités principales

- **Gaming / FPS** : haute performance, désactivation Xbox DVR/Game Bar, priorité CPU, latence réseau réduite…
- **Vieux PC** : allègement démarrage, désactivation animations, nettoyage registre, réduction charge RAM…
- **Nettoyage** : disque, corbeille, logs, prefetch, apps inutiles, réparation système…
- **Réseau** : optimisation TCP, DNS rapide (Google), blocage télémétrie Microsoft, reset réseau…

Interface moderne en Tkinter avec terminal intégré pour suivre les actions en temps réel.

## 📥 Téléchargements (dernière version)

→ **[Releases](https://github.com/InfoZen-git/infozen-optimizer/blob/main/infozen.exe)**

**Version actuelle** : v2.0 (premiers tests)

## 🚀 Comment l’utiliser (30 secondes)

1. Télécharge le **.exe** depuis les Releases
2. **Clic droit → Exécuter en tant qu’administrateur**
3. Si SmartScreen / Defender bloque :  
   → « Plus d’informations » → « Exécuter quand même »
5. L’interface se lance → choisis une catégorie ou un pack complet

## ⚠️ Informations importantes

- **Droits administrateur obligatoires** → l’outil se relance automatiquement en admin si besoin
- **Faux positifs antivirus** très fréquents (PyInstaller + modifications registre)  
  → Ajoute l’exécutable en exclusion dans Windows Defender / ton antivirus
- Certaines modifications (registre, services, hosts) sont **irréversibles sans sauvegarde**  
  → **Crée un point de restauration système** avant la première utilisation
- Actuellement **Windows uniquement** (10 et 11 testés)
- Pas de collecte de données, pas de connexion internet

## 🐛 Signaler un bug / donner un retour

1. Va sur le serveur Discord dans le salon #🪳┃bugs
2. Décris le bug :
   - Ce que tu faisais
   - Ce qui s’est passé (message d’erreur, plantage, tweak qui ne marche pas…)
   - Ta version de Windows
   - Si possible : capture d’écran du terminal InfoZen

Les retours sont très précieux en phase test — merci d’avance !

## ⚙️ Construit avec

- Python 3.14
- Tkinter (interface graphique)
- PyInstaller (exécutable standalone)

**Merci de tester InfoZen optimizer !**  
N’hésite pas à mettre une étoile ⭐ si l’outil te plaît ou t’aide.
