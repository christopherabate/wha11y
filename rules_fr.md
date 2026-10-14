# Référentiel de bonnes pratiques d'accessibilité numérique

## À propos de ce référentiel

Ce référentiel propose 11 points pour examiner l'accessibilité de
différents supports : sites et applications web, applications mobiles,
documents bureautiques et PDF, communications numériques, maquettes de
conception et contenus audio ou vidéo.

Pour chaque point, il présente le principe, l'objectif concret, la règle
à appliquer, les problèmes potentiels, des exemples, les personnes
concernées, les difficultés possibles et les références WCAG 2.2
pertinentes.

Les WCAG 2.2 portent sur les contenus web. Leurs critères peuvent aussi
être pertinents pour certaines applications et certains documents
numériques, mais leur applicabilité doit être vérifiée selon le support
et le contexte. Les références ci-dessous sont des correspondances
utiles, pas une déclaration de conformité complète. Les niveaux A, AA et
AAA sont ceux des WCAG.

Référence générale : [WCAG 2.2 --- version
française](https://www.w3.org/Translations/WCAG22-fr/) · [Vue d'ensemble
des WCAG](https://www.w3.org/WAI/standards-guidelines/wcag/fr)

## 1. Organiser clairement les informations

**Catégorie :** Structure

**Objectif :** Aider les personnes à comprendre comment le contenu est
organisé et à repérer rapidement les différentes parties.

**Règle :** Structurer les informations avec des titres et des
regroupements clairs.

**Problèmes potentiels** - Les titres sont absents, peu explicites ou
organisés dans un ordre incohérent. - Des informations liées ne sont pas
regroupées. - Les relations entre les éléments ne sont pas perceptibles
ou ne sont pas correctement restituées par les technologies
d'assistance. - La présentation ne permet pas de distinguer facilement
les différentes parties du contenu.

**Exemples** - **Site ou application web :** utiliser une hiérarchie de
titres cohérente pour les sections et sous-sections. - **Application
mobile :** regrouper les informations liées et donner un titre explicite
aux sections ou écrans. - **Document bureautique ou PDF :** utiliser les
styles de titres et des listes structurées, plutôt que de simuler la
structure uniquement avec du gras ou une grande taille. -
**Communication numérique :** choisir un objet explicite et séparer les
sujets en paragraphes distincts. - **Maquette de conception :**
représenter la hiérarchie des titres, les groupes d'informations et les
régions principales. - **Audio ou vidéo :** annoncer les grandes parties
ou proposer des chapitres lorsque cela aide à se repérer.

**Personnes concernées** Les personnes qui utilisent un lecteur d'écran,
qui parcourent les titres pour trouver une information ou qui ont besoin
de repères clairs pour comprendre l'organisation d'un contenu.

**Difficultés possibles** Ne pas comprendre comment le contenu est
organisé, manquer une section ou ne pas retrouver une information.

**Références WCAG 2.2** - [1.3.1 --- Information et relations
(A)](https://www.w3.org/WAI/WCAG22/Understanding/info-and-relationships.html)
: les relations et la structure doivent pouvoir être déterminées par un
programme. - [2.4.6 --- En-têtes et étiquettes
(AA)](https://www.w3.org/WAI/WCAG22/Understanding/headings-and-labels.html)
: les titres et étiquettes décrivent le sujet ou la fonction. - [2.4.10
--- En-têtes de section
(AAA)](https://www.w3.org/WAI/WCAG22/Understanding/section-headings.html)
: pertinent pour une structuration plus poussée, au niveau AAA.

## 2. Présenter les informations dans un ordre logique

**Catégorie :** Structure

**Objectif :** Permettre de comprendre le contenu et de suivre les
étapes sans devoir reconstituer l'ordre attendu.

**Règle :** Organiser les informations et les étapes dans un ordre
facile à suivre.

**Problèmes potentiels** - Les informations ou les étapes sont
présentées dans un ordre incohérent. - L'ordre de lecture restitué par
une technologie d'assistance ne correspond pas à l'ordre nécessaire pour
comprendre le contenu. - Une consigne importante apparaît après l'action
qu'elle explique. - Des étapes nécessaires sont difficiles à repérer ou
sont présentées séparément sans lien clair.

**Exemples** - **Site ou application web :** placer les instructions
avant la commande concernée et conserver un ordre de lecture cohérent. -
**Application mobile :** présenter les étapes d'une démarche dans
l'ordre où elles doivent être réalisées. - **Document bureautique ou PDF
:** vérifier que l'ordre de lecture du document suit le déroulement
logique, y compris dans les colonnes et les tableaux. - **Communication
numérique :** annoncer le contexte avant les demandes et préciser les
étapes à suivre. - **Maquette de conception :** prévoir un ordre de
lecture et de parcours cohérent avec le sens du contenu. - **Audio ou
vidéo :** présenter les explications dans un ordre qui permet de
comprendre les étapes sans devoir deviner les liens entre elles.

**Personnes concernées** Les personnes qui utilisent un lecteur d'écran,
qui ont besoin de suivre les étapes dans un ordre précis ou qui ont des
difficultés à traiter plusieurs consignes successives.

**Difficultés possibles** Ne pas savoir par où commencer, perdre le fil,
réaliser une action dans le mauvais ordre ou manquer une étape.

**Références WCAG 2.2** - [1.3.2 --- Séquence compréhensible
(A)](https://www.w3.org/WAI/WCAG22/Understanding/meaningful-sequence.html)
: l'ordre de lecture doit préserver le sens. - [2.4.3 --- Parcours du
focus (A)](https://www.w3.org/WAI/WCAG22/Understanding/focus-order.html)
: l'ordre de navigation au clavier doit préserver le sens et
l'opérabilité. - [3.2.3 --- Navigation cohérente
(AA)](https://www.w3.org/WAI/WCAG22/Understanding/consistent-navigation.html)
: les mécanismes de navigation répétés apparaissent dans le même ordre
relatif.

## 3. Rendre les contenus non textuels accessibles

**Catégorie :** Contenu

**Objectif :** Donner accès à l'information utile portée par une image,
un son ou une vidéo, même lorsque la personne ne peut pas percevoir le
média d'origine.

**Règle :** Proposer une alternative adaptée aux images, aux sons et aux
vidéos qui transmettent une information.

**Problèmes potentiels** - Une image porteuse d'information n'a pas de
description adaptée. - Le texte alternatif est absent, vague ou ne
transmet pas l'information utile. - Une vidéo ne propose pas les
sous-titres ou la transcription nécessaires. - Une information
importante est donnée uniquement par la voix, un son ou un élément
visuel, sans alternative équivalente. - Une description répète des
détails sans expliquer le sens utile du contenu.

**Exemples** - **Site ou application web :** ajouter un texte alternatif
utile à une image informative et un nom accessible aux icônes qui
servent de commandes. - **Application mobile :** donner un nom
compréhensible aux boutons représentés uniquement par une icône. -
**Document bureautique ou PDF :** fournir un texte alternatif aux images
informatives et une description ou un tableau de données pour un
graphique complexe. - **Communication numérique :** décrire les
informations importantes d'une image dans le texte du message, et ne pas
transmettre une information essentielle uniquement dans une image. -
**Maquette de conception :** documenter le texte alternatif prévu et le
sens des éléments visuels informatifs. - **Audio ou vidéo :** fournir
des sous-titres pour la parole et les sons utiles, une transcription
pour les contenus audio et une audiodescription lorsque des informations
visuelles sont nécessaires à la compréhension.

**Personnes concernées** Les personnes aveugles ou malvoyantes qui ont
besoin d'une description des informations visuelles, ainsi que les
personnes sourdes ou malentendantes qui ont besoin d'une transcription
ou de sous-titres pour accéder aux informations sonores.

**Difficultés possibles** Manquer une information transmise uniquement
par l'image, le son ou la vidéo, ou ne comprendre qu'une partie du
contenu.

**Références WCAG 2.2** - [1.1.1 --- Contenu non textuel
(A)](https://www.w3.org/WAI/WCAG22/Understanding/non-text-content.html)
: alternatives textuelles aux contenus non textuels, avec des exceptions
définies. - [1.2.1 --- Audio seul et vidéo seule (préenregistrés)
(A)](https://www.w3.org/WAI/WCAG22/Understanding/audio-only-and-video-only-prerecorded.html). -
[1.2.2 --- Sous-titres (préenregistrés)
(A)](https://www.w3.org/WAI/WCAG22/Understanding/captions-prerecorded.html). -
[1.2.3 --- Audiodescription ou version de remplacement pour un média
préenregistré
(A)](https://www.w3.org/WAI/WCAG22/Understanding/audio-description-or-media-alternative-prerecorded.html). -
[1.2.5 --- Audiodescription (préenregistrée)
(AA)](https://www.w3.org/WAI/WCAG22/Understanding/audio-description-prerecorded.html). -
[1.2.4 --- Sous-titres (en direct)
(AA)](https://www.w3.org/WAI/WCAG22/Understanding/captions-live.html),
lorsque le contenu est diffusé en direct.

## 4. Permettre de consulter le contenu à son rythme

**Catégorie :** Contenu

**Objectif :** Laisser suffisamment de temps pour lire, comprendre et
agir, et éviter que les mouvements ou les changements automatiques ne
perturbent l'accès au contenu.

**Règle :** Permettre de contrôler les contenus qui bougent ou changent
automatiquement.

**Problèmes potentiels** - Un carrousel, un bandeau ou un texte défile
sans que la personne puisse arrêter le mouvement. - Une information
disparaît avant que la personne ait eu le temps de la lire. - Un contenu
se met à jour automatiquement et interrompt la lecture ou déplace le
point de repère. - Des animations ou des clignotements détournent
l'attention ou provoquent une gêne. - Une limite de temps empêche de
lire une information ou de terminer une action sans possibilité adaptée
de prolonger le délai.

**Exemples** - **Site ou application web :** proposer une commande pour
mettre en pause, arrêter ou masquer un contenu en mouvement qui démarre
automatiquement et dure. - **Application mobile :** éviter de faire
disparaître trop rapidement les messages utiles et permettre de
contrôler les contenus animés. - **Document bureautique ou PDF :**
éviter les animations inutiles dans les documents présentés à l'écran et
laisser le temps de lire les diapositives. - **Communication numérique
:** ne pas faire reposer une information essentielle sur un GIF animé
rapide ou un message éphémère. - **Maquette de conception :** préciser
les commandes de pause et les comportements attendus des carrousels et
mises à jour automatiques. - **Audio ou vidéo :** permettre la pause et
la reprise, et éviter les flashs susceptibles de déclencher des
réactions.

**Personnes concernées** Les personnes qui ont besoin de plus de temps
pour lire ou agir, qui utilisent une technologie d'assistance ou qui
sont gênées par les mouvements, les clignotements ou les changements
automatiques.

**Difficultés possibles** Perdre une information, ne pas avoir le temps
de la lire, perdre sa place ou ressentir une gêne liée aux mouvements.

**Références WCAG 2.2** - [2.2.2 --- Mettre en pause, arrêter, masquer
(A)](https://www.w3.org/WAI/WCAG22/Understanding/pause-stop-hide.html) :
pour certains contenus en mouvement, clignotants ou qui se mettent à
jour automatiquement. - [2.2.1 --- Réglage du délai
(A)](https://www.w3.org/WAI/WCAG22/Understanding/timing-adjustable.html)
: pour les limites de temps, sous réserve des exceptions prévues. -
[2.3.1 --- Pas plus de trois flashs ou sous le seuil critique
(A)](https://www.w3.org/WAI/WCAG22/Understanding/three-flashes-or-below-threshold.html)
: pour les flashs. - [2.2.6 --- Délais d'inactivité
(AAA)](https://www.w3.org/WAI/WCAG22/Understanding/timeouts.html) :
information sur les délais d'inactivité, au niveau AAA.

## 5. Faciliter la perception des informations

**Catégorie :** Visuels

**Objectif :** Rendre les textes, les commandes et les informations
visuelles suffisamment faciles à distinguer et à lire.

**Règle :** Présenter les textes et les éléments visuels avec une taille
et un contraste adaptés.

**Problèmes potentiels** - Le texte est trop petit ou difficile à
lire. - Le contraste entre le texte et l'arrière-plan est insuffisant. -
Les informations sont présentées dans une mise en page dense ou
difficile à parcourir. - Certains caractères ou éléments visuels sont
difficiles à distinguer. - Des éléments importants sont peu visibles ou
se confondent avec le reste du contenu.

**Exemples** - **Site ou application web :** vérifier le contraste du
texte et des composants d'interface, et permettre l'agrandissement du
texte. - **Application mobile :** employer une taille de texte lisible
et éviter que les commandes importantes se fondent dans
l'arrière-plan. - **Document bureautique ou PDF :** utiliser une taille
de texte lisible, des contrastes suffisants et une mise en page aérée. -
**Communication numérique :** ne pas placer un texte important sur une
image chargée sans contraste suffisant. - **Maquette de conception :**
vérifier les contrastes, la taille des textes et la visibilité des
commandes dès la conception. - **Audio ou vidéo :** rendre les
sous-titres lisibles, suffisamment contrastés et visibles assez
longtemps.

**Personnes concernées** Les personnes malvoyantes, celles qui ont
besoin d'agrandir les textes ou d'améliorer le contraste, et celles qui
consultent le contenu dans des conditions d'affichage difficiles.

**Difficultés possibles** Lire difficilement, confondre des éléments ou
ne pas repérer une information importante.

**Références WCAG 2.2** - [1.4.3 --- Contraste (minimum)
(AA)](https://www.w3.org/WAI/WCAG22/Understanding/contrast-minimum.html)
: contraste du texte. - [1.4.11 --- Contraste des éléments non textuels
(AA)](https://www.w3.org/WAI/WCAG22/Understanding/non-text-contrast.html)
: contraste de certains composants d'interface et éléments graphiques
nécessaires à la compréhension. - [1.4.4 --- Redimensionnement du texte
(AA)](https://www.w3.org/WAI/WCAG22/Understanding/resize-text.html). -
[1.4.12 --- Espacement du texte
(AA)](https://www.w3.org/WAI/WCAG22/Understanding/text-spacing.html). -
[1.4.10 --- Redistribution
(AA)](https://www.w3.org/WAI/WCAG22/Understanding/reflow.html) : contenu
consultable sans défilement dans deux directions, dans les conditions
prévues par le critère.

## 6. Ne pas transmettre une information uniquement par la couleur

**Catégorie :** Visuels

**Objectif :** Faire en sorte que les informations restent
compréhensibles lorsque les couleurs sont difficiles à distinguer ou ne
sont pas visibles.

**Règle :** Associer aux couleurs un autre moyen de distinguer les
informations importantes.

**Problèmes potentiels** - Une erreur est signalée uniquement par un
champ rouge. - Les champs obligatoires ne sont distingués que par leur
couleur. - Les catégories d'un graphique sont différenciées uniquement
par des couleurs proches. - Un état ou une action est indiqué par la
couleur sans texte, symbole ou autre repère.

**Exemples** - **Site ou application web :** associer un message
explicite et un symbole à la couleur qui signale une erreur. -
**Application mobile :** indiquer textuellement l'état activé ou
désactivé, au lieu de le signaler uniquement par la couleur. -
**Document bureautique ou PDF :** ajouter des étiquettes, des motifs ou
des symboles aux catégories d'un graphique. - **Communication numérique
:** préciser dans le texte les éléments signalés en rouge ou en vert. -
**Maquette de conception :** prévoir un libellé, une icône ou une forme
en complément de la couleur. - **Audio ou vidéo :** expliquer oralement
les catégories d'un graphique si leur distinction par couleur est
nécessaire à la compréhension.

**Personnes concernées** Les personnes daltoniennes ou qui distinguent
difficilement certaines couleurs, ainsi que celles qui utilisent un
affichage en niveaux de gris ou des réglages qui modifient les couleurs.

**Difficultés possibles** Ne pas distinguer une erreur, une catégorie,
un état ou une information signalée uniquement par une couleur.

**Références WCAG 2.2** - [1.4.1 --- Utilisation de la couleur
(A)](https://www.w3.org/WAI/WCAG22/Understanding/use-of-color.html) : la
couleur ne doit pas être le seul moyen visuel de transmettre une
information, d'indiquer une action ou de distinguer un élément.

## 7. Adapter la présentation aux besoins des personnes

**Catégorie :** Adaptabilité

**Objectif :** Préserver l'accès aux informations et aux fonctions
lorsque la personne modifie l'affichage selon ses besoins.

**Règle :** Permettre d'adapter la présentation sans perdre
d'information ni de fonctionnalité.

**Problèmes potentiels** - L'agrandissement du texte coupe des mots ou
masque des commandes. - Une fenêtre étroite fait disparaître des
informations ou oblige à faire défiler la page dans plusieurs
directions. - La modification de l'espacement, des couleurs ou des
polices rend le contenu illisible ou inutilisable. - Les réglages
d'affichage ou les technologies d'assistance empêchent d'accéder à
certaines informations ou fonctions.

**Exemples** - **Site ou application web :** conserver le contenu et les
fonctions lorsque le texte est agrandi ou que la fenêtre est réduite. -
**Application mobile :** prendre en compte les tailles de texte choisies
dans les réglages du système. - **Document bureautique ou PDF :**
proposer, lorsque c'est possible, un document source structuré et un PDF
dont le contenu reste accessible avec les fonctions d'agrandissement. -
**Communication numérique :** éviter de transmettre l'essentiel
uniquement dans une image dont le texte ne peut pas être adapté. -
**Maquette de conception :** prévoir les états à petite largeur, avec
texte agrandi et espacement modifié. - **Audio ou vidéo :** permettre de
régler la taille et l'apparence des sous-titres lorsque le lecteur le
permet.

**Personnes concernées** Les personnes qui agrandissent le texte,
modifient l'espacement ou les couleurs, utilisent un petit écran ou ont
besoin de réglages spécifiques pour lire et utiliser le contenu.

**Difficultés possibles** Perdre du texte ou des commandes, devoir faire
défiler la page dans plusieurs directions ou ne plus pouvoir réaliser
une action après adaptation.

**Références WCAG 2.2** - [1.4.4 --- Redimensionnement du texte
(AA)](https://www.w3.org/WAI/WCAG22/Understanding/resize-text.html). -
[1.4.10 --- Redistribution
(AA)](https://www.w3.org/WAI/WCAG22/Understanding/reflow.html). -
[1.4.12 --- Espacement du texte
(AA)](https://www.w3.org/WAI/WCAG22/Understanding/text-spacing.html). -
[1.3.1 --- Information et relations
(A)](https://www.w3.org/WAI/WCAG22/Understanding/info-and-relationships.html)
: pertinent lorsque la structure doit rester disponible pour différentes
présentations.

## 8. Permettre différentes méthodes d'interaction

**Catégorie :** Interactions

**Objectif :** Permettre à chaque personne d'effectuer les actions sans
dépendre d'un seul type de commande ou d'un geste difficile à réaliser.

**Règle :** Permettre d'effectuer les actions avec différents moyens de
commande adaptés.

**Problèmes potentiels** - Une action ne peut être réalisée qu'avec une
souris ou un geste tactile précis. - Une commande exige un geste
complexe, rapide ou effectué avec plusieurs doigts, sans autre méthode
disponible. - Certains boutons ou contrôles ne peuvent pas être atteints
ou activés au clavier. - Une action n'est pas compatible avec la
commande vocale, un contacteur ou un dispositif de pointage adapté.

**Exemples** - **Site ou application web :** rendre les fonctions
utilisables au clavier et afficher clairement le focus. - **Application
mobile :** proposer une alternative à un geste complexe, par exemple un
bouton pour remplacer un glissement. - **Document bureautique ou PDF :**
ne pas dépendre uniquement d'une action à la souris pour accéder à une
fonction ou à une information. - **Communication numérique :** fournir
un lien utilisable plutôt que de demander de réaliser une action
uniquement par un geste sur une image. - **Maquette de conception :**
indiquer les commandes clavier, l'état du focus et les alternatives aux
gestes. - **Audio ou vidéo :** rendre les commandes principales du
lecteur accessibles au clavier et aux technologies d'assistance.

**Personnes concernées** Les personnes qui utilisent le clavier, la
commande vocale, un contacteur ou un dispositif adapté, ainsi que celles
qui ont des difficultés à effectuer des gestes précis ou complexes.

**Difficultés possibles** Ne pas pouvoir activer une commande, effectuer
un geste demandé ou terminer une tâche avec le moyen de commande
disponible.

**Références WCAG 2.2** - [2.1.1 --- Clavier
(A)](https://www.w3.org/WAI/WCAG22/Understanding/keyboard.html). -
[2.1.2 --- Pas de piège au clavier
(A)](https://www.w3.org/WAI/WCAG22/Understanding/no-keyboard-trap.html). -
[2.4.7 --- Visibilité du focus
(AA)](https://www.w3.org/WAI/WCAG22/Understanding/focus-visible.html). -
[2.4.11 --- Focus non masqué (minimum)
(AA)](https://www.w3.org/WAI/WCAG22/Understanding/focus-not-obscured-minimum.html). -
[2.5.1 --- Gestes de manipulation
(A)](https://www.w3.org/WAI/WCAG22/Understanding/pointer-gestures.html). -
[2.5.7 --- Mouvements de glissement
(AA)](https://www.w3.org/WAI/WCAG22/Understanding/dragging-movements.html). -
[2.5.8 --- Taille de la cible (minimum)
(AA)](https://www.w3.org/WAI/WCAG22/Understanding/target-size-minimum.html). -
[2.5.6 --- Mécanismes d'entrée simultanés
(AAA)](https://www.w3.org/WAI/WCAG22/Understanding/concurrent-input-mechanisms.html)
: pertinent pour ne pas restreindre inutilement les mécanismes d'entrée.

## 9. Permettre de se repérer et de se déplacer dans le contenu

**Catégorie :** Navigation

**Objectif :** Aider les personnes à savoir où elles se trouvent, à
comprendre où mène une commande et à retrouver une information.

**Règle :** Permettre de savoir où l'on se trouve et de retrouver
facilement les informations.

**Problèmes potentiels** - Les menus, liens ou repères de navigation
sont absents, peu explicites ou difficiles à trouver. - Il est difficile
de savoir quelle page, section ou étape est affichée. - Le déplacement
au clavier ne suit pas un ordre compréhensible ou la position courante
n'est pas visible. - Il faut parcourir une grande quantité de contenu
pour retrouver une information déjà consultée. - Les liens ne permettent
pas de comprendre clairement leur destination.

**Exemples** - **Site ou application web :** fournir une navigation
cohérente, un titre de page explicite et des liens dont la destination
est compréhensible. - **Application mobile :** indiquer clairement
l'écran courant et proposer un moyen prévisible de revenir à l'étape
précédente. - **Document bureautique ou PDF :** utiliser une table des
matières ou des signets pour les documents longs, lorsque cela est
pertinent. - **Communication numérique :** donner aux liens un libellé
descriptif plutôt que « cliquez ici » sans contexte. - **Maquette de
conception :** représenter les menus, les états actifs, le parcours
clavier et les moyens de revenir en arrière. - **Audio ou vidéo :**
proposer des chapitres ou des repères temporels lorsque la longueur et
la structure du contenu le justifient.

**Personnes concernées** Les personnes qui naviguent au clavier ou avec
un lecteur d'écran, et celles qui ont besoin de repères stables pour
retrouver une rubrique ou reprendre leur lecture après une interruption.

**Difficultés possibles** Perdre sa position, ne pas retrouver une page
ou une rubrique, ou devoir parcourir tout le contenu pour atteindre une
information.

**Références WCAG 2.2** - [2.4.1 --- Contourner des blocs
(A)](https://www.w3.org/WAI/WCAG22/Understanding/bypass-blocks.html). -
[2.4.2 --- Titre de page
(A)](https://www.w3.org/WAI/WCAG22/Understanding/page-titled.html). -
[2.4.5 --- Accès multiples
(AA)](https://www.w3.org/WAI/WCAG22/Understanding/multiple-ways.html). -
[2.4.6 --- En-têtes et étiquettes
(AA)](https://www.w3.org/WAI/WCAG22/Understanding/headings-and-labels.html). -
[2.4.7 --- Visibilité du focus
(AA)](https://www.w3.org/WAI/WCAG22/Understanding/focus-visible.html). -
[3.2.3 --- Navigation cohérente
(AA)](https://www.w3.org/WAI/WCAG22/Understanding/consistent-navigation.html). -
[2.4.4 --- Fonction du lien (selon le contexte)
(A)](https://www.w3.org/WAI/WCAG22/Understanding/link-purpose-in-context.html).

## 10. Aider à comprendre les informations et les actions à réaliser

**Catégorie :** Compréhension et aide

**Objectif :** Permettre de comprendre les textes, de savoir ce qui est
attendu et de réaliser une action sans devoir deviner les consignes.

**Règle :** Utiliser des textes clairs et donner des instructions
précises au moment nécessaire.

**Problèmes potentiels** - Les textes contiennent des phrases complexes,
des termes techniques ou des formulations ambiguës. - Les instructions
sont absentes, vagues ou difficiles à trouver. - Les informations
nécessaires pour réaliser une action ne sont pas données au bon
moment. - Le format attendu pour une réponse ou une saisie n'est pas
expliqué. - Des consignes reposent sur des connaissances ou des usages
qui ne sont pas explicités.

**Exemples** - **Site ou application web :** préciser le format attendu
d'une date et donner un libellé clair à chaque champ. - **Application
mobile :** expliquer une permission ou une étape avant de demander à la
personne d'agir. - **Document bureautique ou PDF :** développer les
abréviations peu courantes et expliquer les termes techniques
nécessaires. - **Communication numérique :** formuler clairement la
demande, l'échéance et l'action attendue. - **Maquette de conception :**
prévoir les libellés, les instructions et les aides contextuelles, pas
uniquement l'apparence des champs. - **Audio ou vidéo :** expliquer les
termes spécialisés ou annoncer les étapes importantes dans un langage
adapté au public visé.

**Personnes concernées** Les personnes qui ont des difficultés à
comprendre des textes complexes, des termes techniques ou des consignes
implicites, ainsi que celles qui découvrent un service ou une démarche.

**Difficultés possibles** Ne pas comprendre ce qui est demandé, quelles
informations fournir ou quelle action effectuer.

**Références WCAG 2.2** - [3.1.1 --- Langue de la page
(A)](https://www.w3.org/WAI/WCAG22/Understanding/language-of-page.html). -
[3.1.2 --- Langue d'un passage
(AA)](https://www.w3.org/WAI/WCAG22/Understanding/language-of-parts.html). -
[3.1.3 --- Mots rares
(AAA)](https://www.w3.org/WAI/WCAG22/Understanding/unusual-words.html). -
[3.1.4 --- Abréviations
(AAA)](https://www.w3.org/WAI/WCAG22/Understanding/abbreviations.html). -
[3.1.5 --- Niveau de lecture
(AAA)](https://www.w3.org/WAI/WCAG22/Understanding/reading-level.html). -
[3.2.4 --- Identification cohérente
(AA)](https://www.w3.org/WAI/WCAG22/Understanding/consistent-identification.html). -
[3.3.2 --- Étiquettes ou instructions
(A)](https://www.w3.org/WAI/WCAG22/Understanding/labels-or-instructions.html). -
**Limite importante :** les WCAG ne prescrivent pas un langage FALC
général pour tous les contenus. Un langage clair peut aller au-delà de
ce que les critères exigent.

## 11. Aider à comprendre et à corriger les erreurs

**Catégorie :** Retour et aide

**Objectif :** Permettre de repérer une erreur, de comprendre ce qui
doit être corrigé et de poursuivre la tâche sans perdre inutilement les
informations saisies.

**Règle :** Signaler les erreurs clairement et expliquer comment les
corriger.

**Problèmes potentiels** - Une erreur n'est pas signalée ou le message
est trop vague. - Le message n'indique pas le champ ou l'information à
corriger. - La personne ne reçoit pas d'explication sur la façon de
résoudre le problème. - Un message d'erreur n'est pas annoncé ou rendu
accessible à la technologie d'assistance utilisée. - Les informations
déjà saisies sont perdues après une erreur ou une tentative de
correction.

**Exemples** - **Site ou application web :** indiquer quel champ est
incorrect, expliquer pourquoi et proposer une correction lorsque c'est
possible. - **Application mobile :** placer le message près du champ
concerné et permettre de le retrouver avec un lecteur d'écran. -
**Document bureautique ou PDF :** expliquer clairement les corrections
attendues dans un formulaire numérique ou un document à compléter. -
**Communication numérique :** lorsqu'une démarche échoue, expliquer la
cause connue et les prochaines étapes au lieu d'afficher uniquement «
une erreur est survenue ». - **Maquette de conception :** prévoir les
états d'erreur, leur annonce accessible et le maintien des données déjà
saisies. - **Audio ou vidéo :** lorsqu'une interface associée au média
comporte un formulaire ou une commande, rendre les messages d'erreur
explicites et accessibles.

**Personnes concernées** Les personnes qui ont besoin d'explications
précises pour identifier une erreur, comprendre comment la corriger et
reprendre leur tâche sans perdre les informations déjà saisies.

**Difficultés possibles** Ne pas repérer l'erreur, ne pas comprendre
comment la corriger, perdre les informations saisies ou devoir
recommencer.

**Références WCAG 2.2** - [3.3.1 --- Identification des erreurs
(A)](https://www.w3.org/WAI/WCAG22/Understanding/error-identification.html). -
[3.3.3 --- Suggestion après une erreur
(AA)](https://www.w3.org/WAI/WCAG22/Understanding/error-suggestion.html). -
[3.3.4 --- Prévention des erreurs (juridiques, financières, données)
(AA)](https://www.w3.org/WAI/WCAG22/Understanding/error-prevention-legal-financial-data.html). -
[3.3.7 --- Saisie redondante
(A)](https://www.w3.org/WAI/WCAG22/Understanding/redundant-entry.html) :
éviter de demander à nouveau certaines informations déjà fournies au
cours d'un même processus, dans les conditions du critère. - [4.1.3 ---
Messages d'état
(AA)](https://www.w3.org/WAI/WCAG22/Understanding/status-messages.html)
: pour les messages de statut qui doivent pouvoir être déterminés par un
programme sans recevoir le focus.
