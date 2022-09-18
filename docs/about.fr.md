---
title: "À propos"
---

# À propos des fonctions installées

La configuration de ce projet permet l'utilisation des éléments suivants. 

Veuillez vous référer à la documentation officielle de [mkdocs-material](https://squidfunk.github.io/mkdocs-material/reference/) pour plus d'informations ou pour toute modification des paramètres. 

---


## :material-information-outline: Admonitions

La configuration de ce projet permet les _admonitions_, également appelées _call-outs_.

Voici quelques exemples (pour plus d'informations, veuillez vous référer à la documentation officielle de [mkdocs-material](https://squidfunk.github.io/mkdocs-material/reference/admonitions/)).

!!! warning "Attention"

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.


!!! tip "Phasellus posuere in sem ut cursus"

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.


???+ note "Lorem ipsum"

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

---

## :material-gesture-tap-button: Boutons  

La configuration de ce projet permet d'ajouter des attributs à tous les éléments de niveau ligne et bloc avec une syntaxe simple, transformant ainsi tout lien en bouton.

Voici quelques exemples (pour plus d'informations, veuillez vous référer à la documentation officielle de [mkdocs-material](https://squidfunk.github.io/mkdocs-material/reference/buttons/)).

[S'abonner à notre newsletter](#){ .md-button }      [S'abonner à notre newsletter](#){ .md-button .md-button--primary }      [Envoyer :fontawesome-solid-paper-plane:](#){ .md-button }

---

## :material-code-json: Blocs de codes

Cette configuration active la coloration syntaxique des blocs de code et des blocs de code en ligne, et permet d'inclure le code source directement à partir d'autres fichiers.

Voici quelques exemples (pour plus d'informations, veuillez vous référer à la documentation officielle de [mkdocs-material](https://squidfunk.github.io/mkdocs-material/reference/code-blocks/)).

    ``` py title="exemple avec mise en évidence des lignes" hl_lines="2 3"
    def bubble_sort(items):
        for i in range(len(items)):
            for j in range(len(items) - 1 - i):
                if items[j] > items[j + 1]:
                    items[j], items[j + 1] = items[j + 1], items[j]
    ```


``` py title="exemple avec mise en évidence des lignes" hl_lines="2 3"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```


    ``` py title="exemple avec annotation"
    def my_method(self):
        return self # (1)
    ```

    1.  :man_raising_hand: Je suis une annotation de code ! Je peux contenir du `code`, du __texte formaté__, des images, ... en fait, tout ce qui peut être écrit en Markdown.


``` py title="exemple avec annotation"
def my_method(self):
    return self # (1)
```

1.  :man_raising_hand: Je suis une annotation de code ! Je peux contenir `code`, du __texte formaté__, des images, ... en fait, tout ce qui peut être écrit en Markdown.


```
Je suis un bloc de code en ligne  `#!python range()` avec une coloration syntaxique.
```

Je suis un bloc de code en ligne  `#!python range()` avec une coloration syntaxique.

---

## :material-tab-plus: Onglets de contenu

Cette configuration active les onglets de contenu, et permet d'imbriquer du contenu arbitraire dans les onglets de contenu, y compris des blocs de code et ... plus d'onglets de contenu !

Voici quelques exemples (pour plus d'informations, veuillez vous référer à la documentation officielle de [mkdocs-material](https://squidfunk.github.io/mkdocs-material/reference/content-tabs/)).

    === "C"

        ``` c
        #include <stdio.h>

        int main(void) {
        printf("Hello world!\n");
        return 0;
        }
        ```

    === "C++"

        ``` c++
        #include <iostream>

        int main(void) {
        std::cout << "Hello world!" << std::endl;
        return 0;
        }
        ```
=== "C"

    ``` c
    #include <stdio.h>

    int main(void) {
      printf("Hello world!\n");
      return 0;
    }
    ```

=== "C++"

    ``` c++
    #include <iostream>

    int main(void) {
      std::cout << "Hello world!" << std::endl;
      return 0;
    }
    ```
---

## :octicons-workflow-24: Diagrammes

Cette configuration permet la prise en charge native de diagrammes `Mermaid.js`.

Voici quelques exemples (pour plus d'informations, veuillez vous référer à la documentation officielle de [mkdocs-material](https://squidfunk.github.io/mkdocs-material/reference/diagrams/)).

    ``` mermaid
    graph LR
    A[Start] --> B{Error?};
    B -->|Yes| C[Hmm...];
    C --> D[Debug];
    D --> B;
    B ---->|No| E[Yay!];
    ```

``` mermaid
graph LR
A[Start] --> B{Error?};
B -->|Yes| C[Hmm...];
C --> D[Debug];
D --> B;
B ---->|No| E[Yay!];
```

---

## :material-format-font: Mise en forme


Cette configuration permet la prise en charge des touches du clavier, le suivi des modifications dans les documents, la définition des sous-script et super-script et la mise en évidence du texte.

Voici quelques exemples (pour plus d'informations, veuillez vous référer à la documentation officielle de [mkdocs-material](https://squidfunk.github.io/mkdocs-material/reference/formatting/)).

    ```
    ++ctrl+alt+del++

    ```

++ctrl+alt+del++


    ```
    Le texte peut être {--effacé--} et le texte de remplacement {++ajouté++}. Ceci peut également être combiné en {~~une~> seule~~} opération. {==La mise en évidence==} est également possible {>>et des commentaires peuvent être ajoutés en ligne<<}.

    {==

    Le formatage peut également être appliqué aux blocs en plaçant les balises d'ouverture et de fermeture sur des lignes distinctes et en ajoutant de nouvelles lignes entre les balises et le contenu.
    
    ==}

    ```

Le texte peut être {--effacé--} et le texte de remplacement {++ajouté++}. Ceci peut également être combiné en {~~une~>seule~~} opération. {==La mise en évidence==} est également possible {>>et des commentaires peuvent être ajoutés en ligne<<}.

{==

Le formatage peut également être appliqué aux blocs en plaçant les balises d'ouverture et de fermeture sur des lignes distinctes et en ajoutant de nouvelles lignes entre les balises et le contenu.

==}

---

## :material-bug: Icônes, Emojis 

Cette configuration permet l'utilisation d'icônes et d'emojis à l'aide de simples shortcodes que l'on peut découvrir par le biais de la docmentation en ligne [icon search](https://squidfunk.github.io/mkdocs-material/reference/icons-emojis/#search).

Voici quelques exemples (pour plus d'informations, veuillez vous référer à la documentation officielle de [mkdocs-material](https://squidfunk.github.io/mkdocs-material/reference/icons-emojis/)).

```:smile: :fontawesome-regular-face-laugh-wink: :octicons-smiley-16:```

:smile: :fontawesome-regular-face-laugh-wink: :octicons-smiley-16:

---

## :material-image-plus-outline: Images

Cette configuration ajoute la possibilité d'aligner les images, d'ajouter des légendes aux images (en les rendant sous forme de figures) et de marquer les grandes images pour un chargement progressif. Elle fonctionne également pour la fonctionnalité de zoom sur les images.

Voici quelques exemples (pour plus d'informations, veuillez vous référer à la documentation officielle de [mkdocs-material](https://squidfunk.github.io/mkdocs-material/reference/images/)) and [mkdocs-glightbox](https://github.com/blueswen/mkdocs-glightbox).

![Image title](https://dummyimage.com/600x400/){ loading=lazy }

---

## :material-format-list-checks: Listes 

Cette configuration permet d'utiliser des listes de définitions et des listes de tâches, qui ne font pas partie de la syntaxe Markdown standard.

Voici quelques exemples (pour plus d'informations, veuillez vous référer à la documentation officielle de [mkdocs-material](https://squidfunk.github.io/mkdocs-material/reference/lists/))

    `Lorem ipsum dolor sit amet`

    :   Sed sagittis eleifend rutrum. Donec vitae suscipit est. Nullam tempus
        tellus non sem sollicitudin, quis rutrum leo facilisis.

    `Cras arcu libero`

    :   Aliquam metus eros, pretium sed nulla venenatis, faucibus auctor ex. Proin
        ut eros sed sapien ullamcorper consequat. Nunc ligula ante.

        Duis mollis est eget nibh volutpat, fermentum aliquet dui mollis.
        Nam vulputate tincidunt fringilla.
        Nullam dignissim ultrices urna non auctor.

`Lorem ipsum dolor sit amet`

:   Sed sagittis eleifend rutrum. Donec vitae suscipit est. Nullam tempus
    tellus non sem sollicitudin, quis rutrum leo facilisis.

`Cras arcu libero`

:   Aliquam metus eros, pretium sed nulla venenatis, faucibus auctor ex. Proin
    ut eros sed sapien ullamcorper consequat. Nunc ligula ante.

    Duis mollis est eget nibh volutpat, fermentum aliquet dui mollis.
    Nam vulputate tincidunt fringilla.
    Nullam dignissim ultrices urna non auctor.

```
    - [x] Lorem ipsum dolor sit amet, consectetur adipiscing elit
    - [ ] Vestibulum convallis sit amet nisi a tincidunt
        * [x] In hac habitasse platea dictumst
        * [x] In scelerisque nibh non dolor mollis congue sed et metus
        * [ ] Praesent sed risus massa
    - [ ] Aenean pretium efficitur erat, donec pharetra, ligula non scelerisque
```

- [x] Lorem ipsum dolor sit amet, consectetur adipiscing elit
- [ ] Vestibulum convallis sit amet nisi a tincidunt
    * [x] In hac habitasse platea dictumst
    * [x] In scelerisque nibh non dolor mollis congue sed et metus
    * [ ] Praesent sed risus massa
- [ ] Aenean pretium efficitur erat, donec pharetra, ligula non scelerisque


---

## :fontawesome-solid-bars-progress: Barre de progression 

Cette configuration permet de prendre en charge les barres de progression/d'état.


Voici quelques exemples (pour plus d'informations, veuillez vous référer à la documentation officielle de [PyMdown](https://facelessuser.github.io/pymdown-extensions/extensions/progressbar/))


    ```
    [=0% "0%"]
    [=5% "5%"]
    [=25% "25%"]
    [=45% "45%"]
    [=65% "65%"]
    [=85% "85%"]
    [=100% "100%"]
    ```

[=0% "0%"]
[=5% "5%"]
[=25% "25%"]
[=45% "45%"]
[=65% "65%"]
[=85% "85%"]
[=100% "100%"]

    ```
    [=0%]{: .thin}
    [=5%]{: .thin}
    [=25%]{: .thin}
    [=45%]{: .thin}
    [=65%]{: .thin}
    [=85%]{: .thin}
    [=100%]{: .thin}
    ```

[=0%]{: .thin}
[=5%]{: .thin}
[=25%]{: .thin}
[=45%]{: .thin}
[=65%]{: .thin}
[=85%]{: .thin}
[=100%]{: .thin}
