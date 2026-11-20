# Security notes – TP7

## Observations sur actions/setup-node
- Badge créateur vérifié : oui (GitHub)
- Nombre d'étoiles : 5K
- Code source : dossier src/ (code compilé dans dist/)

**Q3.** @main change à chaque nouveau commit. Une modification ou une attaque sur la branche arrive directement dans notre workflow. @v4 fixe la version utilisée.

**Q4.** Non. Le badge prouve seulement l'identité de l'éditeur. Il ne garantit pas que le code est sans faille ni qu'il ne sera pas compromis.

**Q5.** Lire le code source et les permissions demandées par l'action. Épingler l'action sur un SHA de commit précis au lieu d'un tag.