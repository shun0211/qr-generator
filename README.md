# QR Generator
## Usage
**Command**
```bash
$ go run main.go -o 'hoge.png' -w 200 -d 200 https://google.com
```
oオプション: ファイル名を指定  
wオプション: 幅を指定  
dオプション: 高さを指定  

**Server Start**
```bash
$ go run server/main.go
```
ブラウザでアクセス  
http://localhost:8080/generate?url=google.com&width=500&height=500

or

ファイルを開く  
(ファイルまでのディレクトリ)/qr-generator/index.html

## License
https://www.techpit.jp/courses/220
