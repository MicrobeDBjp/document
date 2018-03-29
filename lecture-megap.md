## DDBJ pipeline上でのMeGAP実行結果の取得まで ##
DDBJ Read Annotation Pipelineは、次世代シーケンサ配列のクラウド型データ解析プラットフォームで、国立遺伝学研究所スーパコンピュータ上で運用されています。
MeGAPの実行は、DDBJ Read Annotation Pipelineの機能拡張として実装されており、ログイン後メタゲノム配列データ(.fastq)のアップロードおよびMeGAP実行が可能になります。

### DDBJ pipelineのユーザ登録 ###
#### 1. トップページ ( https://p.ddbj.nig.ac.jp/pipeline/Login.do ) にアクセスし、"New account"をクリックする ####
![ddbj_pipeline_new_account](https://github.com/MicrobeDBjp/document/blob/master/Figures/ddbj_pipeline_new_account.png)
#### 2. すべてのユーザ情報を入力し、"Registration"をクリックする ####
![ddbj_pipeline_registration.png](https://github.com/MicrobeDBjp/document/blob/master/Figures/ddbj_pipeline_registration.png)
登録メールアドレスに送られてくるメールによる確認操作により登録完了となります。
#### 3. Extensionトップページにアクセスする http://p.ddbj.nig.ac.jp/pipeline/ext/Login.do ####
#### 4. Extensionページから登録されたアカウントおよびメールにより送信されたパスワードを入力し、"ExtensionLogin"を実行する ####
![ddbj_pipeline_extension_top.png](https://github.com/MicrobeDBjp/document/blob/master/Figures/ddbj_pipeline_extension_top.png)

#### 5. メタゲノム解析をアップロードする ####
#### 6. 解析に用いるデータを選択し、MeGAPを実行する ####
#### 7. MeGAPの結果を取得する ####
