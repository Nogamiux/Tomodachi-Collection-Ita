# Tomodachi Collection Ita 

<h3 align="center">Traduzione italiana di Tomodachi Collection</h3>
<p align="center"> Questa è una traduzione basata sul leggendario Tomodachi Collection per Nintendo DS, titolo uscito esclusivamente in Giappone </p>
<p align="center"> ⚠ è La prima volta che mi cimento in questo mondo, per tanto ci potrebbero essere molti errori. sono comunque molto felice in caso vogliate provare questa traduzione. </p>
<p align="center"> Essendo una traduzione NON ufficiale, Bug, errori di traduzione, crash improvvisi ed errori di sintassi sono molto frequenti. per ogni cosa potete aprire una [Issue](https://github.com/Nogamiux/Tomodachi-Collection-Ita/issues) questo semplifica di molto la risoluzione dei bug. </p>

<br>
<br>

<p> Siamo partiti dalla versione di <a href="https://gbatemp.net/threads/unfinished-tomodachi-collection-english-translation-patch.357438/">jjjewel</a>, autore della patch inglese del gioco. </p>

 <s> ⚠️ Attualmente la Beta 2 NON funziona su TWiLight Menu++, sono necessari una qualsiasi Flashcard o emulatore come <a href="http://desmume.org/">DeSmuMe</a> o <a href="https://melonds.kuribo64.net/">MelonDS</a> </s>

 <h4> Dalla versione v27.17.1 di TWiLight Menu++, Tomodachi Collection - Ita (beta 2) è completamente supportato e non richiede più l'ausilio di flashcarts o emulatori </h4> 

<br>

## Patching

<h2 align="center"> COME BUILDARE </h2>

<h4 align="center"> Requisiti: </h4>

- Rom .nds di Tomodachi Collection 1.1 (NON OFFRIREMO ALCUN AIUTO SU COME TROVARE ONLINE IL GIOCO, DEVI POSSEDERE LA TUA COPIA)

- La patch italiana del gioco, la potete trovare nelle [releases](https://github.com/Peppe30brick/Tomodachi-Collection-Ita/releases)

- Un patcher Xdelta, ne esistono di numerosi, consigliamo [xdelta-wasm](https://kotcrab.github.io/xdelta-wasm/)

<br>

<h4 align="center"> Procedimento: </h4>

1. Una volta ottenuto tutto il necessario bisognerà accedere al sito linkato sopra
2. Nella voce "Source File" inserire la rom .nds di Tomodachi Collection 1.1
3. Nella voce "Patch file" inserire il file .xdelta scaricato nella pagina delle releases
4. Premere "Apply Patch", il download del gioco dovrebbe iniziare e sarete pronti per giocare

<br>

## Tabella dei File

| Nome File | Stato Traduzione | Descrizione |
| :--- | :---: | :--- |
| `tmd_common_msg_JP.bmg` | ✅ Completato | Pulsanti principali dell'interfaccia di sistema (es. Ok, Sì, No). |
| `tmd_contents_msg_JP.bmg` | ✅ Completato | Testi dei contenuti extra (es. descrizioni delle classifiche). |
| `tmd_costume_msg_JP.bmg` | ✅ Completato | Nomi e descrizioni degli articoli di abbigliamento. |
| `tmd_etc_msg_JP.bmg` | ✅ Completato | Testi vari: nomi/descrizioni caratteri, menu creazione Mii e intro del gioco. |
| `tmd_explain_msg_JP.tmd` | ✅ Completato | Richieste specifiche dei Mii (cibo, vestiti e oggetti). |
| `tmd_item_msg_JP.tmd` | ✅ Completato | Nomi e descrizioni degli oggetti. |
| `tmd_job_msg_JP.tmd` | ✅ Completato | Testi del (Job Diagnosis) e dei relativi lavori. |
| `tmd_mainroom_msg_JP.bmg` | ✅ Completato | Messaggi della panoramica stanze (Mii fuori casa, visite, nuove amicizie). |
| `tmd_miitouch_msg_JP.tmd` | ✅ Completato | Testi della tabella relazioni, informazioni del Mii e interfaccia dello schermo superiore. |
| `tmd_minicontents_msg_JP.tmd` | ✅ Completato | Eventi e contenuti minori quando il Mii non ha richieste attive. |
| `tmd_msg_JP.tmd` | ⌛ Non necessario | Messaggi di sistema generici o residui (da verificare). |
| `tmd_news_msg_JP.tmd` | ✅ Completato | Testi e dialoghi dei notiziari (Mii News). |
| `tmd_ng00_msg_JP.tmd` | ⌛ Non necessario | Filtro parole censurate (NG = No Good) - Parte 1. |
| `tmd_ng01_msg_JP.tmd` | ⌛ Non necessario | Filtro parole censurate (NG = No Good) - Parte 2. |
| `tmd_room_msg_JP.tmd` | ✅ Completato | Nomi e descrizioni degli stili degli appartamenti (Interni). |
| `tmd_select_msg_JP.tmd` | ✅ Completato | Finestre di dialogo e scelte multiple (es. proposte di fidanzamento). |
| `tmd_song_msg_JP.tmd` | ✅ Completato | Testi delle esibizioni musicali e stili delle canzoni. |
| `tmd_staff_msg_JP.tmd` | ⌛ Non necessario | Testi dei titoli di coda (Credits). |
| `tmd_talk_cool_JP.tmd` | ✅ Completato | Dialoghi dei Mii con personalità "Cool" (Sicuro di sé / Spigliato). |
| `tmd_talk_dry_JP.tmd` | ✅ Completato | Dialoghi dei Mii con personalità "Dry" (Indipendente / Pragmatico). |
| `tmd_talk_msg_JP.tmd` | ✅ Completato | Dialoghi generici di base, non legati a una personalità specifica. |
| `tmd_talk_nagomi_JP.tmd` | ✅ Completato | Dialoghi dei Mii con personalità "Nagomi" (Rilassato / Dolce). |
| `tmd_talk_nori_JP.tmd` | ✅ Completato | Dialoghi dei Mii con personalità "Nori" (Energico / Estroverso). |
| `tmd_trouble_msg_JP.tmd` | ✅ Completato | Domande e richieste d'aiuto generiche dei Mii. |

(Se ritrovate un errore di descrizione, non esitate a creare una issue, o contattare me o collaboratori su social come discord. non essendo molto esperto potrei aver sbagliato alcune descrizioni.)

<h2 align="center"> Che Tool Abbiamo Usato? </h2>

Editor Esadecimale [HxD](https://mh-nexus.de/en/hxd/) By Maël Hörz

Rom Editor [Tinke](https://github.com/pleonex/tinke) By pleonex

Image Editor [NitroPaint](https://github.com/Garhoogin/NitroPaint/releases) By Garhoogin
And [Crystal Tile 2](https://www.romhacking.net/utilities/818/) By Angel Team

Bmg Editor [MSBT Editor](https://gitlab.com/AeonSake/msbt-editor) By Aeon
and [EditorArquivoBMG](https://www.romhacking.net/utilities/1132/) By Viniciusmlschulz

Xdelta Patcher [Xdelta UI](https://www.romhacking.net/utilities/598/) By KaioShin

AP-Patch for TWL++ Support [RocketRobz](https://github.com/RocketRobz)

<h2 align="center"> CREDITI </h2>

- [Nogamiux](https://gitlab.com/Nogamiux) (Lead Developer)

- [Sasso.Figo](https://github.com/SassoFigo) (Translator)

- [LeoChrom](https://github.com/LeoChrom) (Translator)

- [Ricky676k](https://github.com/ricky676k) (Translator)

- [CertifiedRhm](https://github.com/CertifiedRhm) (Translator)

- [DefeatOf13](https://github.com/DefeatOf13) (Translator)

- [Mutty](https://gitlab.com/fraerostaticon) (Translator)

- [20Mimikyu07](https://gitlab.com/20Mimikyu07) (Translator)

- [Simo3ds](https://github.com/Simo3ds) (Translator)

- [Pako](https://github.com/PakoJSTL) (Translator)

- [RocketRobz](https://github.com/RocketRobz) (Twilight Menu++ Maintainer & Developer)