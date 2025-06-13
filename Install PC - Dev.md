# Dev - Java

## JDK 11
- [ ] Copiar de `S:\Softwares\Java\JDK` para `C:\Program Files\Java`
- [ ] [JDK 11 Downloads](https://www.oracle.com/java/technologies/javase/jdk11-archive-downloads.html)
- [ ] [Java Downloads](https://www.oracle.com/java/technologies/downloads/)

## Configuração de Ambiente
- [ ] Configurar variáveis de ambiente Java e Maven
  - [Guia de Configuração](https://medium.com/beelabacademy/configurando-vari%C3%A1veis-de-ambiente-java-home-e-maven-home-no-windows-e-unix-d9461f783c26)

## Maven
- [ ] [Download](https://maven.apache.org/download.cgi)
- [ ] Instalar em `C:\Program Files\Apache\apache-maven-3.8.6`
- [ ] [Guia de Instalação](https://maven.apache.org/install.html)

## IDEs e Editores
### VS Code
- [ ] [Download](https://code.visualstudio.com/docs/?dv=win)

### IntelliJ IDEA
- [ ] [Download](https://www.jetbrains.com/pt-br/idea/download/#section=windows)
- [ ] Importar configurações da IDE de `S:\Desenvolvimento\IDE\IntelliJ\Configurações IDE`

### Spring Tool Suite
- [ ] [Download](https://spring.io/tools)
- [ ] Descompactar em `C:\Program Files\SpringToolSuite`
- [ ] Criar atalho para desktop
- [ ] Configurar workspace para `D:\Desenvolvimento\Java\Projetos\workspace sts`

## Ferramentas de Comunicação
### Discord
- [ ] [Download](https://discord.com/download)
- [ ] Em caso de erros de conexão, configurar DNS do Google (8.8.8.8 e 8.8.4.4)
  - [Vídeo de referência](https://www.youtube.com/watch?v=7HQTRQ07SOQ)

### Slack
- [ ] [Download](https://slack.com/intl/pt-br/downloads/windows)

## Terminal
### Cmder
- [ ] [Download](https://cmder.net/)
- [ ] Adicionar ao PATH: `C:\Program Files\cmder`

## Editores de Texto
### Sublime Text 3
- [ ] [Download](https://www.sublimetext.com/3)

## Ferramentas de API
### Postman
- [ ] [Download](https://www.postman.com/downloads/)
- [ ] Importar variáveis de ambiente de `D:\Users\Alvaro\Google Drive\Sync\Trabalho\Diazero\postman`

## Banco de Dados
### MySQL Workbench
- [ ] [Download](https://www.mysql.com/products/workbench/)
- [ ] Configurações e importar dumps QA e Local de `D:\Users\Alvaro\Google Drive\Sync\Trabalho\Diazero\BD\mysql`

### HeidSQL
- [ ] [Download](https://www.heidisql.com/download.php)

## Docker
### Instalação
- [ ] [WSL2](https://docs.microsoft.com/pt-br/windows/wsl/install-manual#step-4---download-the-linux-kernel-update-package)
- [ ] [Docker Desktop](https://docs.docker.com/desktop/windows/install/)
- [ ] [Guia de instalação](https://www.youtube.com/watch?v=sYsIoWtS5LY&t=3s)

### Imagens Docker
#### Keycloak
```bash
docker run -p 8080:8080 -e KEYCLOAK_ADMIN=admin -e KEYCLOAK_ADMIN_PASSWORD=admin quay.io/keycloak/keycloak:18.0.2 start-dev
```

#### RabbitMQ
```bash
docker run -d -e RABBITMQ_NODENAME=my-rabbit --name rabbitmq -p 8082:15672 -p 61613:61613 -p 5671:5671 -p 5672:5672 -e RABBITMQ_DEFAULT_USER=admin -e RABBITMQ_DEFAULT_PASS=rabbit resilva87/docker-rabbitmq-stomp
```

#### MySQL
```bash
docker run -p 3307:3306 --name mysql -e MYSQL_ROOT_PASSWORD=iniciar -e MYSQL_DATABASE=portal -d mysql:8.0.21 --default-authentication-plugin=mysql_native_password
```

## Controle de Tempo
### Toggl Track
- [ ] [Download](https://toggl.com/track/time-tracking-windows/)

## Controle de Versão
### Git
- [ ] [Download](https://git-scm.com/download/win)

### TortoiseGit
- [ ] [Download](https://tortoisegit.org/download/)
- [ ] Utilizar chaves SSH:
  - `D:\Users\Alvaro\Google Drive\Sync\Putty Key\Notebook Samsung`
  - `D:\Users\Alvaro\Google Drive\Sync\Putty Key\MiniPC Ryzen9\rsa-key-20230620`

### Configuração do SSH
#### Arquivos do Git
- [ ] Copiar arquivos de `D:\Users\Alvaro\Google Drive\Sync\Putty Key\arquivos\git` para `C:\Program Files\Git\etc\ssh`

#### Arquivos do Usuário SSH
- [ ] Copiar arquivos de `D:\Users\Alvaro\Google Drive\Sync\Putty Key\arquivos\ssh - user\.ssh` para `C:\Users\alvar\.ssh`

#### Gerar Novas Chaves
- [ ] Ver instruções em `D:\Users\Alvaro\Google Drive\Sync\Putty Key\MiniPC Ryzen9\Readme.txt`

## Ferramentas de Desenvolvimento
### WinMerge
- [ ] [Download](https://winmerge.org/)

### FortiClient
- [ ] [Download](https://www.fortinet.com/support/product-downloads)

### Node.js
- [ ] [Download](https://nodejs.org/pt-br/download/)

### Movavi Video Suite
- [ ] Instalar de `S:\Softwares\Video\Movavi\Movavi Video Suite 21.2.0`

### Veracode
- [ ] Baixar e instalar o plugin Veracode Greenlight para IntelliJ
- [ ] [Veracode Analysis Center](https://analysiscenter.veracode.com/)
- [ ] Configurar credenciais
  - [Guia de Configuração](https://docs.veracode.com/r/t_configure_credentials_windows)
