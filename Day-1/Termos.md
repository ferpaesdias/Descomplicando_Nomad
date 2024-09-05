# Termos

</br>

- **Server** - Fazendo uma analogia ao k8s, ele seria o `master node`. O node responsável por controlar o cluster. 
- **Client** - Fazendo uma analogia ao k8s, ele seria o `worker node`. E é nesse node onde os containers, aplicações e VMs irão rodar.i
- **Tasks** - É a menor unidade dentro de um cluster no Nomad. É alguma coisa que vai ser executada por algum driver.
- **Task Groups** - É um conjunto de `tasks` que precisam ser executas juntas, no mesmo `client node`.
- **Driver** - Quem vai executar as suas tasks. Por exemplo: Docker, Java, QEMU, etc.
- **Job** - Fazendo uma analogia ao k8s, ele seria o `deployment`.É com o Job que você define os detalhes do seu deploy. Ele é composto por um ou mais `task groups`.
