# Kubernetes - Implementação Minikube

Requerimentos necessários
- 2 CPUs or more
- 2GB of free memory
- 20GB of free disk space
- Internet connection
- Container or virtual machine manager, such as: Docker, QEMU, Hyperkit, Hyper-V, KVM, Parallels, Podman, - VirtualBox, or VMware Fusion/Workstation

Para instalar, coloque o IP do seu servidor no arquivo *hosts*, altere também o nome da chave que está utilizando para autenticar no seu servidor.

Execute o comando

```sh
ansible-playbook -i hosts playbook.yaml 
```