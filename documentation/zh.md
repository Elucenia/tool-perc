<!-- ELUCENIA technical documentation · perc · zh · no clinical/professional/rights approval -->

# PERC 标准

[条件、来源与许可](https://elucenia.org/zh/tools/perc)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 年龄 ≥ 50 岁

`idade`

### 心率 ≥ 100 bpm

`fc`

### 空气吸入时氧饱和度 \< 95%

`sat`

### 单侧下肢水肿

`edema`

### 咯血

`hemoptise`

### 过去 4 周内因手术或创伤住院

`cirurgia`

### 既往深静脉血栓或肺栓塞

`tev`

### 使用雌激素（避孕或激素替代）

`hormonio`

## 方法版本

PERC/Kline 2004：低初始怀疑下8项阴性标准；不自动决策

## 已记录的公式

八个是/否问题。PERC为 阴性 仅当所有答案均为“否”。只适用于医生已判断临床 低概率 （临床总体判断\<15%）。

## 限制与适用人群

PERC 2004在因疑似肺栓塞接受评估的急诊患者中推导，并在低风险和极低风险人群中检验。八项标准须同时为阴性，包括原始研究中的年龄\< 50岁、脉搏\< 100/min和氧饱和度\> 94%。该规则不能确定风险为零，适用性取决于预先选择的人群；时间定义和纳入标准应核对所采用的版本。

## 参考文献

- [Kline JA et al. Clinical criteria to prevent unnecessary diagnostic testing in emergency department patients with suspected pulmonary embolism. J Thromb Haemost, 2004.](https://doi.org/10.1111/j.1538-7836.2004.00790.x)

- [Freund Y et al. Effect of the Pulmonary Embolism Rule-Out Criteria on subsequent thromboembolic events among low-risk emergency department patients: the PROPER randomized clinical trial. JAMA, 2018.](https://doi.org/10.1001/jama.2017.21904)

## 复现技术测试

在此仓库的根目录中运行 node test.cjs，以重复已记录的合成案例。原始输入、预期结果和容差保持不变。技术测试不构成临床验证。

```sh
node test.cjs
```

tool.json 包含来源、版本和审查范围。examples.json 保留合成输入与预期结果；results.json 记录实际得到的结果。

[记录与参考文献](../tool.json) · [JavaScript代码](../calculator.js) · [参考案例](../examples.json) · [results.json](../results.json)

## 审查与使用条件

尚未开展独立临床审查。

此界面为自主编写的翻译，并非官方或认证版本。尚未完成独立临床审查、专业语言审查或工具权利授权。

公式或分类结果。解释、处理及适用性须结合专业评估和所选来源。

## 许可与署名

Apache-2.0 仅适用于 ELUCENIA 代码。工具、出版物、翻译和数据的权利仍归各自权利人所有。请保留 LICENSE 和 NOTICE。

ELUCENIA · Felipe Guedes · Copyright © 2026
