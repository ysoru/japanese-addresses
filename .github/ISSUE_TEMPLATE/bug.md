---
name: バグ報告
about: japanese-addresses のバグを報告するときにこのテンプレートをお使いください。
title: バグ報告
labels: バグ報告
assignees: champierre

---

# バグの内容

- (例) latest.csv の長野県長野市篠ノ井塩崎の「大字町丁目名カナ」および「大字町丁目名ローマ字」のデータが空欄。

# 再現手順

- (例) latest.csv をダウンロードする。
- (例) latest.csv を開き、長野県長野市篠ノ井塩崎のデータを確認すると、以下のように「大字町丁目名カナ」および「大字町丁目名ローマ字」の欄が空です。

```
"20","長野県","ナガノケン","NAGANO KEN","20201","長野市","ナガノシ","NAGANO SHI","篠ノ井 塩崎","","",,"36.552969","138.109935"
```

# 本来どう動作すべきか

- (例) 「大字町丁目名カナ」および「大字町丁目名ローマ字」の欄にデータが入っているべき。

# スクリーンショット(オプション)

スクリーンショットがあったほうがわかりやすい場合には、ここに添付してください。

# 参考情報(オプション)

その他参考のために必要な情報があれば、ここに記載してください。