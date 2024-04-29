# 生成requirements

* 先安装 pipreqs

```
  pip install pipreqs
```

* 在当前目录使用生成

```
  pipreqs ./ --encoding=utf8 --force
  --encoding=utf8 ：为使用utf8编码
  --force ：强制执行，当 生成目录下的requirements.txt存在时覆盖 
  . /: 在哪个文件生成requirements.txt 文件
```