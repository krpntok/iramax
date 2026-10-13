# Iramax

Carnet bien-être de Maxime à Seminyak (Bali) : brief quotidien, suivi poids et ventre, idées de week-end.

- **URL** : https://iramax.netlify.app (redirige vers le carnet hébergé sur Claude)
- **Carnet** : https://claude.ai/artifact/8VyZ3x7hZk8o9tqy5PZE8u

## Structure

- `public/` : le site Netlify (redirection + page de secours)
- `source/irama.html` : source du carnet, pour l'historique des versions. Cette page tourne dans Claude : elle utilise la base de données des artifacts (`window.claude.use("db")`), elle ne fonctionne donc pas seule sur Netlify.

## Données

Les données (journal, validations, briefs, week-ends) vivent dans la base de l'artifact Claude, pas dans ce dépôt. Le brief est écrit chaque matin à 5 h 49 (Asia/Makassar) par une tâche programmée Claude.
