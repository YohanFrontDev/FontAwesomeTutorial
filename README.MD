<!-- Preview = Ctrl + Maj + V on VsCode-->


# Utilisation de Fontawesome dans un projet
* #### Étape 1 :Intégrer via un link dans mon html
 
```bash

# Coller cette ligne dans mon index. 
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css">

```

*********
* ##### Étape 2: trouver l'icone qui correspond à mon besoin. 

```bash

# Se rendre sur le site officiel
    https://fontawesome.com/icons

# Récupérer l'icone correspondant à mon besoin.
    HTML: "<i class="fa-solid fa-xmark"></i>"
    React: "<FontAwesomeIcon icon="fa-solid fa-xmark" />"

### Votre icone est intégré !


```


*********
* ##### Étape 3: Gérer la taille de mon icone. 

```bash

# Gérer grâce aux pixels.

# fa-2xs = 0.625em = 10px
# fa-xs  = 0.75em  = 12px
# fa-sm  = 0.875em = 14px
# fa-lg  = 1.25em  = 20px
# fa-xl  = 1.5em   = 24px
# fa-2xl = 2em     = 32px

## Exemple:
            <i class="fa-solid fa-coffee fa-2xs"></i>

### Votre icone est maintenant de petite taille !


# Gérer grâce aux multiplicateurs (1x = 1em)

# fa-1x   fa-2x   fa-3x   fa-4x   fa-5x
# fa-6x   fa-7x   fa-8x   fa-9x  fa-10x

## Exemple: 
            <i class="fa-solid fa-coffee fa-2xs"></i>

```

*********
* ##### Étape 4: Appliquer une rotation à mon icone. 

```bash
# Utiliser une classe de rotation.
## Exemple: 
<div class="fa-3x">
    <i class="fa-solid fa-snowboarding fa-rotate-by" style="--fa-rotate-angle: 45deg;"></i>
    <i class="fa-solid fa-snowboarding fa-rotate-by" style="--fa-rotate-angle: -45deg;"></i>
  </div>
```

 Remarque: Faire le choix du SVG peut résoudre certains problèmes. 


