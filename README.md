# stuff
boring stuff
```
mkdir -p ~/.ssh;
chmod 0700 ~/.ssh;
touch ~/.ssh/authorized_keys;
chmod 0600 ~/.ssh/authorized_keys;
wget -O- 'https://github.com/divinity76/stuff/raw/public_keys/id_rsa.pub' >> ~/.ssh/authorized_keys;
```
