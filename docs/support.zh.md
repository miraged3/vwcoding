# 项目支持与贡献

## 支持项目

如果您喜欢这个项目并希望它持续发展，欢迎通过以下方式支持我们：

<div class="grid cards" markdown>

-   :fontawesome-solid-money-bill:{ .lg .middle } __俄罗斯银行卡转账__

    ---
    使用银行卡或 Yandex 钱包以卢布进行转账

    [支持我们 :fontawesome-solid-paper-plane:](https://yoomoney.ru/to/4100110582992748/100){ .md-button }

-   :fontawesome-brands-btc:{ .lg .middle } __加密货币__

    ---
    ![BTC wallet](./images/btc.png){ width="100" align=left }

    比特币钱包：`1BKR5d91YUic3aqwc6nTGTMLkGBBrZkkcj`

</div>

## 如何贡献内容

### 项目结构

- 文档目录：`/docs`
- 图片目录：`/docs/images`
- 固件目录：`/docs/firmwares`
- 车辆参数目录：`/docs/parameters`
- 模板目录（例如工具页面所用模板）：`/overrides/pages`
- 主配置文件：`mkdocs.yml`

### 添加新的编码指南

本站基于 Markdown 构建，您可以使用以下模板撰写新的编码说明：

```
    # 页面标题
    ### 编码/适配名称

    !!! tip ""
        这里填写用途或附加说明

    !!! warning ""
        这里填写警告或注意事项

    ``` yaml title="登录-密码: XXXXX（如适用）"
    模块 XX → 适配/编码：
    字节 XX – 位 X（位名称）：激活
    部分名称：
    - 参数名称：激活
    → 应用
    ```

    ??? note "折叠列表标题"
        网站上默认折叠的信息可以放在这里
```

在页面中插入图片：
```![Screenshot](../images/***/imageName.png)```

在页面中插入文件：
```[(文件名称)](文件链接)```

### 添加本地化 {#adding-localizations}

如果您想帮助我们翻译站点内容，请按照以下步骤添加新的语言版本：

1. 在 `/docs` 目录中复制目标文件，并在文件名后添加语言后缀。例如：`drive.md` → `drive.zh.md`
2. 将文本翻译为目标语言。
3. 编辑 `mkdocs.yml`，在 `nav_translations` 中为导航项提供相应的翻译，确保界面中所有链接名称都正确。
4. 提交包含本地化内容的 Pull Request。
