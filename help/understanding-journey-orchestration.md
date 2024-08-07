---
title: 'Journey Orchestration: cos’è e come funziona'
description: Comprendi il concetto di Journey Orchestration, possibili casi d’uso e gli elementi chiave del suo funzionamento.
feature: Overview
topics: Introduction
jira: KT-2773
thumbnail: 29307.jpg
audience: user, developer
doc-type: video
activity: understand
role: User, Admin
exl-id: db4f69bb-183c-4376-9791-eb6b1f78ab32
source-git-commit: 9db2765ee5e9520280711a6b1fe3c618963f6f87
workflow-type: tm+mt
source-wordcount: '280'
ht-degree: 100%

---

# Comprensione di [!UICONTROL Journey Orchestration]

[!UICONTROL Journey Orchestration] consente di applicare l’orchestrazione in tempo reale per diversi casi d’uso, sfruttando i dati contestuali provenienti da eventi o origini dati.

## Introduzione a [!UICONTROL Journey Orchestration]

[!UICONTROL Journey Orchestration] è un servizio applicativo integrato con Adobe Experience Platform. Fornisce un ecosistema intelligente e aperto per attivare tutti i dati dinamici pertinenti attraverso un impegno scalabile basato su eventi, su qualsiasi canale richiesto dalla tua azienda, dal marketing alle operazioni ai servizi. [!UICONTROL Journey Orchestration] è in grado di sfruttare qualsiasi dato proveniente da Adobe Experience Platform e da qualsiasi sistema di consegna esterno, per creare e consegnare esperienze di grande efficacia.

Il video seguente introduce

* Il concetto di [!UICONTROL Journey Orchestration]
* Tipi di casi d’uso che consente
* Elementi chiave del funzionamento di [!UICONTROL Journey Orchestration]

>[!VIDEO](https://video.tv.adobe.com/v/29307?learn=on){transcript=true}

## Come configurare un percorso

Principali fasi di preparazione per generare percorsi:

1. [Configurare eventi di streaming](/help/configuring-journey-orchestration/configure-streaming-events.md): questa configurazione è obbligatoria, in quanto [!UICONTROL Journey Orchestration] è progettato per ascoltare gli eventi.
1. [Configurare le origini dati](/help/configuring-journey-orchestration/configure-data-sources.md): questa configurazione non è necessaria se i percorsi sfruttano solo i dati locali provenienti dal payload di un evento.
1. [Configurare azioni personalizzate](/help/configuring-journey-orchestration/configure-actions.md): necessario se si desidera utilizzare un servizio di qualsiasi provider di terze parti che può essere chiamato tramite un [!DNL REST API] con un payload in formato JSON

>[!NOTE]
>
>Questi passaggi di configurazione richiedono conoscenze tecniche. È necessario avere familiarità con [Experience Data Model (XDM)](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/schemas-and-experience-data-model.html?lang=it) ed essere in grado di[ comporre gli schemi experience event XDM](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/create-schemas.html?lang=it).

## Creare, pubblicare e analizzare un percorso

1. [Creare un percorso](/help/building-a-journey/creating-a-journey.md)
1. [Convalidare e pubblicare un percorso](/help/validate-and-publish-a-journey.md)
1. [Analizzare un percorso con strumenti di reporting](/help/analyze-a-journey-via-reporting-tools.md)

## Risorse aggiuntive

* [Centro Risorse Journey Orchestration](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=it)
* [Tutorial su Adobe Experience Platform](https://experienceleague.adobe.com/docs/platform-learn/tutorials/overview.html?lang=it)
* [Assistenza per Journey Orchestration](/help/understanding-journey-orchestration.md)
* [Adobe Experience Platform Mobile SDK - Avvio](https://experienceleague.adobe.com/docs/platform-learn/data-collection/mobile-sdk/overview.html?lang=it)
* [Adobe Experience Platform Location Service](https://experienceleague.adobe.com/docs/places/using/home.html?lang=it)
