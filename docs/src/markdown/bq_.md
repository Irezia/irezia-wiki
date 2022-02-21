
# ServerCore

# **BetonQuest Conditions:**

 - [irskill_level](#irskill_level)
# **BetonQuest Objectives:**
 - [irfish](#irfish)
 - [irfish_rarity](#irfish_rarity)
 - [irfish_length](#irfish_length)
 - [irstay](#irstay)
 - [irmobkill](#irmobkill)
 
 # Conditions

## irskill_level 
 

    Format: irskill_level <SkillName> <MinLevel> <MaxLevel>

> condition: irskill_level Mining 5 10


# Objectives

> Note: "Name" peut être remplacé par "*", ce qui prendra en compte tout les poisson du plugin.

## irfish 
    Format: irfish <Name> <Amount>

> objective: irfish Anchovies 10 <- Pêcher 10 poissons dont le nom est Anchovies

> objective: irfish * 10 <- Pêcher 10 poissons (qui viennent du plugin)
## irfish_rarity 
    Format: irfish_rarity <Name> <Rarity> <Amount>

> objective: irfish_rarity Anchovies RARE 10 <- Pêcher 10 poissons rare dont le nom est Anchovies

> objective: irfish_rarity * RARE 10 <- Pêcher n'importe quel poisson rare
## irfish_length 
     Format: irfish_length <Name> <MinLength> <MaxLength> <Amount>

> objective: irfish_length Anchovies 10 20 1 <- Pêcher un poisson dont le nom est Anchovies et dont la taille se situe entre 10 & 20 CM

> objective: irfish_length * 10 20 1 <- Pêcher n'importe quel poison dont la taille se situe entre 10 & 20 CM

## irstay
    Format: irstay <region> <temps>


> objective: irstay Banque 60 <- Rester dans la region banque pendant 60 secondes

## irmobkill
    Format: irmobkill <mob|agressive|passive|mob>
            - Agressive est remplacé par la liste des mobs agressives
            - Passive est remplacé par la liste des mobs passives
            - Mob est remplacé par la liste de tout les mobs

> Objective: irmobkill zombie,passive 10 -> Tuer 10 zombie ou mob de la catégorie passive
