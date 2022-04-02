上传方法：
1.https
git remote add origin https://github.com/codeThirf/git-test.git
git branch -M main
git push -u origin main

以后再上传直接git push就行了

使用ssh key可以免密登录

①id_ _rsa (私钥文件,存放于客户端的电脑中即可)
②id_ _rsa.pub (公钥文件，需要配置到Github中)
ssh-keygen -t rsa -b 4096 -C "1585869092@qq.com"
放在/c/Users/86181/.ssh/id_rsa  将pub里面的内容复制到GitHub里面的sshkey就行了
 再用ssh -t git@github.com验证否成功
上传方法2：
ssh
