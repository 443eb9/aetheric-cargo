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
    "message": "留言，或者是简介，也可以是一个颜文字，总之随便写（",
    "dialog": [
        {
            "expression": "https://link.to.your/persona/hi",
            "content": "具体留言内容",
            "customHtml": "<p>自定义 html</p>"
        },
        {
            "expression": "https://link.to.your/persona/smile",
            "content": "具体留言内容"
        }
    ]
}
```

其中 `dialog` 可选，如果你填了，那用户就有某种方式触发你的框。`customHtml` 允许你编写一些 html 代码，会被注入至对话框中成为 DOM 元素。

当然，如果你写了 `customHtml` ，`content` 就可以留空了（填空字符串 `""` 就行，但是请不要不填）。
