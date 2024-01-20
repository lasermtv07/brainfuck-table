# Brainfuck table generator
Brainfuck table generator is a brainfuck program that generates preset for an HTML table, for example:
```
<table>
<tr>
<td> </td>
<td> </td>
<td> </td>
<td> </td>
<td> </td>
</tr>
</table>
```
We had this as assignment in school (to write it in PHP), however I decided it wasn't challenging enough so I remade it in brainfuck. Because why not?
## How to use
The input is entered in the format 
```
[Number of rows][Delim][Number of columns]
```
where `[Number of rows]` and `[Number of columns]` must be padded with zeroes to make 3 digit numbers (eg. `005` and not `5`) and `[Delim]` is **any single character** serving as delimiter.
It does essentially nothing, I added it to make the input easy to read for the user. It is hardcoded, *something* must be here.
<br>**Recommended interpreter:** [El Brainfuck](https://copy.sh/brainfuck/)<br>
**Debugger I use:** [minoid.xyz](https://minond.xyz/brainfuck/)<br>

![image](https://github.com/lasermtv07/brainfuck-table/assets/118477750/582a5d74-fadb-4224-909c-70e4e4bc18a8)

---
*(c) lasermtv, 2024<br>
This program, including its documentation and everything else related to the program that I have rights over is released under the terms of the WTFPL v2 license from Sam Hocevar.
More info on his website, [wtfpl.net](http://www.wtfpl.net/). Full license text via the LICESE file*.


