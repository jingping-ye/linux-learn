# Linux 目录结构与文件基本操作



## 目录

```shell
# 查看当前所在目录
pwd
```



## 文件

### 创建文件

```shell
# 创建文件
touch file.txt

# 创建多个文件
touch abc.txt efg.txt

# 批量创建文件
# 生成file_1.txt至file_10.txt
touch file_{1..10}.txt
```

### 查找文件

```shell
# 查找以txt结尾的文件
ls *.txt

# 
find /
```

## 文件内容查看

```shell
# 查看末尾行
tail
```

