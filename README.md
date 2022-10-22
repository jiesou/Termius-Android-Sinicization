# Termius-Android-Sinicization

> This is a resource repository for the Chinese [Termius](https://termius.com) Android client.

> This repository only provides the XML files required in the process of sinicization, but does not provide the way to modify the files, also does it provide the packaged results after sinicization
> 
> 本存储库仅提供汉化过程中需要的 XML 文件，而不提供修改该文件的方式，**也不提供汉化后打包的成果**

## 特性

能翻译的内容都翻译了，基于机翻，大多数常见字符经过人工修改确认。仍有的部分英文是不包含在资源文件中的（写死在代码里）

整体汉化率大概 70%+

当前版本适用于 Termius for Android 5.8.2

## 演示

![主页](https://user-images.githubusercontent.com/84175239/197340293-0b822986-d4b5-4b54-8f49-f99c42ab335d.jpg)
![新建本地](https://user-images.githubusercontent.com/84175239/197340294-286c61ad-cb6e-4a87-8325-0ffabcb2a86c.jpg)
![终端](https://user-images.githubusercontent.com/84175239/197340292-3e4c1dc6-256f-49ca-a30a-a1a4366990b8.jpg)

## 如何使用

下载存储库，将 `/src/[应用版本]/string-zh-rCN.xml` 替换至 Termius apk 包资源文件的对应位置即可（反编译 `resources.arsc`）

## 许可证

[WTFPL](https://github.com/jiesou/Termius-Android-Sinicization/blob/main/LICENSE)
