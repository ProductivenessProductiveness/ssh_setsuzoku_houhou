# awsのサーバーに他のパソコンから接続する方法
1. macのターミナルを開く
2. カレントディレクトリをpemファイルがある場所に移動
3. chmod 400 設定した名前.pem このコマンドを使用する（SSH が機能するには、キーが公開されていないことが必要）
4. パブリック DNS を使用しインスタンスに接続します。
5. 例　ssh -i "設定した名前.pem" ec2-user@ec2-54-160-145-160.compute-1.amazonaws.com






