city
========

一款用于生成行政区划联动数据的小工具

### 特色

- 数据权威，来自国家统计局，每年更新
- 自由选择是否包含海外国家列表数据（来自维基百科）
- 自由选择生成一级（省）、二级（省市）、三级（省市县）数据
- 支持输出JSON、原生js文件、AMD/CMD规范js文件
- 支持输出压缩后的代码及格式化后的代码
- 支持输出地区代码（身份证前6位）

### 使用方法

使用npm安装

```sh
npm install -g city
```

使用：

```sh
city
```

支持参数：

- `-V` `--version` 输出版本号
- `-h` `--help` 输出菜单
- `-l` `--level level` 输出指定级别行政区数据，取值1-3
- `-o` `--output fileName` 输出文件路径
- `-j` `--js varibleName` 以指定变量名输出js文件
- `-a` `--amd` 以AMD规范输出js文件
- `-m` `--cmd` 以CMD规范输出js文件
- `-p` `--pretty` 格式化输出
- `-s` `--overseas` 包含海外地区
- `-c` `--code` 包含地区编码（身份证前6位）
- `-u` `--update` 重新抓取原始数据