AWS CLF Study Lab v4 - 難易度改善版

今回の改善
==========
「問題文の単語を見ればサービス名が分かる」問題を重点的に修正しました。

例:
旧:
  多数のIoTデバイスを...IoTソリューションを...
  → AWS IoT Core が名前だけで選べる

新:
  工場にある数万台のセンサーや小型機器から、認証された接続で
  テレメトリをクラウドへ送信し、クラウド側から各機器へメッセージも届けたい。
  → 要件を理解しないと AWS IoT Core を選べない

同様に見直した代表例:
- CodeBuild: 問題文から「ビルド処理」という答え直結語を削除
- CodePipeline: 「パイプライン」を削除
- FSx for Windows File Server: 「Windowsファイル共有」をSMB/AD要件へ変更
- DocumentDB: 「ドキュメントDB」を削除しMongoDB互換要件へ
- AWS Backup: 「バックアップを一元管理」を保護ポリシー/保持期間/復旧ポイントへ
- ACM: 「証明書」をX.509/TLS要件へ
- Service Catalog: 「カタログ化」を承認済み標準構成のセルフサービス提供へ
- License Manager: 「ライセンス」をBYOL/契約上限管理へ
- SCT: 「スキーマ変換」を異種DBのストアドプロシージャ等の書き換え要件へ
- AppStream: 「ストリーミング」を削除
- Secure Browser: 「ブラウザ」を削除
- Organizations: 「組織として」を削除
- Tape Gateway / S3 Versioning なども名称直結表現を調整

修正問題数: 20
名称ヒント監査の残件: 0

注意:
監査は「答えの名前がそのまま問題文に見えてしまう」ことを検出するものです。
サービスの本質的な要件（例: SFTP、MongoDB互換、TLS、SMB）は、
知識として判断するために意図的に残しています。
