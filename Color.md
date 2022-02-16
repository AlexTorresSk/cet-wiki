The **Color** class is a class that has been used from the vscode project.

## Static colors
You will find the following static colors that you can use to design your title bar, icons or menus.

- ![#000000](https://via.placeholder.com/15/000000/000000?text=+) `Color.BLACK`
- ![#0000FF](https://via.placeholder.com/15/0000FF/000000?text=+) `Color.BLUE`
- ![#00FFFF](https://via.placeholder.com/15/00FFFF/000000?text=+) `Color.CYAN`
- ![#00FF00](https://via.placeholder.com/15/00FF00/000000?text=+) `Color.GREEN`
- ![#D3D3D3](https://via.placeholder.com/15/D3D3D3/000000?text=+) `Color.LIGHTGREY`
- ![#FF0000](https://via.placeholder.com/15/FF0000/000000?text=+) `Color.RED`
- ☐ `Color.TRANSPARENT`
- ![#FFFFFF](https://via.placeholder.com/15/FFFFFF/000000?text=+) `Color.WHITE`

If instead you want to use your own color you can do so using the `fromHex` method, which receives a hexadecimal color in string format and returns a **`Color`**.

`Color.fromHex('#ff0000')`