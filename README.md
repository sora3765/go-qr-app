# go-qr-gen-app

- URLからQRコードを生成する
- サンプルコード
 `$ qrg -o ./qr-image.png -w 500 -d 500 https://www.google.com/`
 `$ go run main.go -o ./qr-image.png -w 500 -d 500 https://www.google.com/`
 
 - option
   - `-o` ・・・出力先ディレクトリ＆名前指定
   - `-w -d`・・・出力サイズ指定
