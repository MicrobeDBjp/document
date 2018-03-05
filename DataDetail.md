# Data detail
### MicrobeDB.jpで用いているデータ
+   `ゲノムデータ`:MBGD release 2015-01に含まれるNCBI RefSeq DB [O'Leary NA, et al. 2016]のゲノムデータ、およびRefSeqに含まれておらずかつhigh qualityなdraft genomeデータはINSDC Genome DB [Cochrane G, et al. 2016]

+   `オーソログデータ`:MBGD release 2015-01 [Uchiyama I, et al. 2015].

+   `Culture collection data`: 2012年版のNBRCの菌株データと、2016年版のJCMの菌株データ

+   `病気関連微生物データ`: NCBI BioProject DBとJGI GOLDのゲノム解読済み株のメタデータ、および元のゲノム論文から、病原菌関連のデータを抽出

+   `メタ16S・メタゲノムデータ`: 2014年8月にダウンロードした、INSDC DRA/ERA/SRA由来のメタ16S・メタゲノムデータについて、系統組成と遺伝子機能組成をサンプルごとにMeGAP2で再解析した結果

### 使用している代表的なオントロジー
+   `ゲノムデータ`:FALDO、SO、INSDCO

+   `オーソログデータ`:OrthO、MBGDO

+   `Culture collection data`:MCCV、NCBI Taxonomy、MEO

+   `病気関連微生物データ`:PDO、CSSO

+   `メタ16S・メタゲノムデータ`:MEO、MSV、NCBI Taxonomy

### Data models
MicrobeDB.jpのRDFデータのデータモデルについては、現在準備中のMicrobeDB.jp論文の中で詳しく述べております。
その論文以外ですと、FALDOを用いた微生物ゲノムのRDFについては、[Bolleman JT, et al. 2016]、MBGD-OやOrthO等のオントロジーを用いたオーソログRDFについては、[Chiba H, et al. 2015、Fernández-Breis JT, et al. 2016]に詳細が記述されております。
メタゲノムのメタデータのデータモデルについては、sra_metadata_schema、メタゲノムの系統組成のデータモデルについては、sra_analysis_tax_abundance_schema、メタゲノムの遺伝子機能組成のデータモデルについては、sra_analysis_env_function_schema、
PDOやCSSOを用いた病原菌のデータモデルについては、disease_schemaに詳細が描画されております。

### Backend infrastructure
OpenLink Virtuoso version 7.1をRDFストアとSPARQL検索に用いております。
TogoStanzaフレームワークを、個別アプリケーションにおけるHTML/CSS/JavaScriptの視覚化等に用いております。
Apache Solrを文字列データの検索の際に用いております。
Elasticsearchを比較解析のファセット検索に用いております。
