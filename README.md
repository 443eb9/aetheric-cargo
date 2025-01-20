# Aetheric Cargo 以太集装箱

一个神秘的容器，承载着...好了我编不下去了，以后再编（

总之这里是给[晨暮群岛](https://github.com/443eb9/crepuscular-archipelago)，也就是[我的个人网站](https://443eb9.dev)存储一些可以被其他用户修改数据的地方。你可以通过提交 PR 的方式来修改这些数据。

## 分区 Partitions

不同分区存储不同数据（废话

除非特别标注，你可以通过PR修改任意分区的数据。

### `friends.json`

友链交换区~

格式：

```json
{
    "avatar": "https://link.to.your/avatar.format",
    "name": "Your site",
    "link": "https://example.your.site",
    "message": "留言，或者是简介，也可以是一个颜文字，总之随便写（"
}
```

其中，`message` 还可以是

```json
{
    // ...
    "message": [
        {
            "expression": "https://link.to.your/persona/hi",
            "content": "具体留言内容"
        },
        {
            "expression": "https://link.to.your/persona/smile",
            "content": "具体留言内容"
        }
    ]
}
```

如果你选用了这种形式，那么在网站上，别人可以通过点击你头像来触发类似于对话的操作。
