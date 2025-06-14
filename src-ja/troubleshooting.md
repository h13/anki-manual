# トラブルシューティング

Ankiで問題が発生した場合は、次の手順を順番に試してください：

### 1. Ankiを再起動する

Ankiを閉じてから、再度起動してください。

エラーメッセージのためにAnkiを閉じることができない場合は、タスクマネージャーを使用してAnkiを終了するか、コンピュータを再起動してください。Ankiは定期的に保存するため、ほとんどの状況で数分以上の作業を失うことはありません。

問題が再発しない場合は、以下の手順をスキップできます。

### 2. アドオンを確認する

Ankiを閉じてから、Ankiの起動時に<kbd>Shift</kbd>キーを押したままにして、セーフモードで開いてください。画面上のメッセージがAnkiがセーフモードで起動したことを通知するまで、<kbd>Shift</kbd>を押し続けてください。

問題が解消した場合、アドオンが問題を引き起こしていることを示しています。
必要のないアドオンを削除し、他の半分を無効にしてください。問題が続く場合は、もう半分を試してください。どのアドオンが問題を引き起こしているかがわかるまで、このプロセスを繰り返してください。その後、「デバッグ情報をコピー」ボタンを使用して、その情報をレポートに貼り付けて、アドオンの作者に問題を報告してください。

### 3. Ankiのバージョンを確認する

使用しているバージョンは、**ヘルプ → Ankiについて**または**Anki → Ankiについて**メニューで確認できます。使用しているバージョンが<https://apps.ankiweb.net>で公開されている最新バージョンでない場合は、Ankiを閉じて最新バージョンをインストールし、Ankiを再度起動して問題が解消したかどうかを確認してください。

Linuxを使用している場合は、ディストリビューションが[壊れたバージョン](platform/linux/distro-packages.md)を配布することが多いため、Ankiウェブサイトのパッケージバージョンを使用してエラーを再現できることを確認してください。

### 4. データベースを確認する

Ankiを再起動した後、**ツール → データベースをチェック**メニューアイテムを試して、コレクションに問題がないことを確認してください。

### 5. コンピュータを再起動する

コンピュータを再起動することが役立つ場合があります。

### 6. ビデオドライバーを変更する

クラッシュや表示の問題は、ビデオドライバーが原因である可能性があります。別のビデオドライバーに変更すると役立つ場合があります。すべてのドライバーオプションを試し、各変更後にAnkiを再起動してください。

Ankiバージョン23.10以降を使用している場合、最も簡単な方法は**ツール → 設定**（Macの場合は**Anki → 設定**）を開き、ドロップダウンメニューからドライバーを変更することです。

古いAnkiバージョンを使用している場合、または何らかの理由で設定にアクセスできない場合は、代わりにコマンドラインの指示を使用して、gldriverファイルを手動で変更できます：

- [Windows](https://docs.ankiweb.net/platform/windows/display-issues.html)
- [Mac](https://docs.ankiweb.net/platform/mac/display-issues.html)
- [Linux](https://docs.ankiweb.net/platform/linux/display-issues.html)

### 7. ウィンドウサイズをリセットする

Ankiの起動直後に設定画面の**ウィンドウサイズをリセット**ボタンを押すことが役立つ場合があります。

### 8. 問題が解決しない場合

最新のAnkiバージョンを使用していることを確認し、Shiftキーを押しながらAnkiを起動してもエラーが発生する場合は、[問題を報告](./getting-help.md)してください。投稿には次に受け取るエラーを含めてください。