# 介绍

本工具基于protobuf3.0的c#版，点击build就可以使用，节省你打开CMD的时间，另外为了保证工作效率提高，你还可以编辑.bat文件，以下是修改建议

```bat
protoc --csharp_out=./Target-CSharpFile ProtoFile/test.proto
copy "./Target-CSharpFile/test.cs" "客户端目标目录"
copy "./Target-CSharpFile/test.cs" "服务器目标目录"
pause
```
