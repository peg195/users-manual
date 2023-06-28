用户手册
库贝莱特用户手册

book.cuberite.org 有一个自动更新的手册版本，如果将新的提交推送到此存储库，则每小时更新一次。

开发者专区
本书的结构是每章的单独HTML片段。文件名描述节号和节的名称，用“ - ”分隔。

示例输入目录结构为：

/
|> 0 - Introduction/
|   |> 1 - Intro.html
|   |> 2 - Notes.html
|> 1 - Setting Up/
|   |> 1 - Downloading.html
|   |> 2 - Running.html
这个想法是生成器将文件组合成 2 个输出 - 一个独立的 HTML 页面，所有部分都集成了内部链接，另一个每个文件（或部分？）都是一个单独的页面。目前，生成器仅编译为单个页面，但计划为多个页面。

这是写作指南：

指向另一个部分的链接是自动生成的，如下所示 - 。{{Section Number - Text of Link}}

以下是用于特定目的的语义正确和样式化的 HTML 元素列表：

<p>对于段落
<h4>对于标题
<aside class="infobox">对于与内容切线相关的信息。
<aside class="warnbox">有关与内容相关的警告。
<figure class="codebox">对于带有嵌套和标记的代码示例。（可选）带有 for 标题。<pre><code><figcaption>
<figure class="imgbox"对于图像/屏幕截图。（可选）带有 for 标题。<figcaption>
