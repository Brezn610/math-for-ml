# Math for Machine Learning — Notes & Code

<p align="center">
A structured collection of notes, derivations, and Python implementations for understanding  
the mathematical foundations behind machine learning and deep learning.  
<br>
All content is written and executed inside a WSL2 + VS Code + Conda environment.
</p>


Markdown 本身不支持“文本对齐（左/中/右）”，因为它的设计哲学就是 保持纯文本简单、不带格式。

但是——
GitHub / VS Code 预览 / Markdown 解析器支持一种扩展语法：
👉 使用 HTML 标签来对齐文本

Markdown 中 可以直接混用 HTML！

这意味着你可以写：

✔️ 1. 左对齐（默认）
左对齐是默认的，不用写任何东西。

✔️ 2. 居中对齐（最常用的）
<p align="center">
A structured collection of notes, derivations, and Python implementations.
</p>


显示效果：

<p align="center"> A structured collection of notes, derivations, and Python implementations. </p>
✔️ 3. 右对齐
<p align="right">
This text is right aligned.
</p>


效果：

<p align="right"> This text is right aligned. </p>
✔️ 4. 你可以让整段描述居中（最常用于 README 顶部说明）

例如把你的 README 开头改成：

<p align="center">
A structured collection of notes, derivations, and Python implementations for understanding  
the mathematical foundations behind machine learning and deep learning.  
<br>
All content is written and executed inside a WSL2 + VS Code + Conda environment.
</p>


效果 👇

<p align="center"> A structured collection of notes, derivations, and Python implementations for understanding the mathematical foundations behind machine learning and deep learning. <br> All content is written and executed inside a WSL2 + VS Code + Conda environment. </p>
✔️ 5. 标题也可以居中
<h1 align="center">Notes & Code</h1>


效果：

<h1 align="center">Notes & Code</h1>
✔️ 6. 组合：标题居中 + 描述居中（专业项目常用）

复制这段，你的 README 会变成 GitHub 高级项目一样：

<h1 align="center">📘 Notes & Code</h1>

<p align="center">
A structured collection of notes, derivations, and Python implementations  
for understanding the mathematical foundations behind machine learning and deep learning.  
<br>
All content is written and executed inside a WSL2 + VS Code + Conda environment.
</p>

📌 总结：Markdown 没有对齐语法，但 HTML 可以完美解决

只要记住一句话：

Markdown = 简单文字 + 允许嵌 HTML 来扩展格式能力

所以你想要对齐、颜色、字体大小、换行等，都可以用 HTML 实现。

