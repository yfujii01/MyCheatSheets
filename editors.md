# エディターチートシート

※コマンドに入れているのは自分用設定なので初期値でない可能性がある

## カーソルを下に増やす(マルチカーソル)

  | editor   | コマンド          | 設定方法                        |
  | -------- | ----------------- | ------------------------------- |
  | vscode   | ctrl + alt + down | editor.action.insertCursorBelow |
  | intellij | ctrl + alt + down | Clone Caret Below               |
  | vim      | -                 | (設定方法不明)                  |

## カーソル上の単語と同一の単語全てにカーソルを置く(マルチカーソル)

  | editor   | コマンド          | 設定方法                                        |
  | -------- | ----------------- | ----------------------------------------------- |
  | vscode   | ctrl + f2         | editor.action.changeAll                         |
  | intellij | -                 | 不明                                            |
  | vim      | f2                | let g:multi_cursor_select_all_key      = '<f2>' |

## コメントアウト

  | editor   | コマンド                              | 設定方法                        |
  | -------- | ------------------------------------- | ------------------------------- |
  | vscode   | ctrl + /                              | editor.action.commentLine       |
  | intellij | ctrl + /                              | Comment with Line Comment       |
  | vim      | (normalmode) gcc <br> (visualmode) gc | プラグイン'tomtom/tcomment_vim' |

## 行を下へ移動

  | editor   | コマンド            | 設定方法                          |
  | -------- | ------------------- | --------------------------------- |
  | vscode   | ctrl + shift + down | editor.action.moveLinesDownAction |
  | intellij | ctrl + shift + down | Move Line Down                    |
  | vim      | -                   | (設定方法不明)                    |

## フォーマット

  | editor   | コマンド            | 設定方法                          |
  | -------- | ------------------- | --------------------------------- |
  | vscode   | ctrl + alt + l      | editor.action.formatDocument      |
  | intellij | ctrl + alt + l      | Reformat Code                     |
  | vim      | gg=G                | デフォルト(※調整はインデントのみ) |
