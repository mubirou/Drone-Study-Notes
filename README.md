# Drone-Study-Notes
ドローン（回転翼航空機･マルチローター）関連の勉強･研究メモ

## REAL FLIGHT

* 用意するもの
    * [REAL FLIGHT EVOLUTION + WSC-1付](https://www.rc.futaba.co.jp/products/detail/I00000336)
    * 空用送信機（[Futaba T16IZ Super ヘリ用 送信機のみ](https://www.rc.futaba.co.jp/products/detail/I00000332)）
    * Windows PC（[推奨スペック](https://www.meta.com/ja-jp/help/quest/articles/headsets-and-accessories/oculus-link/requirements-quest-link/)）
    * [Meta Quest 3](https://www.meta.com/jp/quest/quest-3/)
    * [Meta Quest Linkケーブル](https://www.meta.com/jp/quest/accessories/link-cable/)

1. 送信機（[T16IZ Super](https://www.rc.futaba.co.jp/products/detail/I00000332)）の設定
    1. [取扱説明書](https://www.rc.futaba.co.jp/downloads/W8C1674N2302020928toqx6.pdf?mode=view)のダウンロード
    1. 「[マルチコプター](https://drone-navigator.com/multicopter)」に変更（取説73-74頁）
        * [リンケージメニュー]-[モデルタイプ]-[マルチコプター]
    1. 「[モード2](https://ds-chiba.jp/2023/06/08/04/)」に変更（取説30頁）
        * [システムメニュー]-[ハードウェア設定]-[スティックモード]-[モード2]
    1. 「[フルスプリング](https://www.rc.futaba.co.jp/support/faq/?cat=98)」仕様に変更（取説30頁）
    1. 「[S-FHSS](https://www.rc.futaba.co.jp/support/tips/detail/31)」に変更（取説81-82頁）
        * [リンケージメニュー]-[システムタイプ]-[S-FHSS]
    1. 設定の保存
        * [モデルセレクト]-[新規]（任意で [名称変更] をします）
    1. 動作確認
        * [リンケージメニュー]-[サーボモニター]

1. 送信機（[T16IZ Super](https://www.rc.futaba.co.jp/products/detail/I00000332)）と PC をワイヤレス接続
    1. 付属の [WSC-1](https://www.rc.futaba.co.jp/products/detail/I00000274) をPCのUSBポートに接続
    1. 送信機の電源を入れてパソコンに近付ける（20cm以内）
    1. [WSC-1](https://www.rc.futaba.co.jp/products/detail/I00000274) と PC を「[リンク操作](https://www.rc.futaba.co.jp/downloads/shop/WCI00000274N210726142330epq.pdf?mode=view)」する（緑点灯でリンク操作成功）

1. [REAL FLIGHT EVOLUTION](https://www.rc.futaba.co.jp/products/detail/I00000336) のインストール
    1. [STEAM](https://store.steampowered.com/about/) をインストール（登録アカウントが必要）
    1. STEAM を起動
    1. [ゲーム]-[Steamウォレットコードを有効化する] で製品コードを入力
    1. [ライブラリ]-[RealFlight Evolution]-[インストール]

1. 実行
    1. STEAM を起動
    1. [ライブラリ]-[RealFlight Evolution]-[プレイ]-[FLY]
        * [RealFlght Evolutionをプレイ]：平面ディスプレイで実行（各種設定時）
        * [Oculus VRモードでRealFlight Evolutionを起動]：360°VR空間で実行


1. 各種設定
    * **画面上のプロポ表示**：[Esc]-[Settings]-[Controller]-[Configure Cotroller]
    * プロポのスティック設定：[Esc]-[Settings]-[Controller]-[Configure Controller]-[Profile]-[Futaba]-[Edit]
        * Channel 1 - Aileron（エルロン）：[右]-[↔]
        * Channel 2 - Elevator（エレベーター）：[右]-[↕]（Reverse）
        * Channel 3 - Throttle（スロットル）：[左]-[↕]
        * Channel 4 - Rudder（ラダー）：[左]-[↔]
    * 同キャリブレーション：[Esc]-[Settings]-[Controller]-[Configure Controller]-[Profile]-[Futaba]-[Calibrate]
    * ドローン機体：[Select an Aircraft]-[Quadcopter X]
    * 太陽の角度：[Esc]-[My RealFlight]-[Edit Current Airport]-[Properties]-[Sun Indnation (deg)]-[90]
    * 空港（国家試験飛行経路）：
        1. [Esc]-[Help]-[Websites]-[Swap PAges]-[Categories]-[RealFlight Evolution]-[[Airports](https://forums.realflight.com/index.php?resources/categories/airports.184/&page=2)]
            * uav_license_test_line_2nd_AP
            * uav_license_test_eitght_2nd_AP
            * uav_license_test_square_2nd_AP
        1. [Esc]-[My RealFlight]-[Import]-[RealFlight Archive] から上記3つを選択
        1. [Esc]-[Free Play]-[Airport] から上記のいずれかを [Select]
    * ATTIモード
        * [Esc]-[Settings]-[User Interface]-[Gadgets]-[Flight Modes]-[Flight Modes Gadget Enabled]-[Enabled]-[ON]：フライトモードの表示
        * プロポ（T16IZS）の設定（[参考動画](https://www.youtube.com/watch?v=5zdZzGGeB9w)）
            1. [リンケージメニュー]-[ファンクションネーム]-[予備1]-[名称変更] で"予備1"→"MODE"に変更
            1. [リンケージメニュー]-[ファンクション]-[5 ジャイロ]-[2/2]-[MODE] で "ジャイロ"→"MODE"に変更
            1. 引き続き [MODE]-[コントロール]-[--]-[SA]
    * 乱気流：

### この項目は編集中です

1. 活用方法

    * [Esc]-[Settings]-[Wind]-[Wind Variation]-[20%]

    * [リンケージメニュー]-[トレーナー]-[動作] を [INH] → [ACT] に変更 👈たぶん不要

© 2024 夢寐郎  
