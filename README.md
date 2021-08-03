# Windows 10 Vagrant Box

Download windows 10 vagrant box:
```bash
vagrant box add gusztavvargadr/windows-10 \
  --box-version=2101.0.2106  \
  --provider=virtualbox
```

start windows:
```bash
vagrant up
```

sleep and resume:
```bash
vagrant suspend
vagrant resume
```

delete windows:
```bash
vagrant destroy
```
