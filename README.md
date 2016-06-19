# edison-tsl2561

弊社Henryボード用のリポジトリです。  
Intel様のupmからTSL2561関係だけ抜き出しました。  
Henryボードは拡張スルーホールのi2cのバス接続は6へ接続しているのでサンプルやヘッダファイルの調整もしてあります。  
なお、pythonのSwigに問題があるようなので使えません。そのためにコンパイルの設定はOFFにしています。  
手順は下記の通りです。  
`git clone https://github.com/MotionCTL/edison-tsl2561.git`  
`cd edison-tsl2561`  
`cmake .`  
`make`  
`make install`  