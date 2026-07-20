# Gut Microbiome LOD

腸内細菌、菌属、代謝産物、健康作用の関係をRDF形式で表現したLinked Open Dataです。
セマンティックweb授業

## 内容

このLODでは、次のクラスを定義しています。

- GutBacterium：腸内細菌
- BacterialGenus：菌属
- Metabolite：代謝産物
- HealthEffect：健康作用
- Reference：参考資料

## 主な関係

- belongsToGenus：腸内細菌が属する菌属
- produces：腸内細菌が産生する代謝産物
- associatedWith：腸内細菌と健康作用の関連
- hasRelatedEffect：代謝産物と健康作用の関連
- hasReference：情報の参考資料

## RDFファイル

- microbiome.ttl

## License

This dataset is licensed under CC BY 4.0.
