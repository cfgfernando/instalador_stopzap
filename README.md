FAZENDO DOWNLOAD DO INSTALADOR & INICIANDO A PRIMEIRA INSTALAÇÃO (USAR SOMENTE PARA PRIMEIRA INSTALAÇÃO):

```bash
sudo apt install -y git && git clone https://github.com/cfgfernando/instalador_whatspainel.git && sudo chmod -R 777 instalador_whatspainel && cd instalador_whatspainel && sudo ./install_primaria
```

ACESSANDO DIRETORIO DO INSTALADOR & INICIANDO INSTALAÇÕES ADICIONAIS (USAR ESTE COMANDO PARA SEGUNDA OU MAIS INSTALAÇÃO:
```bash
cd && rm -rf instalador_whatspainel && git clone https://github.com/cfgfernando/instalador_whatspainel.git && sudo chmod -R 777 instalador_whatspainel && cd instalador_whatspainel && sudo ./install_instancia
```

