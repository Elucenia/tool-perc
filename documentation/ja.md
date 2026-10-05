<!-- ELUCENIA technical documentation · perc · ja · no clinical/professional/rights approval -->

# PERC基準

[条件・出典・許諾](https://elucenia.org/ja/tools/perc)

## 使い方

ポータルでツールを使用するか、ローカルHTTPサーバー経由でindex.htmlを開いてください。言語を選択し、項目を入力して計算してください。

## 入力項目と単位

### 年齢 ≥ 50 歳

`idade`

### 心拍数 ≥ 100 bpm

`fc`

### 室内気で酸素飽和度 \< 95%

`sat`

### 片側下肢浮腫

`edema`

### 喀血

`hemoptise`

### 過去4週間以内の入院を要する手術または外傷

`cirurgia`

### 深部静脈血栓症・肺塞栓症の既往

`tev`

### エストロゲン使用（避妊薬またはホルモン補充）

`hormonio`

## 方法の版

PERC/Kline 2004：初期疑いが低い患者の8陰性基準；自動判断ではない

## 記載された計算式

8つのはい/いいえ質問。PERCが 陰性 となるのはすべて「いいえ」の場合のみ。医師が既に臨床的 低確率 と判断した患者のみ（ゲシュタルト\<15%）。

## 限界・対象集団

PERC 2004は、肺塞栓症の評価を受けた救急患者から導出され、低リスクおよび非常に低リスクの群で検証されました。原研究の年齢\< 50歳、脈拍\< 100/min、酸素飽和度\> 94%を含め、八つの基準がすべて同時に陰性である必要があります。このルールはリスクがゼロであることを示すものではなく、適用可能性は対象集団の事前選択に依存します。時間に関する定義と組入れ基準は、使用する版で確認する必要があります。

## 参考文献

- [Kline JA et al. Clinical criteria to prevent unnecessary diagnostic testing in emergency department patients with suspected pulmonary embolism. J Thromb Haemost, 2004.](https://doi.org/10.1111/j.1538-7836.2004.00790.x)

- [Freund Y et al. Effect of the Pulmonary Embolism Rule-Out Criteria on subsequent thromboembolic events among low-risk emergency department patients: the PROPER randomized clinical trial. JAMA, 2018.](https://doi.org/10.1001/jama.2017.21904)

## 技術テストの再現

このリポジトリのルートディレクトリでnode test.cjsを実行すると、記録された合成ケースを再実行できます。元の入力、期待結果、許容誤差は保持されています。技術テストは臨床的検証を意味しません。

```sh
node test.cjs
```

tool.jsonには出典、版、確認範囲が記録されています。examples.jsonには合成入力と期待結果が保持され、results.jsonには実際に得られた結果が記録されています。

[記録・参考文献](../tool.json) · [JavaScriptコード](../calculator.js) · [参照ケース](../examples.json) · [results.json](../results.json)

## 確認状況と使用条件

独立した臨床レビューは実施されていません。

このインターフェースは独自に作成した翻訳であり、公式版や認証済みの版ではありません。独立した臨床レビュー、専門家による言語レビュー、評価尺度等の権利許諾の確認は実施されていません。

式または分類の結果です。解釈、対応、適用可能性は専門家による評価と選択した出典に依存します。

## ライセンスと帰属表示

Apache-2.0はELUCENIAのコードにのみ適用されます。評価尺度等、出版物、翻訳、データの権利は、それぞれの権利者に帰属します。LICENSEとNOTICEを保持してください。

ELUCENIA · Felipe Guedes · Copyright © 2026
