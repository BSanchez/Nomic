# Liste des règles

# 101 -  Obéir aux règles
Type: Immuable

Tous les joueurs doivent toujours respecter toutes les règles alors en vigueur, dans la forme dans laquelle elles sont en vigueur à cet instant donné. 
L'ensemble de règles initial est en vigueur chaque début de partie. 
L'ensemble de règles initial comprend les règles 101-116 (immuables) et 201-214 (modifiables).



# 102 -  Nature des joueurs
Type: Immuable

Un joueur est toute personne physique possédant au moins un compte Github enregistré comme collaborateur sur « BSanchez/Nomic ». 
Le Greffier est un joueur sensé valider la fin d'une période de vote et s'assurer du bon respect de la forme des propositions, 
il se reconnaît à la présence d’un asterisque (*) dans la liste des joueurs. Un Greffier secondaire est un joueur dont le rôle est
de servir de Greffier dans le cas ou le Greffier est aussi l'auteur d'une proposition ou le Juge. Il se reconnait à la présence de deux asterisques (**) dans la liste des joueurs.
Le jeu contient exactement un Greffier et un Greffier secondaire à tout moment de la partie.



# 103 -  Modification de règles
Type: Immuable

Une modification de règle se défini par n'importe laquelle des actions suivantes :

a. l'adoption, l'abrogation ou l'amendement d'une règle modifiable ;
b. la transmutation d'une règle immuables en règle modifiable, ou vice versa.



# 104 -  Faire une proposition de modification de règle
Type: Immuable

Pour proposer une modification de règle, le joueur doit créer une pull request en contenant les modification qu’il souhaite apporter au corpus de règles. 

En cas d’adoption, il faut créer un nouveau fichier dans le dossier « règles » nommée selon le numéro cardinal de la règle et comme extension « md », 
et dont le formatage du contenu est conforme au contenu du fichier « templates/regle.md ».
En cas d’abrogation ou d’amendement, le joueur doit impacter le fichier de règle dans le sens de sa modification (en le supprimant pour une abrogation, en le modifiant et le renommant pour un amendement).

Chaque proposition ne peut contenir qu’une seule modification de règle. 
Le message de la pull request doit suivre la template « proposition de modification de règles », et être tagée en fonction du type de modification proposée.
Si une proposition est soumise avec une forme inacceptable, le Greffier peut décider à sa convenance s’il veut corriger la forme lui même ou demander à l’auteur
de la proposition de la corriger. Une proposition n’ayant pas une forme acceptable lors de la fin de la période de vote est rendue nulle quel que soit le résultat du vote.



# 105 -  Adopter une proposition
Type: Immuable

Toutes les propositions faites dans les règles et correctement formée doivent êtres soumises au vote.
Voter signifie commenter un message contenant uniquement « :+1 : »(thumb up) ou « :-1 : » (thumb down) dans la pull request. 
Il est possible de s’abstenir « explicitement » avec « :hand : ». En vas de votes multiples, le dernier vote effectué dans la perdiode de vote sera conservé.
Trois conditions doivent êtres satisfaites pour qu’une proposition de modification de règle soit acceptée : 

a. le Quorum est atteint.
b. le nombre de voix requis pour l’adoption de la proposition est atteint.
c. soit la période de vote est arrivée à son terme, soit l’ensemble des joueurs a voté.

Une proposition ne complétant pas les trois conditions précédentes à la fin de la période de vote est rejetée.



# 106 -  Cas particulier des propositions de transmutation
Type: Immuable

Les propositions de transmutations qui change une règle immuable en règle modifiable ne sont adoptées que si le vote obtient l’unanimité. 
Une transmutation ne peut pas êtres implicite, elle doit être déclaré explicitement dans la proposition pour faire effet.



# 107 -  Modifier les règles
Type: Immuable

Quand une proposition est acceptée, la pull request correspondante est validée. Aucune modification de règle ne peut prendre effet avant la résolution du vote correspondant à ladite acceptation. Aucune modification de règle ne peut avoir d’effet rétroactif.



# 108 -  Plan de numérotation
Type: Immuable

Chaque règle à un numéro cardinal. Chaque proposition de modification de règle à un numéro cardinal. La numérotation commencera au numéro 301 et toute proposition de modification des règles présenté conformément aux règles en vigueur se verra affecter le numéro entier suivant dans l'ordre, que la proposition correspondante soit ou non adoptée.

Les règles abrogées, puis réadoptées, se voient affecter  le numéro d'ordre du projet visant leur réadoption. Les règles amendées ou transmutées se voient affecter le numéro d'ordre du projet visant à les amender ou à les transmuter.



# 109 -   Conflit entre règles immuables et modifiables
Type: Immuable

En cas de conflit entre une règle immuable et une règle modifiable, la règle modifiable est considéré comme entièrement nulle et sans effets.



# 110 -  Tenue d’une séance de débat
Type: Immuable

Lorsqu'une modification projetée de règles est peu claire, ambiguë, paradoxale ou explicitement nuisible au jeu, 
ou lorsqu'on peut arguer qu'elle vise en fait à apporter au moins deux modifications aux règles, 
ou lorsque la modification consiste en un amendement qui n'introduit aucune modification véritable, 
ou se révèle discutable pour quelque autre raison, 
les joueurs autres que celui ou celle qui a soumis le projet de modification peuvent y soumettre des amendements ou exposer leurs critiques 
avant que le projet ne soit mis aux voix. Un délai raisonnable et ne pouvant dépasser 48h sera réservé à ce débat pendant lequel la période de vote est suspendue. 

L'auteur du projet ayant fait l'objet dudit débat décide de la forme finale sous laquelle son projet est mis aux voix et du moment auquel 
le débat prend fin pour laisser place au vote. 
Si la proposition à changée dans sa forme ou son fond, les votes précédents ce changements sont annulés et leurs propriétaires sont libre de voter de nouveau.



# 111 -  Gagner la partie
Type: Immuable

La définition de ce qui constitue la victoire au Nomic ne peut être modifiée : elle demeure le fait d'avoir accumulé n points. 
Cependant la valeur de n peut être changée et des règles définissant le gagnant lorsque la poursuite du jeu s'avère impossible peuvent être adoptées ou, si elles sont modifiables, amendées ou abrogées.



# 112 -  Quitter le jeu
Type: Immuable

Chaque joueur a à tout moment la possibilité de quitter le jeu en se retirant des collaborateurs du dépôt plutôt que de continuer à jouer ou subir une pénalité. 
Aucune pénalité pire que perdre, selon l’avis du joueur qui la subit, ne peut être imposé.



# 113 -  Au moins une règle modifiable
Type: Immuable

Le corpus de règles doit à tout moment comporter au moins une règle modifiable. L'adoption de modifications ne doit jamais être absolument interdite.



# 114 -  Les règles méta
Type: Immuable

Les modifications de règles affectant les règles nécessaires à l'autorisation ou l'application des modifications sont une forme de modification des règles parfaitement licite. 
Sont également autorisées les modifications de règles qui amendent ou abrogent leur propre autorité. Aucune modification de règle, aucun coup ne peut être interdit pour cause d'auto-référence ou d'auto-application de règle.



# 115 -  Permissibilité du non-interdit
Type: Immuable

Tout ce qui n'est pas explicitement interdit ou réglementé par une règle donnée est autorisé et non réglementé, 
à la seule exception de la modification des règles qui n'est autorisée que lorsqu'une règle ou un ensemble de règles le permet implicitement ou explicitement.



# 116 -  En cas d’impasse
Type: Immuable

Si les règles sont changées de façon à ce qu’aucun tour supplémentaire soit possible, 
ou que la légalité d’une proposition soit impossible à déterminer, 
ou qu’un juge décide qu’une action est à la fois légale et illégale et que donc un jugement ne peut pas être rendu et que sa décision n’est pas rejetée, 
alors le premier joueur qui est incapable de terminer son tour est déclaré vainqueur.

Cette dernière règle a priorité sur toute autre règle déterminant le gagnant. 



# 201 -  Ordre des joueurs
Type: Modifiable

Les joueurs jouent à tour de rôle dans l’ordre alphabétique de la liste des noms d’utilisateurs Github.



# 202 -  Description d’un tour de jeu
Type: Modifiable

Le tour d’un joueur est composé des phases suivantes :

1. Le joueur dont c’est le tour actuellement propose une modification de loi.
2. La loi est soumise au vote.
3. Le greffier impacte la branche principale conformément au résultat du vote, soit en validant la PR en cas d’acceptation soit en fermant la PR correspondant à la proposition en cas de rejet de la proposition.
4. Des points sont attribués aux joueurs en fonction du résultat du vote.



# 203 -  Conditions d’acceptation des propositions
Type: Modifiable

Le quorum est égal à la moitié du nombre de joueurs participant à la partie. Le nombre de
votes requis pour l’acceptation d’une proposition de modification est égal à la moitié des
votes légaux et hors abstention soumis plus un. Chaque joueur a exactement un vote et
chaque joueur peut changer son vote à tout moment tant que tous les joueurs n’ont pas voté
et que la période de vote n’a pas atteint son terme. La période de vote d’une proposition de
modification de règle est de 48h.



# 204 -  Ordre des joueurs
Type: Modifiable

Quand une proposition de modification de règles est acceptée, les joueurs ayant voté
contre cette proposition gagne 5 points, et l’auteur de la proposition gagne 10 points.
Quand une proposition de modification de règle est rejetée, son auteur perd 10 points. Si
une proposition de modification de règle est rendu nulle car mal formatée, son auteur perd
10 points.



# 205 -  Nombre de points requis
Type: Modifiable

Le vainqueur est le premier joueur à atteindre 200 points ayant au moins 20 points de
plus que tout les autres joueurs.



# 206 -  Résoudre les conflits entre règles
Type: Modifiable

Si deux ou plusieurs règles modifiables entrent en conflit les unes avec les autres, ou si
deux ou plusieurs règles immuables entrent en conflit les unes avec les autres, la règle dont
le numéro d'ordre est le plus petit fait foi.

Si l'une des règles entrant ainsi en conflit stipule explicitement qu'elle est subordonnée à
l'application d'une autre règle (ou type de règle) ou qu'elle régit l'application d'une autre
règle (ou type de règle), ces dispositions l'emporteront sur la détermination numérique de
la priorité énoncée ci-dessus.

Si plusieurs règles affirment être subordonnées à d'autre ou en régir l'application, c'est de 
nouveau la méthode numérique qui détermine la priorité.



# 207 -  Mise en application des modifications de règles acceptées
Type: Modifiable

Une modification de règle acceptée prend effet au moment de la complétion du vote qui l’a
acceptée.



# 208 -  Invocation du Jugement
Type: Modifiable

Tout joueur qui a un doute à propos d’une loi ou de son interprétation peut à tout moment
Invoquer un Jugement. Pour invoquer un jugement, un joueur doit créer un fichier dans le
dossier « jugements » ayant pour nom le numéro du jugement sur 3 chiffres et comme
extension « md » . Le formatage du contenu de ce fichier doit être conforme au contenu du
fichier « templates/jugement.md ». Le message de la pull request doit suivre la template «
invocation de jugement », et être tagée « invocation de jugement ».



# 209 -  Sélection du Juge
Type: Modifiable

Les juges ne peuvent être sélectionné que dans la liste des joueurs n’étant ni le joueur
ayant invoqué le jugement, ni l’auteur de la proposition actuellement en vote, ni un joueur
ayant déjà refusé de juger cette déclaration.

La sélection du juge est automatique en fonction de l’identifiant du commit ayant invoqué
le jugement grace au script suivant :
``` list[commit.gsub(/[a-z]/, "").to_i % list.length] ```

Si le joueur accepte la charge de juge, il faut éditer le fichier d’invocation du jugement
pour mettre son nom en auteur. Dans le cas contraire, il faut recommencer une sélection.

S’il est impossible d’effectuer la sélection du juge car la liste de juges potentiels est vide,
le jugement délivré est « indécis », le nom du juge laissé vide et la Pull Request acceptée.



# 210 -  Délivrer un Jugement
Type: Modifiable

Un juge doit rendre son jugement dans les 48h suivant l’acceptation de l’office de juge en
modifiant le fichier correspondant à l’invocation du jugement et en validant la pull request.
Un Juge qui échoue à cette tache perd 10 points et est considéré comme ayant refusé le
poste de juge. Dans ce cas, le Greffier ferme la pull request correspondant au jugement, en
ouvre une nouvelle identique et reprend la sélection du Juge.



# 211 -  Trois possibles jugements
Type: Modifiable

Il n’y a que trois jugements possible que peut rendre un juge : Vrai, Faux et Indécis. Un
jugement peut être accompagné d’arguments expliquant le choix fait, mais ils ne font pas
partie du jugement officiel.



# 212 -  Les jugements doivent suivre les règles
Type: Modifiable

Tout les jugements doivent être rendu en accord avec les règles alors en vigueur. Si les
règles sont silencieuses, inconsistantes ou peu clair sur la déclaration soumise au jugement,
le juge doit considéré l’historique, les habitudes et l’esprit de la partie actuelle pour juger
la question.



# 213 -  Jurisprudence
Type: Modifiable

Si une déclaration pour laquelle un jugement a été invoqué est déclaré vrai par ledit
jugement, elle devient une part explicite de la partie en rejoignant ce que l’on nomme
l’usage. 
Si une des règle d’usage entre en conflit avec une règle modifiable ou une règle
immuable, la règle d’usage est considéré comme entièrement nulle et sans effets. 
Si le jugement est annulé, la déclaration correspondante sort de l’usage.



# 214 -  Annuler un jugement
Type: Modifiable

A n’importe quel moment dans les 7 jours suivants un jugement rendu, n’importe quel
joueur peut proposer l’annulation de ce jugement, c’est à dire changer le jugement rendu
en « indécis ».
Si une proposition de modification est actuellement en vote, la période de vote et la période
de débat de cette dernière sont mises en pause, et reprendront dés la fin
de la période de vote de cette proposition d’annulation de jugement. 
Si la proposition d’annulation est adoptée, le juge ayant rendu ce jugement perd 20 points.
Si la proposition d'annulation est rejetée, l'auteur de l'invocation de jugement perd 20 points
