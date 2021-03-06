
## 自己紹介
初めまして、東京都立大学・システムデザイン研究科・情報科学域M1のLIU YIと申します。中国からの留学生として、日本に来てからはちょうど一年yon4ヶ月です。 趣味はバドミントンと旅行です。大学の専門はソフトウェア工学なので、主にJava、Pythonを使ったWEB、APP開発とソフトプロジェクト管理の知識について勉強してきました。 そして、今は知能情報処理研究室にHumanーRobot インタラクションに関する研究をしています。 研究の内容は＜VRにおける生体情報を用いた感情認識＞です。 VR環境に脳波と心拍を取得し、会話の音声も使う、被験者たちの感情と会話雰囲気を認識する研究です。 本日はどうぞよろしくお願いします。

## Why日本へ
私は大学二年生の時、日本に興味が持っているので、日本語を勉強し始めました。そして、一年半の学習で、日本語能力試験N１に合格しました。
日本語と英語の能力も備えたので、私は日本へ留学したいという気持ちを両親に伝えて、留学の申請、大学院試験の準備をして始めました。
来日一か月ご、私は大学院の冬試験に合格しました。その時、お父さんが”すでに日本に留学しているので、中国にとどまらず、世界を目指せ！”と私にこう言いました。
だから、私はグロバールな人材になりたく、世界を目指して、御社のような海外進出する企業で頑張りたいと思います。

## サイバーエージェントを志望する動機
（１）サイバーエージェントはインターネット広告事業、ゲーム事業に続き、「AbemaTV」を中心としたメディア事業を育てながら、「新しい力とインターネットで日本の閉塞感を打破するパーパスを揚げ、幅広い事業を行っています。そして、トップシェアを誇るサービスを有しながらも、新しい事業にずっと挑戦を続けています。私は学生時代に、色んなエリアに挑戦を挑むことで培われる経験や技術を貴社に活かしたいと考えています。  
（２）二つ目は、「海外進出」です。サイバーエージェントは、新型の日本企業になってグローバルカンパニーを目指し、日本の高品質サービスを全世界に届けたい、
一方、私もグローバルな人材になりたく、海外進出というミッションがあり、自分の視野や経験を活かしてサイバーエージェントと一緒に日本だけでなく、世界を変えると考えています。  
（３）最後、サイバーエージェントは人材育成に力を入れており、年功序列を排除しており、創業以来、継続的に成長している大きなグループ会社で、WEB業界を注目している私はきっとサイバーエージェントで成長できると思うので、応募させていただきます。  

## 自分の研究・問題点
システムの名前:　VRにおけるセンサフュージョンに基づくグループレベルの感情認識  
なぜ開発しようと思ったか:　生体情報でVRユーザーの本物の感情を把握できるバーチャルヒューマンを開発したい  
問題点: データが足りない、より多くのデータを収集し、サンプルの多様性を高める。 Muse2脳波計は接続不良の問題があるので、複数人数の実験にはMuse2を使わないにした。  
プロダクトを作る上でこだわった点や工夫した点:　 生体情報には個人差が出てくるので、まずPCA図でデータの分布を見て、異常値を排除する。 Undersampling とOversamplingを使って学習サンプルのバランスを保つ。 PCAを使って、データの特徴を削減して、标准化とone-hot encodingを使い、SVM・KNN・Naive Bayesなどの機械学習モデルを学習して分類してみた。  

## 最近気になっている技術について。メリットデメリット含む。
（１）
Virtual Realityと強化学習Reinforcement learningについて興味があります。  
自分の研究はVR環境における感情認識です。  
次の学期、VRにおけるユーザーの悲しみを感知できるバーチャルロボットを作ってみたいと考えています。
メリット：VRで疑似体験が面白い。  
デメリット：VRの購入費用が高い、現有のハードウェアとソフトウェアではとてもリアルなVR世界を体験することが難しいため、VRに興味のあるひとが少ない、VRを使った経験のある人が少ないです。

強化学習は機械学習の一種であり、コンピューター エージェントが動的環境と、繰り返し試行錯誤のやりとりを重ねることによってタスクを実行できるようになる手法です。  

犬のしつけで、「お座り」という命令で犬が座るようにしつけたい場合、実際にお座りができたら報酬として餌をあげるようにすると、何度も何度も繰り返しトレーニングするうちに「お座り」を学習するが、これと同じ原理である  

メリット：この学習手法により、エージェントは、タスクの報酬を最大化する一連の意思決定を行うことができます。人間が介入したり、タスクを達成するために明示的にプログラムしたりする必要はありません。そして、難しい場面や未知なる環境への適応が期待できること。  
デメリット：強化学習は行動の評価方法自体が学習できる反面、どのような評価方法を取るか、どのような行動を学習させるかは、実際の学習モデルに依存してしまいます。  
人間が理解できない、意図しないような行動を取る可能性が出てくることもある。性能を改善するために、どこまでどのように手を加えるのがベストなのかが分かりにくい  

（２）Spring Bootに興味があります。
JAVEEアプリケーションシステムでは、複雑なSetting、開発効率の低下、難易度の高い3つの統合、複雑な導入プロセスなどが開発者から非難されています。
Springのような軽量レベルのリソース統合フレームワークを使用しても、比較的多くのリソース統合を実現するには、大量の手動依存管理、複雑なXML構成が必要です。
Springプロジェクトの初期構築と開発プロセス。Spring Bootは、開発者がxml構成を大量に必要としないように、特定の注釈方式で構成されています。

## それを今後使う予定はあるかどうか
ある

## 努力したこと
大学時代、私はソフトウェア開発プロジェクトに取り組む5人のチームのリーダーとして、画像処理と自然言語処理（せいきひょうげん、regular expression）に基づく問題集の認識・切り出しできるAIプロジェクトを成功させました。 みんなの能力の最大限に生かすため、チームメンバーのモチベーションを高めることに力を入れました。 まず、チームメンバーはほとんど初対面だったので、賞罰ゲームなどアイスブレイクの活動を導入してみました。そして、技術力に自信のないメンバーもいったので、私は勉強会を開き、開発が上手なメンバーとそうではないメンバーをペアに組んで一緒にドキュメント作成、コードのテストなどを行いました。
そして、AIの精度を高めるため、私たちは画像処理の精度と自然言語処理・文章分類の精度について工夫しました。画像処理は、Hough Transformというアルゴリズムで問題用紙の範囲を認識し、そして文字を黒く、大きくさせ、文字認識の誤差を下がりました。そして、文章分類の精度を高めるため、学習用のsampleを多く収集して、丁寧にラベルつきをしました。
あの時は本当に懐かしい、みんなが同じ目標を向かって頑張っています。 
その結果、メンバーたちが仲良くなって、お互い勉強し合う雰囲気を作ることで全員のモチベーションが高くなりました。みんな協力して開発したプロジェクトはアウトソーシング開発大会に二等賞を受賞し、学校の奨学金をもらいました。

## エンジニアとして将来どのようなキャリアを歩んでいきたいか
（１）一つ目は、「「多岐にわたる分野で事業の創出」です。  
私は技術だけでなく、業務にも深く興味があるなので、サイバーエージェントで幅広い事業に経験を積んで、一緒にトップシェアを誇るサービスを作って、技術力と事業経験が深くなったら、新しい事業に挑戦できるという一人前のエンジニアになりたいです。  
（２）技術力について、フレームワーク、library、cloudだけでなく、システムのアーキテクチャと要件定義をする高い能力を身につけたいと思います。
（３）そして、  
将来的には、御社が目指している海外展開に向けた役割を担う人材になりたいです。御社の「世界に進出する」目標のため、グローバルな人材として成長したいと考えています。海外展開に向け、毎日欠かさず語学学習に取り組んでいます  

## teamwork
大学時代、私は5人のチームのリーダーとして、画像処理と自然言語処理に基づく問題集の認識・切り出しできるAIプロジェクトを成功させた。メンバーの能力を最大限に生かすため、賞罰ゲームなどアイスブレイクの活動を導入し、勉強会を開き、ベテラン開発者と初心者をペアに組ませて一緒にドキュメント作成、コードのテストなどを行った。結果、チームが一丸となって開発したプロジェクトはアウトソーシング開発大会に二等賞を受賞した。

## 実務経験にもとづいた話やなぜこの技術に興味があるのか。
【楽天トラベル　API開発インターンシップ 期間：2022年3月～2022年4月（1ヵ月） 使用技術：SpringBoot、Maven、Log4J 内容：私は2022年3月からの一ヶ月、楽天TravelでAPI開発エンジニアのインターンシップに参加した。主に楽天トラベルのダイヤモンド・プラチナ会員向けの隠し奨励(例えば無料朝食)のデータの取得とフォーマットの変換のコードを開発した。そしてPOSTMANを使ってAPIをテストし、Log4Jのロッグを見てコードをDEBUGした。その正社員と一緒に開発する経験を通して、API開発に関する必要な知識（GIT、Jenkins、Log4J、Spring bootなど）を身に付けた。】　　

【Raspberry PiとVisionKitを用いた研究室向けモニタリングシステム・東京都立大学久保田研究室共同研究 期間:　2021年6月~2021年9月（3ヵ月） 　 開発環境:　Python, Rasberry Pi 4B, Visionkit, Sokcet 内容:　Raspberry Pi、VisionKitと環境センサーの構築、ローカルサーバーの構築。BME280モジュールは温度、湿度、気圧のデータを取得し、HC-SR04モジュールは距離データを取得する。SSHを使ってVisionKitを制御し、人物を認識した後、写真と環境データをSlackプラットフォームに送信する。Socketを使って、データ収集と管理のサーバーとクライアントを開発した。 役割:　リーダーとして進捗管理、プログラマーとしてシステムの構築とコア機能の開発】

【MCTSに基づく横浜市旅行経路計画AI・GISシステム開発 期間:2021年3月~2021年6月（3ヵ月） 開発環境:Python, beautiful Soup, Django, folium, Monte Carlo tree search algorithm 内容:beautiful Soupで観光スポットのデータをGoogle APIで収集した。横浜市一日の旅行計画AIをMCTSアルゴリズムで実装した。DjangoでGISウェブサイトを開発した。 ユーザーが入力した好みに合わせて、旅行計画結果を提示する。】

SSMにView层，Controller层，Service层，DAO层があり
Spring IOC特性あり、OBJECTの間の依存関係の完了をSpringにまかせて、OBJECTの間の影響が少なくなる。
AOPの特性で、事務、LOG、permissionなどの管理がやすくなる。
【SSMに基づく杭州市降水量可視化GISサイト開発 期間：2019年6月~2019年7月（1ヵ月） 使用技術：Spring、SpringMVC、MyBatis、Maven、Baidu Map、Echarts、MYSQL 内容：私は2019年6月からの１ヶ月、大学研究室でJava開発の課題に参加した。JAVAでSSMインフラに基づく降水量、洪水可視化GISサイトのバックエンドの部分を開発した。8GのデータをMySqlで保存し、データの取得、更新などの機能を実現した。そして、ARIMAアルゴリズムで降水量予測の機能を実装した。】

【SSMに基づくオンラインテストサイト開発 期間:2019年5月~2018年6月（1ヵ月） 開発環境:Spring、SpringMVC、MyBatis、Oracle 説明:私は2019年5月からの1ヵ月、大学研修でJava開発の課題に参加した。JAVAでSSMインフラに基づくオンラインテストサイトサイトを開発した。問題と答案をアップロード・削除・ステータス変更、自動採点の機能を開発した。】

【SSHに基づくオンラインストレージサイト開発 期間:2018年12月~2018年4月（4ヵ月） 開発環境:Hibernate、Struts、Spring、Baidu Cloud、MYSQL 説明:私は2018年12月からの4ヶ月、大学研修でJava開発の課題に参加した。JAVAでSSHインフラに基づくオンラインストレージサイトを開発した。Jsp/servletでファイルをアップロード・ダウンロード・削除・ステータス変更の機能を開発した。管理員サイト（ユーザーとファイル管理）を開発した。】

## Raspberry PiとVisionKit
大学院の研究室でアルバイトする経験だ。私は2021年六月から三ヶ月間、東京都立大学・久保田研究室の研究を支援するため、Raspberry PiとVisionKitを用いた研究室向けモニタリングシステムの導入と開発の仕事を務めた。当初はグループの3人ともIoT開発の経験がなかったのですが、自分が大学時代にリーダーとしての経験があると考えたので、チームリーダーを志願した。まず、教授と報連相しながら、プロジェクトの学習・開発計画を作成し、メンバーと一緒にプロジェクトの目的や内容を明確にしていた。そして、デバイスの取扱説明書の指示に従ってRaspberry Pi、VisionKitと環境センサーを構築し、インターネットやプラットフォームなどの開発環境を速やかに設定した。正式な開発セッションで、チームリーダーである私は常に教授と要件を確認し、メンバーとともにIoT開発とサーバー開発について学び続け、socketを使ったサーバー開発とSlackに即時送信機能などの開発も担っていた。三ヶ月後、開発プロジェクトは無事に終了し、チームリーダーである私は、教授から「仕事が早い」「責任感が強い」と言われた。

## 日本で就職理由
最初は日本のアニメや文化が好きで、日本語を勉強して日本に留学してきましたが、来日して一年間が経ち、目的も変わりました。日本で就職したいのは、グローバルな時代で活躍できる人間になりたいという思いからです。また、せっかく日本語を勉強したので、日本に残って自分の語学力を最大限に生かしたいと思っています。

## 高并发
高性能なサーバ、高性能なデータベースデザイン、効率的なプログラミング言語（GO）、高性能なWebコンテナを使用  
HTML静态化 スタティック化、画像とサーバーを分けて（OSSを使う）、複数のサーバとデータベース、キャッシュを使う（Redis）、ロードバランス、
ソフトウェアの効率化、マルチスレッド、処理の分散化、メッセージ待ち行列化（メッセージキューQueue），


## 逆質問
どれくらいの期間を経て、どのようなステップで実務に入るのでしょうか？ 　　
Cyber　agentではどのような方が活躍していますか？
Cyber　agentで外国人社員の割合はどうですか？外国人の働きやすさ？外国人はどう活躍できるんですか
コロナがCyber　agentにどのくらい影響しているのでしょうか。
本日の面接のフィードバックをお願いします
