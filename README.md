# script_wg.pl
This is a Word Generator: you can apply some useful options to filter the  words

Encontrei um script em perl que faz todo o trabalho por nos.
O script e capaz de fazer varias combinações inclusive de quebrar senha WPA, alem de uma grande extensão de palavras. O nome do script em perl e Words Generator no português Gerador de Palavras, salve o script abaixo com a extensão .pl, eu sevei com as siglas do nome WG.
Exemplo de como utilizar o script:


No meu caso, como uso Linux salvei o arquivo e de a permissão de torno-lo executável "#chmod +x wg.pl" ou poderia usar a seguinte linha "perl wg.pl" que executaria o script da mesma forma. No windows e so instalar o ActivePerl.

Usei em esse comando:

./wg.pl -l 8 -u 64 -v abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWX YZ0123456789\`\~\!\@\#\$\%\^\&\*\(\)\-\_\+\=\[\]\;\’\,\.\/\<\>\?\:\”\{\}\|\ > words.txt

-l --> Tamanho minimo da palavra
-u --> Tamanho máximo da palavra
-v --> Listar os caracteres que eu vou querer na minha wordlist
> words.txt --> E para salva as palavras(Onde ta words.txt pode ser qualquer nome).

Então minha wordlist vai no minimo 8 caráteres e no máximo 86.
