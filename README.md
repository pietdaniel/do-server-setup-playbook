# Digital Ocean Server Provisioning

To run,

1. Ensure ~/.ssh/config has the following entry

```config
Host do
  Hostname #{IP_ADDRESS_FROM_DO}
  Port 22
  User #{USERNAME}
```

2. Run the following invocation in the directory

```bash
$ ansible-playbook -i hosts provision.yml
```
