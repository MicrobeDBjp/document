### ファセット検索 ###

例: ヒト腸内メタ16S・メタゲノムサンプルを比較解析したい  
1. https://beta.microbedb.jp/
のAnalysis -> Metagenomic samplesを選択。
![facetTop](https://github.com/MicrobeDBjp/document/blob/master/Figures/facetTop.jpg)
  
2. 比較解析対象のメタ16S・メタゲノムサンプルの絞り込み検索ページで、以下の3つの操作を行い、ヒト腸内メタ16S・メタゲノムサンプルのみに絞り込む。
+   hasMetagenomeAnalysisでtaxonomyを選択し、系統組成が計算済みのサンプルのみにする
+   hasMEO (Text)にgutと入力し、サンプリングされた環境を腸内とする
+   hasHostTaxonomy (Text)にhumanと入力し、宿主の生物をヒトに限定する
![facetSamplechoose](https://github.com/MicrobeDBjp/document/blob/master/Figures/facetSamplechoose.jpg)

3. メタデータ等を元に、比較解析したいメタ16S・メタゲノムサンプルのみAddボタンを押して選択する。
![facetSamplechoose2](https://github.com/MicrobeDBjp/document/blob/master/Figures/facetSamplechoose2.jpg)

4. 車輪マークを選択し、比較解析したい系統階層をGenus-Domainの中から選択して、compareを押す。
![facetComparison](https://github.com/MicrobeDBjp/document/blob/master/Figures/facetComparison.jpg)
各サンプルの系統組成のグラフや、系統組成を元に主座標分析(PCoA)や階層的クラスタリングをした結果、メタゲノムサンプルの場合はKEGG PathwayやKEGG Orthology組成のグラフ等が表示される。
