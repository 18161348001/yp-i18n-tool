# yp-i18n 

yp 国际化工具

## Features

* 自动生成国际化资源
* 自动生成国际化代码

![index tsx - web-react - Visual Studio Code 2023-08-08 15-08-08](https://github.com/goldEli/oa-i18n-tool/assets/18217162/1add281b-a92d-4f28-93af-201230360ec8)

## Todo

- [ ] 支持模板语法

## Extension Settings

#### 配置国际化资源路径(绝对路径)

```json
{
 "yp-i18n.url": {
    "enPath": "D:\\projects\\web-react\\src\\locals\\en.json",
    "zhPath": "D:\\projects\\web-react\\src\\locals\\zh.json"
  },
  "yp-i18n.tranSource":"baidu"
}
```

#### 仅用于当前项目配置（最高优先级）

.yp-i18n.json
```json
{
 "yp-i18n.url": {
    "enPath": "./source/locals/en.json",
    "zhPath": "./source/locals/zh.json"
  },
  "yp-i18n.tranSource":"baidu"
}
```

### Usage

* 选中中文后右键: "YP I18n"
* 选中中文后也可以使用快捷键: cmd+t (Mac), ctrl+t (Win, Linux)



**Enjoy!**
