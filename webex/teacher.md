# ［教員向け］Webexの使い方

## 全体の流れ

1. [1度だけ行う準備](#prepare_once)
    1. [Webexアカウントの作成](#make_new_account)
    1. [アプリのインストール](#app_install)

1. [講義の前に行う準備](#prepare_class)
    1. 資料の作成など（本稿では説明しません）
    1. [講義のスケジュール](#schedule_class)
    1. 講義URL等の取得
    1. BEEF等への講義URLの掲載による講義の周知

1. 講義の実施

<h2 id="prepare_once">1度だけ行えば良い準備</h3>

<h3 id="make_new_account">アカウントの作成</h4>

ビデオ会議をホストするには，まず，Cisco Webexのアカウントを作成します。

1. [Cisco Webexのサイト](https://www.webex.com/ja/) にアクセスし，無料で登録のボタンをクリック（図中，赤で囲った部分）
![Cisco Webexのサイト](imgs/webex_account_1.png)

1. メールアドレスを入力して「サインアップ」をクリック
![サインアップ](imgs/webex_account_2.png)

1. 国を選択，氏名を入力して「次へ」（※国は日本でいいと思います）
![氏名の入力](imgs/webex_account_3.png)

上記までの手順を終了すると，登録したメールアドレスにメールが届く。

1. メール中の「パスワードを作成」というリンクをクリックしてWebサイトにアクセスする。
![メール](imgs/webex_account_4.png)

1. Webサイトでパスワードを入力
![パスワードの入力](imgs/webex_account_5.png)

登録が終了すると，そのまま以下のようなWebex Meetingsの画面に移行する。
![Webex Meetingsの画面](imgs/webex_meetings_dashboard.png)

<h3 id="app_install">アプリのインストール</h4>

ビデオ会議用のアプリケーションである「Cisco Webex Meetings」をインストールします。

1. インストーラのダウンロード
    - Webex Meetingsの画面上の右側に「Cisco Webex Meetingsアプリを今すぐインストール」の画面が出ている場合はその下の「ダウンロード」をクリック。
    ![Webex Meetingsからのダウンロード](imgs/webex_meeting_dl_1.png)
    - そうでない場合は[Cisco Webexダウンロード](https://www.webex.com/ja/downloads.html)にアクセスして「Cisco Webex Meetings」をダウンロード
1. 手元のPC上でインストーラを開いて，指示に従ってインストール。


<h2 id="prepare_class">講義の前に行う準備</h2>

<h3 id="schedule_class">講義のスケジュール</h3>

Webexの講義のスケジュールはWebサイト経由で行います。

1. まず，Webex Meetingsのサイトにログインします。ログイン画面へのアクセスは以下の2通りです。
    - 直接，[Webex Meetingsのログイン画面](https://www.webex.co.jp/go/jp_host-meeting)にアクセスします。
    - [Webexのサイト](https://www.webex.com)にアクセス。画面上の「ホスト」をクリックします。

![Webex Meetingsへのログイン画面](imgs/webex_signin.png)

1. Webex Meetingsのホーム画面から「スケジュールする」をクリックします。
![Webex Meetingsのホーム画面](imgs/webex_class_schedule_1.png)

1. ミーティングのスケジュール画面で以下の情報を入力し，スケジュールします。なお，詳細設定を含め，全ての設定はスケジュールを作成後に変更可能です。
    - ミーティングの議題：講義名で良いと思います。
    - ミーティングバスワード：ランダムなものが生成されます。自分で設定することも出来ますが，セキュリティ上あまりお薦めしません。
    - 日時：ミーティングの開始時間と継続時間を設定します。授業時間は105分（1時間45分）ですが，前後に5分程度余裕を持たせて2時間ぐらいでどうでしょう。
    - タイムゾーン：なぜかクアラルンプール（UTC+8）になっていることが多いので「大阪，札幌，東京（UTC+9）」に変更します。
    - 繰り返し：これを使うと毎週同じ時間のミーティングが設定できます。毎週の講義は繰り返しで予定すると良いかもしれません。
    - 出席者：空で結構です。
![講義のスケジュール設定](imgs/webex_class_schedule_2.png)

1. 必要に応じて「詳細設定」を行います。詳細設定で特に注意したいのは以下の点です。
    - 主催者より先に参加：出席者（学生）は主催者（教員）がミーティング（授業）を開始するよりも，設定された時間だけ早めに接続して待つことができます（デフォルトでは5分前に接続できる）
    - 出席者の権限：出席者同士のプライベートなチャットを許可するかどうかは考慮の必要があるかと思います。

1. ミーティングがスケジュールされると，Webex Meetingsのホーム画面下に「開催予定のミーティング」として（画像上），また，Cisco Webex Meetingsのアプリケーション起動画面の「今後のミーティング」（画像下）に表示されます。

![Webex Meetingsホーム画面でのスケジュール表示](imgs/webex_schedule_view_web.png)

![Webex Meetingsアプリ画面でのスケジュール表示](imgs/webex_schedule_view_app.png)

### 講義URLの取得

### BEEF等への講義URLの掲載による講義の周知
