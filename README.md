# Sonolus-Tools-Data

Sonolus Tools Data

## 添加翻译

在对应语言代码文件夹下增加相应文件编写即可。

## 修改默认语言

打开`.defaultlang`，将内容设置为默认语言代码，如

> zh-CN

这样框架就会使用该语言作为获取内容失败时的默认语言。

没有配置目录而自动生成目录时，也会根据默认语言进行生成。

## 设定目录

编辑`contents.json`，使用object进行嵌套，如：

```json
{
    "files": ["README"],
    "dir": {
        "guide": {
            "files": ["quick-start", "favorite"]
        }
    }
}
```

*编写配置时必须省略.md后缀；files下所有的文件均应为markdown。*

如果定义了contents.json，则会根据该文件生成目录，无论各语言文件夹的目录结构如何。