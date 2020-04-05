# 压缩与解压缩

### tar命令
归档：压缩的意思
#### 常用命令参数

+ -v 详细的列出处理的文件
+ -c 创建一个新的归档
+ -x 从一个归档中解出文件
+ -j 通过bzip2进行归档
+ -J 通过xz进行归档
+ -z 通过gzip进行归档
+ -f 使用归档文件或 ARCHIVE 设备

### 例子
~~~
# 压缩(bzip2)
tar -vcjf test.tar.bz2 test
# 解压缩(bzip2)
tar -vxjf test.tar.bz2 

# 压缩(gz)
tar -vczf test.tar.gz test

# 解压缩(gz)
tar -vxzf test.tar.gz
~~~





