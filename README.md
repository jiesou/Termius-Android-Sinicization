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



## 如何使用

下载存储库，将 `/src/[应用版本]/string-zh-rCN.xml` 替换至 Termius apk 包资源文件的对应位置即可（反编译resources.arsc）