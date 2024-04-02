## Homework 2

教程： https://github.com/InternLM/Tutorial/blob/camp2/helloworld/hello_world.md

作业： https://github.com/InternLM/Tutorial/blob/camp2/helloworld/homework.md

1. 使用 `InternLM2-Chat-1.8B` 模型生成 300 字的小故事（需截图）

   ![](https://github.com/libingixn/hw4InternLM/blob/main/hw2/images/img1.png)

2. 部署实战营优秀作品 `八戒-Chat-1.8B` 模型

   ![](https://github.com/libingixn/hw4InternLM/blob/main/hw2/images/bajie.png)

   ![](https://github.com/libingixn/hw4InternLM/blob/main/hw2/images/%E7%8C%AA%E7%8C%AAchat.png)

   从本地使用 ssh 连接 studio 端口时遇到permission denied问题：

   ![](https://github.com/libingixn/hw4InternLM/blob/main/hw2/images/perssion%20denied.png)

   通过在首页配置ssh key解决以上问题。

3. 熟悉 `huggingface` 下载功能，使用 `huggingface_hub` python 包，下载 `InternLM2-Chat-7B` 的 `config.json` 文件到本地（需截图下载过程）

![](https://github.com/libingixn/hw4InternLM/blob/main/hw2/images/load.png)

![](https://github.com/libingixn/hw4InternLM/blob/main/hw2/images/load_config.png)

![](https://github.com/libingixn/hw4InternLM/blob/main/hw2/images/load2.png)

4. 完成 `浦语·灵笔2` 的 `图文创作` 及 `视觉问答` 部署（需截图）

**图文创作 效果**

![](https://github.com/libingixn/hw4InternLM/blob/main/hw2/images/%E5%9B%BE%E6%96%87%E5%86%99%E4%BD%9C1.png)

![](https://github.com/libingixn/hw4InternLM/blob/main/hw2/images/%E5%9B%BE%E6%96%87%E5%86%99%E4%BD%9C2.png)

![](https://github.com/libingixn/hw4InternLM/blob/main/hw2/images/%E5%9B%BE%E6%96%87%E5%86%99%E4%BD%9C3.png)

![](https://github.com/libingixn/hw4InternLM/blob/main/hw2/images/%E5%9B%BE%E6%96%87%E5%86%99%E4%BD%9C4.png)

**图文创作 日志**

- 文本分割、语义理解

![](https://github.com/libingixn/hw4InternLM/blob/main/hw2/images/%E5%9B%BE%E6%96%87seg.png)

- 判断图像插入位置、生成图片标题

![](https://github.com/libingixn/hw4InternLM/blob/main/hw2/images/%E5%9B%BE%E6%96%87%20%E7%94%9F%E6%88%90%E5%9B%BE%E5%83%8F%E6%A0%87%E9%A2%98.png)

- 图片下载、为每个图片插入位置选择最合适的图片

![](https://github.com/libingixn/hw4InternLM/blob/main/hw2/images/%E5%9B%BE%E6%96%87%20%E4%B8%8B%E8%BD%BD%E9%80%89%E6%8B%A9%E5%9B%BE%E7%89%87.png)

**视觉问答**

![](https://github.com/libingixn/hw4InternLM/blob/main/hw2/images/%E8%A7%86%E8%A7%89%E9%97%AE%E7%AD%94.png)

5. 完成 `Lagent` 工具调用 `数据分析` Demo 部署（需截图）

![](https://github.com/libingixn/hw4InternLM/blob/main/hw2/images/Lagnet1.png)

![](https://github.com/libingixn/hw4InternLM/blob/main/hw2/images/Lagent2.png)
