# エディターチートシート

※コマンドに入れているのは自分用設定なので初期値でない可能性がある

## カーソルを下に増やす(マルチカーソル)

| editor   | コマンド                   | 設定方法                                   |
| ---      | ---                        | ---                                        |
| vscode   | ctrl + alt + down          | editor.action.insertCursorBelow            |
| intellij | ctrl + alt + down          | Clone Caret Below                          |
| vim      | -                          | -                                          |

## カーソル上の単語と同一の単語全てにカーソルを置く(マルチカーソル)

| editor   | コマンド                   | 設定方法                                   |
| ---      | ---                        | ---                                        |
| vscode   | ctrl + f2                  | editor.action.changeAll                    |
| intellij | -                          | -                                          |
| vim      | f2                         | let g:multi_cursor_select_all_key = '<f2>' |

## コメントアウト

| editor   | コマンド                   | 設定方法                                   |
| ---      | ---                        | ---                                        |
| vscode   | ctrl + /                   | editor.action.commentLine                  |
| intellij | ctrl + /                   | Comment with Line Comment                  |
| vim      | ctrl + / ctrl + /          | プラグイン'tomtom/tcomment_vim'            |

## 行を下へ移動

| editor   | コマンド                   | 設定方法                                   |
| ---      | ---                        | ---                                        |
| vscode   | ctrl + shift + down        | editor.action.moveLinesDownAction          |
| intellij | ctrl + shift + down        | Move Line Down                             |
| vim      | -                          | -                                          |

## フォーマット

| editor   | コマンド                   | 設定方法                                   |
| ---      | ---                        | ---                                        |
| vscode   | ctrl + alt + l             | editor.action.formatDocument               |
| intellij | ctrl + alt + l             | Reformat Code                              |
| vim      | gg=G                       | インデントのみ                             |

## 連番作成

| editor   | コマンド                   | 設定方法                                   |
| ---      | ---                        | ---                                        |
| vscode   | Insert Seqence Number      | プラグイン(vscode-input-sequence)          |
| intellij | -                          | -                                          |
| vim      | :'<,'>RenBang @ 1 1 1 %03d | 'deris/vim-rengbang'                       |
