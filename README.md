# 職務経歴書

## 基本情報

| 項目            | 内容                          |
| --------------- | ----------------------------- |
| 氏名            | 安孫子 直弘 (アビコ ナオヒロ) |
| 生年月日        | 1993.7.17                     |
| 出身地 / 居住地 | 埼玉県 / 東京都               |
| 最終学歴        | 早稲田大学 法学部             |
| 資格            | AT普通自動車運転免許          |

## 会社経歴

| 年月日    | 経歴                    |
| --------- | ----------------------- |
| 2018.4.1  | 富士ソフト株式会社 入社 |
| 2021.6.31 | 富士ソフト株式会社 退社 |

## プロジェクト経歴

###### 2021.5/~2021.6

### 大手機械メーカーのWebアプリの保守（C#）

PLと2人で連携して開発エンジニアとして

###### やったこと

レイアウトの修正、検索速度のチューニング  

<div style="page-break-before:always"></div>

* HTML,CSSを修正し、レイアウトを整える、ページローディングの機能を追加。  
* 機械部品データベース内を全文検索した際のクエリ速度が遅いので、C#のLinqコードを調査、二重ループのロジックを修正、検索結果ページごとにSQLServerにIndexを貼り、検索速度を改善。

###### 2021.3~2021.5

### 外務省のビザに関するWebサイトをアプリ連携させる（Java）

15人チームでエンジニアとして

###### やったこと

コードバグ改修、テスト

* 大規模アプリを開発するに伴い、既存のWebサイトを連携させるという開発プロジェクト。
* 主に画像ファイルを処理するプログラム、画像ファイルをDB、ファイルサーバ両方に保存し、APIでアプリと連携させるためのテーブルの処理を追加する工程で発生したバグをテストし、改修。
* あまり大きな役割は果たしていない。

###### 2020.6.1~2021.3

### 大手マスメディアの基幹システム開発（C#）

100人規模の開発チーム(6人)のPL補佐、構成管理チーム(3人)のCI/CD構築エンジニアとして

###### やったこと

構成管理、実装、設計、テスト

* 自社ブランドのパッケージを用いた開発でしたが、パッケージ開発は大規模かつ各企業のドメインとすり合わせることが難しく、炎上したプロジェクトへの12,13ほどある開発チームのうちの1チーム(6人ほど)に開発者兼PL補佐として参画。  

<div style="page-break-before:always"></div>

* 定期券購入者の電車、バス経路情報をデータベースから反映させる処理を担当。
* 経費処理を仕様に合わせてSQLクエリを作成、検索処理を担当。
* 3人の構成管理チームへ参画。構成管理ではGit管理、DB管理、テスト環境や受入環境へのビルド・リリースを手作業で行っていたものをInfrastracture as Codeの元シェルでCI/CDを構築しました。  
一通りシェルスクリプトのバッチ、Windowsバッチを作成し、半自動化したのち、誰でもリリースできるよう、Jenkins導入を試みました。  
しかし、複雑な環境に柔軟に合わせることが困難と判断し、諦めてスクリプトでバッチを管理するということにしました。

###### 2018.6.1~2020.5.31

### 大手機械メーカーの生産管理システム開発（C#）

20人(パートナー社員含む)のPJのプロパーとして

###### やったこと

テスト、インフラ構築、実装、受入、本番環境リリース

* 上司がいるプロジェクトチームで、最初はテストケースを考え、仕様書を作成し、実施することで下地となる経験を積ませてもらいました。簡単な追加機能を実装したり、メールサーバーやWebサーバー、DBサーバーの構築、リリース等色々なことをしました。
* ちょっと雑務も多かったですね。

<div style="page-break-before:always"></div>

## 個人開発

<!-- ### [Ocha🌿](http://ocha.onrender.com) -->
### <a href="http://ocha.onrender.com" target="_blank" rel="noopener noreferrer">Ocha🌿</a>

###### 2023.8~2023.9

いわゆるリンクをまとめておけるプロフィールサービスです。自分が欲しいので作りました。<a href="http://ocha.onrender.com/u/nao" target="_blank" rel="noopener noreferrer">わたしのプロフィールはこちら</a>
<!-- ![ocha_profile](https://user-images.githubusercontent.com/46675984/270082722-84c31972-b542-4eff-9c39-b8fe0e848f07.png) -->

###### 使用した技術

PHP / PostgreSQL / Apache / Bootstrap / Docker

###### 学習した点

* RenderにDockerからデプロイするために初めてDockerを学びました。Apacheを含めてインフラ関係の知識を現場開発に支障がないくらいに学習するために2,3週間費やしました。
* PHPも初めてでした。また、Webの知識を付けるためLaravel等のフレームワークは使用していません。
* セキュリティも対策しました。CSRF対策、 XSS、SQLインジェクション等

### 絵描き友達のポートフォリオ

###### 2023.9~2023.10

##### <a href="https://demohouse-react.netlify.app/" target="_blank" rel="noopener noreferrer">デモサイト</a>
<!-- ![demo](https://github.com/naonao0001777/egg-react-demo/assets/46675984/bd624375-a10f-4b84-a1cb-343098433cae) -->
###### 使用した技術

React / TypeScript / Bulma

###### 課題

* アニメーション(アイコンのスクロールの位置によるスタイル変化)を実装したいですが、今はまだできていません。

<div style="page-break-before:always"></div>

* 最初はNext.js、GatsbyJS、Astroを使用して開発しようと考えていましたが、フレームワークゆえの障害もあり、ReactとTypescriptのみで開発することにしました。

### 私の個人開発ポートフォリオ

###### 2020~現在

##### <a href="http://naopem.com/" target="_blank" rel="noopener noreferrer">http://naopem.com/</a>
<!-- ![demo](https://github.com/naonao0001777/egg-react-demo/assets/46675984/bd624375-a10f-4b84-a1cb-343098433cae) -->
###### 使用した技術

HTML5 / CSS3 / jQuery
###### 課題

* CSSフレームワークを使用していないサイトなので、デザイン共にそろそろ刷新したいです。

### Youtubeコメントを取得し検索/ソートをするWebサイト

###### 2019~数週間程度

##### <a href="https://github.com/naonao0001777/getting-youtube-live-chat" target="_blank" rel="noopener noreferrer">Github</a>

YoutubeAPIを使用した何かを作りたいと思い、コメントを取得してくるサイトを作ってみました。
<!-- ![YouTubeAPIを使用した代表作](https://user-images.githubusercontent.com/46675984/124333733-13650480-dbd0-11eb-8a29-b30718afd31f.gif)   -->
###### 使用した技術

.NET C# / Azure / jQuery / Bootstrap / YouTubeAPI  

###### 大変だった点

* APIを利用して一から開発をするのは初めてだったため初めての挑戦でしたが、意外とデータを取ってくるところだけ注意してなんとか開発しきりました。

<div style="page-break-before:always"></div>

### 英和⇔和英翻訳LINE bot

###### 2019~数週間程度

##### <a href="https://github.com/naonao0001777/translation-line-bot" target="_blank" rel="noopener noreferrer">Github</a>

すぐに翻訳できるサイトかアプリが欲しいと思い、LINEBotを作成してみたいのもあって作成。

###### 使用した技術

GoogleAppScript / LineAPI

## 保有スキル

#### プログラミング

* C# .NET Framework
  * データベースと連携したWebアプリの一部機能を開発することができます。
  * 個人開発でもAPIを用いてWebアプリを開発することができます。
* Java
  * ソースコードを修正することができます。
  * 機能追加までは実務上やっていませんが、やることはできます。
* PHP (v8.2.9)
  * データベースを用いてWebアプリを個人開発することができます。
* React (v18.0.0)
  * シンプルな静的Webサイトを作成することができます。
* Typescript (v4.4.2)
  * シンプルな静的Webサイトを作成することができます。
* jQuery
  * Ajax処理、アニメーション機能を追加することができます。
* HTML5/CSS3 (Bootstrap-v5.3.0, Bulma等)
  * 静的Webサイトを作成することができます。
  * CSSフレームワークは根本の知識は押さえているので他のCSSフレームワークも使用できます。

#### データベース

* MySQL
  * 簡易的なDBを構築し、クエリを用いてCRUD処理を書くことができます。
* SQLServer
  * 複数テーブルからデータを取ってくるクエリを書くことができます。
* PostgreSQL
  * 簡易的なDBを構築し、クエリを用いてCRUD処理を書くことができます。

#### その他

* Docker
  * Dockerfile、yamlを書いて個人開発用の環境を構築、DockerHubにプッシュすることができます。
* Sass
  * CSSフレームワークにないクラス、要素を追加することができます。
* Node.js (v16.7.13)
  * サーバーとして使用し、npmを操作することができます。
* Shell
  * シェルスクリプトを用いて、Gitブランチを統合、ビルド、リリースまでのインフラを自動化することができます。
* Windows
  * Windowsコマンドを用いて、DBダンプ、バックアップ、バッチ処理を作成することができます。
* Apache
  * Webアプリのサーバーとして個人開発用に使用することができます。
* AWS
  * リリースのためにEC2起動、ログインをしていた程度です。
* チケット, Git管理
  * 現場でチーム開発をすることができます。
* 英語
  * 日常会話レベル (ビジネス会話レベルはちょっとやってみないと分かりません。)
  * ゲームでフレンドといつもテキスト、会話でコミュニケーションをしています。

## アピールポイント

富士ソフトでは主にC#、SQLServerのWebアプリをエンジニアとして開発していましたが、正直なところ、パートナーと同等のレベルで実装をさせてもらうことができずにいたので、
個人開発をして技術を身に着けました。  
そのため、自学自習をして自走し、やりきることができます。バックエンドが得意です。  
また、実務ではSREと言えるかは分かりませんが、構成管理というチームでCI/CDをシェルスクリプトで構築しました。  
手動でブランチを統合、ビルド、リリースしていた前任者から引継ぎ、Infrastracture as Codeで半自動化しました。  
したがって、DevOps開発の下地経験があります。Jenkinsの導入も自ら動きましたが、結局これは頓挫しました。一番主体性を発揮した経験がCI/CD構築でした。  
いつかはJenkinsに限らず、k8s等OSSを用いたDevOps開発をしたいという熱い考えがあります。

## これからやりたいこと

DevOpsでのアジャイル開発、スクラム開発がしたいです。  
富士ソフトのようなハードワークな開発現場を経験し、ミッションに共感できる開発現場とDevOpsに理解がある組織で開発インフラが自動化されたエンジニアの快適空間を作りたいという思いがあります。  
こういうふうに書いてしまうとSREをやりたいのかと思われると思いますが、DevOpsの環境で働きたいからDevOpsを牽引するSREをしたいのであって、DevOpsがある組織で基本は開発エンジニアをしたいです。  
エンジニアファーストな企業で、ボトムアップな開発がしたいです。

<div style="page-break-before:always"></div>

## 現在興味があるもの

Webサービス、Saas開発に興味があります。  
GoやPHPと書かれているとわくわくしてしまいますが、Javaや他の言語を使用していても大丈夫です。  
事業のバリュー、今後の事業の成長性、顧客ターゲット層や開発目的、マネタイズのフローがイメージしやすいサービスだととても楽しそうだと思います。  
事業ドメインに関してはさほど絞っていませんが、友達が使用してもイメージしやすいBtoCサービスだったり、困っている人を解決するBtoB, BtoCサービスには興味を持ちやすいと思います。

## 好きなこと

* 個人開発が好きです。  
これからもまだまだ作りたいものがたくさんあります。そして、ツール等を自作している人をとてもリスペクトしています。便利な物を作っていると思うととても好奇心とリスペクトの念が湧きます。  
* オンラインマルチプレイヤーゲームも好きです。  
FallGuysはプロレベルにまでやり、動画をアップロードしていました。賞金付き大会も出てました。
* 本を読むのも好きです。  
一時期は4ヵ月で10冊以上技術書を買ってました。Effective DevOpsは読んでて感動しています。他にもカイゼンジャーニー、アジャイルサムライ、Team Geek、SOFT SKILLS、達人プログラマーは
たまに読んではモデルを形成し、開発体験、キャリア体験に落としたいと思う本です。

## ソーシャルメディア

* <a href="https://github.com/naonao0001777" target="_blank" rel="noopener noreferrer">Github</a>
* <a href="https://twitter.com/salty_special" target="_blank" rel="noopener noreferrer">Twitter</a>
* <a href="https://zenn.dev/naozen" target="_blank" rel="noopener noreferrer">Zenn</a>
* <a href="https://qiita.com/salty_special" target="_blank" rel="noopener noreferrer">Qiita</a>
