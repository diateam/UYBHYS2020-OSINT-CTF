# La Belle

## Intitulé
Bonjour, Inspecteur Edmond !

Merci d'avoir accepté de parcourir à nouveau Le Réseau pour cette mission spatio-temporelle.

Avant toute chose, nous allons vérifier que votre transmetteur temporel fonctionne correctement. Vos renseignements sont à nous fournir sous un format spécifique, encadrés par la balise *UYBHYS{flag}*.

Par exemple, si la réponse à la question posée est *crèpe*, le flag à fournir sera **UYBHYS{crèpe}**; vous n'avez pas à vous inquiéter pour la casse, celle-ci n'est pas prise en compte sauf si précisé dans l'énoncé.

Prêt ? Voici votre première mission, Inspecteur !

Nous recherchons une femme que le voyageur temporel aurait rencontrée au XVIIIe siècle dans une rue de Brest. Elle a été perdue de vue un jour de carnaval alors qu'un incendie se déclarait au Refuge Royal.

*Quel est le nom de famille de cette femme ?*

## Solution
À partir de l'énoncé, il est possible d'isoler plusieurs indices :
* Femme
* XVIIIe siècle
* Brest
* jour de carnaval
* incendie
* Refuge Royal

En construisant une requête à partir de ces indices pour la soumettre à un moteur de recherche, par exemple :

`femme brest refuge royal`

nous trouvons [cet article du Ouest France](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwjx_q2yiYftAhVIJBoKHUnIDMkQFjAAegQIAxAC&url=https%3A%2F%2Fwww.ouest-france.fr%2Fbretagne%2Ffinistere%2Fbrest-la-rue-ou-l-maltraitait-les-femmes-5517871&usg=AOvVaw2B2CMe1J2-MbVeizooObsb) où nous découvrons le nom de cette femme.

**Le flag : UYBHYS{tamisier}**
## Outils
Moteur de recherche (ex.: Google)