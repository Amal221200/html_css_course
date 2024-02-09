# HTML Lists

HTML lists allow web developers to group a set of related items in lists.

## Unordered HTML List
An unordered list starts with the ``<ul>`` tag. Each list item starts with the ``<li>`` tag.

The list items will be marked with bullets (small black circles) by default:

Example: 
```
    <ul>
        <li>Coffee</li>
        <li>Tea</li>
        <li>Milk</li>
    </ul>
```

## Ordered HTML List
An ordered list starts with the ```<ol>``` tag. Each list item starts with the ```<li>``` tag.

The list items will be marked with numbers by default:

Example: 
```
    <ol>
        <li>Coffee</li>
        <li>Tea</li>
        <li>Milk</li>
    </ol>
```

## HTML Description Lists
HTML also supports description lists.

A description list is a list of terms, with a description of each term.

The ``<dl>`` tag defines the description list, the ``<dt>`` tag defines the term (name), and the ``<dd>`` tag describes each term:

Example: 
```
<dl>
  <dt>Coffee</dt>
  <dd>- black hot drink</dd>
  <dt>Milk</dt>
  <dd>- white cold drink</dd>
</dl>
```

## Nested Lists
Lists inside a list

Example
```
<ul>
    <li>Fruits</li>
    <ol>
        <li>Apple</li>
        <li>Mangoes</li>
        <li>Grapes</li>
    </ol>
    <li>Vegetables</li>
    <ol>
        <li>Tomato</li>
        <li>Potato</li>
        <li>Spinach</li>
    </ol>
</ul>
```