# HackForMe
## gobuster
Abbiamo un Software di una banca nel desktop e una WorldList cioè un elenco di parole da scorrere per trovare le pagine nascoste.
La banca non ha una conessione sicura per questo possiamo facilmente entare per far danno.

Con gobuster possiamo trovare tutte le pagine nascoste.

Ex: gobuster -u http://fakebank.com -w wordlist.txt dir

-u viene utilizzato per indicare che il sito web che stiamo analizzando -w accetta un elenco di parole da scorrere per trovare le pagine nascoste.
