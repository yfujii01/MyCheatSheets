# javascript チートシート

- テーブル内容をテキストで抜き出す

``` javascript
var tbl = document.querySelector('#tableid');
var rows = tbl.rows;
var table_str = '';
for (var i = 0, len = rows.length; i < len; i++) {
  var cols = rows[i].cells.length;
  var line = '';
  for (var j = 0; j < cols; j++) {
    line += rows[i].cells[j].innerText;
  }
  table_str += line.trim() + '\n'
}
```
