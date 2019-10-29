---
layout: page
title: Nodo di smistamento degli ordini di acquisto delle amministrazioni pubbliche (NSO)
description:
lang: it
ref: nso
order: 6
child_of_ref: e-procurement
---

Come previsto dalla Legge di bilancio 2018, a decorrere dalla data che sarà stabilita con appositi decreti ministeriali,
gli acquisti pubblici legati al settore sanitario saranno gestiti
con ordini elettronici (eOrder). NSO, il "nodo di smistamento per gli ordini di acquisto della pubblica
amministrazione" gestito dal Ministero dell'Economia e delle Finanze (MEF), è il gateway centrale per
lo scambio di ordini elettronici tra enti pubblici e fornitori.

Il formato del documento eOrder adottato da NSO è conforme alle specifiche tecniche PEPPOL BIS 3.0,
disponibili al seguente <a aria-label="PEPPOL BIS 3.0 - Collegamento a sito esterno" href="https://docs.peppol.eu/poacc/upgrade-3/" title="Collegamento a sito esterno">link</a>.

Maggiori informazioni su NSO sono disponibili sul
<a aria-label="Ministero dell'Economia e delle Finanze - Collegamento a sito esterno" href="http://www.rgs.mef.gov.it/VERSIONE-I/e_government/amministrazioni_pubbliche/acquisti_pubblici_in_rete_apir/nodo_di_smistamento_degli_ordini_di_acquisto_delle_amministrazioni_pubbliche_nso/" title="Collegamento a sito esterno">sito web</a> del MEF.

PEPPOL, tra gli altri canali, è supportato da NSO come infrastruttura ufficiale per la trasmissione di eOrder.

## PEPPOL e NSO

Secondo le regole tecniche di NSO, l'acquirente deve interagire con NSO per convalidare un documento eOrder:
questa azione può essere intrapresa direttamente dall'acquirente o da un intermediario prima di inviare il documento.

Se l’eOrder viene indirizzato a un fornitore, il cui identificativo è dato da un Participant ID PEPPOL, il messaggio
verrà recapitato attraverso la rete PEPPOL. Ciò significa che se sei un Access Point (AP) Service Provider e i tuoi
clienti devono ricevere documenti eOrder da un ente pubblico italiano, allora non ci sono azioni da intraprendere
poiché le specifiche PEPPOL saranno sufficienti per ricevere il messaggio.

Invece, se sei un AP Service Provider che funge da intermediario per una pubblica amministrazione italiana (acquirente),
devi adottare uno dei canali disponibili per comunicare con NSO per la fase di convalida prima di inoltrare l'eOrder
sulla rete PEPPOL. I canali sono gli stessi disponibili per SdI, il Sistema di Interscambio nazionale delle fatture
elettroniche; maggiori informazioni sono disponibili
al seguente <a aria-label="FatturaPa - Collegamento a sito esterno" href="https://www.fatturapa.gov.it/export/fatturazione/en/normativa/f-3.htm" title="Collegamento a sito esterno">link</a>.

Tuttavia, uno scenario complesso che richiede al fornitore di rispondere all'acquirente (come "Ordine" e "Contratto di ordine")
potrebbe richiedere azioni diverse ai fornitori di servizi AP. Maggiori specifiche sono disponibili sul
<a aria-label="Ministero dell'Economia e delle Finanze - Collegamento a sito esterno" href="http://www.rgs.mef.gov.it/VERSIONE-I/e_government/amministrazioni_pubbliche/acquisti_pubblici_in_rete_apir/nodo_di_smistamento_degli_ordini_di_acquisto_delle_amministrazioni_pubbliche_nso/" title="Collegamento a sito esterno">sito web</a> del MEF.