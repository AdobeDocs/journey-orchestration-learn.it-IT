---
title: Comprensione di Journey Orchestration
description: “Comprendere il concetto di Journey Orchestration, i tipi di casi d’uso che consente e gli elementi chiave del suo funzionamento.”
feature: Panoramica
topics: Introduction
kt: 2773
thumbnail: 29307.jpg
audience: user, developer
doc-type: video
activity: understand
role: Professionista, Amministratore
translation-type: ht
source-git-commit: dcfca5cee7399c2e708d29dbc7dcdea1114805f5
workflow-type: ht
source-wordcount: '330'
ht-degree: 100%

---


# Comprensione di [!UICONTROL Journey Orchestration]

## Introduzione a [!UICONTROL Journey Orchestration]

[!UICONTROL Journey Orchestration] consente di generare casi di utilizzo di orchestrazione in tempo reale, sfruttando i dati contestuali archiviati negli eventi o nelle origini dati.

[!UICONTROL Journey Orchestration] è un servizio applicativo integrato con Adobe Experience Platform. Fornisce un ecosistema intelligente e aperto per attivare tutti i dati dinamici pertinenti attraverso un impegno scalabile basato su eventi, su qualsiasi canale richiesto dalla tua azienda, dal marketing alle operazioni ai servizi. [!UICONTROL Journey Orchestration] è in grado di sfruttare qualsiasi dato proveniente da Adobe Experience Platform e da qualsiasi sistema di consegna esterno per creare e consegnare esperienze irresistibili.

Il video seguente introduce

* Il concetto di [!UICONTROL Journey Orchestration]
* Tipi di casi d’uso che consente
* Elementi chiave del funzionamento di [!UICONTROL Journey Orchestration]

>[!VIDEO](https://video.tv.adobe.com/v/29307?quality=12)

## Come configurare un percorso

Principali fasi di preparazione per generare percorsi:

1. [Configurare eventi di streaming](/help/configuring-journey-orchestration/configure-streaming-events.md): questa configurazione è obbligatoria, in quanto [!UICONTROL Journey Orchestration] è progettato per ascoltare gli eventi.
1. [Configurare origini dati](/help/configuring-journey-orchestration/configure-data-sources.md): questa configurazione non è necessaria se i percorsi sfruttano solo i dati locali provenienti da un payload dell’evento.
1. [Configurare azioni personalizzate](/help/configuring-journey-orchestration/configure-actions.md): necessario se si desidera utilizzare un servizio di qualsiasi provider di terze parti che può essere chiamato tramite un [!DNL REST API] con un payload in formato JSON

>[!NOTE]
>
>Questi passaggi di configurazione richiedono conoscenze tecniche. Sarà necessario avere familiarità con [Experience Data Model (XDM)](https://docs.adobe.com/content/help/it-IT/platform-learn/tutorials/schemas/understanding-the-xdm-system-and-experience-data-model.html) e sapere [come comporre gli schemi experience event XDM](https://docs.adobe.com/content/help/it-IT/platform-learn/tutorials/schemas/create-your-first-schema-with-out-of-the-box-components.html).

## Creazione, pubblicazione e analisi di un percorso

1. [Creare un percorso](/help/building-a-journey/creating-a-journey.md)
1. [Convalidare e pubblicare un percorso](/help/validate-and-publish-a-journey.md)
1. [Analizzare un percorso tramite strumenti di reporting](/help/analyze-a-journey-via-reporting-tools.md)

## Risorse aggiuntive

* [Centro Risorse Journey Orchestration](https://docs.adobe.com/content/help/it-IT/journeys/using/journey-orchestration-home.html)
* [Tutorial su Adobe Experience Platform](https://docs.adobe.com/content/help/it-IT/platform-learn/tutorials/overview.html)
* [Come trovare la guida con Journey Orchestration](/help/understanding-journey-orchestration.md)
* [Adobe Experience Platform Mobile SDK - Avvio](https://docs.adobe.com/content/help/it-IT/core-services-learn/tutorials/launch-mobile/understanding-the-mobile-sdks.html)
* [Adobe Experience Platform Location Service](https://docs.adobe.com/content/help/it-IT/places/using/home.translate.html)
