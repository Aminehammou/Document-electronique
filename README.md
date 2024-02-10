# Alarme par rupture
Description



![image](https://github.com/Aminehammou/Document-electronique/assets/133261059/550183e2-d15c-425d-a29f-4cd2dacabaec)
Qu’il s’agisse de protéger une armoire à pharmacie ou
bien un placard à confitures, vous serez contraints d'avoir
recours à l'électronique, seule solution élégante, à moins que
vous n'adoptiez la méthode plus sévère du cadenas.

Sans constituer un antivol « sans parade », le montage
simplifié que nous vous proposons trouvera de nombreuses
applications. Si vous voulez, par exemple, protéger un local, il
vous suffira de tendre un piège à l'aide d'une boucle de fil émaillé très fin, et judicieusement
disposée. La moindre rupture de ce fil qui peut atteindre plusieurs mètres de long
provoquera le retentissement d'un signal sonore. Il ne va pas sans dire que le montage ne
constitue pas une sirène destinée à faire fuir l'intrus, mais une « boucle de surveillance ».

Le schéma de principe
La figure propose le schéma de principe complet du dispositif. Ce dernier est
construit autour d'éléments très connus et peu onéreux, notamment le NE 555.
Le circuit intégré constitue un multivibrateur astable destiné à délivrer une « note »
audible. Pour ce faire, quelques composants « discrets » sont associés à ce circuit et
conformément aux instructions précisées par le fabricant.
La fréquence des signaux HF dépend de la valeur des éléments R1, R2et C1. La
sortie s'effectue alors au niveau de la borne (3), et un transistor T1 du type PNP fait suite. Il
va jouer deux rôles, celui de préamplificateur et celui de « commutateur » grâce à la
présence des bornes A et B de la boucle de surveillance.
En effet, cette boucle constitue un interrupteur fermé, et dans ces conditions, le
transistor T1 reste bloqué et aucun son ne parvient à l'amplificateur constitué de deux
transistors complémentaires T2 et T3.
En revanche, s'il se produit une rupture du fil en question, la base du transistor T1 se
trouve libérée et les signaux engendrés par le multivibrateur sont amplifiés, par la section
basse fréquence et l'alarme est donnée.
En fait, la boucle peut même être remplacée par toute une série de contacteurs
spéciaux qui resteront fermés tant que la porte ou la fenêtre seront fermées et qui
s'ouvriront à l'ouverture et provoqueront donc l'alarme.
Enfin la tension d'alimentation du montage peut se réaliser de 4,5 à 13,5 V sans
problèmes.

Réalisation pratique
Pour l'implantation des éléments, vous le savez, certains composants sont polarisés
et comportent par conséquent une gorge, un point, un ergot, un repère qu'il convient de
judicieusement orienter. On se méfiera, également des transistors qui se présentent sous
un boîtier analogue T2 et T3 mais qui renferment une technologie différente NPN et PNP. Il
suffira donc d'ouvrir l'oeil et de surveiller les références inscrites en clair afin d'éviter toute
substitution, important.
Quant à la boucle de surveillance, vous pourrez la réaliser à l'aide d'un fil émaillé,
très fin, comme celui destiné à confectionner les bobinages. La longueur peut atteindre 10
voire même 20 mètres. Des méthodes très simples et très pratiques de mise en place du fil
peuvent se réaliser. Toutes les fois on cherchera la rupture, très facile du fil, compte tenu de
son diamètre par le débattement de la porte ou de la fenêtre, et même si l'intrus en venait à
trouver le fil, la coupure suffit à faire retentir l'alarme.

Liste des composants
R1 : 100k
R2 : 4,7 k
R3 : 2,2 k
R4 : 4,7 k
R5 : 220
T1 : 2N2907, ou 2N2904, ou BC178
T2 : 2N1613 ou 2N1711
T3 : 2N2905 ou 2N2904
C1 : 10 nF
C2 : 0,1 μF
C3 : 100μF/16V
C4 : 0,1 μF/16V
IC1 : NE555
1 haut parleur miniature de 8 ohm

Montage



![image](https://github.com/Aminehammou/Document-electronique/assets/133261059/d3e9bfba-5366-43ef-9d43-3fd39c1ef8ce)
