<!--------------------------------------------------------- Arduino et les bases de l’IoT ------------------------------------------------------------->

#   (29/01/2024 - 02/02/2024) Semaine 1 :

Durant ma première semaine en spécialité IoT, j'ai appris à utiliser Arduino qui est un logiciel de prototypage, qui 
permet de créer des objets électroniques interactifs (des objets connectés) à partir de cartes électroniques 
matériellement libres sur lesquelles se trouve un microcontrôleur.

C’est à partir de là que nous avons commencé un projet basé sur l’utilisation d’une carte 
Arduino. C’est un projet qui était déjà commencé bien avant mon arrivé. Ce projet consiste à pouvoir indiquer
aux utilisateurs si la pièce dans laquelle ils sont ai pollués ou pas. Pour les guidés, un oiseau va grâce 
aux servo moteurs, progressivement s’incliné jusqu’à s’être à l’envers la tête dans le vide, si l’air est 
pollué. Dans le cas contraire, l’oiseau reste à l’en droit si l’air n’est pas pollué.

Grâce à cette carte électronique, j'ai pu rajouter des puces qui captent des données sur 
la vitesse de déplace de celle-ci, mais aussi j'ai pu rajouter un servo moteur qui peut faire tourner un 
support comme une hélice.

Enfin, j'ai rajouté sur la carte Arduino un Ecran sur lequel, il me renvoie des données sur 
les particules de l’air. 

Vers la fin de semaine, j’ai utilisé une carte XiaoESP32 dans lequel j’ai du la branché sur 
le Shield, composé de plusieurs pin, dont j’ai du branché un Grove - Laser PM2.5 Sensor (HM3301) qui permet 
grâce à un ventilateur et des lasers de calculer les particules de l’air

Cependant, j’ai eu beaucoup de difficulté à la mise en place du système car j’avais du mal 
a cerné certaines branchements comme pour Grove - Laser PM2.5 Sensor (HM3301) dont j’ai du trouvé le bon pin 
et à aussi le programmé comme il le faut.

Cette difficulté a été aussi ressenti dans la programmation du servo moteur dans le projet 
à le faire tourner selon la quantité d’air saturé. Mais aussi dans les branchements de la XiaoESP32 car elle 
avait souvent tendance a planté.

C’est surtout durant la dernière jour de la semaine, que j’ai pu me rendre compte de mes 
difficultés car certains erreurs dans mon code était très difficile à faire partir notamment pour les trois
objets sités dans le paragraphe précédents (Grove - Laser PM2.5 Sensor (HM3301), XiaoESP32 et le servo moteur), qui m’ont fait perdre beaucoup de temps.

<!--------------------------------------------------------------- Modélisation sur Fusion360 ---------------------------------------------------------------------->

A la fin de la semaine, on m’a initié à la modélisation 3D sur fusion360, dans lequel, j’ai 
pu concevoir un dé à 6 afin de vraiment pratiquer et tester le logiciel ainsi que de voir son fonctionnement

Ensuite, avec ce logiciel, j’ai pu me consacré à la création d’une pièce importante du  projet qu’il valait refaire.

J’ai pu même la concevoir grâce à une imprimante 3D qui a matérialisé physiquement l’objet modélisé.






<!--////////////////////////////////////////////////////////////////////////////\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\-->






#   (06/02/2024 - 09/02/2024) Semaine 2 :

<!--------------------------------------------------------- Initiation à Prisma et la création d'API ------------------------------------------------------------->

Durant une grande partie de la dernière semaine, on m’a initié à Prisma qui est un ORM Node.js et TypeScript qui permet de
travailler avec des bases de données grâce à son modèle de données intuitif, ses migrations automatisées, sa sécurité de type et sa complétion
automatique. 

Avec Prisma,on m'a appris les bases grâce aux docs qu'on retrouve sur internet qui nous apprend correctement les bonnes configurations
à faire sur Visual Studio, mais aussi grâce nos enseignants j'ai appris à utiliser de manière correct les API et Prisma, qui n'ont pas été facile à cerner 
pour moi au début (j'ai eu du mal sur tout :)).
Le plus difficile au début a été sur la suite car, j'ai codé du coder une application web dans lequel j'ai crée des API pour ajouter, mofier et supprimer des
données de ma BDD.
Je n'ai pu finir malheureusement par manque de temps, mais aussi de compréhension dans le code.

<!-------------------------------------------------------------- Projet du Baby-foot Connectée ------------------------------------------------------------------->

#   (27/02/2024 - 01/03/2024) Semaine 3 :

<!--------------------------------------------------- Présentation ---------------------------------------------------------->

Le mardi 28 Février 2024, mes camarades et moi avons commencé à choisir un projet parmi : le dévérouillage
d'un porte avec une empreinte digitale, un distributeur de nourriture pour animaux connecté, un babyfoot connecté ainsi qu'un 
cat feeder (c'est la meme chose que mon projet) automatisé.

A l'unaminité,j'ai choisi ainsi que tts mes camarades le baby-foot connecté car, c'était le projet le plus
passionnant à mes yeux, car nous allions apporter des fonctionnalités sur un vrai baby-foot, notamment un système de Goalinline (
un laser qui détecte si le ballon à franchi la ligne de but), un écran qui affiche le score (un écran ssd relié à la goalinline),
Des LED qui afficheront des couleurs différentes s'il y a un but et une application dans lequelle il y aura une page connexion, 
une page pour s'inscrire, un menu avec un bouton pour créer une partie. <br/><br/>
Les joueurs pourront créer une partie grâce à un formulaire qui comprend: le nombre de joueur, le choix du mode (2vs2,1vs1 ou un tournoi)
et le baby-foot.

<!------------------------------------------------------- Recherche & Développpement --------------------------------------------->

Dans la meme journée, nous avons commencé à faire des recherches sur les matériaux qui nous faudraient pour 
faire ce projet.<br/><br/>
Mais au cours de cette journée, j'ai rencontré un problème avec mes camarades car l'université ne disposait pas de baby-foot, et
le coute pour acheter un baby-foot n'est pas donnée (~230€).<br/><br/>
Par la suite, nous nous sommes répartis les taches et pour ma part, j'avais décidé de faire la connexion à l'application du baby-foot.

<!------------------------------------------------------ Prototypage et début de la conception ---------------------------------->

#   (05/03/2024 - 08/03/2024) Semaine 4 :

// 05-03-2024
Cette semaine, je me suis tt d'abord consacrée à la recherche d'une idée prototypage du kit sur le babyfoot, dont mon idée à été de crée un kit en plusieurs partie, avec le panneau des "sponsors" coupé en 4 partie,
puis par dessus on clipsera un autre kit au dessus des cages qui comprend 2 hauts-parleurs, un écran ainsi que le capteur infrarouge.

Ensuite, j'ai testé un écran lcd pour vérifier s'il fonctionnait ou pas. Puis, j'ai réfléchi avec mes camarades sur l'utilisation un écran tactile au lieu d'un écran non-tactile.
Après mur réflexion avec mes camarades, on a décidé d'utiliser l'écran tactile car dessus on pouvait beaucoup plus facilement d'jouter des joueurs dans une partie.

Après cela, j'ai commencé un début de maquette en fin de journée que j'ai pas pu finir par manque de temps.

// 06-03-2024

Le jour suivant, j'ai repris mon travail sur la maquette avec tts mes collègues, puis une fois la maquette du terrain du baby-foot terminé, j'ai conçu une maquette de ce que donnerait le kit sur un cage (j'ai mis pour l'instant que l'écran).

Puis cet après-midi, moi et mes camarades nous nous sommes répartis les taches sur la partie électronique du babyfoot. Pour ma part j'ai choisi de faire la parti de la programmation du laser avec la XIAOESP32 afin qu'il puisse détecter un objet qu'il traverse.
Mais durant la montage pour faire fonctionner le laser, je me suis rendu compte que les files du laser sont très fines et fragiles. Pour compenser ce problème, j'ai soudé ces files avec d'autres files plus solides.

![Cover](https://github.com/Midza21/iliaes_p1.github.io/assets/99647643/6ad3b04e-cd2d-428d-852e-4fdbbd2798c5)

// 07-03-2024

// 08-03-2024

Aujourd'hui, j'ai commencé agrandir l'axe de mon prototype pour le laser car il ne rentrait pas dedans. Puis ensuite, j'ai pu finir de souder le fil de l'analog sur la photorésistance et la résistance. Une fois que j'avais fini de les souder, j'ai testé la photorésistance sur une Arduino Uno, dans son support dans le prototype, avec le laser pile en face.

Une fois le test réussi, j'ai testé mon code sur le XIAO ESP32S3 et cela à fonctionner. Une ce test fait, j'ai aidé mon camarade Saïd a fini régler des problèmes liées à ESP32 avec les LED sur son pc. 

<!------------------------------------------------------ Montage Babyfoot et de la partie électro ------------------------------------------------->

#   (26/03/2024 - 28/03/2024) Semaine 5 :

// 26/03/2024
Aujourd'hui, j'ai repris ma partie sur l'allumage des LED quand la balle traverse un laser, avec la phase de test cette fois sur mon pc avec tt d'abord des LED fonctionnel, cette étape m'a pris tt la matinée car j'ai eu des difficultés sur le branchement des LED ainsi que sur le pin a ciblé de led.

L'après-midi, j'y ai consacré l'entièreté à tester d'autres LED dont l'aspect était beaucoup mieux, puis après de nombreux tests je n'ai fini pas pu les faire fonctionner, car j'ai eu beaucoup de difficulté sur le branchage de des led ainsi que sur la pin a ciblé.

// 27/03/2024
Aujourd'hui, j'ai repris mon travail sur le test d'autres led mais, malheureusement je n'ai pas pu les faire fonctionner car l'ESP32 a fini par griller à cause de cette dernière mais aussi par la complexité à la faire fonctionner. Donc c'est pour cela que je me suis rabbatu sur l'essentiel à savoir faire transiter les données du buts vers l'appli via le Wifi.

L'après midi, j'ai continué dessus mais je n'ai pas pu le finir et j'étais meme proche du but. Malheureusement cela est du, car j'ai eu beaucoup d'erreur de code sur Arduino.
