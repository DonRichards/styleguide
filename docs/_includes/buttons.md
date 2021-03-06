# Buttons

Buttons are used for **actions**, like in forms, while textual hyperlinks are used for **destinations**, or moving from one page to another.

### Default buttons

Use the standard—yet classy—`.btn` for form actions and primary page actions. These are used extensively around the site.

When using a `<button>` element, **always specify a `type`**. When using a `<a>` element, **always add `role="button"` for accessibility**.

{% example html %}
<button class="btn" type="button">Button button</button>
<a class="btn" href="#" role="button">Link button</a>
{% endexample %}

### Sizes

Buttons are availables in multiples sizes: Large, Normal, Small and Extra-Small.

{% example html %}
<button class="btn btn-lg" type="button">Large Button</button>
<button class="btn" type="button">Button</button>
<button class="btn btn-sm" type="button">Small button</button>
<button class="btn btn-xs" type="button">Extra Small button</button>
{% endexample %}

### Styles

Buttons can be filled to indicate a more important action:

{% example html %}
<button class="btn btn-primary" type="button">Primary button</button>
<button class="btn btn-success" type="button">Success button</button>
<button class="btn btn-danger" type="button">Danger button</button>
<button class="btn btn-warning" type="button">Warning button</button>
{% endexample %}

### Colored Text

Different styles of buttons are available to indicate different kind of actions.

{% example html %}
<button class="btn btn-text-primary" type="button">Primary button</button>
<button class="btn btn-text-success" type="button">Success button</button>
<button class="btn btn-text-danger" type="button">Danger button</button>
<button class="btn btn-text-warning" type="button">Warning button</button>
<button class="btn btn-link" type="button">Link button</button>
{% endexample %}

### Block Buttons

Create block level buttons—those that span the full width of a parent— by adding `.btn-block`.

{% example html %}
<button type="button" class="btn btn-primary btn-lg btn-block">Block level button</button>
<button type="button" class="btn btn-lg btn-block">Block level button</button>
{% endexample %}

### Outline

Outline buttons downplay an action as they appear like boxy links. Just add `.btn-outline` and go.

{% example html %}
<button class="btn btn-count" type="button">Default button</button>
<button class="btn btn-primary btn-outline" type="button">Primary button</button>
<button class="btn btn-success btn-outline" type="button">Success button</button>
<button class="btn btn-danger btn-outline" type="button">Danger button</button>
<button class="btn btn-warning btn-outline" type="button">Warning button</button>
{% endexample %}

### Plain

Plain buttons are flat and filled buttons.

{% example html %}
<button class="btn btn-plain" type="button">Default button</button>
<button class="btn btn-primary btn-plain" type="button">Primary button</button>
<button class="btn btn-success btn-plain" type="button">Success button</button>
<button class="btn btn-danger btn-plain" type="button">Danger button</button>
<button class="btn btn-warning btn-plain" type="button">Warning button</button>
{% endexample %}

### States

Buttons can have different states:

{% example html %}
<div class="btn-toolbar">
    <button class="btn" type="button">Default</button>
    <button class="btn active" type="button">:active or .active</button>
    <button class="btn" disabled type="button">:disabled or .disabled</button>
</div>
<div class="btn-toolbar">
    <button class="btn btn-primary" type="button">Default</button>
    <button class="btn btn-primary active" type="button">:active or .active</button>
    <button class="btn btn-primary" disabled type="button">:disabled or .disabled</button>
</div>
{% endexample %}

### Buttons Labels

Buttons can contains a new-line label:

{% example html %}
<button class="btn btn-primary btn-block" type="button">
    Download for OS X
    <span class="btn-label">OS X 10.9 or later</span>
</button>
{% endexample %}

