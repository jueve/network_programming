# port-scanner

## 参考元
[teru01/port-scanner](https://github.com/teru01/port-scanner)

## 実行
`.env`ファイルを作る。
```
MY_IPADDR=192.168.11.3 
MY_PORT=33333
MAXIMUM_PORT_NUM=1024
```

以下のコマンドを叩く。
```
$ cargo build
$ sudo ./target/debug/port-scanner [destination] [sS|sF|sN|sX]
```