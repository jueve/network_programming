# packet-capture

## 参考元
[teru01/packet-capture](https://github.com/teru01/packet-capture)

## 実行
```
$ ip addr
1: interface_name_01: (snip)
2: interface_name_02: (snip)
3: interface_name_03: (snip)
```

```
$ cargo build
$ sudo ./target/debug/packet-capture [interface_name]
```