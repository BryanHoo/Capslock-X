# CapsLock-X

## 快速开始

1. 下载安装 [Karabiner-Elements](https://karabiner-elements.pqrs.org/)，按照系统提示赋予权限
2. 使用 Safari 打开下面的链接，将自动打开程序并加载配置文件

```
karabiner://karabiner/assets/complex_modifications/import?url=https://raw.githubusercontent.com/BryanHoo/Capslock-X/main/capslock-x.json
```

3. 打开 Karabiner，切换到 ComplexModification，点击按钮 Add Rules 启用 CapsLock-X 规则

## 规则

### 基础规则

| 按键             | 描述                          |
| ---------------- | ----------------------------- |
| 点击 `CapsLock`  | 单击 CapsLock 映射到 ESC      |
| 按住 `CapsLock`  | 按住 CapsLock 启用 Hyper      |
| 点击 `ESC`       | 单击 CapsLock 映射到 ESC      |
| `Hyper` + 空格键 | 按住 Hyper 和空格键切换输入法 |

### 光标移动规则

| 按键        | 描述               |
| ----------- | ------------------ |
| `Hyper`+`h` | 向前移动一个字符   |
| `Hyper`+`l` | 向后移动一个字符   |
| `Hyper`+`k` | 向上移动一个字符   |
| `Hyper`+`j` | 向下移动一个字符   |
| `Hyper`+`;` | 向前移动一个单词   |
| `Hyper`+`'` | 向后移动一个单词   |
| `Hyper`+`i` | 移动到当前行行首   |
| `Hyper`+`o` | 移动到当前行行尾   |
| `Hyper`+`u` | 移动到当前页面顶部 |
| `Hyper`+`p` | 移动到当前页面底部 |

### 光标选中规则

| 按键              | 描述               |
| ----------------- | ------------------ |
| `Hyper`+`cmd`+`h` | 向前选中一个字符   |
| `Hyper`+`cmd`+`l` | 向后选中一个字符   |
| `Hyper`+`cmd`+`k` | 向上选中           |
| `Hyper`+`cmd`+`j` | 向下选中           |
| `Hyper`+`cmd`+`;` | 向前选中一个单词   |
| `Hyper`+`cmd`+`'` | 向后选中一个单词   |
| `Hyper`+`cmd`+`i` | 选中到当前行行首   |
| `Hyper`+`cmd`+`o` | 选中到当前行行尾   |
| `Hyper`+`cmd`+`u` | 选中到当前页面顶部 |
| `Hyper`+`cmd`+`p` | 选中到当前页面底部 |

### 删除规则

| 按键             | 描述               |
| ---------------- | ------------------ |
| `Hyper`+`m`      | 删除光标前一个字符 |
| `Hyper`+`,`      | 删除光标后一个字符 |
| `Hyper`+`n`      | 删除光标前一个单词 |
| `Hyper`+`.`      | 删除光标后一个单词 |
| `Hyper`+`delete` | 删除到行首         |

### 应用规则

| 按键        | 描述           |
| ----------- | -------------- |
| `Hyper`+`s` | 切换应用内 tab |
| `Hyper`+`r` | 打开 iTerm2    |
