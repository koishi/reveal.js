# SAC iOS勉強会 第1回
### SAC iOS Programing Workshop
## 第1システム部 大石 弘一郎
---
##はじめに
参加ありがとうございます。

私自身まだ勉強不足の面もあり、分からないこともあると思いますが、一緒に勉強できればと思います。

よろしくお願いします。
---
##自己紹介
- 自分
- 参加者全員
--
自己紹介
## お前誰よ
- 第1システム部第2グループ
- 大石 弘一郎(38歳、SAC12年目)
- 2014年末まで.NETやってた
- 今年2月からiOS開発者
- iOS開発は2011年末から
- 好きなアプリ Zaim 週間Dモーニング
--
自己紹介
##参加者全員
- 所属、名前
- Mac、iPhone持ってますか
- iOS開発の経験
- 好きなアプリ
- やりたいこと
---
##本勉強会について
--
## 勉強会の目的
- 開発手法、開発環境の習得
- iOS開発の現場への参画
- その他
--
## 具体的に勉強会でやること
- iOS開発手法の習得
- iOS概念の理解
- Objective-Cの習得
- アプリ開発
- フレームワークの習得
- その他関連ツールの習得
--
##iOS開発手法
アプリ作るまでの一通りの流れ

アプリのアイデアから開発、テスト、リリースまで
--
##iOS開発の概念

Cocoa Touchフレームワークの理解
フレームワークいっぱい
--
##Objective-Cの習得
まずはコードに慣れるところから始めて

少しずつ言語仕様の理解

最終的にはSwiftにも触れるところまでできたらよさそう。
--
##簡単なアプリの開発
とりあえず何か課題を考えるので、

みんな一緒に基礎レベルのアプリを作ってみる

Hello Worldから
--
##フレームワークの習得
課題でアプリをいくつか作って、

色々なフレームワークを使った開発
--
##やや本格的なアプリ開発
TODOリストとか、データを入力して保存するような
アプリを作ります。
もしくはWebAPIを使ったアプリも考えます。
--
##その他関連ツールの習得
開発を通じてGitやGithubの習得。
Xcodeに内蔵されているデバッガツールの習得。
--
## 今後の予定

現在の予定はこんな感じ

- Mac環境構築
- Objective-C入門
- アプリ開発実習
- Git入門
---
##で、今日のアジェンダ
- iOSの紹介、開発について
- iOSの現場について
- 学習方法
---
#iOSの紹介
--
iOSの紹介
##歴史
- 初代iPhoneからApple Watchまで

※以前のスライドを使用
--
iOSの紹介
##定期的なアップデート
###毎年のiOS、iOSデバイス
- Apple Watch
- フォーストラックパッド
- WWDC iOS9 iPhone 6s?
--
iOSの紹介
## 開発者に求められること
--
iOSの紹介
## iOSの理解
--
iOSの紹介
## iOS開発の知識
--
iOSの紹介
## 毎年のアップデートへの対応
- 普段からの情報収集
- WWDC
--
iOSの紹介
##既存アプリ、サービスの知識
- 新しいアプリのチェック
- Webサービスのチェック
- 実際にいろいろ使う
--
iOSの紹介
##開発に関連する技術の知識
- バージョン管理
- チケット管理
- コマンドプロンプトからの操作
- テスト、デバッグ手法
---
##iOS開発について
- 開発環境、ソフトウェア
- 開発言語
- アプリリース
--
iOS開発について
##開発環境、ソフトウェア
###開発環境
- Mac
- Xcode
- iOS端末
--
Mac

![Macbook](https://www.apple.com/jp/pr/products/images/MBP13_PFOP_Mavericks_131021_HERO.jpg)

Mac Book Proがおすすめ、Airとか最近出た薄いやつはスペック低め。
--
Xcode

![Xcode](https://devimages.apple.com.edgekey.net/xcode/images/whats-new-2014.png)

無料でダウンロード
--
iOS端末

![iOS](https://www.apple.com/support/assets/images/products/iphone/hero_iphone_6_5.png)

大体の人が持ってるはず
--
iOS開発について
##開発環境その他
- CocoaPods
- Ruby,RVM,Ruby Gems
- Git / Github
- その他便利ツール

HomeBrew / MacPort
Alfred
--
iOS開発について
##開発言語
###言語
- Objective-C
- Swift
###DB
- CoreData
--
iOS開発について
##アプリリース

![](http://cdn.soasta.com/findouthow/mobileapp/img/cat3_topic1_img-2_pdf.png)

- iOS Developer Program
- 年間12,000円くらい
- 実機テスト
---
## iOS開発のポイント
### Objective-Cの理解
- Objective-Cの特徴
- Swift
--
## Cocoa Touchの理解
- 基本的なアプリの構造
--
## 各種フレームワークの理解
- UIKit
- GPS
- その他、たくさん
--
## モバイルアプリ
- ネットワーク処理の理解
- GPS
--
## 非同期処理
- 同期処理
- 非同期処理の話
--
## メモリ管理
### 大抵クラッシュするのはメモリ
### ARC , MRC
メモリの話
###アプリリリースまでの手順
- アプリ開発
- アイコン、スクショ、アプリ申請
---
## iOS開発の現場について
- 実際の現場
- 参画に必要なスキル
--
## 実際の現場
- iOS,Android
- 要件定義
- コードレビュー
- 動作確認テスト
- 新しい技術
--
## iOS,Android
--
## 要件定義
--
## コードレビュー
- 他の人が自分のコードをチェック
- 基本的な設計思想
- Objective-Cの命名規則
--
## 動作確認テスト
- ロジックの全ルートチェック
正常系、異常系、ネットワークエラー時まで
- その他細かいパターン、操作はQAさん、弱電界テストなども
--
## 新しい技術
- VR
- Apple Watch
--
#参画に必要なスキル
--
##自分の場合の面談
###アプリ作成
###アピール
###必要なスキル
- WebAPI
- アカウント認証
---
#自主学習方法
- Web
- 書籍
- 社外勉強会
--
#Web
## Mixiのチュートリアル
https://github.com/mixi-inc/iOSTraining
--
#書籍
##iOS
- 入門 iOS SDK、詳解 iOS SDK
他の技術書との違い
- iOS プログラミング
アーロン本
--
#Objective-C
##詳解Objective-C
--
#Swift
##詳解Swift
--
##社外勉強会
- 勉強会の紹介
- 探し方
--
##勉強会
--
##探し方
ATNDとかいろんなイベント告知サイトあり、Azusaarで探す
http://azusaar.appspot.com
---
#次回予定
##アプリ開発実習
実際にXcodeを使ってシミュレータ上で動くものを作ってみる
##Git入門
##Mac環境構築
