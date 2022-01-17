<img src="https://raw.githubusercontent.com/leonardor666/images/main/fenrir.jpg"  height="600" />

# FenrirBrute-mysql é uma ferramenta de bruteforce

FenrirBrute-mysql é uma ferramenta para bruteforce de MySQL que permite ataques com usuário e lista de senhas.
Utiliza como base o Python 3 com a biblioteca "mysql.connector".

## Instalação

**Faça o download da ultima versão**
```
git clone https://github.com/suiteloki/FenrirBrute-mysql.git
```
**Mude para o diretorio do TwinCrows**
```
cd FenrirBrute-mysql
```
**Dê permissão de execussão**
```
chmod +x FenrirBrute-mysql.py
```
## Modo de uso
```
./FenrirBrute-mysql.py -a <host> -u <user list> -s <pass list>
```
**Exemplo**
```
./FenrirBrute-mysql.py -a 192.168.1.8 -u root -s pass_list.txt
```
## Instalação da biblioteca mysql.connector

Caso a biblioteca não esteja instalada, pode ser feita com o pip3
```
pip3 install mysql.connector
```

## Opções

|Opção|descrição|
|-----|---------|
| -a | Endereço do host alvo|
| -p | Porta do serviço ftp, padrão é 3306|
| -u | Usuário|
| -s | Lista de senhas|
| -v | Modo verbose, mostra todas as tentativas de login|
| -b | Testa senha em branco|
| -h | Exibe a ajuda|


![FB](https://raw.githubusercontent.com/leonardor666/images/main/fb/fbmysql1.png)

![FB](https://raw.githubusercontent.com/leonardor666/images/main/fb/fbmysql2.png)
