#Generate SSH Key#
ssh-keygen -t rsa -C "najunuoyan@126.com"

file id_rsa is private key, id_rsa.pub is public key.

#Add public Key#
Account Settings->SSH Keys-> Add SSH Key.

input name in 'Title' and paste the content of id_rsa.pub in 'Key', OK

verify you key:

ssh -T git@github.com

you may be need the password you set in 'Generate SSH Key' step.

#MarkDown#
[MarkDown Ref Chinese](http://www.ituring.com.cn/article/775)  

[MarkDown Ref English](http://daringfireball.net/projects/markdown/syntax)

