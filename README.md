[README.md](https://github.com/user-attachments/files/33496081/README.md)
# HELLO WORLD · Digital Evolution

Une frise immersive de l'histoire de l'informatique et des réseaux, de 1945 à aujourd'hui.

**Voir le site : [charlesdev-web.github.io/hello-world](https://charlesdev-web.github.io/hello-world/)**

## Le concept

Le site ne raconte pas seulement les époques : il **devient** chaque époque. Au fil du scroll, l'interface change de typographie, de couleurs, de matière et de façon de bouger. Le fil rouge : comment les machines se sont connectées entre elles, et le message « Hello, World! », que l'on retrouve à chaque époque.

## Les 9 parties

1. **Ouverture** : un écran noir s'allume comme un vieux tube cathodique, « Hello, World! » s'écrit lettre par lettre.
2. **Années 40-50** : une carte perforée encode « HELLO, WORLD! » trou par trou, avec le vrai code de l'époque (code Hollerith).
3. **Années 70** : un terminal vert, le premier message envoyé sur ARPANET (« LO », en 1969), puis la carte du réseau qui grandit.
4. **1984** : un bureau en noir et blanc pixelisé, une souris, des fenêtres et des icônes.
5. **Années 90** : l'interface prend du relief, la connexion par modem, les fenêtres empilées en 3D et la naissance du web.
6. **Années 2000** : le web 2.0, avec ses boutons brillants, ses reflets et ses rebonds.
7. **Années 2010** : un smartphone en 3D, avec les notifications qui sortent de l'écran.
8. **Aujourd'hui** : le téléphone se dissout en particules qui forment un nuage (le cloud), et une IA dit bonjour au monde dans 11 langues.
9. **Fin** : tout se resserre en un point de lumière, un compteur remonte de 2026 à 1945, et le site revient à son ouverture.

## Techniques utilisées

- **HTML, CSS et JavaScript** dans un seul fichier
- **GSAP + ScrollTrigger** pour les animations pilotées par le scroll et les sections épinglées
- **Lenis** pour un défilement fluide
- **Three.js** pour le smartphone en 3D et le nuage de particules (shader personnalisé)
- **Canvas 2D** pour les lampes, la carte perforée et la pixellisation
- **Web Audio API** pour les sons, générés par le code (aucun fichier audio)

## Défis relevés

- **La fluidité** : les scènes lourdes ont été optimisées (lampes dessinées une seule fois puis copiées, nombre de particules adapté à l'appareil, un seul rendu par image).
- **Les transitions entre époques** : chaque passage est une vraie transformation, sans coupure (extinction d'écran, pixellisation, gonflement, dissolution en particules).
- **L'accessibilité** : le site respecte le réglage « réduire les animations » du système et propose alors une version statique lisible. Le son ne démarre qu'après un clic.
- **Le responsive** : le site fonctionne sur ordinateur et sur téléphone.

## Interactions

Le site se parcourt au scroll, mais on peut aussi : déplacer les fenêtres de 1984 et des années 90, utiliser la calculatrice, cliquer sur les liens du navigateur, voter avec les étoiles du web 2.0, faire réagir le nuage de particules avec la souris, et relancer la réponse de l'IA.

## À propos

Projet personnel de portfolio. Tous les visuels sont originaux : aucun logo ni aucune interface de marque réelle n'est reproduit.

Réalisé avec l'aide de Claude (Anthropic).
