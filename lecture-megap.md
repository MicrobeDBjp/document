## DDBJ pipeline上でのMeGAP実行結果の取得まで ##
DDBJ Read Annotation Pipelineは、次世代シーケンサ配列のクラウド型データ解析プラットフォームで、国立遺伝学研究所スーパコンピュータ上で運用されています。詳細なヘプルページはこちら https://sites.google.com/a/g.nig.ac.jp/pipeline_help/home

MeGAPの実行は、DDBJ Read Annotation Pipelineの機能拡張として実装されており、ログイン後メタゲノム配列データ(.fastq)のアップロードおよびMeGAP実行が可能になります。
注意: バグフィックス中の場合、不具合が発生する場合があります。ショットガンの解析は現在使えません。

### DDBJ pipelineのユーザ登録 ###
#### 1. トップページ ( https://p.ddbj.nig.ac.jp/pipeline/Login.do ) にアクセスし、"New account"をクリックする ####
![ddbj_pipeline_new_account](https://github.com/MicrobeDBjp/document/blob/master/Figures/ddbj_pipeline_new_account.png)
#### 2. すべてのユーザ情報を入力し、"Registration"をクリックする ####
![ddbj_pipeline_registration.png](https://github.com/MicrobeDBjp/document/blob/master/Figures/ddbj_pipeline_registration.png)
登録メールアドレスに送られてくるメールによる確認操作により登録完了となります。
#### 3. Extensionトップページにアクセスする http://p.ddbj.nig.ac.jp/pipeline/ext/Login.do ####
#### 4. Extensionページから登録されたアカウントおよびメールにより送信されたパスワードを入力し、"ExtensionLogin"を実行する ####
![ddbj_pipeline_extension_top.png](https://github.com/MicrobeDBjp/document/blob/master/Figures/ddbj_pipeline_extension_top.png)

#### 5. メタゲノム解析配列データFASTQをアップロードし、MeGAPを実行する ####
データをアップロードするため、左メニューANALYSIS >  Upload Query をクリックし、画面中央の"Add new files"を選択する
![megap_1](https://github.com/MicrobeDBjp/document/blob/master/Figures/megap_1.png)
SSH、FTP、HTTP経由でデータをアップロード後、”Upload Query"で解析したいデータを選択し、Add to listをクリックする
![megap_2](https://github.com/MicrobeDBjp/document/blob/master/Figures/megap_2.png)
クエリファイルを選択して"Next"
![megap_3](https://github.com/MicrobeDBjp/document/blob/master/Figures/megap_3.png)
Run Optionを選択する　（注意: 現在、Shotgun Metagenome Sequencingは不具合解消中のため使えません）
![megap_4](https://github.com/MicrobeDBjp/document/blob/master/Figures/megap_4.png)
確認画面からRunを実行する
![megap_5](https://github.com/MicrobeDBjp/document/blob/master/Figures/megap_5.png)

![megap_6](https://github.com/MicrobeDBjp/document/blob/master/Figures/megap_6.png)

#### 6. MeGAPの結果を取得する ####
JOB STATUS > MeGAPで終了を待つ"Detail View"で結果を表示する
Download All の megap_result_all.tar.gz が結果です。このファイルをそのままMicrobeDB.jpにアップロード可能です。
![megap_result](https://github.com/MicrobeDBjp/document/blob/master/Figures/megap_result.png)
![megap_result_upload](https://github.com/MicrobeDBjp/document/blob/master/Figures/megap_result_upload.png)
