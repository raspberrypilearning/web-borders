Utilise la classe `solid-border` ou `dashed-border` pour ajouter une bordure solide ou en pointillés autour d'un `<section>` ou d'un `<div>`. Les bordures utilisent la couleur `detail2`.

![Un \<section> avec une bordure en pointillés, suivi de trois éléments \<div>. L'un d'eux a une bordure en pointillés, l'autre n'a pas de bordure et le troisième a une bordure pleine.](images/web-borders.png)

## --- code ---

language: html
filename: index.html
line_numbers: false
--------------------------------------------------------

<section>
    <h2 class="xcenter dashed-border">Lorem Ipsum</h2>
</section>

<section class="wrap">
    <div class="secondary dashed-border xcenter ycenter tile">
        <h3>Lorem ipsum</h3>
    </div>
    <div class="tertiary xcenter ycenter tile">
        <h3>Lorem ipsum</h3>
    </div>
    <div class="primary solid-border xcenter ycenter tile">
        <h3>Lorem ipsum</h3>
    </div> 
</section>

\--- /code ---

**Astuce :** tu peux ajuster les valeurs de `border` pour les classes `solid-border` et `dashed-border` dans `style.css`.
