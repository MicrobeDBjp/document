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
