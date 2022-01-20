Transformez une maquette en site web

Scénario
Enfin, vous avez trouvé votre premier stage en tant que développeur web chez Reservia, une
petite entreprise proposant un outil de planification de vacances. Leur site permet aux usagers
de trouver des hébergements et des activités dans la ville de leur choix. Les hébergements
peuvent également être filtrés par thématique, par exemple leur budget ou leur ambiance.
Un nouveau design basé sur les principes du Material Design vient d’être proposé par Loïc,
designer UI.

Avant de valider définitivement ce design, l’entreprise décide de réaliser un prototype. La
première étape consiste à intégrer la maquette responsive en HTML et CSS. Voici donc la tâche
qui vous est attribuée ! Loïc vous envoie un mail pour vous en dire plus, en mettant en copie
Transformez une maquette en site web - OpenClassrooms 9/29/21, 12:07
https://openclassrooms.com/fr/projects/transformez-une-maquette-en-site-web/assignment Page 3 of 6
votre manager, Sarah, qui est CTO de l’entreprise.

De : Loïc
À : Vous
CC : Sarah
Objet : Intégration maquette Reservia
Bonjour !
!
Je t’envoie les nouvelles maquettes desktop et mobiles du site Reservia. Le dossier comprend
aussi les images. Voici quelques précisions qui te seront utiles pour l’intégration.
 Fonctionnalités
Les usagers pourront rechercher des hébergements dans la ville de leur choix. Le champ
de recherche est donc un champ de saisie, dont le texte peut être édité par l’usager. En
revanche, à ce stade, le bouton de recherche ne sera pas fonctionnel.
Chaque carte d’hébergement ou d’activité devra être cliquable dans son intégralité. Pour
l’instant les liens seront vides.
Les filtres ne seront pas fonctionnels pour cette version, en revanche, il faut qu’ils changent
d’apparence au survol. Je te laisse décider de l’effet le plus approprié.
Dans le menu, les liens “Hébergements” et “Activités” sont des ancres qui doivent mener
aux sections de la page.
 Contraintes techniques
Je te fournis deux maquettes : l’une desktop et l’autre mobile. Le site devra également être
adapté aux tablettes. Sur ce support, tu es libre de faire les adaptations nécessaires avec la
mise en page, tant qu’aucun élément n’est coupé et que le texte a une taille suffisante. Je
te laisse choisir les breakpoints appropriés.
Comme je ne savais pas de quels tailles et formats d’image tu avais besoin, j’ai exporté les
images en différents formats. Je te laisse choisir le format le plus adapté par rapport à la
résolution et au temps de chargement.
Les icônes proviennent de la bibliothèque Font Awesome. Les couleurs de la charte sont le
bleu #0065FC, et sa version plus claire #DEEBFF ainsi que le gris pour le fond #F2F2F2.
La police du site est Raleway.
Si tu as des questions n’hésite pas à m’écrire.
Bonne journée!

Vous vous plongez dans ce projet… Et commencez à vous poser quelques questions techniques
sur l’intégration. Heureusement, votre manager rebondit sur l’échange de mails pour vous
apporter des précisions !


À : Vous
CC : Loïc
Objet : RE - Intégration maquette Reservia
Hello,
J’espère que les premiers éléments partagés par Loïc te semblent clairs ! Comme c’est ton
premier projet avec nous et que tu es en stage, je voulais te guider un peu plus :
N’utilise pas de framework ou pré-compilateur CSS pour ce projet (comme SASS par
exemple) : comme tu démarres, je préfère que tu montes en compétences sur HTML et
CSS et que tu apprennes à coder from scratch. On aimerait tester tes compétences làdessus !
Je te recommande d'utiliser Visual Studio Code, plusieurs plugins pourront te simplifier la
vie, par exemple Live Server ou Prettier.
Tu peux intégrer les icônes Font Awesome en HTML ou CSS. Je te conseille fortement
d’utiliser Flexbox mais tu peux aussi utiliser CSS Grid si tu veux.
Ton code devra utiliser les balises sémantiques et ne doit contenir aucune erreur ni alerte
au validateur W3C HTML et CSS.
Le site devra être compatible avec les dernières versions de Chrome et Firefox.
Pense à séparer le HTML et le CSS et à organiser ton dossier de rendu.
N’oublie pas de versionner ton code avec Git, et ce dès les premières lignes de code. C’est
hyper important quand on travaille en équipe. Nous on utilise GitKraken comme client Git,
c'est plus sympa qu'une console, mais tu fais comme tu veux. Ensuite il faut que tu
déploies la page sur GitHub Pages ou GitLab Pages comme tu préfères.
À ta disposition pour en discuter !
Sarah
