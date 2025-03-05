I SSH'd into the server and checked if the authorized_keys file exists using:
``` bash
cat ~/.ssh/authorized_keys
```

I verified whether the public key was already present(server side). Then, I appended the intranet public key (from Task 3) to the authorized_keys file:

``` bash
echo 'key-from-3rd' >> ~/.ssh/authorized_keys
```