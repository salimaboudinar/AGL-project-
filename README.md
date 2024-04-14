# AGL-project-
DIAGRAMME DE CAS D'UTILISATION
![CAP](https://github.com/salimaboudinar/AGL-project-/assets/68598374/adfc219c-6f36-4dc9-8db2-6321d2ab047f)
1.Introduction du projet :


Choix du sujet et description générale :


La domotique représente un système innovant qui offre la possibilité de gérer et d'automatiser divers équipements domestiques tels que l'éclairage, le chauffage, la climatisation, les serrures et les appareils électroménagers. 


Notre domotique aura le nom de CasaControl.


Son objectif premier est d'améliorer le confort, la praticité et l'efficacité énergétique de la maison.


Motivations :


Même si ce projet n’était pas notre premier choix, mais cette technologie a captivé notre intérêt pour plusieurs raisons : 


-	Selon une enquête de Vodafone, 84% des entreprises utilisent l'IoT dans leur activité en 2021. Puisque l'IoT fournit les bases technologiques nécessaires à la création de systèmes domotique, on doit être plus informé sur ces deux domaines.
-	On veut en savoir plus sur la domotique.
-            On veut travailler sur un système qui respecte l’environnement.
-	Le comfort est l’un des besoins essentiels des clients de nos jours. C’est pour cela qu'on veut être renseigné sur ce système tant demandé.
-            Les personnes en situation de handicap et les personnes âgées ont parfois des difficultés, voire même une incapacité totale à effectuer les activités quotidiennes de manière autonome.




Le périmètre du projet :


Le projet CasaControl vise à développer un système domotique complet et personnalisable, offrant une gamme variée de fonctionnalités pour répondre aux besoins individuels des utilisateurs. 

Parmi ces fonctionnalités, on retrouve : 

Le contrôle avancé de l'éclairage
La gestion intelligente de l'énergie
La surveillance proactive de la maison grâce à des capteurs et des caméras
La visualisation à distance via des appareils connectés 
Les alertes en temps réel sur smartphone ou ordinateur
Le stockage sécurisé des enregistrements vidéo
Le contrôle d'accès à distance 
L'automatisation des tâches domestiques. 

En combinant ces éléments, CasaControl offre une solution complète pour rendre chaque domicile plus intelligent, sécurisé et efficace.




2.Spécifications du projet :

a) Notions de base et contraintes du projet :


Les systèmes domotiques se basent sur l'utilisation de capteurs, d'actionneurs et de contrôleurs pour surveiller l'environnement domestique et prendre des décisions en fonction des données collectées. 

Par exemple, un capteur de mouvement peut détecter la présence de personnes dans une pièce et réguler automatiquement l'éclairage.

Les thermostats intelligents ajustent la température de la maison selon l'heure et les préférences des occupants.

La domotique permet un contrôle à distance via des appareils tels que les smartphones, tablettes ou ordinateurs, offrant ainsi aux utilisateurs la possibilité de gérer leurs équipements même lorsqu'ils sont absents.

Les systèmes domotiques peuvent être intégrés à des dispositifs de sécurité pour surveiller la maison à distance et alerter les propriétaires en cas d'intrusion ou de problème.

Les contraintes peuvent être des obstacles à ces notions de ce système, tels que :


L’intégration étroite de capteurs (par exemple, capteurs de mouvement, détecteurs de fumée) et d'une variété d’actionneurs (comme les lumières, les serrures intelligentes).

La nécessité de télécharger un programme informatique pour établir la communication avec le système domotique et contrôler les appareils connectés.

La réactivité en temps réel du système pour garantir un contrôle et une surveillance efficaces des équipements connectés, incluant des critères tels que le temps de réponse, la gestion énergétique..

La communication avec les dispositifs de manière cohérente et fiable, en prenant en compte les protocoles de communication spécifiques à chaque dispositif.

La collecte, le traitement et l’analyse efficaces de grandes quantités de données afin de fournir des fonctionnalités telles que l'automatisation des tâches, la détection d'anomalies..


La mise en œuvre des protocoles de sécurité robustes pour protéger les données sensibles sur la vie privée et la sécurité des utilisateurs en transit et au repos, ainsi que pour sécuriser l'accès aux appareils connectés.

Le fonctionnement de manière fiable, même dans des conditions imprévues ou en cas de défaillance d'un composant.



Considération des besoins et des préférences des utilisateurs dans la conception des interfaces utilisateur pour qu’elles soient conviviales, faciles à utiliser et intuitives .

b) Description des acteurs et fonctionnalités attendues du projet :


Notre système domotique va offrir une gamme variée de fonctionnalités répondant aux besoins et aux préférences individuels des utilisateurs.


L'utilisateur est le principal acteur du système CasaControl. Il interagit avec le logiciel via une interface utilisateur graphique (IHM) pour contrôler et surveiller les équipements de sa maison intelligente.


Voici une description détaillée des fonctionnalités présentées :


Contrôle de l'éclairage : possibilité d'allumer/éteindre, ajuster l'intensité ou la couleur des lumières, et programmer des scénarios d'éclairage.


Gestion de l’économie de  l'énergie : optimisation de la consommation énergétique en régulant les équipements selon les besoins réels et en détectant les gaspillages.


Surveillance de la maison, en temps réel et à distance : détection des intrusions, des fuites d'eau, des incendies, etc., grâce à des capteurs et des caméras de surveillance avec stockage des enregistrements ( dans le cloud ou sur un support local ) et réception des alertes lors des scénarios anormaux ( via des appareils connectés sur smartphone ou ordinateur par exemple ).


Automatisation des tâches : contrôle de la musique, ainsi que la possibilité d’ouvrir/ fermer les portes et les volets, à distance pour les visiteurs autorisés. 
d) Priorité des cas d’utilisation :


Dans l'ordre de priorité des cas d'utilisation pour un système domotique, "Surveiller la maison" est placé en premier, suivi de "Gérer l'économie d'énergie" et enfin "Automatiser les tâches". 

Cette hiérarchisation reflète l'importance de garantir la sécurité et la surveillance de l'environnement domestique en premier lieu, avant de considérer des fonctionnalités visant à optimiser la consommation d'énergie et à automatiser les tâches pour plus de commodité. 

Ainsi, la surveillance de la maison est cruciale pour assurer la tranquillité d'esprit des utilisateurs, suivie par la gestion de l'énergie, tandis que l'automatisation des tâches est considérée comme une valeur ajoutée qui peut améliorer l'efficacité mais qui est moins prioritaire que les deux premiers cas d'utilisation.
1)Surveiller la maison
Table de décision des tests de validation :

| Pré condition             | Test 1 | Test 2 | Test 3 | Test 4 |
|---------------------------|--------|--------|--------|--------|
| communication existante   | F      | T      | T      | T      |
| propriétaires authentifiés| F      | T      | T      | T      |
| équipement fonctionnel    | F      | F      | T      | T      |
| *Post condition*        | *Test 1* | *Test 2* | *Test 3* | *Test 4* |
| sécuriser maison          | F      | F      | F      | T      |
| nombre de test            | 1      | 1      | 1      | 1      |

2)Économiser l'énergie
Table de décision des tests de validation :
| Pré condition                     | Test 1 | Test 2 | Test 3 | Test 4 |
|-----------------------------------|--------|--------|--------|--------|
| communication existante           | F      | T      | T      | T      |
| Faire une analyse de la consommation d'énergie | F      | T      | T      | T      |
| équipement fonctionnel            | F      | F      | T      | T      |
| *Post condition*                | *Test 1* | *Test 2* | *Test 3* | *Test 4* |
| économie d'énergie atteint        | F      | F      | F      | T      |
| nombre de test                    | 1      | 1      | 1      | 1      |

3 )Économie d'énergie contrôlée et maîtrisée
Table de décision des tests de validation :
| Pré condition                           | Test 1 | Test 2 | Test 3 | Test 4 | Test 5 |
|-----------------------------------------|--------|--------|--------|--------|--------|
| communication existante                 | F      | T      | T      | T      | T      |
| Faire une analyse de la consommation d’énergie | F      | T      | T      | T      | T      |
| équipement fonctionnel                  | F      | F      | T      | T      | T      |
| tâche à automatiser configurée dans le système | F      | F      | F      | T      | T      |
| *Post condition*                      | *Test 1* | *Test 2* | *Test 3* | *Test 4* | *Test 5* |
| tâche automatisée                       | F      | F      | F      | F      | T      |
| nombre de test                          | 1      | 1      | 1      | 1      | 1      |


