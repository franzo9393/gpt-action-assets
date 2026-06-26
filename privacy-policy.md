# Privacy policy — Custom GPT Action

Questa Custom GPT Action usa GitHub API per leggere file Markdown da una repository privata autorizzata e per creare issue strutturate di richiesta aggiornamento quando previsto dalla configurazione.

Dati trattati:
- richieste tecniche necessarie a recuperare file Markdown dalla repository configurata;
- testo inserito dall'utente in una richiesta di aggiornamento, quando viene creata una GitHub Issue;
- token OAuth GitHub gestito da OpenAI/GitHub secondo le rispettive impostazioni;
- contenuto dei file autorizzati recuperati tramite Action.

La Action non deve:
- leggere repository diverse da quella configurata;
- scrivere o modificare direttamente file della Knowledge Base;
- creare pull request o commit;
- trattare credenziali, password o dati bancari in chiaro.

Gli utenti devono avere accesso GitHub alla repository privata configurata per usare la Action in modalità OAuth.
