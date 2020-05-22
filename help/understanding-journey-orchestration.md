---
title: Informazioni sull'orchestrazione del viaggio
description: Comprendere il concetto di orchestrazione del viaggio, i tipi di casi di utilizzo attivati e gli elementi chiave di come funziona l'orchestrazione del viaggio.
feature: Journey Orchestration
topics: Introduction
kt: 2773
audience: user, developer
doc-type: video
activity: understand
translation-type: tm+mt
source-git-commit: 795b30fe984b7fe715789144e8c421028d7d32ac
workflow-type: tm+mt
source-wordcount: '326'
ht-degree: 0%

---


# Informazioni [!UICONTROL Journey Orchestration]

## Introduzione a [!UICONTROL Journey Orchestration]

[!UICONTROL Journey Orchestration] consente di creare casi di utilizzo orchestrazione in tempo reale utilizzando i dati contestuali memorizzati in eventi o origini dati.

[!UICONTROL Journey Orchestration] è un servizio di applicazione integrato con Adobe Experience Platform. Offre un ecosistema intelligente e aperto per attivare tutti i dati live pertinenti attraverso un coinvolgimento scalabile basato su eventi su qualsiasi canale richiesto dalla vostra azienda, dal marketing alle operazioni di assistenza. [!UICONTROL Journey Orchestration] puoi sfruttare qualsiasi dato proveniente da Adobe Experience Platform e da qualsiasi sistema di distribuzione esterno per creare e distribuire esperienze coinvolgenti.

Il video seguente introduce

* Il concetto di [!UICONTROL Journey Orchestration]
* Tipi di casi di utilizzo che consente
* Gli elementi chiave del [!UICONTROL Journey Orchestration] funzionamento

>[!VIDEO](https://video.tv.adobe.com/v/29307?quality=12)

## Come configurare un percorso

Le principali fasi di preparazione per i viaggi di costruzione sono:

1. [Configura eventi](/help/configuring-journey-orchestration/configure-streaming-events.md) di streaming - Questa configurazione è obbligatoria, in quanto [!UICONTROL Journey Orchestration] è progettata per ascoltare gli eventi.
2. [Configurare Origini](/help/configuring-journey-orchestration/configure-data-sources.md) dati - Questa configurazione non è necessaria se i viaggi sfruttano solo i dati locali provenienti da un payload di eventi.
3. [Configura azioni](/help/configuring-journey-orchestration/configure-actions.md)personalizzate: Obbligatorio se si desidera utilizzare un servizio di qualsiasi provider di terze parti che può essere chiamato tramite un [!DNL REST API] payload formattato JSON

>[!NOTE]
>Questi passaggi di configurazione richiedono conoscenze tecniche. Sarà necessario avere familiarità con il modello dati [esperienza (XDM)](https://docs.adobe.com/content/help/en/platform-learn/tutorials/schemas/understanding-the-xdm-system-and-experience-data-model.html)e [come comporre gli schemi](https://docs.adobe.com/content/help/en/platform-learn/tutorials/schemas/create-your-first-schema-with-out-of-the-box-components.html)eventi esperienza XDM.

## Come creare, pubblicare e analizzare un percorso

1. [Crea un viaggio](/help/create-a-journey.md)
2. [Convalida e pubblicazione di un percorso](/help/validate-and-publish-a-journey.md)
3. [Analizzare un viaggio mediante gli strumenti di reporting](/help/analyze-a-journey-via-reporting-tools.md)

## Risorse aggiuntive

* [Centro di assistenza per l&#39;orchestrazione del viaggio](https://docs.adobe.com/content/help/en/journeys/using/journey-orchestration-home.html)
* [Esercitazioni sulla piattaforma Adobe Experience](https://docs.adobe.com/content/help/en/platform-learn/tutorials/overview.html)
* [Come trovare aiuto con l&#39;orchestrazione del viaggio](/help/understanding-journey-orchestration.md)
* [SDK di Adobe Experience Platform Mobile - Lancio](https://docs.adobe.com/content/help/en/core-services-learn/tutorials/launch-mobile/understanding-the-mobile-sdks.html)
* [Adobe Experience Platform Location Service](https://docs.adobe.com/content/help/en/places/using/home.html)
