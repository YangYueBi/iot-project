
在将start.sh复制到linux系统后赋予权限:
chmod u+x *.sh
修改在windows和linux换行符不一致问题:
sed -i "s/\r//" start.sh