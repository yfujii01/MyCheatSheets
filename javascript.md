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

- trimする

  - 文字列の先頭および末尾の連続する「半角空白・タブ文字・全角空白」を削除します

    ``` javascript
    String.prototype.trim = function() {
      return this.replace(/^[\s　]+|[\s　]+$/g, '');
    }
    ```

  - 文字列の先頭の連続する「半角空白・タブ文字・全角空白」を削除します
    ``` javascript
    String.prototype.ltrim = function() {
      return this.replace(/^[\s　]+/g, '');
    }
    ```

  - 文字列の末尾の連続する「半角空白・タブ文字・全角空白」を削除します
    ``` javascript
    String.prototype.rtrim = function() {
      return this.replace(/[\s　]+$/g, '');
    }
    ```

  - 文字列の先頭および末尾の連続する「半角空白・タブ文字」を削除します
    ``` javascript
    String.prototype.trim = function() {
      return this.replace(/^\s+|\s+$/g, '');
    }
    ```

