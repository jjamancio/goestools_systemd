# goestools_systemd
Esse repositório disponibiliza unit files para executar o goestools como serviço no Linux.

Esse README considera que o goestools esteja instalado e funcionando (recebendo imagens).

Ao utilizar esse repositório, vocẽ deverá:

- Ajustar o arquivo de configuração goesrecv.conf 
- Alterar o parâmetro "WorkDirectory" no arquivo goesproc.service de acordo com o seu ambiente

O arquivo goesrecv.conf está configurado para trabalhar com o dongle RTL-SDR V3.
Para trabalhar com o airspy, altere todas as entradas no arquivo: 

- De: rtlsdr
- Para: airspy

Se você ainda não instalou os binários do goestools para Linux, considere seguir a documentação oficial no link: 

https://pietern.github.io/goestools/installation.html

