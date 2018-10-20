# Rede
# Instalação e atualização de pacotes

Primeira coisa configurar os pacotes que ficam no repositório:

```
vim /etc/apt/sources.list
```

```
teste
```

Atualizei os pacotes com o comando conhecido

```
apt-get update
```

Depois apt-get update para tualiar todos os pacotes. Comando demorado ...
'''
apt-get update
```
No /var/cache/apt/archives com o comando dpkg -c wget <tab> para ver os arquivos com referencia a documentacao e licença

O comando dpkg -s <nome-do-pacote> da informações do pacote.

```
dpkg -s wget
'''

O comando dpkg -l <nome-do-pacote> fornece informações da instalação e versão do pacote
```
dpkg -l tzdata
```

Ver o tamanho dos pacotes no /var

```
df -hT
```

Instalar um pacote

```
apt-get insta <nome-do-pacote>
```

Desinstalar ...

```
apt-get remove <nome-do-pacote>
```

E para remover até os arquivos de configuração do pacote ...

```
apt-get purge <nome-do-pacote>
```

# Configurando placa de rede

Configurar reduncia da placa de rede. Essa técnica é conhecida como link aggregation.

O Balanceamento de carga é chamado bouding.

## Gerando um par de chaves para acessar o servidor via ssh

Gerar um par de chaves para acessar o servidor via par de chaves é melhor que acessá-lo pela interface do Virtualbox. A opção  de um console para copiar e colocar as linhas de comandos é mais usual que a console padrão do virtualbox.

## gerar um ssh key pair

Comando:
```
ssh-keygen -t rsa
```
##Ver o ip do linux
```
ip a
```

## Configurando as interfaces de rede

```
teste
```
