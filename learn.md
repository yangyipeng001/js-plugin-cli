# 入门须知
用到的依赖库熟悉一下：
- chalk[1] （控制台字符样式）
- commander[2] （实现 NodeJS 命令行）
- download[3] （实现文件远程下载）
- fs-extra[4] （增强的基础文件操作库）
- handlebars[5] （实现模板字符替换）
- inquirer[6] （实现命令行之间的交互）
- log-symbols[7] （为各种日志级别提供着色符号）
- ora[8] （优雅终端 Spinner 等待动画）
- update-notifier[9] （npm 在线检查更新）

# 功能策划
js-plugin-cli 主要命令
- init（初始化模板）
- template（下载模板）
- mirror（切换镜像）
- upgrade（检查更新

# 内容
## mirror 切换镜像链接
- 判断 config.json配置文件是否存在
    - 是 -> 将镜像链接写入 config.json 中。
    - 否
        - 创建 config.json 配置文件（优先）。
        - 将镜像链接写入 config.json 中。

## download 下载/更新模板
- 清空模板文件夹 tpl
- 读取 config.json 的镜像链接
- 执行下载文佳并解压到模板文件夹 tpl

## init 初始化项目
- 判断项目是否存在
    - 是 -> 提示项目已经存在



# 参考资料
[1] chalk: https://www.npmjs.com/package/chalk

[2] commander: https://www.npmjs.com/package/commander

[3] download: https://www.npmjs.com/package/download

[4] fs-extra: https://www.npmjs.com/package/fs-extra

[5] handlebars: https://www.npmjs.com/package/handlebars

[6] inquirer: https://www.npmjs.com/package/inquirer

[7] log-symbols: https://www.npmjs.com/package/log-symbols

[8] ora: https://www.npmjs.com/package/ora

[9] update-notifier: https://www.npmjs.com/package/update-notifier

[10] fs-extra: https://www.npmjs.com/package/fs-extra

[11] js-plugin-cli: https://github.com/zpfz/js-plugin-cli/
