# BUZZ BASE  
サービスURL : https://buzzbase.jp/  

![](/assets/buzz-ogp.png)

### 野球の個人成績をランキング形式で共有できるアプリ

【ゲストユーザーアカウント情報】  
・ゲストユーザー1  
Email : buzzbase.app+1@gmail.com  
Password : password  

・ゲストユーザー2  
Email : buzzbase.app+2@gmail.com  
Password : password     

・ゲストユーザー3  
Email : buzzbase.app+3@gmail.com  
Password : password    

ユーザーは野球の試合結果と個人成績を記録して管理することができます。  
そして、フォローしているユーザー同士でグループを作成することができ、グループ内で個人成績をランキング形式で比較・共有することができます。  
個人成績を可視化して、他人と比較できることで、競争心や楽しさを感じながらユーザーの野球に対するモチベーション向上をサポートするサービスになります。

## 開発背景

私は、16年間野球に取り組んでおり、キャプテンを小学校〜大学まで務めました。その経験からチームメイトのモチベーション管理に課題を感じることが多くありました。特に、大学時代に100名規模のチームのキャプテンを務めた時に、チーム全体が同じ目標に向かって取り組むために、チームメイトの野球に対するモチベーションの維持・向上に課題を感じることが多くありました。  
　キャプテン就任当初は、チームメイトに対して正論をぶつけていくアプローチ方法をとってしまい、チームメイトへ間違ったコミュニケーションをとってしまいました。  
　しかし、試行錯誤していくうちに、普段の練習ではあまりモチベーションが高くない選手でも野球に対するモチベーションが向上するタイミングを見つけました。それは、全国大会につながるリーグ戦です。このリーグ戦の直前〜リーグ戦の最中は、普段居残り練習をしない選手でも、グランドに残って練習する姿を見ました。私なりにその要因を考えたところ、リーグ戦は家族・友人が試合を観にくるので、活躍すると周りからの反応が多く、モチベーションが向上したのではないかということと、チームメイトや後輩が活躍することによる「悔しさ・焦り」からくるモチベーションがあるのではないかと思いました。  
　なので、個人成績を記録して、他のユーザーに発信ができることとランキング機能で、モチベーションが向上した時の感情に近いものをユーザーに体感してもらいたいと思い、このWebサービスを開発しました。

## 主要な機能

- 試合結果・個人打撃・個人投手成績を記録機能
- グループ作成機能
- 個人成績ランキング機能

### 📝 試合結果・個人打撃・個人投手成績を記録録機能

![](/assets/record.png)

| 試合結果を記録                                                                                                                                   | 打撃成績を記録 |
| :----------------------------------------------------------------------------------------------------------------------------------------------------------: | :---: |
| <img src="https://i.gyazo.com/4b3992d3b6493fc02389d9169bcc2eeb.gif" width="320">                                                                              | <img src="https://i.gyazo.com/e0d4423d89b82717e18b94de9621570f.gif" width="320">    |
| <p align="left">試合日付 / 試合種類（公式戦/オープン戦） / 大会名 / 自分チーム名 / 相手チーム名 / 点数 / 打順 / 守備位置 / メモ</p> | <p align="left">打席結果 / 打点 / 得点 / 失策 / 盗塁 / 盗塁死</p> |

| 投手成績を記録                                                                                                                                   | 成績まとめ |
| :----------------------------------------------------------------------------------------------------------------------------------------------------------: | :---: |
| <img src="https://i.gyazo.com/3d8031261e0e2e9d1fafd3b2c13134ae.gif" width="320">                                                                              | <img src="https://i.gyazo.com/d9eb11c5bbb7504d06387cb63942e253.gif" width="320">    |
| <p align="left">勝敗 / 投球回数 / 投球数 / 完投 / ホールド / セーブ / 失点 / 自責点 / 被安打 / 被本塁打 / 奪三振 / 四球 / 死球</p> | <p align="left">記録した成績のまとめ画面。</p> |

1試合ごとに「試合結果」と「個人成績」を記録することができます。

### 👬 グループ作成機能

![](/assets/group-v2.png)

| グループ作成 | メンバー追加 |
| :---: | :---: |
| <img src="https://i.gyazo.com/b9f4dca471348eb44cfea1100345d9f7.gif" width="320"> | <img src="https://i.gyazo.com/4ec6a5612e76622dcc8985479156f391.gif" width="320"> | 
| <p align="left">グループアイコン画像 / グループ名 / グループメンバー招待</p> | <p align="left">グループ作成後に、新規にユーザーをグループに招待することができます。</p> |

| メンバー退会 | グループ編集 |
| :---: | :---: |
| <img src="https://i.gyazo.com/e96a1f01bf651b5b57d59bf69dfcb002.png" width="320"> | <img src="https://i.gyazo.com/f3e54f250d1a28d00d82a4affef0fa76.png" width="320"> | 
| <p align="left">メンバー一覧画面で、退会させたユーザーのチェックを解除することで、特定のユーザーを退会させることができます。</p> | <p align="left">グループ編集画面では、「アイコン画像」「グループ名」を変更することができます。また、グループ作成者のみ「グループを削除」することができます。</p> |

フォローしているユーザーのみに対して、グループメンバーに招待することができます。招待時には「通知」を送信し、ユーザー自身がグループに「参加」or「拒否」を選択することができます。  
また、グループ作成後に「新規メンバー招待」「メンバー退会」「グループ削除」が行えるようになっています。

### 👑 個人成績ランキング機能

![](/assets/ranking-v2.png)  

| 打撃成績ランキング | 投手成績ランキング |
| :---: | :---: |
| <img src="https://i.gyazo.com/5936adaa3dbe88bc09046fcf7e739e1c.gif" width="320"> | <img src="https://i.gyazo.com/37d9b3c4640b786a5c8f0d00137ef910.gif" width="320"> | 
| <p align="left">打率 / 本塁打 / 打点 / 安打 / 盗塁 / 出塁率</p> | <p align="left">防御率 / 勝利 / セーブ / HP / 奪三振 / 勝率</p> |

グループに参加しているメンバー同士で、「打撃成績」「投手成績」をランキング形式で共有することができます。

## その他機能

### 🙍‍♂️ ユーザー機能

| メールアドレス認証 | リアルタイムバリデーション | マイページ |
| :---: | :---: | :---: |
| <img src="https://i.gyazo.com/fbdbdc65350675f713460b88718cc7f4.gif" width="220"> | <img src="https://i.gyazo.com/9c7e6c199fd75b5b39869da825e001ff.gif" width="220"> | <img src="https://i.gyazo.com/076dd7646bb4ad712302ef0c7a2f9258.gif" width="220"> | 
| <p align="left">新規会員登録時に「メールアドレス認証」を実装しました。<br> これにより不正なアカウントを作成することなどを防ぎ、セキュリティ面の向上を図りました</p> | <p align="left">リアルタイムバリデーションを導入することで、フォームを送信する前に入力ミスをユーザーに伝えることができ、UXの向上を図りました。</p> | <p align="left">マイページで「ポジション」「所属チーム」「受賞タイトル」「成績」「試合結果」などの情報を確認することができます。</p>

### 🔍 ユーザー検索機能

| オートコンプリート | 
| :---: |
| <img src="https://i.gyazo.com/cd124a2e3739f0d2ed61812215f06bda.gif" width="220"> | 
| <p align="left">ユーザー検索には、オートコンプリート機能を実装して、１文字ずつ候補を表示させることで、ユーザーの入力する手間を減らし、UXの向上を図りました。</p> | 

### 🔔 通知機能

| フォロー・グループ招待通知 | 
| :---: |
| <img src="https://i.gyazo.com/99c16d2c933c658cc02d3b05d2b8f1a5.gif" width="220"> | 
| <p align="left">フォロー時とグループ招待時に、通知が届きます。グループへの参加・不参加は、通知画面上で行うようにしました。</p> | 

## 使用技術

| カテゴリ | 技術 | 
| --- | --- |
| フロントエンド | TypeScript 5.3.2 / React 18.2.0 / Next.js 14.0.3 | 
| バックエンド | Ruby 3.2.2 / Ruby on Rails 7.0.8（APIモード） |
| データベース | PostgreSQL 15.5 |
| 認証 | devise toke auth 1.2.2 |
| 環境構築 | Docker |
| CI/CD | Github Actions |
| インフラ | Vercel / Heroku / S3 |
| その他 | SWR / Tailwind CSS / NextUI / Mantine / js-cookie / <br> ESLint / rubocop / CarrierWave / mini magick / letter opener web |

### 🧑‍💻 技術選定理由 

野球成績記録系サービスの競合は、ネイティブアプリが多かったため、シングルページアプリケーション（SPA）を採用して、ユーザーが操作するときにストレスを与えないようにしたいと考えました。また、UIについては出来るだけ開発コストを抑えながら、使いやすさを表現したかったので、TailwindCSSとNextUIを採用しました。

**【フロントエンド】**  
野球成績記録系アプリケーションは、ネイティブアプリで開発されているものが多いため、Webアプリケーションでありながらもユーザーに高速で快適な操作感を提供することを最優先に考えました。そのため、シングルページアプリケーション（SPA）の開発に最適だと判断した、ReactとNext.jsを採用しました。  
Reactは再利用可能なUIコンポーネントを簡単に作成でき、開発効率と保守性を向上させることが期待できます。Next.jsはサーバーサイドレンダリング（SSR）や静的サイト生成（SSG）などの機能を実装することにより、SPAのデメリットである初回ロード時間を短縮することが可能です。  
また、野球成績データは多数のデータを扱うことが想定されるため、TypeScriptを導入しました。これにより型安全性と開発時の自動補完を利用し、データを扱う際に予期せぬバグが発生するリスクを減少させたいと考えました。

**【バックエンド】**  
Railsの「設定より規約」という原則により、アプリケーションの詳細な設定を大幅に減らせて、開発時間を短縮できると思ったため採用しました。例えば、Railsではモデル名が単数形であれば、自動的に対応するデータベーステーブル名が複数形で生成されるといった規約が適用されます。また、RailsはWebアプリケーションに必要な標準機能を提供しており、迅速にアプケーションを構築できると思いました。

**【データベース】**  
野球の成績記録アプリケーションでは、ユーザーデータを中心として、試合結果・打撃結果・投手結果などを扱うため、多様なデータを扱いやすいPostgreSQLを採用しました。

**【認証】**  
`devise token auth` はトークンベースの認証システムであり、サーバー側にセッション情報を持つ必要がないため、RailsをAPIとして使用する場合に適切だと思いました。

**【環境構築】**  
プログラミングスクールRUNTEQ内で「Webアプリケーションのプルリクを相互にレビューする会」に参加したため、レビューワーの方がローカル開発環境を構築しやすいようにDockerを導入しました。

**【CI/CD】**    
デプロイの自動化を行い、開発効率の向上のため、Herokuへのデプロイを GitHub Actions により自動化しました。

**【インフラ】**   
Vercelは、Next.jsとの相性の良さと、CI/CD環境の構築やデプロイの手軽さを重視してVercelを選択しました。  
Herokuは、低コストでPostgreSQLを使用できること、Ruby on Rails の環境構築などのドキュメントが豊富という観点で採用しました。  
Amazon S3は、画像のストレージとしてAmazon S3を採用しました。特に、このアプリケーションが画像を大量に扱わないため、S3の無料利用枠内でコスト効率良く運用できると判断しました。  

**【その他】**    
NextUIは、コア機能である成績を記録する画面での利用を想定して選択をしました。NextUIのフォーム系コンポーネントはシンプルで使いやすく、データ入力をスムーズすることができると思いました。また、UIデザインがモダンで、ターゲットとなりえるZ世代のユーザー層にも直感的でストレスの少ない操作体験を提供できると思いました。  
TailwindCSSは、開発時のスタイリング作業の効率化を目的に採用しました。  
SWRは、成績データなど頻繁に更新が必要な情報を効率的に扱うため採用しました。キャッシング機能とデータ再検証戦略により、アプリケーションのパフォーマンスを向上させ、ユーザーに最新の情報を迅速に提供することができます。SWRは自動的なデータ更新と最適化されたデータフェッチを実現し、ユーザー体験を向上させることができると思いました。

## インフラ構成図

![](/assets/infrastructure-configuration-chart.png)

## ER図

[![Image from Gyazo](https://i.gyazo.com/675a5d6a117b37be94c45cece4db3970.png)](https://gyazo.com/675a5d6a117b37be94c45cece4db3970)

[テーブル設計詳細](https://github.com/ippei-shimizu/buzzbase/blob/main/buzz-base-table.md)

## こだわりポイント

## 今後の開発について（本リリース）

今後、以下の機能を実装予定です。

- 野球ノート機能
- 鍵アカウント機能（成績を他者に公開したくないユーザー向け）
- チーム・所属カテゴリー・所属地域で絞り込まれたユーザーの成績ランキング機能
- ランキング（マルチ検索・オートコンプリート）
- ランキングお気に入り機能
- LINE Messaging API（通知機能の拡張）
- Google認証機能
- 表彰機能（大会で1番打率が良かった選手などに、バッチをプレゼントして、プロフィールに表示されるようにする）
- ファン登録機能（ユーザー登録時に、「選手」と「ファン」のどちらか選択できるようにする）
  - ファンユーザーは、選手に対して応援メッセージが送れる。
- 選手のプロフィールページへのアクセス数ランキング機能


[画面遷移図-figma](https://www.figma.com/file/zwyB9tqtr1JrFWsStPnk91/BuzzBase?type=design&node-id=0-1&mode=design)  
[開発スタート時のREADMEはこちら](https://github.com/ippei-shimizu/buzzbase_front/blob/main/README.md)
