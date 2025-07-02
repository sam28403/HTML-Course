# Chapter 0

## 🧱 一、HTML 是什么？

HTML 全称是 **HyperText Markup Language**（超文本标记语言），它是构建网页的基础，用来**描述网页的结构**。
 HTML 用标签（tag）把内容包裹起来，例如标题、段落、图片、链接等。

------

## 🧾 二、HTML 基本结构

下面是一个最简单的 HTML 页面结构：

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>我的第一个网页</title>
  </head>
  <body>
    <h1>欢迎来到我的网站</h1>
    <p>这是一个段落。</p>
  </body>
</html>
```

### 各部分解释：

| 部分                     | 作用                                           |
| ------------------------ | ---------------------------------------------- |
| `<!DOCTYPE html>`        | 声明文档类型，告诉浏览器这是 HTML5             |
| `<html>`                 | HTML 的根元素，所有内容都放在里面              |
| `<head>`                 | 头部信息，不显示在网页上，例如标题、字符编码等 |
| `<meta charset="UTF-8">` | 设置网页编码，防止中文乱码                     |
| `<title>`                | 网页标题，显示在浏览器标签上                   |
| `<body>`                 | 网页正文，用户可见内容                         |

------

## 🧩 三、常用标签

### 1. 标题标签 `<h1>` 到 `<h6>`

```html
<h1>这是一级标题</h1>
<h2>这是二级标题</h2>
<h3>这是三级标题</h3>
```

### 2. 段落标签 `<p>`

```html
<p>这是一个段落。</p>
```

### 3. 超链接 `<a>`

```html
<a href="https://www.baidu.com" target="_blank">去百度</a>
```

- `href`: 设置链接地址
- `target="_blank"`: 在新窗口打开

### 4. 图片 `<img>`

```html
<img src="图片地址.jpg" alt="图片描述" width="300">
```

### 5. 列表

#### 无序列表 `<ul>`（圆点）

```html
<ul>
  <li>苹果</li>
  <li>香蕉</li>
</ul>
```

#### 有序列表 `<ol>`（编号）

```html
<ol>
  <li>第一步</li>
  <li>第二步</li>
</ol>
```

### 6. 换行 `<br>` 和 水平线 `<hr>`

```html
这是第一行<br>这是第二行
<hr>
```

------

## 🧪 四、试试看：简单练习

把以下代码粘贴进你的电脑的 `.html` 文件里（比如 `index.html`），用浏览器打开看看效果！

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>HTML 初学者页面</title>
  </head>
  <body>
    <h1>Hello HTML!</h1>
    <p>这是你学会的第一个网页。</p>
    <a href="https://www.google.com" target="_blank">点击这里访问 Google</a>
    <hr>
    <h2>我喜欢的水果</h2>
    <ul>
      <li>🍎 苹果</li>
      <li>🍌 香蕉</li>
    </ul>
    <img src="https://via.placeholder.com/150" alt="占位图">
  </body>
</html>
```

------

## 🧠 想继续学习？

下一步你可以学：

- CSS（网页样式）
- HTML 表格（`<table>`）
- 表单（`<form>`）
- 音视频嵌入（`<audio>`、`<video>`）



------

# 🌟 第一节：HTML 基础结构与常用标签（一）

------

## 🎯 本节目标：

- 理解 HTML 页面结构
- 掌握标题、段落、换行、水平线标签
- 编写你自己的第一个网页

------

## 🧱 1. HTML 页面结构

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>网页标题</title>
  </head>
  <body>
    网页可见内容写这里
  </body>
</html>
```

### 🔍 说明：

- `<!DOCTYPE html>`：声明文档为 HTML5
- `<html>`：HTML 根元素
- `<head>`：头部信息（设置标题、编码等）
- `<body>`：网页的“正文”，浏览器看到的内容

------

## 🔤 2. 标题（Heading）

HTML 有六级标题，数字越小标题越大。

```html
<h1>一级标题</h1>
<h2>二级标题</h2>
<h3>三级标题</h3>
<h4>四级标题</h4>
<h5>五级标题</h5>
<h6>六级标题</h6>
```

📝通常 `h1` 代表网页主标题，`h2`~`h6` 用于小节分层。

------

## ✍️ 3. 段落与换行

```html
<p>这是一个段落。</p>
<p>这是另一个段落。</p>
```

### 换行（`<br>`）：

```html
<p>这是第一行<br>这是第二行</p>
```

------

## 🧱 4. 水平线 `<hr>`

画一条水平线用于分隔内容：

```html
<hr>
```

------

## 💻 示例代码：我的第一个网页

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>我的第一个网页</title>
  </head>
  <body>
    <h1>欢迎来到我的网页</h1>
    <p>这是我的第一个段落。</p>
    <p>这是我的第二个段落。<br>这一行是通过换行标签产生的。</p>
    <hr>
    <h2>再见！</h2>
  </body>
</html>
```

你可以：

1. 将上面代码粘贴到记事本或 VS Code 中。
2. 保存为 `hello.html`。
3. 用浏览器打开看看效果！

------

## 🎯 小练习（请自己动手写）：

请写一个 HTML 网页，包含以下内容：

- 一个 `h1` 标题：“你好，HTML！”
- 两个段落（`p`），第二个段落中加入一个换行
- 一条水平线 `<hr>`

------

# 🌐 第二节：超链接和图片插入

------

## 🎯 本节目标：

- 学会插入超链接 `<a>`
- 学会插入图片 `<img>`
- 理解常用属性如 `href`、`src`、`alt`、`width`、`target`

------

## 🔗 一、超链接 `<a>`

### 🔍 语法：

```html
<a href="链接地址">链接文本</a>
```

### ✅ 示例 1：打开百度

```html
<a href="https://www.baidu.com">去百度</a>
```

### ✅ 示例 2：在新窗口打开链接（加 `target="_blank"`）

```html
<a href="https://www.google.com" target="_blank">打开 Google（新窗口）</a>
```

### 🔎 常用属性：

| 属性              | 作用                     |
| ----------------- | ------------------------ |
| `href`            | 链接地址                 |
| `target="_blank"` | 新窗口打开               |
| `title`           | 鼠标悬停提示文本（可选） |

------

## 🖼️ 二、插入图片 `<img>`

### 🔍 语法：

```html
<img src="图片地址" alt="替代文字" width="宽度">
```

### ✅ 示例 1：插入网络图片

```html
<img src="https://via.placeholder.com/150" alt="占位图">
```

### ✅ 示例 2：设置图片宽度

```html
<img src="https://via.placeholder.com/300x100" alt="横图示例" width="200">
```

### 🔎 常用属性：

| 属性              | 作用                         |
| ----------------- | ---------------------------- |
| `src`             | 图片地址                     |
| `alt`             | 图片无法加载时显示的替代文字 |
| `width`、`height` | 设置图像大小（像素 px）      |

------

## 🧪 示例代码：带链接与图片的网页

```html
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>第二节示例</title>
</head>
<body>
  <h1>我的第二节网页</h1>

  <p>访问一个网站：</p>
  <a href="https://www.wikipedia.org" target="_blank" title="点击查看维基百科">点我去维基百科</a>

  <hr>

  <p>这是一个图片：</p>
  <img src="https://via.placeholder.com/200" alt="占位图片" width="200">

</body>
</html>
```

------

## ✍️ 小练习：

请你写一个 HTML 页面，内容包括：

1. 一个标题（`<h1>`）：“欢迎访问我的站点”
2. 一段文字介绍你要链接的网页
3. 一个超链接，点击后跳转到一个你喜欢的网站（用 `target="_blank"`）
4. 插入一张图片（可用网络图或本地路径），设置 `alt` 和 `width=300`

------

准备好后，下一节我们进入：

> ✅ 第三节：列表（有序列表、无序列表）和文本格式标签（加粗、斜体、下划线）

------

# 📋 第三节：列表和文本格式标签

------

## 🎯 本节目标：

- 学会创建 **有序/无序列表**
- 使用 **加粗、斜体、下划线** 等文本格式
- 巩固网页结构排版技巧

------

## 📌 一、有序列表 `<ol>`（带数字）

```html
<ol>
  <li>下载 GSI</li>
  <li>刷入镜像</li>
  <li>重启设备</li>
</ol>
```

> 💡`<ol>` 表示“Ordered List”，`<li>` 是列表项。

------

## 📌 二、无序列表 `<ul>`（带圆点）

```html
<ul>
  <li>PixelOS</li>
  <li>LineageOS</li>
  <li>crDroid</li>
</ul>
```

------

## 🖍️ 三、文本格式标签

| 格式   | 标签                | 示例              |
| ------ | ------------------- | ----------------- |
| 加粗   | `<b>` 或 `<strong>` | `<b>重要信息</b>` |
| 斜体   | `<i>` 或 `<em>`     | `<i>强调部分</i>` |
| 下划线 | `<u>`               | `<u>重点</u>`     |

⚠️ 推荐使用 `<strong>` 和 `<em>`，语义更明确，利于搜索引擎和无障碍阅读器。

------

## 💻 示例：格式和列表合体

```html
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>第三节示例</title>
</head>
<body>
  <h1><u>刷机步骤</u></h1>

  <p><strong>请务必备份数据！</strong></p>

  <ol>
    <li>解锁 Bootloader</li>
    <li>进入 Fastboot 模式</li>
    <li><em>刷入 GSI 镜像</em></li>
    <li>重启手机</li>
  </ol>

  <hr>

  <h2>支持的 ROM：</h2>
  <ul>
    <li>PixelOS</li>
    <li><b>LineageOS</b></li>
    <li><i>crDroid</i></li>
  </ul>

</body>
</html>
```

------

## 🧪 小练习

请你创建一个 HTML 网页，包括以下内容：

1. 一个主标题：“我的刷机指南”
2. 一段警告性文字，加粗 + 下划线
3. 一份“操作步骤”用有序列表 `<ol>`
4. 一份“推荐 ROM”用无序列表 `<ul>`
5. 合理使用加粗、斜体或下划线来强调部分内容

------

# 📊 第四节：HTML 表格（Table）

------

## 🎯 本节目标：

- 学会使用 `<table>` 创建表格
- 掌握 `<tr>`（行）、`<td>`（单元格）、`<th>`（表头）用法
- 学会合并单元格：`colspan` 和 `rowspan`
- 编写一个“ROM 对比表格”示例

------

## 🧱 一、表格基础结构

```html
<table border="1">
  <tr>
    <th>ROM 名称</th>
    <th>基于</th>
    <th>是否支持OTA</th>
  </tr>
  <tr>
    <td>PixelOS</td>
    <td>Android</td>
    <td>是</td>
  </tr>
  <tr>
    <td>LineageOS</td>
    <td>Android</td>
    <td>是</td>
  </tr>
</table>
```

### 📌 标签解释：

| 标签      | 含义                                 |
| --------- | ------------------------------------ |
| `<table>` | 表格容器                             |
| `<tr>`    | 表格行（Table Row）                  |
| `<th>`    | 表头单元格（Table Header，加粗居中） |
| `<td>`    | 普通单元格（Table Data）             |

### ⚠️ `border="1"` 是快速加边框的方法，后面我们学 CSS 后会用更好的方式。

------

## 🧩 二、合并单元格

### 合并列（横向）`colspan`：

```html
<td colspan="2">合并了两列</td>
```

### 合并行（纵向）`rowspan`：

```html
<td rowspan="2">合并了两行</td>
```

------

## 💻 示例：ROM 对比表格（带合并）

```html
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>ROM 对比表</title>
</head>
<body>
  <h1>刷机ROM对比表</h1>

  <table border="1">
    <tr>
      <th>ROM 名称</th>
      <th>Android 版本</th>
      <th>特性</th>
    </tr>
    <tr>
      <td>PixelOS</td>
      <td>13 / 14</td>
      <td>原生体验 + 一些 Pixel 功能</td>
    </tr>
    <tr>
      <td>LineageOS</td>
      <td>13 - 21</td>
      <td>极简、稳定、开源</td>
    </tr>
    <tr>
      <td>crDroid</td>
      <td rowspan="2">14</td>
      <td>定制化强，主题丰富</td>
    </tr>
    <tr>
      <td>EvolutionX</td>
      <td>Pixel UI + OTA 更新</td>
    </tr>
  </table>

</body>
</html>
```

------

## ✍️ 小练习（请动手）：

请你写一个 HTML 表格，内容自定，但要包括：

1. 至少 **3行** 数据，1行表头
2. 至少使用一次 **`colspan`** 或 **`rowspan`**
3. 使用 `<h1>` 标题描述表格用途，例如“设备对比表”、“ROM兼容性表”等

------

# 📝 第五节：HTML 表单（Form）与输入控件

------

## 🎯 本节目标：

- 掌握 `<form>` 的基本结构和作用
- 学会使用常见表单控件：`<input>`、`<textarea>`、`<select>`、`<button>`
- 制作一个“刷机ROM下载表单”小项目

------

## 🧱 一、表单基础结构

```html
<form action="提交地址" method="提交方式">
  <!-- 表单控件写这里 -->
</form>
```

| 属性     | 含义                                          |
| -------- | --------------------------------------------- |
| `action` | 表单数据提交到哪个地址（这节我们先写空或“#”） |
| `method` | `get`（默认）或 `post`                        |

------

## 🧩 二、常用表单控件

### ✅ 1. 文本输入框（单行）

```html
<label for="name">用户名：</label>
<input type="text" id="name" name="username">
```

### ✅ 2. 密码框

```html
<label for="pwd">密码：</label>
<input type="password" id="pwd" name="password">
```

### ✅ 3. 多行文本框 `<textarea>`

```html
<label for="comment">留言：</label><br>
<textarea id="comment" name="message" rows="4" cols="30"></textarea>
```

### ✅ 4. 单选框 `<input type="radio">`

```html
<p>选择你最喜欢的 ROM：</p>
<input type="radio" name="rom" value="PixelOS"> PixelOS
<input type="radio" name="rom" value="LineageOS"> LineageOS
<input type="radio" name="rom" value="crDroid"> crDroid
```

✅ 相同的 `name` 表示只能选一个。

------

### ✅ 5. 复选框 `<input type="checkbox">`

```html
<p>你想要的功能：</p>
<input type="checkbox" name="feature" value="OTA"> 支持OTA
<input type="checkbox" name="feature" value="Custom"> 高度定制
<input type="checkbox" name="feature" value="Battery"> 优化续航
```

✅ 可多选。

------

### ✅ 6. 下拉选择 `<select>`

```html
<label for="device">选择设备：</label>
<select name="device" id="device">
  <option value="pixel">Pixel 9 Pro</option>
  <option value="xiaomi">Xiaomi 15</option>
  <option value="samsung">Galaxy S25</option>
</select>
```

------

### ✅ 7. 提交按钮

```html
<input type="submit" value="提交">
<!-- 或者 -->
<button type="submit">提交表单</button>
```

------

## 💻 示例：ROM 下载表单

```html
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>ROM 下载表单</title>
</head>
<body>
  <h1>ROM 下载申请</h1>

  <form action="#" method="post">
    <p>
      <label for="name">你的名字：</label>
      <input type="text" id="name" name="username">
    </p>

    <p>
      <label for="device">你的设备：</label>
      <select id="device" name="device">
        <option value="pixel">Pixel 9 Pro</option>
        <option value="s25">Galaxy S25</option>
        <option value="x15">Xiaomi 15 Ultra</option>
      </select>
    </p>

    <p>你选择的 ROM：</p>
    <input type="radio" name="rom" value="PixelOS"> PixelOS
    <input type="radio" name="rom" value="LineageOS"> LineageOS
    <input type="radio" name="rom" value="crDroid"> crDroid

    <p>
      <label for="msg">备注说明：</label><br>
      <textarea id="msg" name="message" rows="4" cols="30"></textarea>
    </p>

    <button type="submit">提交下载申请</button>
  </form>
</body>
</html>
```

------

## 🧪 小练习：

请你写一个表单，内容可以参考或修改上面示例，要求包含：

1. 一个文本输入框（如昵称）
2. 一个下拉菜单（如选择设备）
3. 至少一个单选框组（选择ROM）
4. 至少一个复选框（选择功能）
5. 一个文本框（留言）
6. 一个提交按钮

------

# 🎓 第六节：HTML 总复习 + 实战项目实践

------

## 🧠 一、HTML 总复习（知识回顾）

你已经掌握了以下所有核心内容：

| 模块       | 标签                                                         | 功能                     |
| ---------- | ------------------------------------------------------------ | ------------------------ |
| 结构       | `<!DOCTYPE> <html> <head> <body>`                            | 页面基础框架             |
| 文本       | `<h1>`~`<h6>`, `<p>`, `<br>`, `<hr>`                         | 标题、段落、换行、分隔线 |
| 链接与图片 | `<a>`, `<img>`                                               | 超链接、插图             |
| 列表       | `<ul>`, `<ol>`, `<li>`                                       | 无序/有序列表            |
| 文本样式   | `<b>`, `<i>`, `<u>`, `<strong>`, `<em>`                      | 加粗、斜体、下划线、强调 |
| 表格       | `<table>`, `<tr>`, `<td>`, `<th>`, `rowspan`, `colspan`      | 展示结构化数据           |
| 表单       | `<form>`, `<input>`, `<textarea>`, `<select>`, `<option>`, `<button>` | 收集用户输入             |

------

## 🧩 二、项目实战：Pixel ROM 展示页（迷你项目）

> 💡我们来构建一个简单的 **“Pixel ROM 展示网页”**，展示常见ROM、特性、设备支持，并可留言。

------

### 💻 完整代码示例：

```html
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Pixel ROM 中心</title>
</head>
<body>

  <h1>📱 Pixel ROM 展示中心</h1>

  <p>欢迎访问！这里收录了常见的 Pixel ROM 版本信息及用户反馈入口。</p>
  <hr>

  <h2>🔥 主流 ROM 简介</h2>
  <ul>
    <li><strong>PixelOS：</strong> 极简体验 + 原生风格</li>
    <li><strong>LineageOS：</strong> 稳定、开源、轻量</li>
    <li><strong>crDroid：</strong> 强调定制性和主题</li>
  </ul>

  <h2>📊 ROM 兼容性表</h2>
  <table border="1">
    <tr>
      <th>ROM</th>
      <th>支持设备</th>
      <th>是否支持OTA</th>
    </tr>
    <tr>
      <td>PixelOS</td>
      <td>Pixel 6 ~ Pixel 9</td>
      <td>✅</td>
    </tr>
    <tr>
      <td>LineageOS</td>
      <td>Pixel 2 ~ Pixel 9</td>
      <td>✅</td>
    </tr>
    <tr>
      <td>crDroid</td>
      <td>Pixel 3 ~ Pixel 9</td>
      <td>部分支持</td>
    </tr>
  </table>

  <h2>📥 反馈或留言</h2>
  <form action="#" method="post">
    <p>
      <label for="name">昵称：</label>
      <input type="text" id="name" name="name">
    </p>
    <p>使用过的 ROM：</p>
    <input type="checkbox" name="used" value="PixelOS"> PixelOS
    <input type="checkbox" name="used" value="LineageOS"> LineageOS
    <input type="checkbox" name="used" value="crDroid"> crDroid

    <p>
      <label for="comment">你的感受：</label><br>
      <textarea id="comment" name="comment" rows="5" cols="40"></textarea>
    </p>
    <button type="submit">提交留言</button>
  </form>

</body>
</html>
```

------

## 🧪 小练习挑战（项目实践）：

请你尝试写一个类似的项目页面，主题可以是：

- “Pixel ROM 下载站”
- “售后登记中心”
- “ROM 对比评测页”
- 甚至 “我的设备清单展示页”

你可以自由组合之前学过的内容，包括标题、列表、表格、表单等。写好贴出来我可以帮你优化 + 点评。

------

## 🎯 下一阶段预告：

你已经完成了 HTML 的入门系统课程！

🎉 你已经可以做出结构完整、功能丰富的网页。

👉 接下来我们可以进入：

- **CSS 基础**：网页美化
- **布局系统**（Flexbox/Grid）
- **HTML+CSS 实战页面**







------

# 🎨 CSS 入门第一节：选择器与基础样式

------

## 🎯 本节目标：

- 理解什么是 CSS，为什么要用它
- 掌握 CSS 的基本语法
- 学会三种使用 CSS 的方式
- 学会基础选择器（标签、类、ID）
- 给网页加上**颜色、字体、边框、对齐**

------

## 🧠 一、什么是 CSS？

> CSS（Cascading Style Sheets）中文叫 **层叠样式表**，用于控制 HTML 元素的样式，比如颜色、大小、位置等。

🌟 HTML 决定结构，CSS 决定“长什么样”。

------

## 🧱 二、CSS 的三种写法

### ✅ 1. **内联样式**（不推荐，但简单）

```html
<p style="color: red;">我是红色段落</p>
```

------

### ✅ 2. **内部样式表（写在 `<style>` 里）**

```html
<head>
  <style>
    p {
      color: blue;
    }
  </style>
</head>
```

------

### ✅ 3. **外部样式表**（最推荐！）

新建一个 `style.css` 文件：

```css
p {
  color: green;
}
```

在 HTML 中引入：

```html
<link rel="stylesheet" href="style.css">
```

------

## 🧩 三、CSS 基本语法

```css
选择器 {
  属性1: 值1;
  属性2: 值2;
}
```

### 示例：

```css
h1 {
  color: purple;
  font-size: 32px;
}
```

------

## 🎯 四、选择器基础

### ✅ 1. 标签选择器（直接写元素名）

```css
p {
  color: darkblue;
}
```

### ✅ 2. 类选择器 `.class`（多个元素共享）

HTML：

```html
<p class="highlight">高亮内容</p>
```

CSS：

```css
.highlight {
  background-color: yellow;
}
```

------

### ✅ 3. ID 选择器 `#id`（唯一）

HTML：

```html
<h1 id="main-title">主标题</h1>
```

CSS：

```css
#main-title {
  text-align: center;
  color: green;
}
```

------

## 💡 常见样式属性（你现在就能用的）

| 属性               | 功能     | 示例值                |
| ------------------ | -------- | --------------------- |
| `color`            | 文字颜色 | red / #333            |
| `background-color` | 背景色   | lightblue             |
| `font-size`        | 字体大小 | 16px / 1.5em          |
| `text-align`       | 对齐方式 | left / center / right |
| `border`           | 边框     | 1px solid black       |
| `padding`          | 内边距   | 10px                  |
| `margin`           | 外边距   | 10px                  |

------

## 💻 示例：给网页加点颜色

```html
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>样式示例</title>
  <style>
    body {
      background-color: #f5f5f5;
      font-family: Arial, sans-serif;
    }

    h1 {
      color: navy;
      text-align: center;
    }

    p {
      color: #333;
      font-size: 18px;
    }

    .highlight {
      background-color: yellow;
      border: 1px solid orange;
      padding: 10px;
    }

    #footer {
      text-align: center;
      color: gray;
      font-size: 14px;
    }
  </style>
</head>
<body>

  <h1>Pixel ROM 样式测试</h1>

  <p>欢迎来到 ROM 中心。</p>
  <p class="highlight">这是重点提示内容</p>

  <p id="footer">版权所有 © 2025</p>

</body>
</html>
```

------

## 🧪 小练习：

请你写一段 HTML 页面，并在 `<style>` 里加入 CSS，要求：

1. 页面背景色改为浅灰色
2. 所有 `<h1>` 文字居中、蓝色、加大字号
3. 给某段 `<p>` 加类 `.warn`，设置背景为浅红、边框为红色
4. 页面底部加一个 `<p>`，设置 ID 为 `footer`，颜色灰色、居中对齐

------

# 📦 CSS 第二节：盒模型与布局基础

------

## 🎯 本节目标：

- 理解 **盒模型（Box Model）** 的概念
- 掌握 `margin`、`padding`、`border` 的作用
- 学会设置元素大小：`width` / `height`
- 初步掌握块级元素与行内元素的布局特性

------

## 🧱 一、什么是盒模型（Box Model）

在 CSS 中，每一个 HTML 元素都被看成一个盒子，结构如下：

```
+-----------------------------+
|         margin（外边距）    |
|  +-----------------------+  |
|  |    border（边框）      |  |
|  |  +-----------------+  |  |
|  |  | padding（内边距） |  |  |
|  |  | +-------------+ |  |  |
|  |  | | content     | |  |  |
|  |  | +-------------+ |  |  |
|  |  +-----------------+  |  |
|  +-----------------------+  |
+-----------------------------+
```

------

## 🔑 关键属性详解：

| 属性             | 作用                         | 举例                      |
| ---------------- | ---------------------------- | ------------------------- |
| `content`        | 内容区域                     | 文字、图片、表单          |
| `padding`        | 内容与边框之间的“内边距”     | `padding: 10px`           |
| `border`         | 元素边框                     | `border: 1px solid black` |
| `margin`         | 元素与其他元素之间的“外边距” | `margin: 20px`            |
| `width / height` | 内容区域的宽高               | `width: 300px`            |

------

## 🧩 二、盒模型示例（推荐动手试试）

```html
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>盒模型示例</title>
  <style>
    .box {
      background-color: lightblue;
      width: 300px;
      height: 100px;

      padding: 20px;
      border: 5px solid blue;
      margin: 30px;
    }
  </style>
</head>
<body>

  <div class="box">
    这是一个盒子，看看它周围的边距、内距和边框。
  </div>

</body>
</html>
```

------

## 🧠 小提示：

- **内边距 `padding`** 会“撑大”盒子尺寸，除非你设置 `box-sizing: border-box`
- **外边距 `margin`** 是两个盒子之间的间隔
- 多个块级元素会**竖着排列**（除非用布局控制）

------

## 🎯 块级元素 vs 行内元素

| 类型     | 标签示例                    | 默认行为                 |
| -------- | --------------------------- | ------------------------ |
| 块级元素 | `<div>`, `<p>`, `<h1>`      | 独占一行，可设置宽高     |
| 行内元素 | `<span>`, `<a>`, `<strong>` | 行内排列，不可直接设宽高 |

------

## 🧪 小练习（请尝试完成）：

请你写一个网页，包含：

1. 一个 `<div>` 容器 `.card`，设置：
   - 宽度 400px，高度 200px
   - 背景色浅灰
   - 内边距 20px，外边距 30px
   - 边框 2px 实线深灰
2. 在容器中放一段文字，前面加一个 `<span>`，设置：
   - 背景为黄色
   - `padding: 5px;`，表示强调词

------

# 📐 CSS 第三节：Flexbox 弹性布局入门

------

## 🎯 本节目标：

- 掌握现代网页布局神器：**Flexbox 弹性盒子布局**
- 理解主轴（水平 or 垂直）与交叉轴
- 学会常见对齐方式：居中、等距、换行、右对齐等
- 实战制作一个“ROM 信息卡片布局”

------

## 🧱 一、什么是 Flexbox？

Flexbox（Flexible Box）是一种强大的 CSS 布局方式，用于**一维排列**元素（横向或纵向）。只要你想让多个元素在一行或一列中对齐、分布、居中……Flex 都能做到！

------

## 🧩 二、Flex 基础语法

对父元素设置：

```css
display: flex;
```

就能让子元素成为“弹性盒子”。

------

## 🧭 三个核心属性（父元素）

| 属性              | 示例                                       | 说明                   |
| ----------------- | ------------------------------------------ | ---------------------- |
| `display: flex`   | 开启弹性布局                               |                        |
| `flex-direction`  | `row`（默认） / `column`                   | 主轴方向               |
| `justify-content` | `center` / `space-between` / `flex-end` 等 | 主轴对齐（横向对齐）   |
| `align-items`     | `center` / `stretch` / `flex-start` 等     | 交叉轴对齐（纵向对齐） |

------

## 🔧 子元素常用属性

| 属性          | 示例              | 说明              |
| ------------- | ----------------- | ----------------- |
| `flex-grow`   | `1`               | 剩余空间分配比例  |
| `flex-shrink` | `1`               | 收缩比例          |
| `flex-basis`  | `200px`           | 初始宽度          |
| `flex`        | 简写：`1 1 200px` | grow shrink basis |

------

## 💻 示例：横向排列卡片

```html
<!DOCTYPE html>
<html lang="zh">
<head>
  <meta charset="UTF-8">
  <title>Flex 示例</title>
  <style>
    .container {
      display: flex;
      justify-content: space-around;
      align-items: flex-start;
      gap: 20px;
      margin: 30px;
    }

    .card {
      background-color: #f0f0f0;
      width: 200px;
      padding: 15px;
      border: 1px solid #ccc;
      border-radius: 8px;
    }

    .card h3 {
      margin-top: 0;
    }
  </style>
</head>
<body>

  <h1 style="text-align:center;">主流 Pixel ROM 卡片展示</h1>

  <div class="container">
    <div class="card">
      <h3>PixelOS</h3>
      <p>原生体验、纯净流畅。</p>
    </div>
    <div class="card">
      <h3>LineageOS</h3>
      <p>稳定、开源、极简主义。</p>
    </div>
    <div class="card">
      <h3>crDroid</h3>
      <p>高定制、自由主题。</p>
    </div>
  </div>

</body>
</html>
```

------

## 🧠 解读：

- `.container` 是 Flex 父容器
- `.card` 是子盒子，均匀分布
- `gap` 用于子元素间距（Flex 版 `margin`）
- `border-radius` 是圆角样式，小细节更美观

------

## 🧪 小练习挑战：

请你创建一个 Flex 布局的页面，要求：

1. 一个容器 `.rom-list`，`display: flex`
2. 里面放 3 个 `.rom-card` 卡片，每个写一个 ROM 名称和简介
3. 卡片宽度一致，带边框和 padding
4. 卡片横向排列，间距明显
5. 尝试用 `justify-content` 改变布局对齐方式（`center`, `space-between`, `flex-end`等）

------

# ✍️ CSS 第四节：文本与字体美化

------

## 🎯 本节目标：

- 学会设置文字的字体、大小、颜色、对齐
- 掌握字体加粗、斜体、阴影、行高、字间距
- 掌握中文字体设置技巧
- 引入**网页字体（Google Fonts）**

------

## 🧱 一、基础文本样式属性

| 属性             | 示例值                               | 说明        |
| ---------------- | ------------------------------------ | ----------- |
| `color`          | `red`, `#333`, `rgb(0,0,0)`          | 字体颜色    |
| `font-size`      | `16px`, `1.5em`, `120%`              | 字体大小    |
| `font-weight`    | `normal`, `bold`, `100~900`          | 字体粗细    |
| `font-style`     | `normal`, `italic`                   | 正常 / 斜体 |
| `text-align`     | `left`, `center`, `right`, `justify` | 文本对齐    |
| `line-height`    | `1.5`, `24px`                        | 行高        |
| `letter-spacing` | `2px`                                | 字母间距    |
| `word-spacing`   | `5px`                                | 单词间距    |
| `text-shadow`    | `1px 1px 3px gray`                   | 文字阴影    |

------

## 💻 示例：常见文字样式

```html
<!DOCTYPE html>
<html lang="zh">
<head>
  <meta charset="UTF-8">
  <title>文本样式示例</title>
  <style>
    body {
      font-family: "Segoe UI", "微软雅黑", sans-serif;
      padding: 30px;
    }

    h1 {
      text-align: center;
      color: darkblue;
      text-shadow: 2px 2px 4px #aaa;
    }

    .intro {
      font-size: 18px;
      line-height: 1.8;
      color: #333;
      letter-spacing: 0.5px;
    }

    .highlight {
      font-weight: bold;
      color: darkred;
      background-color: lightyellow;
    }

    .italic {
      font-style: italic;
    }

  </style>
</head>
<body>

  <h1>📖 Pixel ROM 文本样式展示</h1>

  <p class="intro">
    欢迎来到 <span class="highlight">Pixel ROM 中心</span>。在这里你可以查阅各类 <span class="italic">第三方系统</span> 的资料、刷机指南与用户体验分享。
  </p>

</body>
</html>
```

------

## 📚 二、中文字体设置建议

> 在网页中设置中文字体时，请列出多个字体名称，确保兼容性：

```css
body {
  font-family: "PingFang SC", "Microsoft YaHei", "微软雅黑", sans-serif;
}
```

说明：

- `"PingFang SC"`：苹果系统默认中文字体
- `"Microsoft YaHei"` / `"微软雅黑"`：Windows 默认中文字体
- `sans-serif`：没有衬线的通用字体（兜底）

------

## 🔡 三、引入 Google Fonts（可选）

例如引入 [Noto Sans SC](https://fonts.google.com/specimen/Noto+Sans+SC)：

```html
<link href="https://fonts.googleapis.com/css2?family=Noto+Sans+SC&display=swap" rel="stylesheet">
body {
  font-family: 'Noto Sans SC', sans-serif;
}
```

💡 如果你在中国大陆，可通过 CDN 加速（如：fonts.loli.net）

------

## 🧪 小练习挑战：

请你写一个页面，包含：

1. 一个 `<h1>` 居中、颜色为深紫色、有淡淡的文字阴影
2. 一段介绍文字 `.intro`，字号18px、行高1.6、字距0.5px、颜色#444
3. 文中出现强调词用 `<span class="highlight">` 包裹，加粗、背景黄、文字红
4. 至少出现一次斜体 `.italic` 单词

------

# 🌈 CSS 第五节：背景、边框与装饰性样式

------

## 🎯 本节目标：

- 设置背景颜色、背景图片、渐变色
- 掌握边框样式：颜色、粗细、样式、圆角
- 添加盒子阴影，提升视觉层级感
- 初步美化“卡片”类 UI 外观

------

## 🧱 一、背景样式属性

| 属性                  | 示例                   | 说明         |
| --------------------- | ---------------------- | ------------ |
| `background-color`    | `#f0f0f0`, `lightblue` | 背景颜色     |
| `background-image`    | `url("bg.jpg")`        | 设置背景图   |
| `background-size`     | `cover`, `contain`     | 背景缩放适配 |
| `background-position` | `center`, `top left`   | 背景位置     |
| `background-repeat`   | `no-repeat`            | 是否重复平铺 |
| `background`          | 简写                   | 一行搞定多个 |

------

## 🎨 二、边框属性

```css
border: 2px solid gray;
border-radius: 8px;
```

你可以分别设置四边的样式，或用简写统一控制。

------

## ☁️ 三、阴影（阴影 = 立体感）

```css
box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.2);
```

| 参数含义 | 示例      |
| -------- | --------- |
| 水平偏移 | 2px（右） |
| 垂直偏移 | 2px（下） |
| 模糊半径 | 10px      |
| 颜色     | 半透明黑  |

------

## 💻 示例：带背景图的卡片组件

```html
<!DOCTYPE html>
<html lang="zh">
<head>
  <meta charset="UTF-8">
  <title>Pixel 卡片样式</title>
  <style>
    body {
      background-color: #f5f5f5;
      font-family: "Segoe UI", "微软雅黑", sans-serif;
      padding: 40px;
    }

    .card {
      background: linear-gradient(to bottom right, #ffffff, #e0f7fa);
      border: 2px solid #ccc;
      border-radius: 12px;
      padding: 20px;
      width: 300px;
      box-shadow: 4px 4px 16px rgba(0, 0, 0, 0.1);
      margin: 0 auto;
    }

    .card h2 {
      margin-top: 0;
      color: #007acc;
    }

    .card p {
      color: #333;
    }
  </style>
</head>
<body>

  <div class="card">
    <h2>PixelOS</h2>
    <p>A clean and stable ROM offering near-stock Android with Material You and extended customization.</p>
  </div>

</body>
</html>
```

------

## 🧠 解读：

- 使用 `linear-gradient` 做渐变背景
- `border-radius` 做圆角
- `box-shadow` 提升立体感
- `margin: 0 auto` 让卡片居中显示

------

## 🧪 小练习挑战：

请你写一个 `.rom-card` 样式的卡片组件，要求：

1. 设置背景为浅紫色渐变（上浅下深）
2. 添加圆角 `12px`、边框 `2px solid #aaa`
3. 设置 `box-shadow` 为柔和的灰色阴影
4. 卡片中包含 `<h3>` 标题和 `<p>` 简介内容

本节是视觉美化的核心，掌握这些你就能让页面“有设计感”起来！💫

------

# 🎬 CSS 第六节：过渡动画与动态交互

------

## 🎯 本节目标：

- 掌握 `:hover` 伪类（鼠标悬停效果）
- 使用 `transition` 实现平滑动画
- 实战按钮/卡片的**颜色变化、阴影变化、缩放效果**
- 打造“有反馈感”的交互界面

------

## 🧩 一、`:hover` 是什么？

`hover` 是 CSS 中最常见的**伪类选择器**，当鼠标悬停在某个元素上时会触发：

```css
.button:hover {
  background-color: blue;
}
```

------

## 🧪 二、`transition` 属性基础

`transition` 可以让 CSS 的变化“慢下来”，带有动画效果。

```css
transition: all 0.3s ease;
```

| 属性   | 含义                                                 |
| ------ | ---------------------------------------------------- |
| `all`  | 所有可变化的属性                                     |
| `0.3s` | 动画时长                                             |
| `ease` | 缓动函数（常用还有 `linear`, `ease-in`, `ease-out`） |

------

## 💻 示例：交互式卡片样式

```html
<!DOCTYPE html>
<html lang="zh">
<head>
  <meta charset="UTF-8">
  <title>交互式卡片</title>
  <style>
    body {
      font-family: "Segoe UI", "微软雅黑", sans-serif;
      background-color: #f0f0f0;
      padding: 40px;
    }

    .card {
      background: linear-gradient(to bottom, #fff, #f0e6ff);
      border: 2px solid #ccc;
      border-radius: 12px;
      padding: 20px;
      width: 280px;
      margin: 0 auto;
      box-shadow: 2px 2px 8px rgba(0, 0, 0, 0.1);
      transition: all 0.3s ease;
    }

    .card:hover {
      transform: scale(1.05);
      box-shadow: 6px 6px 20px rgba(0, 0, 0, 0.2);
      border-color: rebeccapurple;
    }

    .card h3 {
      margin-top: 0;
      color: rebeccapurple;
      transition: color 0.3s;
    }

    .card:hover h3 {
      color: darkred;
    }

    .card p {
      color: #555;
    }
  </style>
</head>
<body>

  <div class="card">
    <h3>EvolutionX</h3>
    <p>A stylish, fully-featured Pixel ROM with smooth animations and deep theming support.</p>
  </div>

</body>
</html>
```

------

## ✅ 这个示例展示了：

- 卡片悬停后：
  - 缩放放大（`transform: scale()`）
  - 阴影加重
  - 边框变色
  - 标题颜色改变

动画通过 `transition` 平滑进行，让交互更自然。

------

## 🔧 你可以尝试修改或添加：

- 🟣 增加按钮，按钮 hover 时变色/弹跳
- 🟣 让卡片文字渐显 (`opacity`)
- 🟣 给图片添加淡入、放大等动效

------

## 🧪 小挑战练习：

请你写一张 `.card` 卡片，要求：

1. 默认是淡蓝背景 + 圆角 + 阴影
2. 鼠标悬停时：
   - 卡片放大一点点
   - 背景颜色加深
   - 标题颜色变成橘色
   - 加大阴影

这节是进入网页“灵动感”的关键——加了动效，网页就“活”了！💫

## 💡 拓展练习建议（自选挑战）：

1. 添加一个按钮，在 `:hover` 时变色、浮起（如登录按钮效果）
2. 多张卡片排成一行（使用 `flexbox`）
3. 加上图片：悬停时图片也放大（用 `transform: scale()`）

