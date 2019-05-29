# Qu'est ce que Docker ?

##  Introduction

Docker est dans le monde de l’informatique un outil devenu référent en matière de conteneurs. Mais qu’est-ce qu’un conteneur ?

### Définition d’un conteneur :

Pour cette définition, j’aime faire un parallèle avec la vie de tous les jours. Pour nous le conteneur est devenu familier. Nous en voyons sur la route tous les matins lors des bouchons sur les camions, dans les ports lors des vacances, ou encore sur des trains de fret. Le conteneur permet donc de transporter toutes sorte de marchandises, peut importe la composition de celle-ci. Liquide, solide, gros volume, peu importe ; le conteneur **normalise le transport** de ces différentes marchandises. Le fait d’être dans des conteneurs permet aussi une augmentation de la sécurité suivant différents protocoles. Nous avons toujours l’image d’un conteneur de chaussures pour le pied droit, et d’une autre pour le pied gauche, ou encore le conteneur qui est sous scellé. Le conteneur en informatique part du même principe. Peu importe l’application, le conteneur pourra tourner sur les différentes plateformes, que ce soit en local ou sur des serveurs Google par exemple. C’est toute la magie du conteneur, il est léger, sécurisé, polyvalent et permet de répondre à de nombreuses problématiques que nous verrons tout au long du cours.

### Docker, qu’est-ce que c’est ?

Docker est une plateforme de conteneur qui a su démocratiser cette technologie. L’approche est simple et efficace. Il reprend le principe de base des conteneurs en y ajoutant des outils comme le Dockerfile ou le Docker-compose que nous verrons par la suite. Docker est gratuit est multiplateforme \(unix/windows\) cependant il requière d’être sur un environnement Windows pro pour le bon fonctionnement sur celui-ci. En effet il nécessite Hyper-V qui n’est accessible que sur Windows Pro. Nous verrons dans le chapitre suivant comment installer Docker sur les différents OS. Vous trouverez de nombreux articles sur comment marche Docker, pour ce cours nous ne rentrerons pas dans les détails. Dites vous que Docker est l’allégement d’une VM, il n’a pas de couche OS et partage les ressources de l’hôte.

