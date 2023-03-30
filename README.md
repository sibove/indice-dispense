# Dispense Matematica Uniud

## Il progetto
Questo è l'indice che raccoglie le dispense non ufficiali per gli insegnamenti dei corsi di laurea triennale e magistrale in Matematica presso Uniud.
Le dispense sono frutto del lavoro di studenti che hanno frequentato i corsi, e sono principalmente ottenute trascrivendo "in bella" gli appunti presi a lezione. 
Le dispense sono raggruppate in base all'anno accademico in cui i corsi sulle quali sono basate sono state erogate. 
Ogni dispensa ha una propria repository su Github, in cui sono disponibili i sorgenti $\LaTeX$ e ovviamente le dispense vere e proprie in formato pdf. 
L'idea è che, grazie a questo database condiviso, gli studenti che si approcciano a corsi per cui i professori non producono dispense possano partire da un progetto già sostanzialmente pronto, eventualmente adattando le dispense in base agli argomenti trattati, che come noto spesso variano di anno in anno. 

## Cose tecniche

### Perché Github e non...?
La scelta di Github come piattaforma è stata naturale considerando che è il più famoso ambiente di collaborazione per scrivere codice. La struttura dei progetti $\LaTeX$ delle dispense è pensata in modo da sfruttare le meccaniche di questo servizio, tra le quali ad esempio commit, branch ecc. Generalmente, infatti, ogni dispensa ha un file principale (`main.tex`) che contiene le indicazioni di carattere stilistico e i comandi di inclusione dei vari capitoli, e una cartella che contiene i file corrispondenti alle varie lezioni (`lezione01.tex`, `lezione02.tex`, ecc.). Questo consente di spartirsi il lavoro, prendendo in carico la trascrizione di una lezione alla volta mantenendo uno stile coerente all'interno del documento. 

### Come collaborare? 
Ci sono due situazioni: 
* La dispensa su cui vuoi lavorare esiste già. In questo caso è sufficiente aprire una issue sulla repository della dispensa, specificando cosa si vuole fare. Questo è importante per evitare che più persone facciano lo stesso lavoro!
* La dispensa non esiste ancora. In questo caso puoi creare tu la repository per essa, eventualmente clonando quella della dispensa dell'anno precedente per lo stesso corso, se lo ritieni opportuno e conveniente. Dopo averlo fatto, invia un commit per questo documento, aggiungendo in elenco il nome del corso e il link alla repository. Ora puoi iniziare!


## Dispense A.A. 2019/20
* Probabilità I

## Dispense A.A. 2020/21
* Istituzioni di Geometria Superiore, mod. 1 (Analisi complessa)
* Statistica I 
* Statistica II
* Metodi Numerici per Equazioni Differenziali

## Dispense A.A. 2021/22
* Istituzioni di Analisi Superiore, mod. 1
* [Matematiche Complementari](https://github.com/sibove/matcomp) (frattali)
