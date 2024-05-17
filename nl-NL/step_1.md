Gebruik de `solid-border` of `dashed-border` class om een effen of gestippelde rand toe te voegen rond een `<section>` of `<div>`. De randen gebruiken de `detail2` kleur.

![A \<section> with a dashed border, followed by three \<div> elements. One has a dashed border, one has no border, and one has a solid border.](images/web-borders.png)

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

**Tip:** You can adjust the `border` values for the `solid-border` and `dashed-border` classes in `style.css`.
