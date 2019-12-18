# blog

This is my first commit!

创建SSH keys三部曲
第一步: ssh-keygen -t rsa -b 4096 -C "122146588@qq.com"
第二步: 回车三下
第三步(执行后获取ssh-key): cat ~/.ssh/id_rsa.pub

## This is my second commit!!

第四步(验证)： ssh -T git@github.com
第五步(分别执行一下五部)：  
    git config --global user.name "你的名字"
    git config --global user.email "你的邮箱"
    git config --global push.default matching
    git config --global push.fault matching
    git config --global push.editor "vim"

例子：
    git config --global user.name ht-liu
    git config --global user.email 122146588@qq.com
    git config --global push.default matching
    git config --global push.fault matching
    git config --global push.editor "vim"

## This is my threeth commit!!
