# AnsibleEx

Ansible secondary development, to solve the inflexible interface, improve the password use mechanism, increase security and flexibility

The python + web.py framework implements the ansible https interface and increases the flexibility of the ansible interface. The java spring dubbo framework implements the ansible interface call, registers it in redis for consumers to use, and completes the encryption and decryption process of the password, and the consumer uses the encrypted password

Through the python and java modules, the server cluster operation can be completed without the real password of the server being known. In addition, the consumer’s password cannot be used to directly operate the ansible api or log in to the server. Even if the consumer’s password is leaked, it is also impossible to perform any operations on the server and the ansible interface, even if the dubbo registration is found, without knowing the server’s class method parameters In addition, it is impossible to do any operations on ansible and the server.
