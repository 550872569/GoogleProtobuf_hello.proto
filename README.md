# GoogleProtobuf_hello.proto
GoogleProtobuf_hello.proto 生成protobuf objc 文件
```
protoc --proto_path=src --objc_out=build/gen src/foo.proto src/bar/baz.proto

cd /Users/XXX/Desktop
1. 在桌面创建一个文件夹dir_pro
2.在dir_pro文件夹中创建一个 hello.proto 文件
3. cd /Users/XXX/Desktop
使用protoc 命令生成objc文件

protoc --proto_path=dir_pro --objc_out=dir_pro dir_pro/hello.proto

```
