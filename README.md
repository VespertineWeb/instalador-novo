FAZENDO DOWNLOAD DO INSTALADOR & INICIANDO A PRIMEIRA INSTALAÇÃO (USAR SOMENTE PARA PRIMEIRA INSTALAÇÃO):

```bash
sudo apt install -y git && git clone https://github.com/DaniloRiquena/instalador-novo.git && sudo chmod -R 777 instalador-novo && cd instalador-novo && sudo ./install_primaria
```

ACESSANDO DIRETORIO DO INSTALADOR & INICIANDO INSTALAÇÕES ADICIONAIS (USAR ESTE COMANDO PARA SEGUNDA OU MAIS INSTALAÇÃO:
```bash
cd && rm -rf instalador-novo && git clone https://github.com/DaniloRiquena/instalador-novo.git && sudo chmod -R 777 ./instalador-novo && cd ./instalador-novo && sudo ./install_instancia
```

