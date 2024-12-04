# Sniffing Attack using Wireshark


![0S6SCfZB7OR4LEDcx](https://github.com/user-attachments/assets/5b2db472-1d46-4a24-aca2-1f5e73a7b705)




<p><em>Un attacco di sniffing implica l'intercettazione e l'analisi del traffico di rete per catturare informazioni sensibili come nomi utente, password e altri dati. Wireshark è un popolare analizzatore di protocolli di rete che può essere utilizzato per la risoluzione dei problemi e l'analisi della rete, ma può anche essere abusato per scopi malevoli, come gli attacchi di sniffing.</em></p>


<h1>Passo 1: Avviare Wireshark</h1>
<ol>
  <li>Apri Wireshark.</li>
  <li>Vedrai un elenco delle interfacce di rete disponibili. Scegli l'interfaccia che desideri monitorare (ad esempio, Wi-Fi o Ethernet).</li>
</ol>
<h1>Passo 2: Catturare il Traffico</h1>
<ol>
  <li>Clicca sull'interfaccia per iniziare a catturare i pacchetti.</li>
  <li>Puoi applicare filtri per catturare tipi specifici di traffico. Ad esempio, per catturare il traffico HTTP, puoi utilizzare il filtro http.</li></li>
</ol>
<h1>Passo 3: Analizzare i Pacchetti Catturati</h1>
<ol>
  <li>Man mano che i pacchetti vengono catturati, appariranno in tempo reale nell'interfaccia di Wireshark.</li>
  <li>Clicca su un pacchetto per visualizzarne i dettagli. Puoi espandere i dettagli del pacchetto per vedere i vari livelli (Ethernet, IP, TCP, ecc.).</li>
  <li>Cerca informazioni sensibili nei dettagli del pacchetto, come nomi utente e password non crittografati.</li>
</ol>
<h1>Passo 4: Fermare la Cattura</h1>
<ol>
  <li>Clicca sul pulsante rosso quadrato nella barra degli strumenti per fermare la cattura dei pacchetti.</li>
  <li>Puoi salvare i pacchetti catturati per un'analisi successiva andando su File > Save As.</li>
</ol>

<hr/>

<h1>Esempio: Catturare Traffico HTTP</h1>
<ol>
 <li>Inizia a catturare pacchetti sull'interfaccia desiderata.</li> 
  <li>Apri un browser web e naviga verso un sito web che utilizza HTTP (non HTTPS).</li>
  <li>In Wireshark, puoi filtrare i pacchetti catturati inserendo http nella barra dei filtri.</li>
  <li>Cerca pacchetti che contengono richieste GET o POST. Puoi visualizzare i dettagli del pacchetto per vedere i dati trasmessi</li>
</ol>

<h1>Esempio: Utilizzo dei Filtri</h1>
<ul>
  <li>Per filtrare protocolli specifici, puoi utilizzare:</li>
  <li>http per il traffico HTTP</li>
  <li>tcp per il traffico TCP</li>
  <li>udp per il traffico UDP</li>
  <li>ip.addr == 192.168.1.1 per filtrare i pacchetti da un indirizzo IP specifico</li>
</ul>



![image](https://github.com/user-attachments/assets/29bd6be8-e26a-434a-9a9d-0b0d1a854b72)


![image](https://github.com/user-attachments/assets/35572dac-b751-44aa-9f78-f642e0b0990a)


![image](https://github.com/user-attachments/assets/77f78e92-9f66-4dbe-9c8c-1b4fb12a5206)


![image](https://github.com/user-attachments/assets/d0af4881-c6ae-410f-98cb-56bfaa3d507a)

![image](https://github.com/user-attachments/assets/56fd217e-0f33-40d0-8a24-5cc38948b804)
