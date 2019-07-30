---
marp: true
theme: default
paginate: true
size: 16:9
---
![bg](./img/INSPIRED.png)

---
<!-- _paginate: false -->
# INSPIRED BY USER! 立ち上げの思いと<br>アクセシビリティについて

---
## 自己紹介
<!-- _paginate: false -->
![bg right:40%](https://www.oreilly.co.jp/books/images/picture_large978-4-87311-432-3.jpeg)

- 持田 徹
- クラスメソッド**CX事業本部**
- 入社1年1カ月
- 普段の業務:
  - モバイルアプリ/Webアプリの受託開発
  - AWSなどのAIサービスを活用した<br>ソリューションの提供
- 2002年からアクセシビリティの<br>研究・執筆・講演
- ウェブアクセシビリティ基盤委員会<br>WG4(翻訳) 作業協力者

---
## アクセシビリティとは?

- 「アクセスのしやすさ」の意味。転じて、製品やサービスの利用しやすさという意味でも使われる([出典](https://waic.jp/knowledge/accessibility/))。
- ユーザーには年齢や病気などで以下のような特性があり、これらを考慮して、Webサイト、Webアプリ、スマホアプリを、より多くのユーザーがより多くの利用環境からより多くの場面で利用できるようにすること([出典](https://www.slideshare.net/waic_jp/webjis-x-83413-99188222))。
    - 見ることができない(全盲の視覚障害)
    - 見えづらい(弱視、ロービジョン、老眼、屋外)
    - 聴くことができない(聴覚障害、オフィス、イヤホンがない)
    - 聴こえづらい(難聴、加齢による衰え、騒がしい)
    - 細かい操作が困難(上肢不自由、指や手が震える etc.)
    - 認知・理解・学習(認知・言語・学習障害、ディスレクシア、...)

---
## INSPIRED BY USER! 立ち上げの思い

1. アクセシビリティの大切さを実感するには当事者の利用状況を見るのが一番だ！
2. Web以外にもアクセシビリティは必要だ！
3. 日本の**モバイルアプリやWebアプリ**をアクセシブルにしたい！
4. アクセシビリティの問題を知るには、アクセシブルでないアプリを取り上げざるを得ない
5. アクセシビリティはCXの土台である

---
## 持田とアクセシビリティとの出会い(1)

2002年頃 → 歴史をお話すると、ほぼWebアクセシビリティの歴史に(笑)

- 最初は自分のサイトのCSSに凝っていた
- IEとNetscapeで見た目を同じにするとか
- ある日、ヨドバシ梅田で「ホームページ・リーダー」を購入
- 自分のサイトを読み上げさせてみた
- 目をつぶって利用すると「読み上げで理解しやすいサイト」のノウハウ得られた
---
## よりみち: ホームページ・リーダーとは

Webページを音声で読み上げ、キーボードでナビゲーションできるソフトウェア
(現在、このジャンルはスクリーンリーダーが担っている)
![width:500px ホームページ・リーダーのスクリーンショット](https://www-01.ibm.com/common/ssi/rep_ca/3/760/ACC01003/ACC01003_1.gif)

---
## よりみち: 支援技術

### 支援技術(Assistive Technology)
PCやモバイル端末などを使う際に支援が必要なユーザーに向け、それぞれのニーズに合う様々な機能を提供するソフトウェアやハードウェア、デバイスなどの総称
- スクリーン・リーダー
  - **iOSやmacOS:** VoiceOver
  - **Android:** TalkBack
  - **Windows:** ナレーター、JAWS、NVDA、...
- 画面拡大、色反転、ジョイスティック、トラックボール、キーボードガード、...

---

## 持田とアクセシビリティとの出会い(2)

- 実際に視覚に障害のある方はどう利用されているのか？
- 「ASV神戸」に依頼して、インターネット講習を見学させていただいた
- 主婦の方がホームページ・リーダーで電車の乗り換えを検索していた
- そこで、いろいろなショックを受けた → その後の原体験に

---

## それからの歴史をかるく(1)

- [WCAG1.0](https://www.w3.org/TR/WAI-WEBCONTENT/) が勧告されて2年、まだ、いろいろなノウハウが入り乱れていた
- 2004年6月: JIS X 8341-3:2004「高齢者・障害者等配慮設計指針－情報通信における機器，ソフトウェア及びサービス－第3部：ウェブコンテンツ」が公示
  - ガイドラインの統一
  - 工業標準化法67条: 国及び地方公共団体は、調達にあたりJISを尊重すること
- 2008年7月: iPhone3G発売
- 2008年12月: [WCAG2.0](https://waic.jp/docs/WCAG20/Overview.html)が勧告
- 2010年8月: JIS X8341-3:2010が公示
- 2012年10月: WCAG2.0がISO規格([ISO/IEC 40500:2012](https://www.iso.org/standard/58625.html))に
- 2016年3月: JIS X8341-3:2016が公示
- 2018年6月: [WCAG2.1](https://www.w3.org/TR/2018/REC-WCAG21-20180605/)が勧告に

---

## まとめると

アクセシビリティはWebだけの問題ではないが、Web分野が先行している
- 総務省『[みんなの公共サイト運用ガイドライン](http://www.soumu.go.jp/main_sosiki/joho_tsusin/b_free/guideline.html)』
  - 国や地方自治体のサイトでのアクセシビリティ確保の方法や対応期限が記載
- コンペの調達条件にWebアクセシビリティが含まれている(コンテンツ、CMS)
- Webサイトの公開前にアクセシビリティの試験をして結果を公表することが求められる

ただ...「基準を満たすこと」が目的になってしまいがち? (個人の感想です)

---

## スマホアプリの分野では?

- スマホでは、UIとしては[Webよりアプリの利用時間が圧倒的に長い](https://www.mobiloud.com/blog/mobile-apps-vs-the-mobile-web/)
- スマホアプリ開発者向け情報でアクセシビリティのトピックをあまり聞かない
- [障害当事者の方がVoiceOverでスマホアプリを利用できないなど支障が出てきている](https://www.javis.jp/pipermail/salon/20190405/000116.html)
- Webアクセシビリティのような公的なガイドラインは存在しない
- [iOS](https://developer.apple.com/jp/accessibility/ios/)や[Android](https://developer.android.com/guide/topics/ui/accessibility?authuser=1&hl=ja)の開発者向けガイドは存在する

---

## アクセシビリティとビジネス

- アクセシビリティのイベントでは、Web制作会社よりサービス企業の発表が多い印象
  - 自社サービス、自社メディアだとアクセシビリティにも力を入れる？
  - [アクセシビリティの祭典](https://accfes.com/2019/)や[JAC](https://japan-a11y-conf.com/vol2/)でも、自社サービス、自社メディアが多い印象
- 受託開発されるスマホアプリは、ずっとアクセシブルでないままか?
- 公共サイト以外はアクセシブルでなくていいのか?
- 多くの人が利用するスマホ/Webアプリは、公共でなくてもアクセシブルであるべきでは?
- 受託での困難さ: アクセシビリティ向上の工数を見積もりに乗せるかどうか問題...
   - 従来作業に「追加でアクセシブルに」ではなく、最初からアクセシブルにしたい

---

## CXとアクセシビリティ

- CX(Customer Experience): 「顧客（＝カスタマー）としてのあらゆる体験」を指す言葉。サービス・製品を認識してから購入を検討、購入した場合はそれを使用するという一連の流れのすべてにおける体験のこと([出典](https://tech.nikkeibp.co.jp/it/atclact/active/15/051900050/031400083/))

- UIとUXとCX? [出典](https://www.innovation.co.jp/urumo/cx/)
![UXはUIを含み、CXはUXを含み、ブランドはCXを含む包含関係を示す図 h:300px](https://www.innovation.co.jp/urumo/images/2018/02/cx-2.png)

---

## UXハニカムとアクセシビリティ(1)
User Experience Honeycomb in ["User Experience Design"](http://semanticstudios.com/user_experience_design/) by Peter Morville
![User Experience Honeycomb h:300px](https://semanticstudios.com/wp-content/uploads/2004/06/honeycomb.jpg)
UXを構成する要素には、Useful (役に立つ)・Usable (使いやすい)・Desirable (望ましい)・Findable (探しやすい)・Accessible (アクセスしやすい)・Credible (信頼できる)・Valuable (価値がある) という7つの要素で考えられる([出典](https://bookslope.jp/blog/2012/07/evaluationuxhoneycomb.html))

---

## UXハニカムとアクセシビリティ(2)

![h:300px](https://www.bookslope.jp/blog/wp-content/uploads/2012/07/The-User-Experience-Honeycomb.002-001-300x225.png)
[Evaluation method of UX “The User Experience Honeycomb”](https://bookslope.jp/blog/2012/07/evaluationuxhoneycomb.html)

### つまり
- アクセシビリティはCXの土台である
- CXを設計・実装する人はアクセシビリティを意識することになる
