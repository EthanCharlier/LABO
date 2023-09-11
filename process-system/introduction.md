
**2 octobre**


Langage de représentation (norme UML: https://fr.wikipedia.org/wiki/UML_(informatique)).

Draw.io: outils de modélisation graphique.


## Function display(letter)

Chaque système possède sa propre représentation.
**Pre entry**: Display application
**Entry**: Press 'a'

- Système mécanique -> Mise en tension
- Système électronique -> Signal
- Système d'information (gestionnaire entré/sortie, bus électronique)
- Système électronique
- Systèmes mécanique

**Return**: Display 'a'

Opération généralement séquenciel, tout process sera constitué d'entry et de return.


# I - Les logiques de représentation
## 1/ Top-down

Logique qui vas partir d'un niveau d'abstraction très qui vas aller vers un niveau d'abstration très bas.

Abstraction (idée, représenation) -> Implémentation
(Générale -> Particulier)
Plusieurs implémentation peuvent coller à une seule abstraction.

Produit un modèle de l'abstration -> Implémentation matériel/logiciel **Verif**

## 2/ Bottom-up

Matériel -> Abstrait
(Physique, construction d'un modèle pour aller vers une abstraction )
Plusieurs abstraction peuvent coller à un seul modèle.

Comment faire pour modéliser un problème observer ?

# II - Définitions

# 1/ Système

**Système d'exploitation:** Couche qui permet la liaison entre les ressources matériel et les applications. **(Shéma)**

Application
| |
Système Exploitation
| |
Ressources Matériels

**Définition générale:** Représentation de haut niveau (abstrait) qui prend des intérations et qui produit des résultat couvrant des objectifs. **Produit des services permettant de couvrir des objectifs.**

**Les systèmes sont composés d'un ensemble de processus et de leur enchainements.**

## 2/ Objectif

**Définition:** Les attentes en terme de résultast de performances, d'exigences, de contraintes. Application de métrique sur ces résultats.

## 3/ Processus

**Définition informatique:** Un processus prend des data en entry, réalise des traitements sur ces data et produit des data en return.

Le processus change l'état du système.
L'enchainement des processus se fait sur une ensemble de condition de réalisation.

Pour se réaliser un processus doit avoir des conditions d'état du système requises (pré-conditions).
**Exemple:** SE doit avoir les ressources matériel requises.

Une fois réaliser, les traitements du processus vont modifié l'état du système et produire des post-conditions.

## 4/ Enchainement des processus

Hormis le **processus initial**, tout processus ne s'exécute que si ses pré-conditions (post-conditions du processus précédent) sont remplies.
Tout processus s'enchaine si ses post-conditions correspondent aux pré-conditions d'un ou plusieurs processus.
