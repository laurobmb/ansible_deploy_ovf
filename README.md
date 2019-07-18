# Deploy OVF no ESXI usando Ansible

Este script em yaml para Ansible serve para realizar deploy da imagem em OVF no ESXI. Ajuste as variáveis ao ser ambiente para que o script funcione corretamente.

Instalar pyvmomi na maquina que for executar o script 

##### Servidor ESXI -> vcenter
##### Login no ESXI -> root
##### Datastore no ESXI -> datastore1
##### Pasta no ESXI -> '/'

##### Maquinas a serem criadas:
    -> kube01
    -> kube02
    -> kube03
    -> kube04
