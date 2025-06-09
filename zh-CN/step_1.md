使用 `solid-border` 或 `dashed-border` 类在 `<section>` 或 `<div>` 周围添加实线或虚线边框。 边框使用 `detail2` 颜色。

![一个带有虚线边框的 <section>，后跟三个 <div> 元素。 一个有虚线边框，一个没有边框，一个有实线边框。](images/web-borders.png)

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

**提示**：你可以调整 `style.css` 中 `solid-border` 和 `dashed-border` 类的 `border` 值。
