---
title: "About"
---

# About the installed features

The configuration of this project allows the use of the following elements. 

Please refer to the official documentation of [mkdocs-material](https://squidfunk.github.io/mkdocs-material/reference/) for more information or any changes to the settings. 

---


## :material-information-outline: Admonitions

The configuration of this project allows the admonitions, also known as call-outs.

Here are some examples (for more information, please refer to the official documentation of [mkdocs-material](https://squidfunk.github.io/mkdocs-material/reference/admonitions/)).

!!! warning

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

## :material-gesture-tap-button: Buttons  

The configuration of this project allows to add attributes to all inline- and block-level elements with a simple syntax, turning any link into a button.

Here are some examples (for more information, please refer to the official documentation of [mkdocs-material](https://squidfunk.github.io/mkdocs-material/reference/buttons/)).

[Subscribe to our newsletter](#){ .md-button }      [Subscribe to our newsletter](#){ .md-button .md-button--primary }      [Send :fontawesome-solid-paper-plane:](#){ .md-button }

---

## :material-code-json: Code blocks

This configuration enables syntax highlighting on code blocks and inline code blocks, and allows to include source code directly from other files.

Here are some examples (for more information, please refer to the official documentation of [mkdocs-material](https://squidfunk.github.io/mkdocs-material/reference/code-blocks/)).

    ``` py title="example with highlighting lines" hl_lines="2 3"
    def bubble_sort(items):
        for i in range(len(items)):
            for j in range(len(items) - 1 - i):
                if items[j] > items[j + 1]:
                    items[j], items[j + 1] = items[j + 1], items[j]
    ```


``` py title="example with highlighting lines" hl_lines="2 3"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```


    ``` py title="example with annotation"
    def my_method(self):
        return self # (1)
    ```

    1.  :man_raising_hand: I'm a code annotation! I can contain `code`, __formatted text__, images, ... basically anything that can be written in Markdown.


``` py title="example with annotation"
def my_method(self):
    return self # (1)
```

1.  :man_raising_hand: I'm a code annotation! I can contain `code`, __formatted text__, images, ... basically anything that can be written in Markdown.


```
I'm an inline code blocks  `#!python range()` with a syntax highlighting.
```

I'm an inline code blocks  `#!python range()` with a syntax highlighting.

---

## :material-tab-plus: Content tabs

This configuration enables content tabs, and allows to nest arbitrary content inside content tabs, including code blocks and ... more content tabs!

Here are some examples (for more information, please refer to the official documentation of [mkdocs-material](https://squidfunk.github.io/mkdocs-material/reference/content-tabs/)).

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

## :octicons-workflow-24: Diagrams

This configuration enables native support for `Mermaid.js` diagrams.

Here are some examples (for more information, please refer to the official documentation of [mkdocs-material](https://squidfunk.github.io/mkdocs-material/reference/diagrams/)).

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

## :material-format-font: Formatting


This configuration enables support for keyboard keys, tracking changes in documents, defining sub- and superscript and highlighting text.

Here are some examples (for more information, please refer to the official documentation of [mkdocs-material](https://squidfunk.github.io/mkdocs-material/reference/formatting/)).

    ```
    ++ctrl+alt+del++

    ```

++ctrl+alt+del++


    ```
    Text can be {--deleted--} and replacement text {++added++}. This can also be
    combined into {~~one~>a single~~} operation. {==Highlighting==} is also
    possible {>>and comments can be added inline<<}.

    {==

    Formatting can also be applied to blocks by putting the opening and closing
    tags on separate lines and adding new lines between the tags and the content.

    ==}

    ```

Text can be {--deleted--} and replacement text {++added++}. This can also be
combined into {~~one~>a single~~} operation. {==Highlighting==} is also
possible {>>and comments can be added inline<<}.

{==

Formatting can also be applied to blocks by putting the opening and closing
tags on separate lines and adding new lines between the tags and the content.

==}

---

## :material-bug: Icons, Emojis 

This configuration enables the use of icons and emojis by using simple shortcodes which can be discovered through the [icon search](https://squidfunk.github.io/mkdocs-material/reference/icons-emojis/#search).

Here are some examples (for more information, please refer to the official documentation of [mkdocs-material](https://squidfunk.github.io/mkdocs-material/reference/icons-emojis/)).

```:smile: :fontawesome-regular-face-laugh-wink: :octicons-smiley-16:```

:smile: :fontawesome-regular-face-laugh-wink: :octicons-smiley-16:

---

## :material-image-plus-outline: Images

This configuration adds the ability to align images, add captions to images (rendering them as figures), and mark large images for lazy-loading. It also works for image zoom functionality.

Here are some examples (for more information, please refer to the official documentation of [mkdocs-material](https://squidfunk.github.io/mkdocs-material/reference/images/)) and [mkdocs-glightbox](https://github.com/blueswen/mkdocs-glightbox).

![Image title](https://dummyimage.com/600x400/){ loading=lazy }

---

## :material-format-list-checks: Lists 

This configuration enables the use of definition lists and tasks lists, which are both not part of the standard Markdown syntax. 

Here are some examples (for more information, please refer to the official documentation of [mkdocs-material](https://squidfunk.github.io/mkdocs-material/reference/lists/))

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

## :fontawesome-solid-bars-progress: Progress bar 

This configuration enables support for progress/status bars.


Here are some examples (for more information, please refer to the official documentation of [PyMdown](https://facelessuser.github.io/pymdown-extensions/extensions/progressbar/))


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
