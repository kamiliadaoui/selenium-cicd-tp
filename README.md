![alt text](<Capture d'écran 2026-02-11 161819.png>)

![alt text](<Capture d'écran 2026-02-11 162328.png>)

![alt text](<Capture d'écran 2026-02-11 162344.png>)
.
1. Avantages observés

Automatisation des tests :

Gain de temps.

Détection rapide des erreurs.

Réduction des régressions.

Tests reproductibles et fiables.

Plus de confiance lors des modifications du code.

Apport du CI/CD :

Exécution automatique des tests à chaque push.

Blocage du déploiement si les tests échouent.

Amélioration continue de la qualité.

Visibilité grâce aux rapports et métriques.

2. Défis rencontrés

Difficultés avec Selenium :

Problèmes de drivers et compatibilité.

Différences entre environnement local et CI.

Instabilité liée aux temps de chargement.

Gestion des chemins vers les fichiers.

Amélioration de la stabilité :

Utiliser WebDriverWait au lieu de time.sleep.

Appliquer le Page Object Pattern.

Utiliser des sélecteurs stables.

Tester dans un environnement contrôlé (CI).

3. Métriques

Métriques importantes :

Taux de couverture du code.

Taux de réussite des tests.

Temps d’exécution des tests.

Temps de chargement de la page.

Mesure de l’efficacité du CI/CD :

Nombre de builds réussis.

Rapidité du pipeline.

Bugs détectés avant déploiement.

Réduction des erreurs en production.