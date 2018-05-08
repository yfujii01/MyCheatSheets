# エディターチートシート

## カーソルを下に増やす
  |  editor  |     コマンド      |                                               設定方法                                               |
  | -------- | ----------------- | ---------------------------------------------------------------------------------------------------- |
  | vscode   | ctrl + alt + down | { "key": "ctrl+alt+down", "command": "editor.action.insertCursorBelow", "when": "editorTextFocus" }, |
  | intellij | ctrl + alt + down | Clone Caret Below に Add Keyboard Shortcutで設定                                                     |
  | vim      | -                 | 設定方法不明)                                                                                        |

## コメントアウト
  |  editor  |               コマンド                |                                                    設定方法                                                    |
  | -------- | ------------------------------------- | -------------------------------------------------------------------------------------------------------------- |
  | vscode   | ctrl + /                              | { "key": "ctrl+oem_2", "command": "editor.action.commentLine", "when": "editorTextFocus && !editorReadonly" }, |
  | intellij | ctrl + /                              | Comment with Line Comment に Add Keyboard Shortcutで設定                                                       |
  | vim      | (normalmode) gcc <br> (visualmode) gc | プラグイン'tomtom/tcomment_vim'                                                                                |

