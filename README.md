## Quick start
- Habilitar HyperV ou instalar VirtualBox;
- Instalar Vagrant;

## Comandos basicos Vagrant
Iniciando um novo environment 'vagrant'
```
> mkdir vagrant-poc
> cd vagrant-poc
vagrant-poc> vagrant init
```

Consultanto o vagrant provider (virtualbox, vmware, hyperv):
```
vagrant-poc> vagrant provider
```

Iniciando o environment:
```
vagrant-poc> vagrant up
```

Verificando o status do environment:
```
vagrant-poc> vagrant status
```

Acessando um host especifico via ssh:
```
vagrant-poc> vagrant ssh srv01
```

Demais comandos em:
```
vagrant-poc> vagrant -h
```
