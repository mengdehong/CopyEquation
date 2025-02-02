## 介绍

这个扩展允许你从ChatGPT和维基百科复制方程到Word(又名MathML格式)和LaTeX格式。它支持ChatGPT GUI的白色和黑暗模式，以及维基百科网站的[Darkreader扩展](https://chromewebstore.google.com/detail/dark-reader/eimadpbcbfnmbkopoojfekhnkhdbieeh)（以及ChatGPT之一，如果你真的喜欢它）。如果你想使用多行粘贴到MS Word，你只能在Windows上使用[PasteEquation扩展](https://github.com/Foxxey/PasteEquation)（当然也有这个扩展安装）。

**本分支额外支持deepseek公式复制**

## 安装

如果您使用Firefox，请访问https://addons.mozilla.org/addon/copyequation/。它也适用于Android版本的Firefox，这是唯一的移动版本这个扩展支持。对于基于chromium的桌面版浏览器，请按照以下步骤下载和安装该扩展：

### 步骤1：克隆存储库

打开终端并运行以下命令克隆仓库：

```bash
git clone https://github.com/Foxxey/ChatGPT-LaTeX-MathML-Copy.git
```

当然你也可以下载zip包到本地，并解压

### 步骤2：进入“扩展”页面

打开基于chromium的浏览器（Chrome、Edge、Brave等），在地址栏中输入以下URL，进入扩展页面：

```url
chrome://extensions
edge://extensions
```

![image-20250202172353348](https://wenmou-1313491726.cos.ap-shanghai.myqcloud.com/img/image-20250202172353348.png?imageSlim)

确保打开“开发者模式”。

### 步骤3：加载扩展

点击“Load unpack”按钮并选择克隆存储库的目录。这将加载扩展到您的浏览器。

## 如何使用

安装扩展后，访问ChatGPT、维基百科、DeepSeek。当你看到一个数学表达式时，右键单击它。您应该看到一个复制LaTeX或Word/MathML数据的选项。或者，您可以单击“ChatGPT”旁边的图标之一，以复制带有等式的完整消息（用于此“多行”选项的Word/MathML仅在使用[MS Word扩展]（https://github.com/Foxxey/PasteEquation）的Windows上工作）。现在您可以将其粘贴到Word或您最喜欢的TeX分发。玩得开心!

![HowTo](https://github.com/Foxxey/CopyEquation/assets/66215329/36c32793-9779-4a0f-a48a-5ebe57b8da91)

![image-20250202172754385](https://wenmou-1313491726.cos.ap-shanghai.myqcloud.com/img/image-20250202172754385.png?imageSlim)

如果您遇到任何问题或有建议，请随时通过提交[pull request]（https://github.com/Foxxey/Karteikarte.com-Import-Script/pulls）来贡献。如果有，请更新舱单。通过在次要版本中添加1来创建Json。
