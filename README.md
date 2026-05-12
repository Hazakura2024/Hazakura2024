# こんにちは、西尾優太朗です！ 👋

## 📝 About Me
- 九州大学工学部電気情報工学科3年生の学生エンジニアです。
- 国語、数学、物理が大好きです！
- Web開発（フロント、バックエンド両方）をメインに学習してきました。
- 制御×エンタメ・グラフィックorAI駆動制御分野に興味が出てきており、学習中
- 現在興味ある分野が多く、様々な分野に手を出して試行錯誤中。
### 特に興味のある分野
- 制御工学：人型3DCGモデルへの応用やフィジカルAIに関心があり、最近unityで実践中。研究室での専攻も検討中
- Web開発：長期インターンにて学習中、アクセス性の高さに魅力を感じた。
- andoirdアプリ開発：高校の時にやっていて離れていたが、最近思い出し作業中
- グラフィック：Unityのような高レイヤーから数学的なアルゴリズムの双方に興味。

- 自然言語処理：人間の思考である言語を数学的に処理する技術に感動。
- 低レイヤー：中学生の時にC言語からプログラミング始めたころもあり、ハードとのつながりに興味。

## 🛠 スキルセット
- **Languages:** JavaScript, TypeScript, C, Java(Kotlin), C#(学習中), Python(文法基礎), Rust(学習中)
- **Tools:** Docker, Git
- **Frontend**: React
- **Backend**: NestJS (Node.js), TypeORM, Prisma, Firebase, JWT, Cookie
- **Game Engine / Simulation**: Unity
- **Machine Learning**: Pytorch

## 🚀 主要プロジェクト

### [micro-post(掲示板アプリ)]
- **概要:** React×NestJSで掲示板ををフロントからバックエンド、DBまで自分で作成、Render.comでデプロイ
- **技術:** TypeScrtpt, React, NestJS(express), TypeORM, JWT, cookie, TanStackQuery, Zustand, React-hook-From&Zod
- **工夫した点:**
  - Reactにおける現場でのベストプラクティスを目指しリファクタリングを繰り返し中
      - TanStackQuery, Zustand, React-hook-From&Zodなどの導入
      - 情報源をDBに限定
  - ユーザー登録機能をもち、DBにユーザー情報、ポスト情報、認証情報を保存
  - cookieに認証情報を保存、access_tokenとrefresh_tokenでリロード時のログイン維持
  - Web開発の学習ノートのような役割を含める
- [リポジトリへのリンク](https://github.com/Hazakura2024/micro-post)


### [VRMモデル&制御工学で自然なまばたき with Unity]
- **概要:** VRMモデルの「まばたき」を、単なるアニメーション再生ではなく、 制御工学の物理シミュレーションとして、Unityプロジェクトで作成しました。 また、パラメータの数値を変更すると「眠そうな目」「驚いた目」にもできます。また3Dアクションゲームのようにモデルの移動もできます。
- **技術:** Unity(C#)
- **工夫した点:**
  - まぶたの挙動を「インパルス入力＋質量・ばね・ダンパ系(2次遅れ)」として捉え、運動方程式をリアルタイムに解く
  - まばたきのクールタイムもポアソン分布で自然な間隔を計算
- [リポジトリへのリンク](https://github.com/Hazakura2024/unity-VRM-control-engineering-blink)


### [九州大学すれちがいアプリ]
**チーム開発（九州大学プログラミングGleapのうち1班として活動）（メンバー数：8名）**

- **概要:** DSのすれ違い通信(QRコードで代用)を目的としたアプリの開発。ほぼ全員が初心者の中でチーム開発を学ぶ。
- **使用技術:** React
- **自分(他メンバー1人と兼任)の担当範囲:**
    - フロントエンドの「ユーザー一覧画面」の実装
    - フロントエンドの「QRコード作成・読み取り機能」の実装

- **工夫した点・貢献:**
    - チーム内のほぼ全員がＷeb開発未経験のなかReact,Githubを学習、学習をお互いに補助
    - プログラミング未経験者の補助
    - バックエンドをQRコードによる情報の受け渡しのみで作成するため、アイコン画像の送信形式を工夫


### [Fashion-MNISTデータセットのDataAugumentation]
- **概要:** 2年秋学期、研究室室体験授業での実験用コード
- **技術:** Python(Colab), PyTorch, NumPy
- **工夫した点:**
  - 実際のデータの特性によって向き不向きの操作があり、理由を考察（例：左右の向きが定められている靴などに左右反転処理は不適)
- [リポジトリへのリンク](https://github.com/Hazakura2024/university-pytorch-DataAugmentation-fashionMNIST)





## 📝 学習ロードマップと記録
### Web開発
  - [x] 掲示板アプリの作成
  - [micro-post](https://github.com/Hazakura2024/micro-post) 
  - [x] Reactを用いたTodoアプリの作成
  - [x] tailwindCSSの学習
  - [x] Firebaseを用いたNetflixCloneの作成
  - [study-netflix-clone-yt](https://github.com/Hazakura2024/netflix-clone-yt)
  - [x] NextJS基礎の学習
  - [x] NestJS基礎の学習
  - [x] React×NestJSで掲示板アプリの作成
  - [ ] React×NestJSで落語SNSの作成
  - [ ] DjangoでのREST API構築
### androidアプリ
  - [ ] 高校の頃に作っていたアプリの復習
  - [ ] 時間割管理アプリの作成
### Unity
  - [ ] vrスマホアプリの作成  
  - [ ] 2Dアクションゲームの作成
  - [x] 制御工学を用いてVRMもでるに自然なまばたきをつけるプロジェクトの作成
  - [unity-VRM-control-engineering-blink](https://github.com/Hazakura2024/unity-VRM-control-engineering-blink)
  - [ ] フリーのVRM3Dモデルを使用しモーションを実装したゲームの作成
### デスクトップアプリ
  - [x] Tkinterを用いたデスクトップアプリ作成の学習
  - [study-python-tkinter-desktop-app](https://github.com/Hazakura2024/study-python-tkinter-desktop-app)
### 組み込み
  - [ ] ESP32でwifi通信で画面に何か情報（検討中）を表示させる



## 📬 連絡先
- **Email:** nishio.yutaro.carreer@gmail.com
