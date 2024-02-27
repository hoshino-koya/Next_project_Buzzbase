# BuzzBase

### 画面遷移図
Figma https://www.figma.com/file/zwyB9tqtr1JrFWsStPnk91/BuzzBase?type=design&node-id=0%3A1&mode=design&t=jMRCRPuenaHnDUAJ-1

### ER図
[![Image from Gyazo](https://i.gyazo.com/3a036416483bcb92cef9a6c632a760bf.png)](https://gyazo.com/3a036416483bcb92cef9a6c632a760bf)

### READMEに記載した機能
- [x] 会員登録機能
- [x] SNS認証機能
- [x] プロフィール機能
- [x] フォロー機能
- [x] 通知機能機能（LINE Messaging API）
- [x] 試合・個人成績投稿機能
- [x] カテゴリーごとの成績ランキング機能
- [x] グループ作成・招待機能
- [x] ランキング・選手名検索機能  
- [x] グループ内チャット機能 
- [x] メモ機能
- [x] 表彰機能
- [x] ファン登録機能

### 未ログインでも閲覧or利用できるページ
- [x] ランキング検索
- [x] ランキング閲覧
- [x] ユーザー検索
- [x] ユーザープロフィール閲覧

## メールアドレス・パスワード変更確認項目
- [x] メールアドレス
- [x] パスワード

### 想定URL
[こちら](https://xd.adobe.com/view/53d16b6b-bcdf-479b-4e6a-a67539af96c5-25e0/grid/)と同様にURLを記載している場合は違和感がないものになっているか？（必須ではありません）
- [x] 特に記載していない or 特に違和感を感じなかった

## サービス概要
ユーザーは野球の試合結果と個人成績を記録して管理することができることが基本的な機能になります。  
そして、ユーザー同士でグループを作成することができ、グループ内で個人成績をランキング形式で掲載することができます。  
また、記録した個人成績は各地域やカテゴリーごとのランキングへ自動で登録がされます。（例: 2023年_東京都_大学硬式野球_〇〇リーグ_打率ランキング）  
個人成績を可視化して、他人と比較できることで、競争心や楽しさを感じながらユーザーの野球に対するモチベーション向上をサポートするサービスになります。

## このサービスへの思い・作りたい理由
私は、小学校3年生から社会人2年目までの約16年間野球に取り組んでいました。小・中学校・高校・大学時にはキャプテンを、社会人野球時には副キャプテンを務めさせていただきました。その経験の中で、チームが強くなるために必要な要素である、チームメイトのモチベーション管理を行う機会多くあり、その難しさを体験したのでこのサービスを作りたいと思いました。

具体的には、大学時代に部員数約100名のキャプテンを務めさせていただいた時にその難しさを感じました。当時、私はリーグ戦初優勝を目標として取り組んでいました。しかし、強豪大学ではなかったため、選手の野球に対するモチベーションはけっして高いとは言えない状況でした。そのため、優勝するために必要な課題として感じていた、「選手一人一人の能力の底上げ」と「優勝という目標にベクトルが向いている選手を増やす」を行うには、まず根本的な選手の野球に対するモチベーションを向上させることが必要だと感じました。

なので、どうしたら選手のモチベーションが向上するのかを考えて、同級生と相談しながら色々なアプローチを行いました。しかし、最初のアプローチ方法として、選手に対して自分の正論をぶつけていくスタイルでアプローチを行なってしまったため、期待していた結果には繋がりませんでした。その後は、反省をいかして、まずは選手と仲良くなり、その人の性格や特性に合ったコミュニケーションでアプローチを行いまいた。最初のアプローチよりかは効果がありましたが、目標としていたリーグ戦優勝を達成することはできませんでした。

そんな経験から、他人の心を動かして、さらにモチベーションを維持・向上までアプローチすることの難しさを感じましたが、多くの選手に共通してモチベーションが向上するタイミングを知ることができました。それは、「大会直前〜大会期間中」と「身近な人から受ける刺激」です。このタイミングは、普段居残り練習を行わない選手も、自主的に残って練習をしている人が多く見受けられました。

この理由を私なりに考えたところ、1つ目の「大会直前〜大会期間中」は、家族や友人が応援にきたり、普段は会わない他チームの選手から自分のプレーを見られたりと、周りからの刺激が多くなります。なので、「かっこいいところを見せたい！」などの気持ちが大きくなったり、楽しい感情が生まれることから、大会期間中はモチベーションが向上するのではないかと考えました。

2つ目の「身近な人から受ける刺激」ですが、自分と同い年のチームメイトや同じポジションの選手、後輩などが試合で活躍したりすると、モチベーションが向上する選手も多く見受けられました。これは、今まで同じレベルだと思っていた人が成長している姿をみて感じる「悔しさ」や「焦り」からくるモチベーションだと考えました。

以上のモチベーションが向上するであろうきっかけを、このサービスで体験させてあげることができれば、モチベーションの維持・向上をサポートできるのではないかと思いました。

## ユーザー層について
- 個人成績をデジタルで管理したいと思っている学生野球をしている人。
- 既に別のサービスで成績を管理している人。
- チームのキャプテンなどを務めていて、選手のモチベーション管理に悩んでいる人。
- 進学時に別々のチームになったチームメイトと繋がっておき、お互い刺激を受け合う関係でいたいと思っている人。

## サービスの利用イメージ
- 成績を友達と共有して比較することで、楽しく成績を管理することができる。
- 進学時に別々の学校になってしまうが、野球の成績を共有することでお互いの刺激になる。
- チームのリーダー的なポジションの人が、選手とのコミュニケーションを活発化させるためのツールとして使用する。

## ユーザーの獲得について
- 初期ユーザーは今までの野球で知り合った人たちに提案をしてみる。（草野球・軟式社会人・硬式社会人・大学生・高校生・中学クラブチームの指導者・女子野球チームの指導者）
- アプリ導入のハードルを下げるために、チーム向けのサービスではなく、個人で成績を管理するというイメージが伝わるようにしていく。
- ユーザー自身のプロフィールページをSNSでシェアしたくなるように、プロフィールページに通算成績などが記載されるようにする。
- 試合結果を登録した後の動線で、SNSでシェアをしやすい設計にする。
- チーム内の一人がアプリを導入して、グループを作成し、友達を誘う流れにしたいので、新規登録までの動線をわかりやすくするのと、グループへの招待をしやすくする。
- カテゴリーごとのランキングは、トップページに掲載して、登録していないユーザーの検索から流入を狙いたい。

## サービスの差別化ポイント・推しポイント
既存の野球成績管理アプリ系は、「チームで管理するタイプ」と「個人成績管理に特化したタイプ」の二つに分かれています。「個人成績に特化したタイプ」の機能としては、自分の成績を管理するだけのものが多く、友人と共有する機能はSNSシェアのみのものが多かったです。また、「チーム管理タイプ」は同じチーム内で個人成績を管理して、ランキング表示する機能はありましたが、チーム外の人と共有する機能はない印象でした。
以上を踏まえた上で、以下が差別化ポイントになります。
- グループ作成機能は、フォローしているユーザーを招待することができ、チーム内外の友達と成績をランキング形式で共有することができます。
- カテゴリーごとのランキング機能では、狭い範囲内でのランキングにすることで、ランキング順位の変動が起こりやすい状況を作り、ユーザー同士の競争を期待することができます。
- カテゴリーごとのランキング機能は、登録していないユーザーでも閲覧することができるので、成績を管理することが自身のアピールにつながる。

## 機能候補
### MVP
- 会員登録機能
  - メールアドレス認証
- ログイン・ログアウト機能
- プロフィール機能
  - ユーザー名・アイコン設定
  - 自己紹介文設定
  - 自分のポジション登録
  - 所属チーム登録（チーム名・カテゴリー・地域）
  - 受賞歴登録
- フォロー機能
  - フォロー・フォロワー一覧画面
- 通知機能機能
    - フォロー、グループ招待時に通知を送信
- 試合・個人成績投稿機能
  - 試合結果記録
  - 打撃成績記録
  - 投手成績記録
  - 試合・打撃・投手成績の編集・削除
- 試合成績一覧
  - 試合成績絞り込み検索機能（年/試合種類）
- ユーザー全体の試合結果一覧
- 打撃・投手成績の集計機能
- グループ作成・招待機能
  - グループ名・アイコン設定。
  - グループ招待状態管理（招待中・参加・拒否）
  - グループ内のメンバーを対象にした、成績ランキング機能。
  - グループ編集機能。
  - メンバー追加・削除機能。
- シェア機能
  - マイページ・試合成績シェア（URL/X/LINE）
- ユーザー検索機能（オートコンプリート）

### 本リリース
- チーム・所属カテゴリー・所属地域で絞り込まれたユーザーの成績ランキング機能
- ランキング（マルチ検索・オートコンプリート）
- ランキングお気に入り機能
- LINE Messaging API（通知機能の拡張）
- Google認証機能
- 表彰機能（大会で1番打率が良かった選手などに、バッチをプレゼントして、プロフィールに表示されるようにする）
- ファン登録機能（ユーザー登録時に、「選手」と「ファン」のどちらか選択できるようにする）
  - ファンユーザーは、選手に対して応援メッセージが送れる。
- 選手のプロフィールページへのアクセス数ランキング機能

## 機能の実装方針予定
- 通知機能 → LINE Messaging API
- ランキング・選手検索機能 → マルチ検索・オートコンプリート
- グループ作成機能
- カテゴリーごとのランキング機能