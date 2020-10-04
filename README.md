# Default-VisualStudioCode
VisualStudioCode for windows ステップ実行 デフォルトファイル
---
# 参考サイト
- [visual studi codeでC言語をステップ実行](http://aimek-developer.blogspot.com/2018/10/visual-studio-code-c.html)
---
# 変更点

- ファイル名に左右されず，math.hに対応した gccコマンドに変更
  
  - tasks.jon `"command": "gcc -g -lm -O0 -o a.exe ${file}"`
---
