# sshuttle tunel ssh

# conectar
```  
161.35.134.152  Ip del servidor
sshuttle -v --dns -r root@161.35.134.152:22 0/0
```

# conectar sshuttle usando pem
``` 
sudo sshuttle --dns -vr ubuntu@demo.123odoo.com 0/0 --ssh-cmd 'ssh -i /Users/marlonfalcon/Documents/keys/key.pem'
``` 
