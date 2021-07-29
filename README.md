# Automatizar FTP com o GitHub Actions
Afim de compreender melhor o uso do Github Actions esse projeto tem como objetivo automatizar e/ou integrar as alterações usando o FTP pelo Github Actions.

## Pre-requisitos
Ter um servidor de FTP com usuário e senha configurados.

```
Observação: Para esse projeto criei uma instância na aws com um servidor FTP configurado usando o VSFTP.
```

## Configuração
Dentro desse repositório é necessário criar algumas secrets com as credenciais e o host do servidor FTP.
Abaixo segue as secrets que configurei:

```
host_ftp
```

```
user_ftp
```

```
password_ftp
```
