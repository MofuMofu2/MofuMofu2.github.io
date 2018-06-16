# 『今日から始める技術Podcast完全入門』に感銘を受けてPodcastをはじめてみた

[もふもふ（@froakie0021）](https://twitter.com/froakie0021?lang=ja)

---

## [もふもふ（@froakie0021）](https://twitter.com/froakie0021?lang=ja)

* [りまりま団](https://techbookfest.org/event/tbf04/circle/14530001)として[技術書典](https://techbookfest.org/)やコミックマーケットに参加
* 同人誌が商業本になっていたりします。
  + [その1](https://thinkit.co.jp/article/13857)
  + [その2](https://www.amazon.co.jp/Introduction-Elastic-%E3%81%93%E3%82%8C%E3%81%8B%E3%82%89%E3%81%AF%E3%81%98%E3%82%81%E3%82%8B%E3%83%87%E3%83%BC%E3%82%BF%E5%8F%8E%E9%9B%86-%E6%8A%80%E8%A1%93%E6%9B%B8%E5%85%B8%E3%82%B7%E3%83%AA%E3%83%BC%E3%82%BA-NextPublishing/dp/4844398296/ref=sr_1_sc_1?s=books&ie=UTF8&qid=1529118584&sr=1-1-spell&keywords=Elasti+Stack+6)
* [Booth](https://mofu-mofu.booth.pm/)に過去に出した同人誌があったりする

---

## Podcastはじめました

[ひよこなもふもふちゃんと技術同人誌.fm](https://mofumofu2.github.io/hiyokoMofu-fm/)をはじめました

---

## きっかけ

[今日から始める技術Podcast完全入門](https://booth.pm/ja/items/828339)の

> あなたもいますぐPodcastをはじめて、楽しい毎日を過ごそうよ！

という言葉に感銘をうけました😊

---

## 何について話すの？

* ひよこエンジニア（初心者）に向けた内容
* 商業誌/技術同人誌（など）の感想・関連するプロダクトの話
* その他（毎回ネタを入れるのが目標）

---

## はじめた理由

* 商業本/同人誌の感想を届けたい（積ん読防止の側面もある）
* ひよこな人を応援したい（自分もひよこ）
* 自分の原稿のネタを忘れないように（kuso）

---

## 公開方法は？

1. iPhoneのボイスメモで音声ファイルを作成
2. iTunesを利用してmpファイルに変換
3. [yattecast](https://github.com/r7kamura/yattecast)のテンプレートファイルを記載
4. [GitHub](https://github.com/MofuMofu2/hiyokoMofu-fm)にデプロイ
5. [ひよこなもふもふちゃんと技術同人誌.fm](https://mofumofu2.github.io/hiyokoMofu-fm/)のページができます

運用費はかかりません。あなたもできそうですね😏

---

## デプロイ時の注意点

[yattecast](https://github.com/r7kamura/yattecast)、はまりどころも多かったので共有です😺

* タイトルに""など、マークアップを入れるとデプロイされない
* ファイル名に命名規約がある
  - 音声ファイル名は半角数字を利用する（ex:``1.mp``）
  - ``_posts``は``YYYY-MM-dd-mpファイル名（半角数字）.md``とする
* 音声ファイルの容量はByteで記載する
* リポジトリ名は``XXXX.github.io``とする（[公式ドキュメント](https://pages.github.com/)）

詰まったときはYattecastをForkしたリポジトリを参照し、
自分のリポジトリとの差異を調べると良いです👍

[商業化されるらしい](https://yatteiki.fm/episode/54)ので、詳しい解説がされることを期待しましょう😎

---

## おわり

* 面白い本（商業・同人問わず）があれば教えてください
* コミックマーケット（8/10 1日目 ``西ホールめ06-b``）
  にも遊びにきてくれよな！