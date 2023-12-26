# init settings windows

- リカバリーディスクの作成（32GB以上のUSBを準備）
- ファイルエクスプローラーの拡張子の表示
- スリープモード
- 電源ボタンに休止状態を追加
	- コンパネ->右下の電源オプション->左上の電源ボタンの動作を選択する->現在利用可能ではない設定を変更する->休止状態を選択して変更の保存
- onedriveとの同期を停止（タスクバー右下の雲マーク右クリック->設定->バックアップ->バックアップを管理->3つのディレクトリに対しバックアップを停止）
- chocolateyのinstall
	- [chovolateyの公式サイト](https://chocolatey.org/install)にあるインストールコマンドをpower shellの管理者画面で実行
- power shellの管理者画面で下記を実行
	- `install_myLib.bat`
- グラボのドライバをインストール
	- [公式サイト](https://www.nvidia.co.jp/Download/index.aspx?lang=jp)からドライバをダウンロード
	- インストールオプションはカスタム
	- 下記にチェックを付け、クリーンインストールの実行にチェックを付けてインストール
		- グラフィックスドライバー
		- HDオーディオドライバー
		- PhysXシステムソフトウェア
	- nvidia コントロールパネル->3D設定の管理
		- 垂直同期->オフ
		- 電源管理モード->パフォーマンス最大化を優先
- vscodeのエクステンション、設定ファイルのsync
- wsl2のインストール

## 参考
https://chimolog.co/bto-gaming-pc-settings/
