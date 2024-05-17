Gebruik de `solid-border` of `dashed-border` class om een effen of gestippelde rand toe te voegen rond een `<section>` of `<div>`. De randen gebruiken de `detail2` kleur.

![Een \<section> met een stippellijn, gevolgd door drie \<div> elementen. Eén heeft een stippellijn, één heeft geen rand en één heeft een effen rand.](images/web-borders.png)

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

**Tip:** Je kunt de `border` waarden aanpassen voor de `solid-border` en `dashed-border` classes in `style.css`.
