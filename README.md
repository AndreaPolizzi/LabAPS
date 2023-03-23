Nome del caso d’Uso: InserisciContatto
Portata: Rubrica
Livello: Utente
Attore Primario: Utente
Parti interessate e interessi: L’utente vuole poter inserire un nuovo contatto in rubrica
Pre-condizioni: Il contatto non deve essere già salvato in rubrica
Post-condizioni: Il contatto viene salvato in rubrica
Scenario principale di successo:
1. Il caso d’uso inizia quando Utente apre la propria rubrica
2. Il sistema mostra l’elenco dei contatti attualmente in rubrica
3. L’Utente specifica di voler inserire un nuovo contatto
4. Il sistema chiede di inserire i dati del contatto da aggiungere in rubrica
5. L’Utente inserisce i dati richiesti dal sistema
6. Il sistema inserisce il contatto in rubrica e notifica l’utente dell’inserimento avvenuto correttamente
Estensioni:
6a. Nome contatto già presente
6a.1 Il sistema notifica che il nome del contatto è già presente in rubrica
6a.2 L’Utente annulla l’operazione
6b. Numero di telefono errato
6b.1 Il sistema notifica che il numero di telefono del contatto è errato
6b.2 L’Utente corregge il numero e conferma torna poi al passo 5
6c. Limite massimo di contatti raggiunto
6c.1 Il sistema notifica che la rubrica è piena e il contatto non può essere aggiunto
6c.2 L’Utente annulla l’operazione
Extension Points:
Extension point “Contatto protetto” per UC InserisciContattoProtetto si verifica al passo 2 dello scenario
principale di successo
Requisiti Speciali: nessuno
Frequenza di ripetizione: ininterrotta
Nome del caso d’Uso: RimuoviContatto
Portata: Rubrica
Livello: Utente
Attore Primario: Utente
Parti interessate e interessi: L’utente vuole poter rimuovere un contatto dalla rubrica
Pre-condizioni: Il contatto esiste in rubrica
Post-condizioni: Il contatto viene rimosso dalla rubrica associata all’utente
Scenario Principale di Successo:
1. Il caso d’uso inizia quando Utente apre la propria rubrica
2. Il sistema mostra l’elenco dei contatti attualmente in rubrica
3. L’Utente seleziona un contatto da rimuovere dalla rubrica
4. Il sistema rimuove il contatto e notifica Utente della rimozione avvenuta correttamente
Estensioni:
4a. Contatto protetto
4a.1 Il sistema notifica che il contatto da rimuovere è protetto e non potrà essere rimosso
4a.2 L’utente annulla l’operazione
Requisiti Speciali: nessuno
Frequenza di ripetizione: ininterrotta
