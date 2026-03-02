---
name: hello-world
description: Hello Worldメッセージを出力するスキル。ユーザーが「Hello World」の出力、挨拶の表示、動作確認用のテスト出力、またはスキルの動作テストを求めた場合に使用してください。「hello」「挨拶」「テスト出力」などのキーワードにも反応します。
---

# Hello World スキル

このスキルは「Hello World」メッセージを出力します。

## 使い方

ユーザーからHello Worldの出力を求められた場合、以下の手順に従ってください：

1. ユーザーに対して **Hello World** メッセージを表示する
2. 出力形式はユーザーの要望に合わせて柔軟に対応する（プレーンテキスト、コードブロック、ファイル出力など）

## デフォルト出力

特に指定がない場合は、以下のメッセージをそのまま出力してください：

```
Hello, World!
```

## 出力バリエーション

ユーザーの要望に応じて、以下のような形式でも出力できます：

### プレーンテキスト
```
Hello, World!
```

### プログラムコード（例：JavaScript）
```javascript
console.log("Hello, World!");
```

### プログラムコード（例：Python）
```python
print("Hello, World!")
```

### HTMLファイル
```html
<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <title>Hello World</title>
</head>
<body>
  <h1>Hello, World!</h1>
</body>
</html>
```

## 注意事項

- このスキルはシンプルなデモ・テスト用スキルです
- ユーザーが特定のプログラミング言語を指定した場合は、その言語でHello Worldプログラムを作成してください
- 出力後、追加のカスタマイズが必要かユーザーに確認してください
