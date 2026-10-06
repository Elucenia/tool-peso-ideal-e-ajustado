<!-- ELUCENIA technical documentation · peso-ideal-e-ajustado · zh · no clinical/professional/rights approval -->

# 理想体重与调整体重

[条件、来源与许可](https://elucenia.org/zh/tools/peso-ideal-e-ajustado)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 性别

`sexo`

- `F` — 女性
- `M` — 男性

### 身高

`altura`

cm · 范围: 120–230

### 实际体重（用于调整体重）

`peso`

kg · 选填 · 范围: 25–350

## 方法版本

Devine 1974/Robinson 1983/Miller 1983；Pai–Paloucek 2000综述；调整体重本地系数0.4

## 已记录的公式

理想体重 (Devine): 男性 50 kg + 2.3 kg 每增加一英寸，基准为 5 英尺; 女性 45.5 kg + 2.3 kg 每增加一英寸，基准为 5 英尺. 以厘米计: 50 (45.5) + 2.3 × (身高 − 152.4) ÷ 2.54.

调整体重 = 理想体重 + 0.4 × (实际体重 − 理想体重).

## 限制与适用人群

理想体重是由身高/体重表估计的值，并非瘦体重测量。药代动力学关系因药物而异；此摘要没有确认通用调整系数0.4。用于剂量的体重选择应遵循药物来源和对应人群。

## 参考文献

- [Pai MP, Paloucek FP. The origin of the "ideal" body weight equations. Ann Pharmacother, 2000.](https://doi.org/10.1345/aph.19381)

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

## 已记录的结果

以下信息保留该方法对合成示例的输出，不构成独立的临床验证。

### 1

Devine 公式计算的理想体重


### 2

实际体重 > 理想体重的 120%：对于亲水性药物和氨基糖苷类药物，使用调整体重

| 结果详情 | |
| --- | --- |
| 实际体重相对于理想体重 | 160% |
| 调整体重（IBW + 0,4 × 超出部分） | 93.0 kg |


### 3

Devine 公式计算的理想体重


### 4

Devine 公式计算的理想体重

