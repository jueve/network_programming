# socket-programming

## 参考元
[teru01/socket-programming](https://github.com/teru01/socket-programming)


## tcp_server + nc

tcp_server
```
$ cargo run tcp server 127.0.0.1:33333
    Finished dev [unoptimized + debuginfo] target(s) in 0.94s
     Running `target/debug/socket-programming tcp server '127.0.0.1:33333'`
```

nc
```
$ nc 127.0.0.1 33333
hello
hello
```

## tcp_server + tcp_client

tcp_server
```
$ cargo run tcp server 127.0.0.1:33333
    Finished dev [unoptimized + debuginfo] target(s) in 0.01s
     Running `target/debug/socket-programming tcp server '127.0.0.1:33333'`
```

tcp_client
```
$ cargo run tcp client 127.0.0.1:33333
    Finished dev [unoptimized + debuginfo] target(s) in 0.01s
     Running `target/debug/socket-programming tcp client '127.0.0.1:33333'`
hello
hello
```

## udp_server + nc

udp_server
```
$ cargo run udp server 127.0.0.1:33333
    Finished dev [unoptimized + debuginfo] target(s) in 0.01s
     Running `target/debug/socket-programming udp server '127.0.0.1:33333'`
```

nc
```
$ nc -u 127.0.0.1 33333
hello
hello
```

## udp_server + udp_client

udp_server
```
$ cargo run udp server 127.0.0.1:33333
    Finished dev [unoptimized + debuginfo] target(s) in 0.01s
     Running `target/debug/socket-programming udp server '127.0.0.1:33333'`

```

udp_client
```
$ cargo run udp client 127.0.0.1:33333
    Finished dev [unoptimized + debuginfo] target(s) in 0.01s
     Running `target/debug/socket-programming udp client '127.0.0.1:33333'`
hello
hello

```