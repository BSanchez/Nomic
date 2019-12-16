# Comment jouer

Si vous n'avez jamais utilisé Git et Github, la plupart des termes et actions demmandées 
pour participer peuvent paraitre compliquées. Bien que rien dans les règles ne l'y force, 
le greffier se doit d'être conciliant et aider les personnes proposant des lois ou invoquant
des jugements avec les étapes à réaliser.

## Comment proposer une loi.
Pour proposer une loi, il faut "demmander une pull request" contenant les changements proposés.

### Proposition d'adoption de règle
Si la modification voulue est une création de règle, cliquez sur le dossier "règle" pour aller dedans puis cliquez sur "Create new file". Nommez le fichier "<Numéro cardinal>.md, puis copiez-collez-modifier le contenu du fichier "templates/regle.md" ou copiez-collez-modifier le block suivant:

```markdown
---
CARDINAL: XXX
Auteur: John Doe
Type: Modifiable
---

# Rule

Ceci est un exemple de règle sans effet
```

### Proposition d'amendement
Pour un amendement, allez dans le fichier de la règle que vous voulez modifier,
puis appuyez sur le petit crayon pour éditer le fichier. Renomez le fichier en 
fonction du nouveau numéro cardinal, mettez à jour la cassete en haut du 
fichier pour y mettre à jour le numéro cardinal, l'auteur et éventuellement le titre.
Enfin mettez à jour le corps de la règle.

### Proposition d'abrogation
Pour une abrogation rien de plus simple : allez dans la règle que vous souhaitez abroger et utilisez la corbeille trouvable en haut à droite.

### Dans tout les cas
Une fois la modification faite, il faut commiter le changement en mettant comme nom de commit "XXX - <Adoption/Amendenent/Abrogation> - Nom du changement" et laissant la description vide.

Le commit sur la branche master étant impossible, une création de pull request s'ouvre automatiquement. Une fois la template completée, ajoutez le label <adoption/amendement/abrogation>, mettez
le greffier (BSanchez) comme "Reviewer", puis soumettez la pull request : le vote commence.

# Comment voter
Pour voter, il faut commenter la pull request ouverte un pouce en l'air pour un vote positif (:+1:) ou un pouce en bas pour un vote négatif (:-1:). En cas de plusieurs votes, pas besoin de
supprimer son ancien vote, seul le dernier vote est pris en compte.

# Comment invoquer un jugement
Invoquer un jugement se passe de manière très semblable à une proposition d'adoption. Créer un fichier dans le dossier "jugements" nommé "<Numéro Cardinal de jugement>.md", copiez-collez le contenu
 du fichier "templates/jugement.md" ou copiez-collez-modifier le block suivant. Attention, les valeurs entre <> doivent être laissée en l'état, le juge les remplira lui: 

```markdown
---
Jugement: XXX
Auteur: John Doe
Juge: <Non déterminé>
Jugement: <Vrai, Faux>
---

# Déclaration
La déclaration précise qui sera jugée vrai ou fausse. Doit être une phrase affirmative.

## Arguments et Justification
Pourquoi l'auteur pense que cette phrase est vrai.

# Jugement
<Doit être rempli par le juge>
## Arguments et Justification
<Peut être rempli par le juge>
```

Pour le commit, mettez comme titre "XXX - Invocation de jugement", aucune description.
Pour la pull request, mettez "Invocation de jugement" en label, le Greffier (BSanchez) en Reviewer, et remplissez la template.
