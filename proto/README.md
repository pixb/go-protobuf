# go-protobuf

golang使用protobuf的示例。

参考自己的笔记`protobuf_buf`

## 安装

在我的mac上执行：

```bash
brew install bufbuild/buf/buf
```

验证安装：

```bash
buf --version
```

## 初始化配置

这个示例放在`proto`文件夹中。

```bash
mkdir -p proto
cd proto
```

```bash
buf config init
```

将生成`buf.yaml`的配置文件。

## 创建protobuf文件

我这里以Memos项目`store/activity`作为示例。

创建`buf.gen.yaml`生成目标语言配置.

执行生成命令。

```bash
buf generate
```

