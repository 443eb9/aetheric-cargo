# Aetheric Cargo 以太集装箱

一个神秘的容器，承载着...好了我编不下去了，以后再编（

总之这里是给 [晨暮群岛](https://github.com/443eb9/crepuscular-archipelago) ，也就是 [我的个人网站](https://443eb9.dev) 存储一些可以被其他用户修改数据的地方。你可以通过提交 PR 的方式来修改这些数据。

## 分区 Partitions

不同分区存储不同数据（废话

除非特别标注，你可以通过PR修改任意分区的数据。

### `friends.json`

友链交换区~

格式：

```json
{
    "avatar": "https://link.to.your/avatar.webp",
    "name": "Your site",
    "link": "https://example.your.site",
    "message": "留言，或者是简介，也可以是一个颜文字，总之随便写（",
    "background": "https://link.to.a/nice/image.webp",
    "dialog": [
        {
            "expression": "https://link.to.your/persona/hi",
            "content": "具体留言内容",
        },
        {
            "expression": "https://link.to.your/persona/smile",
            "content": "具体留言内容"
        }
    ]
}
```

> `background` 可选，如果你填了，那就会在友链界面使用该图作为背景。 **请注意 *尽量避免* 使用 AI 生成的图像。**

> `dialog` 可选，如果你填了，那用户就有 *某种方式* 触发你的框。
