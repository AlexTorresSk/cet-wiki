The following are properties or options that are added to the constructor when the title bar is created. **They are all optional**.

Here's a small example of how it should go:

```js
new Titlebar({
    ...options...
})
```

---

## Background color

The background color of titlebar. _The default color is `#ffffff`_

<code>
    backgroundColor: <b><a href="Color">Color</a></b>
</code>

## Icon

The icon shown on the left side of titlebar. _The default is the favicon of the index.html_

<code>
    icon: <b>string</b>
</code>

## Icon size

The icon size of titlebar. Value between 16 and 24. _The default is `16`_

<code>
    iconSize: <b>number</b>
</code>

## Icons

The path of the icons of titlebar.<br>
Para saber como se personalizan revise [Icons](Icons)

<code>
    icons: <b>string</b>
</code>

## Shadow

The shadow color of titlebar. _The default is `false`_

<code>
    shadow: <b>boolean</b>
</code>

## Minimizable

Define if the minimize button is enabled. _The default is `true`_

<code>
    minimizable: <b>boolean</b>
</code>

## Maximizable

Define if the maximize and restore buttons are enabled. _The default is `true`_

<code>
    maximizable: <b>boolean</b>
</code>

## Closeable

Define if the close button is enabled. _The default is `true`_

<code>
    closeable: <b>boolean</b>
</code>

## Order

Set the order of the elements on the title bar. You can use `inverted`, `first-buttons` or don't add for. _The default is `undefined`_

<code>
    order: <b>string</b>
</code>

## Title horizontal alignment

Set horizontal alignment of the window title. You can use `left`, `right` or `center`. _The default value is `center`_

<code>
    titleHorizontalAlignment: <b>string</b>
</code>

## Container overflow

Sets the value for the overflow of the container after title bar. Youy can use `auto`, `hidden` or `visible`. _The default value is `auto`_

<code>
    containerOverflow: <b>string</b>
</code>

## Menu

The menu to show in the title bar. You can use `Electron.Menu` or not add this option and the menu created in the main process will be taken. _The default is `undefined`_

For more info view [Menu](Menu). 

<code>
    menu: <a href="https://www.electronjs.org/es/docs/latest/api/menu">
        <b>Electron.Menu</b>
    </a>
</code>

## Menu position

The position of menubar on titlebar. You can use `left` or `bottom`. _The default is `left`_ 

For more info view [Menu](Menu). 

<code>
    menuPosition: <b>string</b>
</code>

## Enable mnemonics

Enable the mnemonics on menubar and menu items. _The default is `true`_ 

<code>
    enableMnemonics: <b>boolean</b>
</code>

## Item background color

The background color when the mouse is over the item. _The default is `undefined` (is calculated automatically)_ 

<code>
    itemBackgroundColor: <b><a href="Color">Color</a></b>
</code>

## Menu SVG color

The color of the svg icons in the menu. _The default is `undefined` (is calculated automatically)_ 

<code>
    svgColor: <b><a href="Color">Color</a></b>
</code>
