# mkdocs-template

mkdocs 编写 markdown 文件，优化后的模板。

```python
# 安装 mkdocs
pip install mkdocs

# 安装 bootstrap 主题
pip install mkdocs-bootstrap

# 创建 xxx 目录
mkdocs new xxx

# 替换 mkdocs.yml
cp src/mkdocs.yml xxx/mkdocs.yml

# 替换其它文件
cp README.md xxx/docs/
mv src/style.css xxx/docs/
mv src/injection.js xxx/docs/

# 运行 demo
cd demo
mkdocs serve
```

运行效果如下

![1712713475439](image/README/1712713475439.png)
