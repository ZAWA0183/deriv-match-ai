Deriv Match AI V1 — iPhone Web App

このV1はDIGITMATCH専用の研究・Paper Tradingアプリです。
実際の注文は行いません。

機能:
- Deriv公開WebSocketからリアルタイムTick取得
- 直近200TickのDigit分析
- Digit 0〜9の頻度
- 遷移分析
- 2桁/3桁コンテキスト分析
- Confidence / Separation
- SKIP判定
- Paper Trading
- 勝敗、勝率、現在/最大連敗
- CSVログ保存
- Symbol切替

iPhoneでの推奨使用方法:
1. このフォルダをHTTPSで公開します。
2. iPhoneのSafariで公開URLを開きます。
3. 共有 → ホーム画面に追加、でアプリ風に起動できます。
4. STARTを押すと公開Tickを取得します。
5. WAIT → SKIP / PAPER ENTRY が表示されます。
6. 実注文はV1にはありません。

最も簡単な公開方法:
- GitHub PagesなどのHTTPS静的ホスティングに index.html と manifest.json をアップロード。
- 公開URLをSafariで開く。

注意:
- Derivの公開WebSocketは市場データ用で、口座取引はできません。
- 実注文を追加する場合は認証済みDemo/Real WebSocketが必要です。
- Confidenceは勝率保証ではありません。
- マーチンゲールは実装していません。
