# Contribution à UGH Pulse Plugins

Merci de vouloir améliorer l'écosystème UGH ! Pour que ton code soit accepté, tu dois respecter ces règles.

## 🛑 Ce qui est STRICTEMENT Interdit
1. **Zéro Reverse Engineering Invasif** : Pas de contournement de DRM, pas de crack. On utilise uniquement les outils CLI officiels (SteamCMD) ou des projets open-source clean (Legendary).
2. **Pas de vol de données** : Tout plugin qui tente de récupérer les identifiants ou les tokens de l'utilisateur en dehors du dossier sécurisé de UGH Pulse sera banni et signalé.
3. **Pas de Bloatware** : Le code doit être optimisé. Si ton plugin consomme plus de 10 Mo de RAM en tâche de fond, il sera refusé.

## 🚀 Comment proposer une modification (Workflow PR)
1. **Fork** le projet et crée une branche propre (`feature/mon-nouveau-plugin` ou `fix/nom-du-bug`).
2. Écris ton code en respectant l'architecture imposée (`manifest.json`, `src/auth.js`, etc.).
3. Ouvre une **Pull Request** (PR) en expliquant clairement ce que fait ton code.
4. **Attends la validation** : Aucun code n'est fusionné sur la branche principale sans une relecture et un test de validation de notre côté.
