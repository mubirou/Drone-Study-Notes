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
    * **旧メニュー表示**：[shift]+[~]（Console表示）→ "showlegacymenu"と入力
    * **視点固定**：[Z]（Autozoom → Manual → Keep Ground in View）
    * **画面上のプロポ表示**：[Esc]-[Settings]-[Controller]-[Configure Cotroller]
    * **NavGuides表示**：[Esc]-[Settings]-[User Interface]-[Gadgets]-[NavGuides]-[NavGudes Gadget Enabled]-[Enabled]-[⚙]
        * Altitude (AGL)：地面と機体との距離（5ft≒1.5m / 11ft≒3.4m）
        * Graphics Frame Rate：現在の描画速度
        * 単位をメートルに変更：[Esc]-[Settings]-[Physics]-[Quality]-[Use Metric Units]-[Enabled]
    * **プロポのスティック設定**：[Esc]-[Settings]-[Controller]-[Configure Controller]-[Profile]-[Futaba]-[Edit]
        * Channel 1 - Aileron（エルロン）：[右]-[↔]
        * Channel 2 - Elevator（エレベーター）：[右]-[↕]（Reverse）
        * Channel 3 - Throttle（スロットル）：[左]-[↕]
        * Channel 4 - Rudder（ラダー）：[左]-[↔]
    * 同**キャリブレーション**：[Esc]-[Settings]-[Controller]-[Configure Controller]-[Profile]-[Futaba]-[Calibrate]
    * **ドローン機体**：[Select an Aircraft]-[Quadcopter X]
    * **太陽の角度**：[Esc]-[My RealFlight]-[Edit Current Airport]-[Properties]-[Sun Indnation (deg)]-[90]
    * **空港**（国家試験飛行経路）：
        1. [Esc]-[Help]-[Websites]-[Swap PAges]-[Categories]-[RealFlight Evolution]-[[Airports](https://forums.realflight.com/index.php?resources/categories/airports.184/&page=2)]
            * uav_license_test_line_2nd_AP
            * uav_license_test_eitght_2nd_AP
            * uav_license_test_square_2nd_AP
        1. [Esc]-[My RealFlight]-[Import]-[RealFlight Archive] から上記3つを選択
        1. [Esc]-[Free Play]-[Airport] から上記のいずれかを [Select]
    * **ATTIモード**
        * [Esc]-[Settings]-[User Interface]-[Gadgets]-[Flight Modes]-[Flight Modes Gadget Enabled]-[Enabled]-[ON]：フライトモードの表示
        * プロポ（T16IZS）の設定 ([参考動画](https://www.youtube.com/watch?v=5zdZzGGeB9w))
            1. [リンケージメニュー]-[ファンクションネーム]-[予備1]-[名称変更] で"フライトモード"に変更
            1. [リンケージメニュー]-[ファンクション]-[5 ジャイロ]-[2/2] にある"フライトモード"に変更
            1. [リンケージメニュー]-[ファンクション]-[5 フライモード]-[--] を選択し [SA] を割当てる
        * Real Flight の設定
            1. [Simulation]-[Select Controller]
        * ATTIモード可能機体
            * Explorer 580 (自作機風:４ローター)
            * Hexacopter 780 (ヘキサコプター:６ローター)
            * Octcopter 1000 (オクトコプター:８ローター)
            * Quadcopter X (クワッドコプター:４ローター)
            * Tricopter 900 (トライコプター:３ローター)
            * X8 Quadcopter 1260 (クワッドコプター:４ローター×２)
        * ATTIモード可能機体 (Mode設定が必要：[参考動画](https://www.youtube.com/watch?v=Igc1PsXv0pc))
            * Heli-Max FORM500
            * Hubsan X4 Pro
            * Hubsan X4 Pro (Prop Guards)
            * Scorpion Sky Strider 280 (10 Degree Arm Angle)：レーシングドローン
            * Scorpion Sky Strider 280 (5 Degree Arm Angle)：レーシングドローン
            * Tempest 250
            * Tempest 250 (Angled Camera)
            * Tempest 280
            * Tricopter 900 (Manual Modes)
    * **風＆乱気流**
        1. 突風時の風速の増加割合 (0～100％)：[Esc]-[Settings]-[Wind]-[<ruby>Wind Gust<rt>ウインド･ガスト</rt></ruby>]-[100％]
        1. 短期的な乱気流 (0～200％)：[Esc]-[Settings]-[Wind]-[<ruby>Turbulence<rt>タービュランス</rt></ruby>]-[200％]
        1. 不規則性：[Esc]-[Settings]-[Wind]-[<ruby>Thermals<rt>サーマルズ</rt></ruby>]-[Simple→Dynamic]
        1. 長期的な乱気流 (0～100％)：[Esc]-[Settings]-[Wind]-[<ruby>Wind Variation<rt>ウインド･バレーション</rt></ruby>]-[100％]
        1. 風向きの初期値：[Esc]-[Free Play]-[Environment]-[Wind Direction]-[130deg] ("Home"or"End"キーで調整)
        1. 風速：[Esc]-[Free Play]-[Environment]-[Wind Speed]-[0MPH] ("PgUp"or"PgOn"キーで調整)
            * 1 MPH ≒ 0.45 m/s
            * 2 MPH ≒ 0.89 m/s
            * 3 MPH ≒ 1.34 m/s
            * 4 MPH ≒ 1.79 m/s
            * 5 MPH ≒ 2.24 m/s
            * 6 MPH ≒ 2.68 m/s
            * 7 MPH ≒ 3.13 m/s
            * 8 MPH ≒ 3.60 m/s
            * 9 MPH ≒ 4.02 m/s
        1. 設定保存：[Esc]-[Free Play]-[Save Scenario]-["Save As Default Scenario"→任意]
    * **カメラ位置**
        * FPVモード：F4
        * 操縦者：F1
    * **AirPort**
        * [uav_license_test_square_2nd_AP](https://forums.realflight.com/index.php?resources/uav_license_test_square_2nd_ap.29950/)：高度変化を伴うスクエア飛行用
        * [uav_license_test_eitght_2nd_AP](https://forums.realflight.com/index.php?resources/uav_license_test_eight_2nd_ap.29951/)：緊急着陸を伴う８の字飛行･ピルエットホバリング用
        * Practice Feild：屋内[アメフト](https://lawyernishimura.com/index.php?QBlog-20171025-1)用 (約110x49m)
        * Athletic Club：多目的体育館 ([バスケ](https://spojoba.com/articles/794)･[バレーボール](https://www.jti.co.jp/sports/thunders/game/guide/03/index.html)･[バドミントン](https://badminton-rule.com/sup1.html)用)

### 練習方法

* 共通設定
    * [<ruby>Wind Gust<rt>ウインド･ガスト</rt></ruby>] (突風時の風速の増加割合)：100％
    * [<ruby>Turbulence<rt>タービュランス</rt></ruby>] (短期的な乱気流)：200％
    * [<ruby>Thermals<rt>サーマルズ</rt></ruby>] (不規則性)：Dynamic
    * [<ruby>Wind Variation<rt>ウインド･バレーション</rt></ruby>] (長期的な乱気流)：100％

#### ホバリング訓練
    * 各種設定
        * 機体：[<ruby>Scorpion Sky Strider<rt>スコーピオン･スカイ･ストライダー</rt></ruby> 280](https://www.polaris-export.com/news/tech/20150912.html) (FPVレース専用)  
        アングルアームクランプ5度
         * 飛行モード：Altitude Hold (ATTIモード)
        * 会場：[uav_license_test_eitght_2nd_AP](https://forums.realflight.com/index.php?resources/uav_license_test_eight_2nd_ap.29951/)：国家試験 (８の字飛行)
        * 風速：10 MPH ≒ 4.5 m/s (約0～9m/s)
    * 練習方法
        * コート中央 (6.5m先) の円内 (半径1m) でホバリング
        * ケツホバ → 1時半 → 3時 → 4時半 → 6時 → 7時半 → 9時 → 10時半

#### スクエア飛行 (機種方向固定) 訓練
    * 各種設定
        * 機体：[<ruby>Hubsan<rt>ハブサン</rt></ruby> X4 Pro](https://hitecrcd.co.jp/products/x4pro/) ([Prop Guards](https://hitecrcd.co.jp/products/h109s-48/))
        * 飛行モード：Altitude Hold (ATTIモード)
        * 会場：[uav_license_test_square_2nd_AP](https://forums.realflight.com/index.php?resources/uav_license_test_square_2nd_ap.29950/)：国家試験 (スクエア飛行)
        * 風速：0～3 MPH ≒ 1.34 m/s (約0～2.7m/s)
    * 練習方法
        * 6m先からある経路 (赤色破線13×5m) を飛行
        * 機種方向固定で A地点 → B地点 → C地点 → D地点 → E地点 → A地点
        * ケツホバ → 1時半 → 3時 → 4時半 → 6時 → 7時半 → 9時 → 10時半

#### ８の字飛行 (機種方向固定) 訓練
    * 各種設定
        * 機体：[<ruby>Hubsan<rt>ハブサン</rt></ruby> X4 Pro](https://hitecrcd.co.jp/products/x4pro/) ([Prop Guards](https://hitecrcd.co.jp/products/h109s-48/))
        * 飛行モード：Altitude Hold (ATTIモード)
        * 会場：[uav_license_test_eitght_2nd_AP](https://forums.realflight.com/index.php?resources/uav_license_test_eight_2nd_ap.29951/)：国家試験 (８の字飛行)
        * 風速：0～3 MPH ≒ 1.34 m/s (約0～2.7m/s)
    * 練習方法
        * 4m先からある経路 (直径5m×2個の赤色破線) を飛行
        * ケツホバ → 1時半 → 3時 → 4時半 → 6時 → 7時半 → 9時 → 10時半

© 2024 夢寐郎  
