# Spring Tools 4

## Linux 64 - STS4-v4.15.3
  [https://download.springsource.com/release/STS4/4.15.3.RELEASE/dist/e4.24/spring-tool-suite-4-4.15.3.RELEASE-e4.24.0-linux.gtk.x86_64.tar.gz](https://download.springsource.com/release/STS4/4.15.3.RELEASE/dist/e4.24/spring-tool-suite-4-4.15.3.RELEASE-e4.24.0-linux.gtk.x86_64.tar.gz)


## Windows 64 - STS4-v4.15.3
[https://download.springsource.com/release/STS4/4.15.3.RELEASE/dist/e4.24/spring-tool-suite-4-4.15.3.RELEASE-e4.24.0-win32.win32.x86_64.self-extracting.jar](https://download.springsource.com/release/STS4/4.15.3.RELEASE/dist/e4.24/spring-tool-suite-4-4.15.3.RELEASE-e4.24.0-win32.win32.x86_64.self-extracting.jar)

## Lombok - v1.18.24
[https://projectlombok.org/downloads/lombok.jar](https://projectlombok.org/downloads/lombok.jar)


## Instalação no Linux

```s
# Baixar e descompacta arquivo
sudo tar xf spring-tool-suite-4-4.15.3.RELEASE-e4.24.0-linux.gtk.x86_64.tar.gz -C /opt/

# Instalar o Lombok, configurar para o diretório do Spring-tools
java -jar lombok.jar

# Mudar Tema para dark ou Light
# Winddow -> Preferences -> General -> Appearance

# Rodar vários projetos no Spring-tools
# Alterar porta em cada projeto
# Ir no projeto
# Boot Dashboard -> Open Config -> Overrride properties: server.port=8080

# Adicionando dependencia
# botão direito em cima do projeto, ir em Spring, Add Starters e escolhe a dependencia. Exemplo Lombok

```
