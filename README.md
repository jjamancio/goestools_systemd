# goestools_systemd
Arquivos unit para executar os processos do goestools

Esse repositório disponibiliza unit files para executar o goestools como serviço no Linux.

Esse README considera que o goestools esteja instalado e funcionando (recebendo imagens).

- Faça os ajustes necessários no arquivo de configuração goesrecv.conf 
- Altere o parãmetro "WorkDirectory" no arquivo goesproc.service

O arquivo goesrecv.conf está configurado para trabalhar com o dongle RTL-SDR V3.
Para trabalhar com o airspy, altere todas as entradas no arquivo: 

- De: rtlsdr
- Para: airspy

Se você ainda não instalou os binários do goestools para Linux, considere seguir a documentação oficial no link: 

https://pietern.github.io/goestools/installation.html

