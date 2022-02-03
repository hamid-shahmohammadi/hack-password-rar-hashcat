# hack-password-rar-hashcat
hack password rar file with hashcat


```
rar2john 10.Quiz\ View.rar > 01.txt  
hashcat -a 0 13600 doc.txt rockyou.txt
hashcat -m 13000 doc.txt rockyou.txt --show
```
