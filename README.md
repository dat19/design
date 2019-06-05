# ゲームデザイン実習
2019年度 デジタルアーツ東京 ゲームデザイン実習用リポジトリー。

# 講義予定
- [シラバス](syllabus.md)

# 学生作品、ブログ一覧
- https://tanakaedu.github.io/dat-works/index.html

# 7回目(6/5)
## 話題
- [日本ゲーム大賞U18部門 予選大会 6/9](https://u18.awards.cesa.or.jp/)

## 前回の課題結果(出席者17名)
- GitHubで提出 14名
- パーフェクト 7名
- 1カ所不足 4名
- 2カ所不足 1名

## 著作権概論
- https://docs.google.com/document/d/15zRG0hcf9OU3TFoJ5vZL43AGPKCqewpD7KS_QYwntaA/

## 演習： 素材を探しと規約の確認、出典URL
アプリに組み込みが可能なフリー素材をインターネットで探して、GoogleシートにURLをまとめてましょう。

- 背景や地面用のアセット
- プレイヤーキャラクター
- 敵用のキャラクター
- アイテム用のキャラクター
- タイトル用フォント
- 説明用フォント
- BGM
- 効果音

## 一枚絵を3Dに読み込む手順
- 素材のjpgやpngファイルを、Projectウィンドウにドラッグ&ドロップ
- HierarchyウィンドウのCreateボタンをクリックして、3D Object > Quadを選択して、四角を作成
- ProjectウィンドウのCreateボタンをクリックして、Materialを作成して、BGなどの画像の名前にする
- InspectorウィンドウのAlbedoの左の四角の枠に、画像ファイルをドラッグ&ドロップ
- Projectウィンドウの今回の例ならBGマテリアルをドラッグして、HierarchyウィンドウのQuadにドロップ
- あとは、QuadのTransformのScaleを調整して、好みのサイズにする

### ちょっと画像が白いのを直す
シェーダーをライトの影響を受けないやつに変更。

- Projectウィンドウからマテリアルをクリックして選択
- shader欄をクリックして、Unlit > Textureに変更

以上で、ライトの影響を受けずに、テクスチャーの色がそのまま反映される。


## 参考URL
- https://opengameart.org/
- http://pixelgameart.org/web/
- http://kenney.nl
- [Sketchfab. 3D作品をWeb上で公開](https://sketchfab.com/)
- [Turbo Squide. 3Dモデル配布・販売サイト](https://www.turbosquid.com)
- [Hightend3D. 3Dモデル配布・販売サイト](https://www.highend3d.com)
- [テクスチャー関連を公開している](https://www.textures.com)
- [cc0textures.com. CC0のPBRテクスチャー素材集]https://cc0textures.com/home
- [3dtextures.me CC0のPBRテクスチャー素材集](https://3dtextures.me/)
- [cgbookcase.com CC0のテクスチャー](https://www.cgbookcase.com/)


## 提出手順
- https://drive.google.com を開いて、Googleアカウントでサインイン
- *新規*をクリックして、*Google スプレッドシート*をクリック
- ドキュメント名を`ensyu0605`にする
- 右上の*共有*をクリック
- 右上の*共有可能なリンクを取得*をクリック
- しばらく待つと、*リンクをコピー*ボタンが表示されるので、クリックしてコピー
- [こちら](https://docs.google.com/spreadsheets/d/1Ky6bU27vJy_jl4-Yu3UiaHj-ZuHUPcQHXOVgjsRn-Mc/)の自分の行に[Ctrl]+[V]キーで貼り付け

以上準備が整ったら、各素材を探そう。

- アセットストア
- ユニティちゃんサイト
- フォント
- その他、CC0やフリー素材サイト

## 時間があまったら
- 取得したアセットをUnityに組み込んで表示してみよう

# 6回目(5/29)
## 前回の課題結果(出席者17名)
- GitHubで提出 15名
- TextMeshProを問題なく実装 6名

## 写真のデザイン
- [スライド](https://am1.jp/dat/design/design6-photo.pdf)
  - [図](https://am1.jp/dat/design/design6-photo-fig.pdf)
- Unityを使った写真的エフェクト-Post Processing Stackの利用

## 作業手順
- https://docs.google.com/document/d/1MmqHpj0_ja1RLz2D5knnFMBqSDyn0INLEEM1omUhW7A/

## 演習準備
### Unityのプロジェクト作成とGitHubへの登録
- プロジェクト名を`ensyu0529`、**3D**でUnityプロジェクトを作成
- [Ctrl]+[S]キーを押して保存ダイアログが開いたら以下を行う
  - 新しいフォルダーを作って、`Scenes`という名前にする
  - 作成した`Scenes`フォルダーをダブルクリックして開く
  - ファイル名を`pps`にして保存する
- *File*メニューから*Save Project*を選択して、プロジェクトを保存
- [UnityプロジェクトをGitHubに登録する手順](https://github.com/dat19/gp1/blob/master/github-unity.md)に従って、作成したプロジェクトをGitHubに登録
- [こちら](https://docs.google.com/spreadsheets/d/1Ky6bU27vJy_jl4-Yu3UiaHj-ZuHUPcQHXOVgjsRn-Mc/)に共有用URLを報告

## 演習
- コーネルボックスを作る
  - [monobook.org. コーネルボックスとは](https://monobook.org/wiki/%E3%82%B3%E3%83%BC%E3%83%8D%E3%83%AB%E3%83%9C%E3%83%83%E3%82%AF%E3%82%B9)
  - [@thiroaki. コーネルボックスをつくってあそぼ](https://qiita.com/thiroaki/items/7a9213150b15810137f2)
- SphereやPlane、ボックスなどを配置して着色
- 様々なライトを試す
- カメラの画角(Field of view = 視野角)
- ポストプロセスによる被写界深度(ボケ)の表現、HDR(High Dynamic Range)による輝き
  - [PostProcessingStack v2リポジトリー](https://github.com/Unity-Technologies/PostProcessing/releases)
  - [設定手順](http://am1tanaka.hatenablog.com/entry/2018/05/19/172121)
- できたらこちらの[手順](https://github.com/dat19/gp1/blob/master/github-unity.md#%E5%A4%89%E6%9B%B4%E3%81%97%E3%81%9F%E3%82%82%E3%81%AE%E3%82%92%E5%8F%8D%E6%98%A0%E3%81%95%E3%81%9B%E3%82%8B%E6%89%8B%E9%A0%86)を参考に、作成したプロジェクトをGitHubにプッシュする

## 時間があれば...
- TextMesh Proのおさらい
- ゲームっぽい画面を作ってみる

## ライティングについて参考
- [Unity公式. ライティングの手法](https://docs.unity3d.com/ja/current/Manual/BestPracticeMakingBelievableVisuals3.html)
- [テラシュールブログ. Lightmap](http://tsubakit1.hateblo.jp/archive/category/Lightmap)
- [テラシュールブログ. 画面効果](http://tsubakit1.hateblo.jp/archive/category/%E7%94%BB%E9%9D%A2%E5%8A%B9%E6%9E%9C)

# 5回目(5/22)
## 話題
- [Anna Mészáros. デザイナーではない人がデザインする上で大切な4つの基本原則](https://gigazine.net/news/20190518-fundamental-design-principles/)

## 前回の課題結果(出席者16名)
- GitHubで提出 14名
- 画面作成 12名
- ボタン実装 11名

## 文字のデザイン
- [スライド](https://am1.jp/dat/design/design5-font.pdf)

## フリーフォントの探し方とUnityでの活用方法
- [coliss. 2019年用、日本語のフリーフォント377種類のまとめ -商用サイトだけでなく紙や同人誌などの利用も明記](https://coliss.com/articles/freebies/japanese-free-fonts-for-2019.html)
  - タイトル用と本文用の2つのフォントを見つけて、リンクをメモ帳などにとっておく
- [提出用URL](https://docs.google.com/spreadsheets/d/1Ky6bU27vJy_jl4-Yu3UiaHj-ZuHUPcQHXOVgjsRn-Mc/)
- [@thorikawa. UnityのText Mesh Proアセットで日本語を使うときの手順](https://qiita.com/thorikawa/items/03b65b75fa9461b53efd)
- [手順](https://docs.google.com/document/d/1V8witriNqNILYd5tdnEE9pnvZokuHfTY3oJEBDtgAo0/)

## 参考
- [PHOTOSHOPVIP. 現役デザイナーが教える！完璧な書体を決める10個の黄金ルールまとめ](http://photoshopvip.net/105840?utm_content=bufferf79a8&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer)
- [個人開発のUI設計術](https://crieit.net/posts/UI)

## 演習：タイトル画面やゲーム画面の作成


# 4回目(5/15)
## 色のデザイン
- [スライド](https://am1.jp/dat/design/design4-color.pdf)
  - [図](https://am1.jp/dat/design/design4-color-fig.pdf)

## 演習準備
### Unityのプロジェクト作成とGitHubへの登録
- プロジェクト名を`ensyu0515`、**2D**でUnityプロジェクトを作成
- [Ctrl]+[S]キーを押して、新しいフォルダーを作って、`Scenes`という名前にして、そのフォルダーをダブルクリックして開く
- ファイル名を`color`にして保存する
- *File*メニューから*Save Project*を選択して、プロジェクトを保存
- [UnityプロジェクトをGitHubに登録する手順](https://github.com/dat19/gp1/blob/master/github-unity.md)に従って、作成したプロジェクトをGitHubに登録
- [こちら](https://docs.google.com/spreadsheets/d/1Ky6bU27vJy_jl4-Yu3UiaHj-ZuHUPcQHXOVgjsRn-Mc/)に共有用URLを報告

### 背景色の設定
- *Main Camera*をクリックして選択
- *Background*の右の四角をクリック
- 黒にする
- xをクリックして、カラーウィンドウを閉じる

### 色見本の作成
- *Hierarchy*ウィンドウの*Create*から、*3D Object* > *Quad*を選択
- *Project*ウィンドウの*Create*をから、*Material*を作成して、Enterキーを押す
- 作成した*New Material*をドラッグして、*Quad*にドロップ
- *New Material*をクリックして選択したら、*Shader*のコンボボックスをクリックして、*Unlit* > *Color*を選択
- *Inspector*ウィンドウの*Transform*欄の*Scale*の*X*と*Y*を`5`ぐらいにして少し大きくする

以上で、色を直接設定できる正方形が作れる。

ここまでできたら、一度保存をして、GitHubにコミット、プッシュしておく([手順](https://github.com/dat19/gp1/blob/master/github-unity.md#%E5%A4%89%E6%9B%B4%E3%81%97%E3%81%9F%E3%82%82%E3%81%AE%E3%82%92%E5%8F%8D%E6%98%A0%E3%81%95%E3%81%9B%E3%82%8B%E6%89%8B%E9%A0%86))。

## 演習1
- SpriteとMaterialを作成して、作成したマテリアルをSpriteにアタッチしておく
- RGBで色を作る
- HSVで色を作る(60ごと6分割)
- QuadとMaterialを複数作成して、それぞれ色を設定
- Main Cameraの背景色とQuadの組み合わせを色々と試してみよう

## UnityのUI(uGUI)
- [作業手順](https://docs.google.com/document/d/1oUDdWBGk2XUjAyt7RLHL2a1shBwrZp-ghrOb4wzGddk/)
- Canvas
- ボタンの設置
- 文字の表示


# 3回目(5/8)

## 形のデザイン
- [スライド](https://am1.jp/dat/design/design3-shape.pdf)
- 形だけで面白いものは作れる

## 参考作品
- [VOODOO](https://play.google.com/store/apps/developer?id=VOODOO)
  - https://play.google.com/store/apps/details?id=com.neonplay.casualrollersplat2
  - https://play.google.com/store/apps/details?id=com.h8games.helixjump
  - https://play.google.com/store/apps/details?id=io.voodoo.paper2
  - https://play.google.com/store/apps/details?id=com.bigframes.color_road
- その他
  - https://play.google.com/store/apps/details?id=com.crazylabs.tricky.traps.game
  - https://play.google.com/store/apps/details?id=com.azurgames.stackball
  - https://play.google.com/store/apps/details?id=com.gamestart.fill
  - https://play.google.com/store/apps/details?id=com.colorup.game

## 演習：基本図形を使ってカジュアルゲームの画面イメージを作ってみよう
- [演習手順](https://docs.google.com/document/d/1xV3s3uG9jT0wCEfQEid83Pc5nBC7pLg8HZg0V8UyJI4/)

### 利用するツール
- Photoshop
- Unity

### 抽象化：円や四角、三角形といった図形を組み合わせてキャラクターを作ってみよう
- 抽象化するキャラクターを選ぶ(ピカチュウでもアイアンマンでもなんでもよい)
- 図形ツールを使って、そのキャラクターを徹底的に抽象化した形を描く(図形、色設定など自由に使ってよい)
- ポイント：元のキャラクターを連想できる限界まで形を抽象化する
- Photoshopの画像を画面に見立てて、丁度よいサイズにキャラクターの大きさを設定する

### 敵や障害物、地面などを作る
- 上記のキャラクターが映えるようなその他の素材を描く
- これも基本図形で構成してみよう

### キーワード
- 抽象化
- 記号
  - アイコン
    - 対象の形を抽象化した記号
  - インデックス
    - 対象を連想させる記号
  - シンボル
    - ！や？など、共通認識がある記号
- モノグラム
- 点、線、面
- 幾何学形態の利用
  - 図形間の距離、大きさ
  - 図形の形状、配置
  - 黄金比、白銀比
- 図と地、ゲシュタルト心理学、プレグナンツの法則
- 錯視

### 提出
- 完成したら、GitHub Desktopでコミットして、Publishすれば提出完了


# 2回目(4/24)
## 講義メモ
- [講義メモ](https://docs.google.com/document/d/1kAfX8-_TyGLNSCaSC4t5R4VafvQYte-Zx-p-pQlB-Tg/)

## 予定
- 前回の企画の発表と講評
- 講義：アイディアの出し方

## 演習A：フリーライティングをやってみよう
- Googleドキュメントを開く
- 新規でスプレッドシートを作成して、名前を`D02ブレスト：氏名`にする(例： `D02ブレスト：田中`)
- 制限時間内に思いついた単語をA列に書きつらねていく
- 指示に従って、B列に乱数を設定
- データから並び替えて、キーワードを決める

## 演習B：企画の作成とブラッシュアップ
- フリーライティングで決めたキーワードを取り入れた企画を考えてみよう
- 前回の企画をブラッシュアップしてみよう

### 手順
- Googleドライブを開いて、新しいGoogleドキュメントを作成
- [これを右クリック](https://docs.google.com/document/d/1JHDSo8WGOY3wxsX48EMjpM0b83QgABhPMkm79Z3v02c/)して、新しいタブで開く
- 開いたドキュメントを[Ctrl]+[A]キーで全部選択して、[Ctrl]+[C]キーでコピー
- 自分で作成したGoogleドキュメントに[Ctrl]+[V]キーで貼り付ける
- タイトルを`D02企画：名前`にする(例： `D02企画：田中`)
- サムネイルは、スマホで撮影したものをメールなどでPCに送るとよい(CamScannerがオススメ)

## 企画例
- https://docs.google.com/document/d/1b9UN7ZmZAJclmxq2OqIbZdHcjwUAEWymhrPZdBqvb4I/

## 時間があれば
- Photoshopで画面作り
- ランダム順で演習結果を発表


# 1回目(4/17)
## 講義メモ
- https://docs.google.com/document/d/1RgzMbtTLhVs-uPG5cSztC5-UFjKLRssgYLCLe1MtvJY/

## 内容
- [ガイダンス](https://docs.google.com/presentation/d/1zaVqeDVWHGBkl5IKj1-pAHpyRRDj8gL7F2r5p9ANK7o/)
  - 参考ブログ： [みたかシロフード. 第1回LookingGlassハッカソン参加・優勝](https://sirohood.exp.jp/20190408-2274/)
  - [制作において心がけて欲しいこと](01-note.md)
- 環境の構築
  - Gmailアドレスの取得。**学校の活動専用**のアカウントを作成する
    - Gmailは、携帯番号の設定が必要です。２段階認証で必要なだけで、営業電話がかかってきたり、番号が他に漏れることはありません
    - Gmail / GitHub
  - Windowsの基本操作
  - 作業用フォルダーの作成
- ゲームデザイン概論(1)
  - ゲームの定義 [Capm Network. ゲーム理論](http://capm-network.com/?tag=%E3%82%B2%E3%83%BC%E3%83%A0%E7%90%86%E8%AB%96)
  - [ゲームの定義や要素からミニゲームを考える](https://docs.google.com/presentation/d/1_psbxg6vPk21C3nAcytyVJm8QTYr-G7AV1qAtjcRclg/)
- 演習：ミニゲームを考えてみよう
  - サムネイルを描く
  - 操作方法：unityroomを参考に、キーやマウスなど、どうやって動かすのかを書く
    - 選択肢に対応するもの
  - ルール
    - 何をするのか
    - 何をしたらいけないのか
  - 簡単な世界観など(あれば)    
  - **プレイヤーは、何を制限されるのか？　を考えるとまとめやすい**
- 参考： https://docs.google.com/drawings/d/1mGXGcm8mcXUBmP3rqVQheMDZLl3jd86qapLr7NChwjU/
