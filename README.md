# 常用工具仓库


## 大致文件
```
├── ConfigFiles 各种配置文件
├── config.json 脚本的配置文件
├── myth.py sdk管理脚本
├── redis-3.2-6381.zip
├── sdk sdk的模板目录
└── zip sdk的zip包放置目录 zip名字为 sdk-version.zip 内容为  version/bin...所有文件

```
### Github
`github仓库 URL规则`
- 目录：
    - https://github.com/用户/项目/tree/分支/相对根目录的目录
- 文本文件：
    -  https://github.com/用户/项目/blob/分支/文件目录
- 二进制文件，例如图片：
    -  https://raw.githubusercontent.com/用户/项目/分支/文件目录
- 例如同仓库下的这个文件`/Linux/Docker.md` 可以直接这样写，方便调用，最好最前面不要加`.`这个表示当前目录的 加了反而会有问题
`md文件 目录规则（页内跳转）`
- `[](#标题名)` 即可，注意标题名不可有空格，`【Name】`看成Name 忽略这个符号
