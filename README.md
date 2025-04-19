## WhatToDo

**1. プロジェクトの概要**  
- **アプリ名**
  - WhaToDo   
- **概要**
  - このアプリは、1日何して過ごすのか。オススメのプランを提案してくれるアプリになります。現在位置を元に周辺の観光スポットや飲食店、アウトドアスポット、インドアスポットなどを含めたプランを提案します。
- **主な機能**  
  - プラン情報の提供：ユーザーの現在位置を元に、周辺の環境で過ごせるプランを提案します。

**2. インストール方法**  
  - 本アプリの管理者へ、インストールの申請をメールで行ってください。お問い合わせ先は 5.サポート情報 をご覧ください。（メール例：WhaToDoアプリの招待メールを送ってほしい）  

**3. 利用方法**  
 1. アプリを起動すると位置情報の取得許可ダイアログが表示されます。許可を押下してください。※許可しないとアプリは利用できません。  
</br><div align="center"><img alt="位置情報ダイアログ" src="https://github.com/rt-1278/WhaToDo-Public/blob/main/位置情報取得ダイアログ.png" width="30%"></div>
 
 2. 位置情報の取得を許可すると、プラン情報の取得開始され、画面がロード中になります。
</br><div align="center"><img alt="ロード中" src="https://github.com/rt-1278/WhaToDo-Public/blob/main/初期画面ロード中.png" width="30%"></div>

 3. ロードが完了し、チュートリアルモーダルが表示されます。次へボタンを押下し、次に進みます。
</br><div align="center"><img alt="チュートリアル１" src="https://github.com/rt-1278/WhaToDo-Public/blob/main/チュートリアル１.png" width="30%"></div>
</br><div align="center"><img alt="チュートリアル１下" src="https://github.com/rt-1278/WhaToDo-Public/blob/main/チュートリアル１下.png" width="30%"></div>
</br><div align="center"><img alt="チュートリアル２" src="https://github.com/rt-1278/WhaToDo-Public/blob/main/チュートリアル２.png" width="30%"></div>
</br><div align="center"><img alt="チュートリアル２下" src="https://github.com/rt-1278/WhaToDo-Public/blob/main/チュートリアル２下.png" width="30%"></div>
</br><div align="center"><img alt="チュートリアル３" src="https://github.com/rt-1278/WhaToDo-Public/blob/main/チュートリアル３.png" width="30%"></div>
</br><div align="center"><img alt="チュートリアル３下" src="https://github.com/rt-1278/WhaToDo-Public/blob/main/チュートリアル３下.png" width="30%"></div>
</br><div align="center"><img alt="チュートリアル４" src="https://github.com/rt-1278/WhaToDo-Public/blob/main/チュートリアル４.png" width="30%"></div>
</br><div align="center"><img alt="チュートリアル４下" src="https://github.com/rt-1278/WhaToDo-Public/blob/main/チュートリアル４下.png" width="30%"></div>
 
 4. チュートリアルモーダルを全て進むと、プランの写真とタイトルが表示されます。
</br><div align="center"><img alt="プラン１" src="https://github.com/rt-1278/WhaToDo-Public/blob/main/プラン１.png" width="30%"></div>  

 5. 横にスワイプすることで他のプランの写真とタイトルが表示されます。
</br><div align="center"><img alt="プラン２" src="https://github.com/rt-1278/WhaToDo-Public/blob/main/プラン２.png" width="30%"></div>

 6. 画面をタップすると、そのプランの詳細が表示されます。プラン詳細は時系列順に３つ表示されます
</br><div align="center"><img alt="プラン詳細１" src="https://github.com/rt-1278/WhaToDo-Public/blob/main/プラン詳細１.png" width="30%"></div>
</br><div align="center"><img alt="プラン詳細２" src="https://github.com/rt-1278/WhaToDo-Public/blob/main/プラン詳細２.png" width="30%"></div>  

 7. プラン詳細の内容をタップすると、詳細をキーワード検索した画面を表示します。
</br><div align="center"><img alt="プラン詳細タップ" src="https://github.com/rt-1278/WhaToDo-Public/blob/main/プラン詳細３タップ.png" width="30%"></div>  

**4. 利用上の注意点**  
- 利用**不可能な**デバイス   
  - タブレット  
  - テレビ  
  - ウェアラベル  
  - 車  
  - ChromeBook  
- **利用可能なAndroid バージョン**  
  - 13.0 ~ 15.0  
- **通信状態と位置情報について**
  - 通信状態がオフラインの状態または現在位置が取得できない場合、アプリの利用ができません。  
- **アプリ内のプランデータについて**  
  - 毎日0時に全データを削除しています。必要なデータはあらかじめスクリーンショットを撮るなどして保存してください。

**5. サポート情報**  
- お問い合わせメールアドレスは[こちら](<mailto:mailto:r.tianzhong1278@gmail.com>)（担当者：田中 ）


**6. Androidアプリ 技術スタック & 特徴まとめ**

  6.1 🔧 技術スタック一覧

  - **プログラミング言語**: Kotlin
  - **アーキテクチャ**: MVVM (Model-View-ViewModel)
  - **非同期処理**: Kotlin Coroutines
  - **通信**: Retrofit2, OkHttp3
  - **テスト**: JUnit（ローカルテスト）, Espresso（インストルメンテーションテスト）
  - **使用ライブラリ**: AndroidX Jetpack（Activity, ViewModel, LiveDataなど）
  - **UIフレームワーク**: XMLレイアウト
  - **認証・セキュリティ**: ProGuard, HTTPS通信
  - **DI（依存性注入）**: 未導入
  - **モニタリング・クラッシュ解析**: Firebase Crashlytics
  - **CI / CD**: GitHub Actions
  - **バージョン管理**: Git + GitHub

  6.2 ✨ アプリの特徴と今後の展望

  - 現在は **APIサーバーとの通信** によりデータを取得・表示
  - ローカルデータの保存には **SharedPreferences** を使用（ユーザーIDなど）
  - データベース（Room）は現在未使用だが、**今後オフライン対応のため導入予定**
  - アプリ利用するには、位置情報の取得とネットワーク環境が必須
  
  #### 今後導入予定の技術・改善案

  - **Jetpack Compose** による宣言的UIの実装
  - **Repositoryパターン** によるデータ取得の抽象化
  - **WorkManager** によるバックグラウンド非同期処理の管理
  - **Android Keystore** による認証情報の安全な保存
  - **証明書ピンニング** によるセキュリティ強化
  - **Room** によるローカルDBの導入（オフライン対応）
  - **Realm** によるNoSQLベースのデータ保存
  - アーキテクチャは以下の **3レイヤー構成**：
    - UIレイヤー
    - ドメインレイヤー（UseCase）
    - データレイヤー（Repository）
  - **ViewModelの肥大化を防ぐ** ため、ビジネスロジックは UseCase に記述
   
