## git push免密码的两种方法：

- 添加密钥，通过ssh协议[clone](https://todebug.com/Tips/)

- 修改配置文件

```
git config --global credential.helper store

打开~/.gitconfig文件，会发现多了一项:

[credential]

　　helper = store
```

