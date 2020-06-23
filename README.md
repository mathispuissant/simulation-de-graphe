# simulation-de-graphe


## Synthèse

	Notre projet initial consistait à reproduire un réseau social, qui rapprocherait les personnes ayant des points communs (par exemple : villes, écoles, sports, etc.). Nous avons donc étudié les réseaux sociaux et en passant du temps dessus, nous avons constaté qu’ils ne parlaient que d’une chose en cette période de confinement : le Covid-19. C’est ainsi qu’une idée nous vînt en tête, et si nous reproduisions un algorithme de propagation d’un virus dans une population donnée ? 

### I)	Le rapprochement social.

Pour qu’il y ait contamination, il doit y avoir rapprochement. Deux individus n’ayant aucun point commun ne se rencontreront jamais et ne pourront donc pas se transmettre la maladie. Finalement, notre projet initial n’a pas été abandonné, mais condensé dans cette partie. Nous cherchons ici à créer des liens entre les individus pour qu’ils puissent se transmettre le virus (c’est virtuel, nous ne voulons contaminer personne !)

### II)	Introduction du virus dans la population.

L’expérience prend plusieurs variables en compte :
- Lacontamination. Au jour 0, notre expérience commence : un individu aléatoire est contaminé. À partir de là, cet individu pourra contaminer les gens qui lui sont proches (d’où la partie 1). Le lendemain il pourra toujours contaminer ceux qu’il n’a pas contaminés le 1er jour et les personnes contaminées au jour 1 pourront elles aussi contaminer leur entourage à partir du jour 2. On peut choisir la probabilité de contamination, étant donné que l’on ne contamine pas son entourage à coup sûr. Nous observerons jour après jour le nombre de personnes contaminées. 
- L’immunité. Nous choisirons combien de temps les individus restent contaminés et peuvent transmettre le virus. Après cette période, les individus ne sont plus malades mais ne peuvent plus être contaminés par ceux qui sont encore malades. 
- La mort. La maladie s’accompagne malheureusement souvent de la mort. Nous choisirons également la probabilité qu’un individu décède suite à cette maladie.

### III)	Expériences et résultats.

Lorsque l’on appliquera cette expérience, nous changerons les variables pour obtenir différents résultats et en tirer des conclusions :
- Lors de la 1ère expérience nous regarderons les conséquences d’un confinement retardé.
- La 2ème expérience consiste à étudier différent type de déconfinement, l’un brutal et l’autre progressif.
- La 3ème expériencenous regarderons les conséquences d’un déconfinement trop tot.
-Enfin, pour la dernière expérience nous avons voulu nous amuser un peu et imaginé un cas d’apocalypse zombie. Ici, Les individus restent malades jusqu’à ce qu’ils meurent. Nous observerons donc combien de survivants il y aurait après 100 jours de pandémie.

Mathis PUISSANT
Achille POPELIER
