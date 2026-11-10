# zhoufengczkx-notes

gRPC · Python · Linux

给自己省点事的小工具

## 用法

```bash
cat data.txt | go run main.go
```

输出：

```
   3  error: timeout
   1  warn: retry
---
2 unique / 4 lines
```

## 为什么写

现有的工具都太重，就想要个能管道拼接的小东西。

## 待办

- [ ] 支持从文件参数读入
- [ ] 加个输出格式选项
- [ ] 补点测试

## 安装

```bash
git clone https://github.com/USER/zhoufengczkx-notes.git
cd zhoufengczkx-notes
go build ./...
```

## License

MIT
