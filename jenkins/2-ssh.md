If you want to use ssh without password you can follow the followings:

**1. Generate a key**
```bash
ssh-keygen 
```
**2. First time login with password**
```bash
ssh-copy-id <username@remoteServerIp>
```

**3. Now login without password**
```bash
ssh username@remoteServerIp
```