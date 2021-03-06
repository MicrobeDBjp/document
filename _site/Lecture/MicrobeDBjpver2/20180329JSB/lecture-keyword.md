### キーワード検索 ###

#### 系統名の検索 ####
例: Rickettsia が見つかる環境を知りたい  
1. https://beta.microbedb.jp/
の一番上の検索窓に Rickettsia と入力してSearch
![RickettsiaHome](https://github.com/MicrobeDBjp/document/blob/master/Figures/RickettsiaHome.jpg)
  
2. RickettsiaについてMicrobeDB.jpのデータを検索した結果が、Stanzaのリストとして[表示される。](https://beta.microbedb.jp/search?q1=Rickettsia "Rickettsia検索結果")
![RickettsiaSecond](https://github.com/MicrobeDBjp/document/blob/master/Figures/RickettsiaStanza.jpg)
  
3. 様々なStanzaが表示されるが、例えばRickettsiaが多い環境については、Environmental Composition of Meta16S Stanzaと、Abundant Samples Stanzaを見ると、有益な情報が得られる。両Stanzaは、公開済みのINSDC DRA/ERA/SRA中のメタ16S/メタゲノム配列データから系統組成をMeGAP2で再解析すると共に、微生物の生息環境オントロジーである[MEO](https://bioportal.bioontology.org/ontologies/MEO)で環境をアノテーションした結果を元に作成されている。Environmental Composition of Meta16S Stanzaは指定した系統（今回はRickettsia）が平均的に多い環境をグラフ化し（値が1に近いほど群集中での平均存在量が多いが、この場合は最大値のbuilding associated（建築物関連）でも0.00139688なので、平均的な存在量は0.1%ほどと少ない）、Abundant Samples Stanzaは指定した系統が特に多いサンプルをリスト化している。
![RickettsiaDist](https://github.com/MicrobeDBjp/document/blob/master/Figures/RickettsiaEnvDist.jpg)
Abundant Samples Stanzaを見ると、昆虫のメタ16Sサンプルに混じってHome microbiome、この場合は家のドアノブ等のメタ16SサンプルでRickettsiaの存在量が多いサンプルがいくつか見つかることがわかる。  
[ERS238916](https://beta.microbedb.jp/search/?q1=ERS238916&q1_cat=sample&q1_param_srs_id=ERS238916)等、詳細を確認したいサンプルのIDを選択すれば、そのサンプルのメタデータや系統組成等がのったページを見ることができる。
![ERS238916](https://github.com/MicrobeDBjp/document/blob/master/Figures/ERS238916.jpg)
  
  
#### 遺伝子名の検索 ####
例:  fliGの系統分布を知りたい  
1. https://beta.microbedb.jp/
の一番上の検索窓に fliG と入力してSearchすると、fliGという文字列でマッチするMBGD orthologリストのStanzaが表示される。
![fliG](https://github.com/MicrobeDBjp/document/blob/master/Figures/fliG.jpeg)
  
2. Ortholog group 1809を選択すると、fliGのortholog groupのリストや系統分布が表示される。fliGの系統分布は、Taxonomic Distribution of Orthologs Stanzaから視覚的に知ることができる。
![fliGtaxa](https://github.com/MicrobeDBjp/document/blob/master/Figures/fliGTaxa.jpeg)
