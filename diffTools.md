# Diffツールチートシート

## どっちが参照でどっちが変更対象

git difftool を引数無しで指定した場合は

- 左が参考
- 右が変更対象(local)

## 変更をステージングする(git用)

  | editor   | コマンド   | 設定方法                |
  | -------- | ---------- | ----------------------- |
  | vim-diff | -          |                         |
  | vscode   | ctrl+enter | git.stageSelectedRanges |

## 変更を取り込む

  | editor   | コマンド | 設定方法   |
  | -------- | -------- | ---------- |
  | vim-diff | do       | デフォルト |
  | vscode   | 不明     | 不明       |

## 変更を送る

  | editor   | コマンド | 設定方法   |
  | -------- | -------- | ---------- |
  | vim-diff | dp       | デフォルト |
  | vscode   | 不明     | 不明       |

## 次の変更へジャンプ

  | editor   | コマンド | 設定方法                      |
  | -------- | -------- | ----------------------------- |
  | vim-diff | ]c       | デフォルト                    |
  | vscode   | f7       | editor.action.diffReview.next |

## 前の変更へジャンプ

  | editor   | コマンド | 設定方法                      |
  | -------- | -------- | ----------------------------- |
  | vim-diff | [c       | デフォルト                    |
  | vscode   | shift+f7 | editor.action.diffReview.prev |
