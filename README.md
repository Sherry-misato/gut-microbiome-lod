# 食品成分・腸内細菌・健康作用に関するLOD

本リポジトリでは、食品、食品成分、食品に含まれる微生物、腸内細菌、健康作用の関係をRDFで表現したLinked Open Dataを公開しています。
セマンティックweb授業

## 概要

食品に含まれる成分や微生物と、腸内細菌および健康作用との関係を、主語・述語・目的語からなるRDFトリプルとして記述しています。

例：

- バナナはフラクトオリゴ糖を含む
- 玉ねぎはイヌリンを含む
- イヌリンはBifidobacterium属の増殖との関連が報告されている
- ブルーベリーはポリフェノールを含む
- ポリフェノールはAkkermansia muciniphilaとの関連が報告されている
- ヨーグルトには製品によってビフィズス菌が使用されている

## 公開データ

- [microbiome.ttl](https://sherry-misato.github.io/gut-microbiome-lod/microbiome.ttl)

## 主なクラス

- Food：食品
- FoodComponent：食品成分
- FoodMicroorganism：食品に含まれる微生物
- GutBacterium：腸内細菌
- HealthEffect：健康作用
- Reference：参考文献

## ライセンス

本データはCC BY 4.0ライセンスの下で公開しています。
