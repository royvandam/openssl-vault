# openssl-vault
Simple OpenSSL AES-256 directory encryption

### Creating a new vault

```
$ git clone https://github.com/royvandam/openssl-vault.git
$ cd openssl-vault
$ mkdir content
```

Copy the files you want to protect into the content folder.

```
$ ./lock
Compressing...
enter aes-256-cbc encryption password:
Verifying - enter aes-256-cbc encryption password:
Purging directory...
Purging archive...
```

### Opening an existing vault

```
$ cd openssl-vault
$ ./unlock
enter aes-256-cbc decryption password:
Decompressing... 
$ cd content
```
