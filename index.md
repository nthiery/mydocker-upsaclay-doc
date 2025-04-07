# MyDocker@Paris-Saclay

[MyDocker@Paris-Saclay](https://mydocker.universite-paris-saclay.fr/)
est un service d'environnements virtuels permettant d'accéder à de
nombreux logiciels scientifiques (dont Jupyter) à partir d'un simple
navigateur web, notamment pour du calcul interactif, du traitement de
données, etc.

Ce service est ouvert aux étudiants et personnels de l'Université
Paris-Saclay. À titre expérimental, il est ouvert plus généralement
aux établissements de la fédération d'identité «Recherche et
Enseignement Supérieur» de Renater); [contactez](contact) nous avant
tout usage intensif.

% Les activités ci-dessous donnent quelques exemples d'environnements
% disponibles sur myDocker. Si vous souhaitez obtenir de l'aide sur
% l'utilisation ou la création d'environnements myDocker (notamment en
% urgence pour des TPs commençant dans la zone de turbulence actuelle à
% Paris-Saclay), vous pouvez contacter Nicolas Thiéry.

## Accès aux environnements

Les items ci-dessous vous donne accès à quelques environnements
génériques. Si vous êtes enseignante ou enseignant, vous pouvez créer
vos propres environnements (documentation à venir), voire proposer
qu'ils soient ajoutés ici. De nombreux autres environnements ont été
créés par des collègues pour toutes sortes de besoin.

Votre [page d'accueil de
myDocker](https://mydocker.universite-paris-saclay.fr/) vous donne
accès à tous les environnements que vous avez déjà utilisé.


:::{admonition} Clone de JupyterHub@Paris-Saclay [Démarrer l'environnement](https://mydocker.universite-paris-saclay.fr/shell/join/qWsmLepfAkaFqYIQBjKL)
:class: dropdown

- Logiciels: Python et ses bibliothèques classiques, SageMath, C++, R, ...
- Interfaces: JupyterLab, Jupyter, Visual Studio Code ou environnement de bureau graphique XFCE
- Ressources: dossier personnel persistant global, 2 CPU, 4Go RAM, extinction après 20 minutes sans interaction

Cet environnement multiusage est strictement identique à celui déployé
sur l'ancien service JupyterHub@Paris-Saclay et a vocation à faciliter
la transition.

Limitation: cet environnement n'a été mis à jour que à la marge depuis
septembre 2023 et restera en l'état. Les versions des logiciels installés y sont donc
vieillissantes. D'autre part il peut être long à charger du fait de sa
taille. **Sauf besoin spécifique, nous recommandons l'usage d'un des
environnements plus spécialisés.**

:::

:::{admonition} JupyterLab et Python [Démarrer l'environnement](https://mydocker.universite-paris-saclay.fr/shell/join/IvvgFOBBFzGLwuGJeFSb)
:class: dropdown

- Interface: JupyterLab en Français
- Logiciels: Python, Numpy, SciPy, MatPlotLib, Pandas, conda, pip, ...
- Ressources: dossier personnel persistant global, 2 CPU, 4Go RAM, extinction après 20 minutes sans interaction, agent conversationnel
- Cours: [«Introduction à la programmation avec Python et Jupyter»](https://introductionprogrammationpython.pages.centralesupelec.fr/), ...
- [Configuration de l'environnement](https://mydocker.universite-paris-saclay.fr/admin/courses/21/edit) (accès restreint)
- [Configuration de l'image](https://gitlab-research.centralesupelec.fr/IntroductionProgrammationPython/introductionprogrammationpython.pages.centralesupelec.fr/)
- Mainteneur: Nicolas M. Thiéry

Cet environnement est conçu pour des usages simple de Python,
notamment pour de l'initiation à la programmation et au calcul.

:::

:::{admonition} JupyterLab, Python et bibliothèques scientifiques [Démarrer l'environnement](https://mydocker.universite-paris-saclay.fr/shell/join/adNzzJUzLSjBjmwQohnD)
:class: dropdown

- Interface: JupyterLab
- Logiciels: Python, Numpy, SciPy, MatPlotLib, Pandas, scikit-learn, conda, pip, ...
- Ressources: dossier personnel persistant global, 2 CPU, 4Go RAM, extinction après 20 minutes sans interaction
- [Configuration de l'environnement](https://mydocker.universite-paris-saclay.fr/admin/courses/34/edit) (accès restreint)
- Mainteneur: Nicolas M. Thiéry

Cet environnement est basé sur l'image
[jupyter-scipy-notebook](https://jupyter-docker-stacks.readthedocs.io/en/latest/using/selecting.html#jupyter-scipy-notebook)
de la communauté Jupyter.

:::


:::{admonition} JupyterLab et PyTorch pour l'apprentissage profond [Démarrer l'environnement](https://mydocker.universite-paris-saclay.fr/shell/join/PQCQGTeqRfsuQaTHOmmd)
:class: dropdown

- Interface: JupyterLab
- Logiciels: Python, Numpy, SciPy, MatPlotLib, Pandas, scikit-learn, PyTorch, conda, pip, ...
- Ressources: dossier personnel persistant global, 4Go RAM, extinction après 20 minutes sans interaction
- Mainteneur: Nicolas M. Thiéry
- [Configuration de l'environnement](https://mydocker.universite-paris-saclay.fr/admin/courses/35/edit) (accès restreint)

Cet environnement est basé sur l'image
[jupyter/pytorch-notebook](https://jupyter-docker-stacks.readthedocs.io/en/latest/using/selecting.html#jupyter-pytorch-notebook)
de la communauté Jupyter.

Pour des raisons techniques, il n'y a actuellement pas de limites sur
l'usage CPU. Merci de ne pas en abuser!

:::


:::{admonition} JupyterLab et C++ [Démarrer l'environnement](https://mydocker.universite-paris-saclay.fr/shell/join/pQlQsEaZSPJMBsBtbxOD)
:class: dropdown

- Interface: JupyterLab, en Français
- Logiciels: compilateurs (gcc, clang) et interpréteur (cling) C++, Travo, ...
- Ressources: dossier personnel persistant global, 2 CPU, 4Go RAM, extinction après 20 minutes sans interaction, agent conversationnel
- Cours:
  - «Introduction à la Programmation Impérative», L1 Math-Info, S2, Faculté des Sciences d'Orsay
  - Programmation Modulaire, L1 Math-Info, S2, Faculté des Sciences d'Orsay
  - «Algorithmes et Structures de Données», L1 Math-Info, S2, Faculté des Sciences d'Orsay
  - «Info 1», Polytech
  - ...
- Mainteneur: Nicolas M. Thiéry
- [Configuration de l'environnement](https://mydocker.universite-paris-saclay.fr/admin/courses/16/edit) (accès restreint)
- [Configuration de l'image](https://gitlab.dsi.universite-paris-saclay.fr/Info111/ComputerLab/-/tree/master/binder)

:::


:::{admonition} JupyterLab et SageMath [Démarrer l'environnement](https://mydocker.universite-paris-saclay.fr/shell/join/gkctIyHvdZkofetGeMju)
:class: dropdown

- Interface: JupyterLab, en Français
- Logiciels: SageMath, Travo
- Ressources: dossier personnel persistant global, 2 CPU, 4Go RAM, extinction après 20 minutes sans interaction, agent conversationnel
- Cours:
  - «Option C: Algèbre et Calcul Formel», Agrégation de Mathématique, Faculté des Sciences d'Orsay
  - «Combinatoire et Calcul algébrique», M1 MPRI, Faculté des Sciences d'Orsay
  - «Projet Math-Info», LDD1 Math-Info, S2, Faculté des Sciences d'Orsay
  - ...
- Mainteneur: Nicolas M. Thiéry
- [Configuration de l'environnement](https://mydocker.universite-paris-saclay.fr/admin/courses/20/edit) (accès restreint)
- [Configuration de l'image](https://gitlab.dsi.universite-paris-saclay.fr/M2MathAgregation/ComputerLab)

:::

:::{admonition} 🚧JupyterLab et Julia [Démarrer l'environnement](https://mydocker.universite-paris-saclay.fr/shell/join/ilpJoKzaJZVisfPVJLcL)🚧
:class: dropdown

- Interface: JupyterLab, en Français
- Logiciels: Julia with packages SymPy, Plots, Statistics, DataFrames,
  DSP, Latexify
- Ressources: dossier personnel persistant et dossier personnel global (dans shared/), 2 CPU, 4Go RAM, extinction après 30 minutes sans interaction
- Cours: ???
- Mainteneur: Nicolas M. Thiéry, Bastien Berret
- [Configuration de l'environnement](https://mydocker.universite-paris-saclay.fr/admin/courses/8/edit) (accès restreint)
- [Configuration de l'image](https://gitlab.dsi.universite-paris-saclay.fr/jupyterhub-paris-saclay/images-alternatives/julia)

Cet environnement est basé sur l'image
[jupyter/pytorch-notebook](https://jupyter-docker-stacks.readthedocs.io/en/latest/using/selecting.html#julia-notebook)
de la communauté Jupyter.

:::

:::{admonition} 🚧JupyterLab et SQL [Démarrer l'environnement](https://mydocker.universite-paris-saclay.fr/shell/join/BwDiQTSWOZJdqReXqpdV)🚧
:class: dropdown

- Interface: JupyterLab
- Logiciels: PostgreSQL, Python et bibliothèque psycopg2
- Ressources: dossier personnel persistant avec dossier de données
  dans ~/pgsql/data, 2 CPU, 4Go RAM
- Services:
     - PostgreSQL (disponible au démarrage, `psql --list` visualise les bases déjà existantes),
     - Serveur web (peut être démarré avec `python -m http.server` dans le dossier choisi; pages consultables via `https://<mydocker-host>/proxy/8000`)
- Cours: ???
- Mainteneur: Chiara Marmo
- [Configuration de l'environnement](https://mydocker.universite-paris-saclay.fr/admin/courses/56/edit) (accès restreint)

Cet environnement est basé sur l'image
[jupyter/minimal-notebook](https://jupyter-docker-stacks.readthedocs.io/en/latest/using/selecting.html#jupyter-minimal-notebook).

:::

:::{admonition} 🚧JupyterLab et R [Démarrer l'environnement](https://mydocker.universite-paris-saclay.fr/shell/join/yTiJIgUfGnwEMXztjsXH)🚧
:class: dropdown

- Interface: JupyterLab
- Logiciels: R et paquets R usuels
- Ressources: dossier personnel persistant, 2 CPU, 4Go RAM
- Cours: ???
- Mainteneur: Nicolas M. Thiéry
- [Configuration de l'environnement](https://mydocker.universite-paris-saclay.fr/admin/courses/53/edit) (accès restreint)
- [Configuration de l'image](https://mydocker.universite-paris-saclay.fr/admin/images/32/edit)

Cet environnement est basé sur l'image
[jupyter/r-notebook](https://jupyter-docker-stacks.readthedocs.io/en/latest/using/selecting.html#jupyter-r-notebook).

Cet environnement est en cours d'élaboration. Nous [contacter](contact) pour toute
suggestion de paquet R classique à ajouter est bienvenue; de même si vous souhaiteriez
utiliser RStudio ou Rcmd.

:::

## À propos du service

:::{admonition} Fonctionnalités essentielles
:class: hint dropdown

- **Ubiquité**: Utilisation depuis un simple navigateur web.
- **Urbanisation**: authentification via la fédération d'identité
  «Recherche et Enseignement Supérieur» de Renater, ou bien par
  intégration comme outil externe dans Moodle (ou autre LMS compatible
  LTI).
- **Environnement au choix**, basés ou non sur Jupyter  
  Avec possibilité de définir des environnements personalisés pour
  choisir finement les logiciels et ressources utilisées.
- **Scalabilité:** dimensionné pour plusieurs centaines (milliers?)
  d'utilisateurs simultanés pour des usages interactifs légers (quelques CPUs).  
  Pour des besoins plus lourds, notamment de GPU pour des applications
  en IA, il est possible au cas par cas d'utiliser l'[instance
  myDocker de Centrale-Supélec](https://mydocker.centralesupelec.fr/),
  dont les serveurs sont loués à la demande. Nous [contacter](contact).
- **Persistance des données**.
- **Hébergement souverain**.
- **IA**: intégration d'un agent conversationnel souverain (Aristote).

:::

:::{admonition} Historique: de JupyterHub@Paris-Saclay à myDocker@Paris-Saclay
:class: hint dropdown

De 2017 à 2024, l'Université Paris-Saclay a mis à disposition de ses
personnels et étudiants un service d'environnements virtuels
[JupyterHub@Paris-Saclay](https://jupyterhub.ijclab.in2p3.fr/) donnant
accès à de nombreux logiciels scientifiques (dont Jupyter). Ce service
était hébergé et coopéré par le Mésocentre
[DataCenter@UPSud](https://www.informatique-scientifique.u-psud.fr/)
de Paris-Saclay et a été utilisé par 8000 personnes de l'enseignement
supérieur et de la recherche, dont 5000 à Paris-Saclay, avec une
centaine d'utilisateurs quotidiens.

En parallèle, CentraleSupélec avait développé et déployé en 2019 un
service similaire, myDocker, avec un accent mis sur la
personnalisation des environnement, la mise à disposition de
ressources plus lourdes (GPU), la scalabilité et la maîtrise de
l'empreinte écologique, pour des enseignements d'intelligence
artificielle, de développement informatique, de simulation numérique,
de modélisation, etc.

Entre novembre 2024 et janvier 2025, et avec le soutien financier du
CMA SaclAI-School, les deux équipes ont opéré une convergence entre
les deux services, avec une montée en gamme de myDocker pour couvrir
les usages en cours à Paris-Saclay et le déploiement de
myDocker@Paris-Saclay qui prend le relais de JupyterHub@Paris-Saclay.

Pour faciliter la migration, un environnement logiciel strictement
identique à celui de JupyterHub@Paris-Saclay est disponible et les
données ont été transférées automatiquement. La migration a été
perturbée et retardée par la cyberattaque donnant lieu à deux étapes:
- Fin octobre 2024: migration des données pour les utilisateurs avec
  un compte Adonis @universite-paris-saclay.fr
- Première semaine de janvier 2025: migration des données pour les
  autres utilisateurs.

Au cas où des utilisateurs aient utilisé les deux services pendant
leur cohabitation, si un fichier existait sur les deux services, la
migration a mis sur myDocker@Paris-Saclay la version la plus récente.

:::

:::{admonition} myDocker@CentraleSupelec et myDocker@Paris-Saclay
:class: hint dropdown

Le service
[myDocker@CentraleSupelec](https://mydocker.centralesupelec.fr/) est
maintenu en parallèle de myDocker@Paris-Saclay. Il est hébergé sur des
serveurs souverains loués à la demande auprès d'OVH. Il est destiné en
priorité aux étudiants et personnels de CentraleSupelec. À titre
expérimental, et en attendant la définition d'un modèle économique
adéquat, un accès peut être donné au cas par cas via eCampus pour des
usages lourds (notamment accès GPU). Du fait du modèle par location,
il est nécessaire de planifier les sessions.

:::

:::{admonition} Remerciements
:class: hint dropdown

Le service myDocker@Paris-Saclay est copiloté par la Faculté des
Sciences et Centrale Supélec, opéré par CentraleSupélec, codévelopé
par la [DISI](https://mycs.centralesupelec.fr/fr/support-DISI) de
CentraleSupelec et [Illuin](https://www.illuin.tech/), cofinancé par
le CMA [SaclAI-School](https://www.dataia.eu/saclai-school) et hébergé
par le mésocentre
[DataCenter@UPSud](https://www.informatique-scientifique.u-psud.fr/).

:::

(contact)=
## Contact et support technique

En cas de panne du service, ou pour de l'aide à l'organisation de
cours utilisant myDocker, vous pouvez contacter le support technique:
[mydocker-upsaclay@listes.centralesupelec.fr](mailto:mydocker-upsaclay@listes.centralesupelec.fr).

## Limitations connues et résolution de problèmes

### Authentification

- Symptôme: Auprès l'étape d'authentification, myDocker affiche
  «impossible de s'authentifier»:  
  Vérifier que l'ordinateur d'où l'on accède à myDocker est bien à
  l'heure. Un décalage de plus de quelques minutes bloque
  l'authentification pour des questions de sécurité. Une évolution de
  mydocker est prévue pour avoir un message clair dans ce cas.

### Démarrage d'un environnement

- Lorsque que le démarrage d'un environnement mets du temps ou échoue,
  très peu de retour est donné à l'utilisateur, rendant le diagnostic
  difficile. Cela sera progressivement amélioré dans les semaines qui
  viennent.

- Le temps de démarrage d'un environnement est souvent plus long qu'il
  ne devrait. Cela apparaît notamment lorsque l'environnement n'a été
  utilisé par personne depuis le week-end précédent et nécessite donc
  un retéléchargement de l'image. Normalement on peut contourner cela
  en rechargeant la page et redemandant un environnement et cela fini
  par passer au bout de quelques essais. Ce problème est en cours
  d'analyse.

### Usage

- **Symptôme:** erreur Keybord interrupt et plantage de
  l'environnement lors d'un calcul nécessitant du parallélisme massif
  (par exemple apprentissage avec scikit-learn ou pytorch)  
  **Analyse:** sur l'instance mydocker de Paris-Saclay basée sur
  Docker-Swarm, lorsque la limitation en nombre de CPU utilisé est
  atteinte, le conteneur entier est tué avec un signal SIGTERM, plutôt
  que de continuer en respectant la limite.  
  **Contournement:** ne pas mettre de limite de CPU à l'environnement.

- Le déploiement actuel ne permet pas encore la collaboration temps
  réel entre plusieurs utilisateurs dans le même environnement.

Suite à venir

## Documentation

### Concepts

myDocker mets à la disposition de ses utilisatrices et utilisateurs
une variété d'**environnements virtuels** (ou simplement
**environnements**), fournis à la demande; chacun de ces environnement
virtuel consiste en un ensemble de ressources :

- une **interface utilisateur** (ex. Jupyter, RStudio, VSCode,
  environnement de bureau type XFCE, terminal via SSH, ...)  donnant
  accès à des **logiciels** (ex. Python, scikit-learn) et des
  **données**
- avec un dossier personnel
- le tout s'appuyant sur des ressources physiques: processeur (CPU,
  GPU), mémoire, espace disque, etc.


Lorsque l'utilisateur **demande un environnement** :
1.  un serveur est identifié pour héberger l'environnement
2.  l'**image docker** contenant les logiciels de l'environnement est
    téléchargée sur ce serveur (si elle n'y est pas déjà présente);
3.  une machine virtuelle légère (conteneur docker) est lancée sur le
    serveur;
4.  le cas échéant, le [dossier personnel](dossiers_personnels) de
    l'utilisateur est monté dans la machine virtuelle;
5.  l'interface utilisateur est démarrée dans la machine virtuelle, et
    mise à disposition de l'utilisateur, typiquement via une nouvelle
    page web.


:::{attention}

Dans l'interface actuelle de myDocker, les environnements sont appelés
*Cours*. Cette terminologie -- provenant de l'usage initial de
myDocker -- peut maintenant prêter à confusion et sera changée. En
effet, un même environnement peut être utilisé par de nombreux cours,
et un même cours pourrait utiliser plusieurs environnements.

:::

### Demander un environnement

Pour demander un environnement, l'utilisateur peut au choix :

- le sélectionner depuis son tableau de bord s'il l'a déjà utilisé;
- ouvrir un lien web (URL) de la forme `https://mydocker.../join/xxxx`
  où `xxx` identifie l'environnement. Cette lien peut par exemple
  venir de cette page de documentation du service, ou être fournie par
  un enseignant, par mail, sur la page web du cours, ou via un
  Environnement Numérique de Travail comme Moodle;
- ouvrir une [**activité myDocker**](activite_lti) depuis un
  Environnement Numérique de Travail comme Moodle. Une telle activité
  utilise le protocole d'intégration LTI qui permet de transmettre à
  myDocker l'identité de l'utilisateur et son [rôle](roles) (élève,
  professeur).

(dossiers_personnels)=
### Dossiers personnels persistants

Dans la plupart des environnements virtuels, l'utilisatrice dispose
d'un dossier pour héberger des documents personnel. Ce dossier est
persistant: l'utilisatrice y retrouvera ces documents après avoir
éteint puis redémarré l'environnement. Selon l'environnement, ce
dossier personnel peut être dédié à l'environnement, ou partagé avec
les autres environnements (global).

:::{note}
La politique de rétention des données décrite ci-dessous est en cours
de définition.
:::

Pour permettre une large gamme d'usages, il n'y a actuellement pas de
quota imposé. Cependant dossier personnel est conçu pour un usage
interactif, pas pour du stockage de fichiers sur le long terme. Aussi
il n'y a pas de garanties de sauvegarde ou de préservation de longue
durée (plusieurs années).

:::{attention}

L'utilisateur est responsable des données hébergées (pas de contenus
illégaux, ou non liés à l'usage du service), de faire le ménage
régulièrement et de sauvegarder ses données importantes.

:::

Nous comptons sur votre coopération pour nous permettre de conserver
une politique des données libérales.  Nous nous réservons le droit
d'intervenir sans préavis pour, par exemple, nettoyer des fichiers
temporaires facilement reconstructibles (typiquement cache pip, conda,
...) ou des contenus illégaux. Ou avec préavis pour d'autres fichiers
volumineux.

(roles)=
### Rôles: élève, professeur, administrateur

myDocker ne fait pas de différence entre les utilisateurs pour
utiliser des environnements virtuels: une fois dans l'un d'entre eux,
on est sur une machine linux générique avec un compte local; comme par
exemple en salle de TP.

Le rôle de «Professeur» permet en outre à l'utilisateur de définir et
mettre à disposition de nouvelles images et nouveaux environnements,
via un onglet dédié sur le tableau de bord de myDocker. On peut avoir
le rôle de Professeur parce que l'établissement auprès du quel on
s'est authentifié a indiqué que l'on était personnel de
l'établissement et non étudiant, ou parce qu'un admin a donné le rôle
de Professeur.

Le rôle d'«Administrateur» permet enfin de gérer les utilisateurs
(notamment de configurer leur rôle).

### Comment organiser un cours utilisant myDocker

Si l'un des environnements préexistant vous convient, vous pouvez
simplement indiquer à vos étudiants de l'utiliser, par exemple en leur
fournissant un lien vers l'environnement. 

(activite_lti)=
::::{admonition} Inclure myDocker comme activité dans Moodle/eCampus/... (à venir)
:class: hint dropdown

:::{admonition} En construction
- récupérer copie d'écran de Charlène
:::

::::

Si l'utilisation est large (par exemple plus d'une centaine
d'étudiants utilisant simultanément myDocker), merci de nous
[contacter](contact); nous essayerons alors de garder un œil plus
attentif sur le service, notamment lors des premières séances.  Cela
permettra aussi de mieux planifier d'éventuelles interruptions de
service hors de périodes critiques (exemple: rendus de projets).
Merci aussi de nous contacter si vous avez besoin de ressources
physiques importantes (exemple: GPU, gros volumes de données).

Si vous avez des besoins spécifiques (par exemple un logiciel ou
version d'un logiciel particulière), vous pouvez [créer et partager
votre propre environnement](creer_environnement).

Alternativement, la plupart des environnements existants utilisent un
système de paquet comme `pip` ou `conda`. Il est alors possible
d'installer des nouveaux logiciels directement depuis l'environnement.
Ils seront typiquement installés dans un dossier `/conda` où
l'utilisateur a les droits d'écriture. Notez cependant que cette
installation n'est pas persistante (sauf à explicitement installer
dans le dossier utilisateur): il faudra réinstaller les logiciels à
chaque redémarrage de l'environnement. Cette alternative est donc
plutôt à réserver pour des petits logiciels rapides à télécharger et
installer.

Enfin, nous vous proposons ci-dessous plusieurs stratégies pour mettre
des ressources pédagogiques à la disposition des élèves.

### Gestion des devoirs (à détailler)

Comment fournir des documents pédagogiques aux étudiants :
- Importer des documents ou archives (avec jupyterlab-archive) à la main
- nbgitpuller
- travo

Comment organiser le rendu des devoirs :
- à la main, éventuellement avec jupyterlab-archive
- travo

### Comment fournir des données (à venir)

- Télécharger au vol
- Inclure dans l'environnement, typiquement via un fichier de contexte
- Montage S3 (à venir)

(collaboration)
### Collaboration temps réel (à venir)

À ce stade, mydocker (comme JupyterHub@Paris-Saclay précédemment) ne
propose pas en soi de fonctionnalité de collaboration. C'est une
limitation bien identifiée!

Cela étant dit: pour les environnements basés sur JupyterLab, il est
possible de configurer l'environnement pour lancer JupyterLab en mode
collaboratif.  Dans ce cas, l'utilisateur pourra partager un lien
d'invitation pour que d'autres personnes se joignent à sa session,
avec édition collaborative comme dans Google colab.

https://jupyterlab-realtime-collaboration.readthedocs.io/en/latest/
https://github.com/jupyterlab-contrib/jupyterlab-link-share

Les limitations sont:
- Nous n'avons pas encore eu l'occasion de tester sur le terrain
- Cela donne un accès complet à l'environnement de l'utilisateur. Si
  cet environnement contient par exemple des dossiers correspondant à
  différents cours, tous ces dossiers seront accessibles.
- Le lien est limité à la session courante. Les invités ne peuvent pas
  l'utiliser pour accéder à l'environnement collaboratif -- et
  notamment le redémarrer -- une fois la session terminée.

Nous souhaiterions avancer sur le sujet, et serions très intéressés
pour vous accompagner si vous étiez partant pour béta tester.

En complément, vous pourriez être intéressés pour l'outil de gestion
des devoirs (préparation, distribution, suivi, collecte)
[Travo](https://travo-cr.gitlab.io/travo/), basé sur GitLab, qui
dispose de quelques fonctionnalités de collaboration asynchrone
simple.

(creer_environnement)=
### Comment créer son propre environnement

La première étape est d'identifier les besoins pour vos usages:
ressources physiques, logiciels, interface, données.

En principe, toute interface permettant un usage depuis le navigateur
peut être utilisée. Ainsi JupyterLab, VSCode ou des environnements de
bureaux type XFCE ont déjà été déployés sur myDocker. De même, des
interfaces comme RStudio ne devraient pas poser de difficulté.

Tout logiciel libre pouvant tourner sous Linux peut être en principe
installé. Si vous avez besoin d'un logiciel non libre,
[contactez](contact) pour nous pour étudier s'il peut y avoir une
solution technique et financière. De même dans le cas d'un logiciel
tournant sous un autre système d'exploitation.

Il est aussi possible de prévoir l'inclusion de données directement
dans l'environnement. Au delà de 1Go, nous [contacter](contact) pour
étudier ensemble les impacts éventuels et alternatives.

Une fois ces éléments identifiés, nous recommandons de chercher une
image et un environnement similaires et de consulter comment il ont
été construits pour vous en inspirer. N'hésitez pas le cas échéant à
contacter le mainteneur pour avoir accès à leur configuration. Vous
pourrez alors créer votre propre image et votre propre environnement
en recopiant et adaptant la configuration.

La plupart des environnements utilisent un gestionnaire de paquets
comme `apt`, `conda`, `pip`, voire `guix` pour des besoins pointus de
reproductibilité. L'adaptation consistera alors simplement à adapter
la liste des paquets à installer. À titre d'essai préalable, vous
pouvez tester l'installation des logiciels directement dans
l'environnement d'inspiration.

:::{admonition} En construction
- Mettre les liens vers quelques images de base (communauté Jupyter, mambaforge)
- Philosophie
:::

Nous documentons ci-dessous quelques uns des éléments de configuration:

:::{admonition} Sessions
:class: hint dropdown

Dans l'onglet «information générales» d'un environnement il est
possible d'indiquer des «sessions».

Sur l'instance myDocker@CentraleSupelec, où les serveurs sont loués à
la demande, ces sessions permettent de réserver les serveurs aux
horaires indiqués. C'est utilisé notamment pour de grands cours
(plusieurs centaines d'étudiants simultanés) ou des cours utilisant
des ressources lourdes (GPU). Ces sessions sont sujettes à validation
par les administrateurs.

Sur l'instance myDocker@Paris-Saclay, ces sessions sont
essentiellement indicatives. En dehors des sessions, l'environnement
n'apparaît pas sur le tableau de bord des élèves. Et les
administrateurs s'en servent pour avoir une idée de l'usage
(prévisionnel) du service et des périodes calmes. La recommandation
est de mettre une session par semestre (ou période) pendant lesquels
les étudiants utilisent le service, en n'hésitant pas à prendre de la
marge, par exemple pour des étudiants qui souhaiteraient utiliser leur
environnement après la fin des cours. Et d'indiquer le nombre total
d'étudiants.

:::

:::{admonition} Extinction automatique des environnements
:class: hint dropdown

Dans l'onglet «informations générales» d'un environnement il est
possible de configurer une extinction automatique des
environnements. Cette fonctionnalité est prévue pour les cas où l'on
souhaite imposer une durée limitée d'accès à l'environnement (examen,
accès à des ressources coûteuses, etc).

Si l'on utilise JupyterLab et si l'on souhaite juste que
l'environnement s'éteigne automatiquement au bout d'un certain temps
d'inactivité, une meilleure alternative est de déléguer cette tâche à
en spécifiant les options adéquates dans la commande de lancement de
JupyterLab. Dans l'exemple suivant, les noyaux, les terminaux puis
l'application JupyterLab tout entière s'éteignent automatiquement au
bout de 20 minutes (1200 secondes) d'inactivité:

```
jupyter lab --no-browser --ip="0.0.0.0" --IdentityProvider.token={{PASSWORD}} --ServerApp.shutdown_no_activity_timeout=1200 --MappingKernelManager.cull_idle_timeout=1200 --TerminalManager.cull_inactive_timeout=1200
```
:::


:::{admonition} Dossier personnel persistant
:class: hint dropdown

L'item «Sauvegarder le travail de l'étudiant» permet d'activer la
persistance d'un dossier personnel de l'utilisateur dédié à cet
environnement. L'item «Activer le répertoire personnel de l'élève» est
similaire sauf que ledit dossier personnel est partagé avec les autres
environnements.

Le «chemin du volume étudiant» est le chemin où le dossier personnel
est mis à disposition dans le conteneur. C'est typiquement
`/home/jovyan` pour une image basée sur la pile docker de Jupyter,
`/home/mambauser` pour une image basée sur `mambaorg/micromamba`.

Pour le déterminer, vous pouvez démarrer votre environnement avant
d'avoir configuré la persistance, ouvrir un terminal et taper `pwd`
pour obtenir le chemin du dossier courant.

Évolution planifiée: améliorer la terminologie dans l'interface pour
plus de cohérence.

:::

:::{admonition} Options d'affichage
:class: hint dropdown

L'onglet «Options d'affichage» permet de configurer comment
l'utilisateur accède à l'interface du conteneur docker. Pour cela, on
peut configurer un ou plusieurs boutons avec pour chacun un lien de
connexion.

Cette connexion est sécurisée par une authentification par un mot de
passe tiré au hasard et éventuellement un identifiant associé qui ont
par ailleurs été transmis au conteneur au démarrage de celui-ci. Le
traitement d'une telle authentification dépend de l'interface utilisée
dans le conteneur docker (JupyterLab, ssh, ...). Idéalement, cette
étape est automatisée, typiquement en transmettant le token via le
lien. Par exemple, avec JupyterLab, on peut utiliser comme lien:

    https://{{HOST['8888']}}/?token={{PASSWORD}}

Sinon, ce sera à l'utilisateur de saisir manuellement le mot de passe
et l'éventuel identifiant à l'ouverture de l'interface. Il faudra donc
les avoir préalablement affichés.

:::

### Références

- [Documentation de myDocker](https://centralesupelec.github.io/mydocker/)

## Alternatives et projets similaires (à venir)

JupyterHub, SSPCloud, CoCalc, https://nuvolos.cloud/, PlasmaBio, ...
Interactive notebook service of [EOSC EU Node](https://open-science-cloud.ec.europa.eu/)
