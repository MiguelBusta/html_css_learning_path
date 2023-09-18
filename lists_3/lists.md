# Lists

- Numbered lists
- Bullet lists
- Definition lists

## Ordered lists

```
<ol>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ol>
```

Browsers indent lists by default.

## Unordered lists

```
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ul>
```

## Definition lists

```
<dl>
    <dt>Sashimi</dt>
    <dd>Sliced raw fish that is served with condiments</dd>
    <dt>Scale</dt>
    <dd>A device used to accurately measure the weight of ingredients</dd>
</dl>
```

```<dl></dl>``` -> Series of terms and their definition.

```<dt></dt>``` -> Contains the term that is going to be defined.

```<dd></dd>``` -> This is used to contain the definition.

## Nested lists

You can put a second list inside an ```<li></li>``` element to create a sub-list or nested list.

```
<ul>
    <li>Mousses</li>
    <li>Pastries
    <ul>
        <li>Croissant</li>
        <li>Mille-feuille</li>
        <li>Palmier</li>
        <li>Profiterole</li>
    </ul>
    </li>
    <li>Tarts</li>
</ul>
```