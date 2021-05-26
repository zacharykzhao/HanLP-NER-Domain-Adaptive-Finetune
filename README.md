# HanLP-NER-Domain-Adaptive-Finetune
Finetun HanLP NER model using domain data

## Install HanLP 2.0
! pip install hanlp[full]

## prepare your data
Chinese character based model:

data format:

| 我   | B-people |
| ---- | -------- |
| 们   | I-people |
| 在   | O        |
| 尝   | O        |
| 试   | O        |
| 中   | B-Target |
| 文   | I-Target |
| 命   | I-Target |
| 名   | I-Target |
| 实   | I-Target |
| 体   | I-Target |
| 识   | I-Target |
| 别   | I-Target |
| 。   | O        |

### 注意：
数据中 data部分不能有：空格" " ， 分隔符:"｜"
