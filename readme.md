# setproxy

  Windowsのプロキシ設定をONまたはOFFにするだけのものです。 Internet Explorer のインターネットプションを開いてプロキシを使用する項目のチェックを入れたり外したりする操作を、直接レジストリを操作することによって実現しています。

## 作った経緯

  実習で学内ネットワークに接続する際にプロキシサーバーを経由する設定になっている学生さんが、自宅でPCをインターネットに接続する際にプロキシ設定を解除したり、また学校に持っていてプロキシを有効にしたりする作業を簡単に行えるようにするために作りました。

  もちろん学校だけでなく会社でも使えますが、最近の会社はセキュリティポリシーで私用PCを持ち込んだり、業務用PCを持ち帰ったりすることを認めていないところが多いので会社で活躍することは少ないと思っています。

## 使い方

  index.html を開いてメニューからプロキシ有効またま解除を選ぶだけです。最近のブラウザではセキュリテイ上ブラウザからこのようなシステム設定を変更することが許可されていないことがほとんどなので、動作しなければ同梱の bat ファイルを実行してください。

  bat ファイルの場合は、 enableproxy.bat でプロキシ有効、 disableproxy.bat でプロキシ無効になります。フォルダ内に同梱ファイル以外のファイルがなければ、コマンドプロンプトで頭文字の ｄ または e をタイプしたあとで tab キーを押すとファイル名が補完されます。

  プロキシサーバーのアドレスやポートは、あらかじめ設定しておいてください。一度設定すればこのコマンドでプロキシを解除してもアドレスやポートは覚えているので、再度プロキシを有効化した段階で元に戻ります。
