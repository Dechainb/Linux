## Avvia Surface da un'unità USB
Nota: Se non desideri avviare Surface dall'unità USB, assicurati che l'unità non sia inserita nella porta USB di Surface all'avvio.

Per tutti i modelli di Surface 
- Prima dell'avvio, assicurati che non vi siano altri dispositivi USB collegati a Surface, ad esempio mouse, tastiere o altre unità di archiviazione. Surface tenterà di eseguire l'avvio da altri dispositivi USB collegati. Ecco come procedere all'avvio da una USB. 
- Spegni Surface.
- Inserisci l'unità USB avviabile nella porta USB di Surface.
- Tieni premuto il tasto di riduzione del volume di Surface. Mentre esegui questa operazione, premi e rilascia il pulsante di alimentazione.
- Il logo Microsoft o Surface viene visualizzato sullo schermo. Continua a tenere premuto il tasto di riduzione del volume. Rilascia il pulsante quando i puntini che ruotano vengono visualizzati sotto il logo.
- Segui le istruzioni visualizzate per avviare il sistema dall'unità USB.

## Avvia dall'USB tramite Windows
Se si verificano problemi con l'avvio di Surface tramite l'USB di avvio, è possibile avviarlo tramite Windows. Ecco come fare:
- Inserisci l'unità USB nella porta USB, quindi seleziona Start  > Settings > Update & security > Recovery.
- In Avvio avanzato seleziona Riavvia ora.
- Nella schermata Scegli un'opzione seleziona Utilizza un dispositivo > Archiviazione USB.

## Configura Surface per l'avvio da un dispositivo USB
Dopo aver configurato l'unità USB come unità di avvio con un sistema operativo appropriato, dovrai configurare Surface per l'avvio da questa unità. Per questa operazione è necessario apportare modifiche nella UEFI in modo che l'unità USB costituisca la prima opzione. Ecco come:

- Spegni Surface.
- Dopo lo spegnimento di Surface, tieni premuto il pulsante di aumento del volume.
- Tenendo premuto il tasto di aumento del volume, premi e rilascia il pulsante di alimentazione di Surface.
- Continua a tenere premuto il tasto di aumento del volume finché il logo di Surface o di Windows non è più visualizzato sullo schermo.
- A questo punto dovrebbe essere visualizzata la UEFI di Surface. È necessario seguire istruzioni specifiche affinché Surface proceda.

## Modifica l'ordine di avvio
È necessario modificare l'ordine di avvio affinché Surgace si avvia da una USB.

Per i modelli surface più recenti, per modificare la configurazione di avvio di Surface:
- Seleziona Boot configuration.
- Seleziona USB Storage e trascina questa voce in cima all'elenco. In alternativa, scorri rapidamente verso sinistra su USB Storage per avviare immediatamente il dispositivo. L'ordine di avvio non verrà alterato.
- Seleziona Esci e quindi seleziona Riavvia.

[support.microsoft][def]

[def]: https://support.microsoft.com/it-it/surface/avviare-surface-da-un-dispositivo-usb-fe7a7323-8d1d-823d-be17-9aec89c4f9f5#WindowsVersion=Windows_10