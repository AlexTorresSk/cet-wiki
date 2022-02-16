The following are methods or functions that can be called after creating the title bar.

## Update background color

Update the background color of the title bar.
<br><br>
Params: <code>backgroundColor: <b><a href="Color.md">Color</a></b></code><br>
Return <code>void</code>

```js
titlebar.updateBackground(Color.fromHex('#ffffff'));
```

## Update menu item background color

Update the item background color of the menunubar.
<br><br>
Params: <code>itemBGColor: <b><a href="Color.md">Color</a></b></code><br>
Return <code>void</code>

```js
titlebar.updateItemBGColor(Color.fromHex('#000000'));
```

## Update title

Update the title of the title bar. _This also changes the title of the html page_
<br><br>
Params: <code>title: <b>string</b></code><br>
Return <code>void</code>

```js
titlebar.updateTitle('wherever');
```

## Update icon

Update the icon of the title bar.
<br><br>
Params: <code>path: <b>string</b></code><br>
Return <code>void</code>

```js
titlebar.updateIcon(path.resolve('icon-route/icon.ext'));
```

## Update menu

Update the menu of the title bar.
<br><br>
Params: <code>menu: <a href="https://www.electronjs.org/es/docs/latest/api/menu"><b>Electron.Menu</b></a></code><br>
Return <code>void</code>

```js
titlebar.updateMenu(myMenu);
```

## Refresh menu

Update the menu from `Menu.getApplicationMenu()`. _This is an `async` method_
<br><br>
Params: void<br>
Return <code>Promise\<void></code>

```js
titlebar.refreshMenu();
```

## Update menu position

Update the position of menubar. You can use `left` or `bottom`.
<br><br>
Params: <code>menuPosition <b>string</b></code><br>
Return <code>void</code>

```js
titlebar.updateMenuPosition('right');
```

## Update title alignment

Update the horizontal alignment of the title. You can use `left`, `center` or `right`.
<br><br>
Params: <code>side: <b>string</b></code><br>
Return <code>void</code>

```js
titlebar.updateTitleAlignment('right');
```

## Dispose titlebar

Remove the titlebar, menubar and all methods.
<br><br>
Params: void<br>
Return <code>void</code>

```js
titlebar.dispose();
```