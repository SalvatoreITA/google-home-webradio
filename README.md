<h1 style="text-align: center;">Google Home WebRadio su Home Assistant V 1.0</h1>
<center><img class="aligncenter wp-image-1369 size-medium" src="https://github.com/SalvatoreITA/radio-google/blob/main/Radio%2001.PNG" alt="" width="239" height="365" /></center>
2.Installazione "<strong>Google Home WebRadio</strong>"</h3>
- Copiare il file "<strong>gh_webradio</strong>" nella cartella "<strong>package</strong>"

<img class="aligncenter size-full wp-image-1361" src="https://domhouse.it/wp-content/uploads/2020/11/002.png" alt="" width="594" height="487" />

- Aprire il package "<strong>gh_webradio</strong>" e modificare i seguenti parametri:
<ul>
 	<li>Inserire i media player esempio media_player.salotto dovrà essere inserito solo salotto</li>
 	<li><strong>Initial:</strong> Inserire il media player di default</li>
 	<li><strong>volume_level: </strong>volume impostato quando la radio va in <strong>ON</strong></li>
 	<li><strong>volume_level: </strong>volume impostato quando la radio va in <strong>OFF</strong></li>
</ul>
- Salvare le modifiche

<img class="aligncenter size-full wp-image-1367" src="https://domhouse.it/wp-content/uploads/2020/11/000000000000000005.png" alt="" width="1423" height="858" />

– Recarsi su “<strong>Impostazioni</strong>” e successivamente su  “<strong>Controlli del Server</strong>”

<img class="aligncenter size-large wp-image-292 lazyloaded" src="https://www.domhouse.it/wp-content/uploads/2020/02/ooio-1024x501.png" alt="" width="747" height="365" data-src="https://www.domhouse.it/wp-content/uploads/2020/02/ooio-1024x501.png" />
– Cliccare su “<strong>Controlla la Configurazione</strong>“; se tutto è Ok, verrà visualizzato il messaggio  “<strong>Configurazione Valida</strong>”

<img class="aligncenter size-full wp-image-293 ls-is-cached lazyloaded" src="https://www.domhouse.it/wp-content/uploads/2020/02/56.png" alt="" width="761" height="299" data-src="https://www.domhouse.it/wp-content/uploads/2020/02/56.png" />

– Successivamente, “<strong>Riavviare</strong>” il sistema.

<img class="aligncenter size-full wp-image-295 ls-is-cached lazyloaded" src="https://www.domhouse.it/wp-content/uploads/2020/02/57.png" alt="" width="711" height="177" data-src="https://www.domhouse.it/wp-content/uploads/2020/02/57.png" />
<h3><strong>3.</strong><strong>Creazione card in Lovelace</strong></h3>
– Aprire il file  “<strong>gh_webradiocard lovelace</strong>”, selezionare le<strong> righe</strong> di <strong>codice</strong> e copiarle (<strong>Ctrl+C</strong>).

<img class="aligncenter size-full wp-image-1365" src="https://domhouse.it/wp-content/uploads/2020/11/0001-1.png" alt="" width="334" height="134" />

–  Cliccare su “<strong>Configurare l’interfaccia Utente</strong>”

<img class="aligncenter wp-image-402 size-large lazyloaded" src="https://www.domhouse.it/wp-content/uploads/2020/02/sonoff6-1024x246.png" alt="Sonoff su Home Assistant 2" width="747" height="179" data-src="https://www.domhouse.it/wp-content/uploads/2020/02/sonoff6-1024x246.png" />

– Selezionare ” <strong>+</strong> ”

<img class="aligncenter size-large wp-image-403 lazyloaded" src="https://www.domhouse.it/wp-content/uploads/2020/02/sonoff7-1024x421.png" alt="" width="747" height="307" data-src="https://www.domhouse.it/wp-content/uploads/2020/02/sonoff7-1024x421.png" />

– Cliccare sulla voce “<strong>Manuale</strong>”

<img class="aligncenter wp-image-714 size-large lazyloaded" src="https://www.domhouse.it/wp-content/uploads/2020/03/07-1-1024x795.png" alt="" width="640" height="497" data-src="https://www.domhouse.it/wp-content/uploads/2020/03/07-1-1024x795.png" />

– Incollare le righe precedentemente selezionate (<strong>Ctrl+V</strong>) e Salvare cliccando su “<strong>Salva</strong>”

<img class="aligncenter size-full wp-image-1366" src="https://domhouse.it/wp-content/uploads/2020/11/0005.png" alt="" width="999" height="867" />
