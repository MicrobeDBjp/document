# document
Documents of MicrobeDB.jp

# About
## MicrobeDB.jp motivation
新型シーケンサーの普及により、微生物のゲノム・メタゲノムデータは公共の塩基配列データベース（DB）中に爆発的な勢いで蓄積されています。それらを独自の手法で整理したDBとしては、ゲノムDBとしては例えばPATRICやMicroScope、Ensembl Bacteria等、メタゲノムDBとしてはMG-RAST、EBI-Metagenomics、IMG/M等、どちらも多数の優れたDBが既に存在します。しかしながら、多様な微生物について、ゲノムとメタゲノムデータを統合して整理したDBは、メタデータに着目して整理したJGI GOLD等以外は、ほとんど存在しません。MicrobeDB.jpプロジェクトは、Semantic Web技術を用いて、微生物のゲノムとメタゲノムデータ、及びオーソログや菌株等の両データと深く関連したデータを統合した微生物の統合DBを構築し、Webサイト上で実装された多様な解析・視覚化手法を用いてそれらのデータから、様々なバックグラウントを持つ研究者が知識発見を容易に行えるようにすることを目的としています。

https://github.com/MicrobeDBjp/document/blob/master/test.md


## Brief description
MicrobeDB.jpプロジェクトでは、主に原核生物の、International Nucleotide Sequence Database Collabolation (INSDC)で公開されているゲノムデータと16S rRNA gene amplicon sequencing (メタ16S)、メタゲノムデータを再解析した上で、Semantic Web技術を用いて統合しております。それらデータに、菌株保存機関由来の菌株データやゲノム・メタ16S・メタゲノムのサンプルの分離源等のメタデータ等の多様なデータを統合するとともに、様々な解析アプリケーションをWebページ上で実装し、微生物の統合DB「MicrobeDB.jp」としてCC BY 4.0のライセンスで公開しております。メタデータについては、様々なオントロジー・統制語彙を用いて異なる由来のデータ間で可能な範囲で用いる語彙を統一して記述をしています。加えて、ユーザが持つ原核生物のゲノム配列データおよびメタ16S・メタゲノム配列データを入力として、homolog組成や系統組成、遺伝子機能組成を計算し、公開済みの組成データと比較解析可能な機能も利用できます。
## Semantic Web technology
Semantic Web技術とは、個々のデータおよびそれらの間のリンクが持つ意味（セマンティクス）を記述し、データの統合・共有・再利用を容易にすることを目的として開発された技術仕様のことを指します。異なるDB由来のデータを統合する際には、それぞれのDBでデータ記述の際に用いる語彙や考え方が異なる点を考慮しつつデータを統合する必要があります。Semantic Web技術を用いて個々のデータの意味を記述し、かつデータ統合の際にデータ間のリンクの意味を記述することで、比較的容易にデータの統合が可能になります。具体的な技術としては、データの記述形式であるResource Description Framework (RDF)やオントロジー記述言語Web Ontology Language (OWL)、RDFに対する検索言語SPARQL Protocol and RDF Query Language (SPARQL)等があります。Semantic Web技術の詳細は、W3CのWebページ (https://www.w3.org/2001/sw/ )　および慶應義塾大学の神崎先生のWebページ　( https://www.kanzaki.com/docs/sw/ )等が参考になります。
## Funding
MicrobeDB.jpプロジェクトは、国立研究開発法人科学技術振興機構 (JST) バイオサイエンスデータベースセンター (NBDC) による、ライフサイエンスデータベース統合推進事業「統合化推進プログラム」により、 2011年4月-2014年3月、2014年4月-2017年3月、2017年4月-2022年3月の3期にわたり研究開発費をサポートしていただいております。
## License
Creative Commons Attribution 4.0 International (CC BY 4.0) license ( https://creativecommons.org/licenses/by/4.0/legalcode.ja )
