# this project is used to test my new develop environment.

# hello git

1. 安装git
2. 在本地生成ssh密钥
```shell
ssh-keygen -t -rsa -C "username@mail.com"
```
找到本地生成的id_rsa和id_rsa.pub
将id_rsa.pub的内容填到github中的setting ssh设置中

3. github中新建一个repository
4. 本地创建项目，
```
git init
git remote add origin https://github.com/your_name/your_new_repository.git
编码...
git add .
git commit -m "comment"
git push -u origin main
```