# Windows 10 Vagrant Box

Download windows 10 vagrant box:
```bash
vagrant box add gusztavvargadr/windows-10 \
  --box-version=2009.0.2012  \
  --provider=virtualbox
```

start windows:
```bash
vagrant up
```

sleep windows:
```bash
vagrant halt
```

delete windows:
```bash
vagrant destroy
```
