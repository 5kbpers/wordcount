## 功能描述  
```shell
./wordcount.py -c file.c     //返回文件 file.c 的字符数
./wordcount.py -w file.c     //返回文件 file.c 的单词总数
./wordcount.py -l file.c     //返回文件 file.c 的总行数
./wordcount.py -o outputFile.txt     //将结果输出到指定文件outputFile.txt
./wordcount.py -s            //递归处理目录下符合条件的文件
./wordcount.py -a file.c     //返回更复杂的数据（代码行 / 空行 / 注释行）
./wordcount.py -e stopList.txt  // 停用词表，统计文件单词总数时，不统计该表中的单词
```
