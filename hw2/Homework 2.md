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

![](D:\AllProject\hw4InternLM\hw2\images\图文写作1.png)

![](D:\AllProject\hw4InternLM\hw2\images\图文写作2.png)

![](D:\AllProject\hw4InternLM\hw2\images\图文写作3.png)

![](D:\AllProject\hw4InternLM\hw2\images\图文写作4.png)

**图文创作 日志**

- 文本分割、语义理解

![](D:\AllProject\hw4InternLM\hw2\images\图文seg.png)

- 判断图像插入位置、生成图片标题

![](D:\AllProject\hw4InternLM\hw2\images\图文 生成图像标题.png)

- 图片下载、为每个图片插入位置选择最合适的图片

![](D:\AllProject\hw4InternLM\hw2\images\图文 下载选择图片.png)

**视觉问答**

![](D:\AllProject\hw4InternLM\hw2\images\视觉问答.png)

5. 完成 `Lagent` 工具调用 `数据分析` Demo 部署（需截图）

![](https://github.com/libingixn/hw4InternLM/blob/main/hw2/images/Lagnet1.png)

![](https://github.com/libingixn/hw4InternLM/blob/main/hw2/images/Lagent2.png)
