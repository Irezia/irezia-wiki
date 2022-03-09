## Avertissement de durabilité

    L'option est activé par defaut.

L'avertissement de durabilité vous permet de recevoir une alert lors ce qu'un de vos objets a une durabilité trop basse.  

Il existe 4 commandes que vous pouvez utiliser.  

``` yaml
/label toggle - Vous permet d'activer/désactiver la fonctionnalité.
```
``` yaml
/label notify mode (1) - Vous permet de changer la façon dont vous êtes alerté. # (1)
```
1.  :man_raising_hand: I'm an annotation! I can contain `code`, __formatted
    text__, images, ... basically anything that can be expressed in Markdown.

``` yaml
/label setmode mode - Vous permet de choisir si vous voulez être alerté quand votre objet 
descend en dessous de X durabilité ou si votre object descend en dessous de X% de durabilité. 
(Mode disponnible: DURABILITY, PERCENT)
```
``` yaml
/label set mode value - Vous permet de définir les valeur pour chaque mode.
```