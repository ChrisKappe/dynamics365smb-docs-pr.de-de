---
title: 'Vorgehensweise: Einrichten eines Kostenartenplans | Microsoft Docs'
description: "Kostenartenpläne ähneln Kontenpläne im Sachkonto."
services: project-madeira
documentationcenter: 
author: SorenGP
ms.service: dynamics365-financials
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: cost types, general ledger, accounts
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 2c13559bb3dc44cdb61697f5135c5b931e34d2a8
ms.openlocfilehash: 7598dbfbedf8faf7a80ac52469c2edcc4e2c1c66
ms.contentlocale: de-de
ms.lasthandoff: 09/22/2017

---
# <a name="how-to-set-up-cost-types"></a><span data-ttu-id="3c1bf-103">So geht's: Kostenarten einrichten</span><span class="sxs-lookup"><span data-stu-id="3c1bf-103">How to: Set Up Cost Types</span></span>
<span data-ttu-id="3c1bf-104">Kostenartenpläne ähneln Kontenpläne im Sachkonto.</span><span class="sxs-lookup"><span data-stu-id="3c1bf-104">The chart of cost types is similar to the chart of accounts in the general ledger.</span></span> <span data-ttu-id="3c1bf-105">Sie können den Kostenartenplan auf die folgenden Weisen einrichten:</span><span class="sxs-lookup"><span data-stu-id="3c1bf-105">You can set up the chart of cost types in the following ways:</span></span>  

-   <span data-ttu-id="3c1bf-106">Strukturieren Sie den Kostenartenplan ähnlich wie GuV-Konten im Sachkontenplan.</span><span class="sxs-lookup"><span data-stu-id="3c1bf-106">Structure the chart of cost types similar to the income statement accounts in the general ledger chart of accounts.</span></span> <span data-ttu-id="3c1bf-107">Dann können Sie den Sachkontenplan in den Kostenartenplan übertragen.</span><span class="sxs-lookup"><span data-stu-id="3c1bf-107">Then, you can transfer the general ledger chart of accounts to the chart of cost types.</span></span> <span data-ttu-id="3c1bf-108">Sie können alle notwendigen Änderungen nach der Übertragung vornehmen.</span><span class="sxs-lookup"><span data-stu-id="3c1bf-108">You can make any necessary adjustments after the transfer.</span></span>  
-   <span data-ttu-id="3c1bf-109">Erstellen Sie einen neuen Kostenartenplan, oder fügen Sie einem vorhandenen Kostenartenplan neue Kostenarten hinzu.</span><span class="sxs-lookup"><span data-stu-id="3c1bf-109">Create new chart of cost types or add new cost types to existing chart of cost types.</span></span> <span data-ttu-id="3c1bf-110">Sie müssen jede neue Kostenart einzeln erstellen.</span><span class="sxs-lookup"><span data-stu-id="3c1bf-110">You must create each new cost type individually.</span></span>  

## <a name="to-transfer-the-general-ledger-chart-of-accounts-to-the-chart-of-cost-types"></a><span data-ttu-id="3c1bf-111">So übertragen Sie den Sachkontenplan in den Kostenartenplan.</span><span class="sxs-lookup"><span data-stu-id="3c1bf-111">To transfer the general ledger chart of accounts to the chart of cost types</span></span>  
1.  <span data-ttu-id="3c1bf-112">Wählen Sie das Symbol ![Nach Seite oder Bericht suchen](media/ui-search/search_small.png "Symbol Nach Seite oder Bericht suchen"), geben **Kostenartenplan** ein und wählen dann den zugehörigen Link aus.</span><span class="sxs-lookup"><span data-stu-id="3c1bf-112">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Chart of Cost Types**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="3c1bf-113">Wählen Sie die Aktion **Kostenarten aus K&ontenplan abrufen**.</span><span class="sxs-lookup"><span data-stu-id="3c1bf-113">Choose the **Get Cost Types from Chart of Accounts** action.</span></span> <span data-ttu-id="3c1bf-114">Klicken Sie im Dialogfeld auf die Schaltfläche **Ja**, um die Übertragung zu bestätigen.</span><span class="sxs-lookup"><span data-stu-id="3c1bf-114">In the dialog box, choose the **Yes** button to confirm the transfer.</span></span> <span data-ttu-id="3c1bf-115">Die Funktion verwendet den Kontenplan, um einen Kostenartenplan zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="3c1bf-115">The function uses the chart of accounts to create a chart of cost types.</span></span>  

    <span data-ttu-id="3c1bf-116">Der Kostenartenplan enthält jetzt alle GuV-Konten im Sachkonto und umfasst Überschriften und Zwischensummen.</span><span class="sxs-lookup"><span data-stu-id="3c1bf-116">The chart of cost types now contain all income statement accounts in the general ledger and include headings and subtotals.</span></span> <span data-ttu-id="3c1bf-117">Sie können den Kostenartenplan ändern, falls erforderlich.</span><span class="sxs-lookup"><span data-stu-id="3c1bf-117">You can change the chart of cost types, as necessary.</span></span> <span data-ttu-id="3c1bf-118">Beispielsweise können Sie doppelt vorhandene Kostenarten löschen.</span><span class="sxs-lookup"><span data-stu-id="3c1bf-118">For example, you can delete duplicate existing cost types.</span></span>  

    > [!IMPORTANT]  
    >  <span data-ttu-id="3c1bf-119">Die **Kostenarten in Kontenplan registrieren**-Funktion aktualisiert das Verhältnis zwischen dem Kontenplan und dem Kostenartenplan.</span><span class="sxs-lookup"><span data-stu-id="3c1bf-119">The **Register Cost Types in Chart of Accounts** function updates the relationship between the chart of accounts and the chart of cost types.</span></span> <span data-ttu-id="3c1bf-120">Das **Nr.**</span><span class="sxs-lookup"><span data-stu-id="3c1bf-120">The **No.**</span></span> <span data-ttu-id="3c1bf-121">Das Feld  wird ausgefüllt und geprüft, um sicherzustellen, dass jedes Sachkonto mit nur einer Kostenart verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="3c1bf-121">field is filled and verified to make sure that each general ledger account is related to only one cost type.</span></span> <span data-ttu-id="3c1bf-122">Die Funktion wird automatisch ausgeführt, bevor Sie Sachposten in die Kostenrechnung übertragen.</span><span class="sxs-lookup"><span data-stu-id="3c1bf-122">The function runs automatically before transferring general ledger entries to cost accounting.</span></span>  

## <a name="to-set-up-new-cost-types-in-the-chart-of-cost-types-window"></a><span data-ttu-id="3c1bf-123">So richten Sie im Fenster "Liquiditätskontenplan" neue Liquiditätskonten ein</span><span class="sxs-lookup"><span data-stu-id="3c1bf-123">To set up new cost types in the Chart of Cost Types window</span></span>  
1.  <span data-ttu-id="3c1bf-124">Öffnen Sie das Fenster **Kontenplan-Arten** im Bearbeitungsmodus.</span><span class="sxs-lookup"><span data-stu-id="3c1bf-124">Open the **Chart of Cost Types** window in edit mode.</span></span>  
2.  <span data-ttu-id="3c1bf-125">Füllen Sie je nach Bedarf die Felder aus.</span><span class="sxs-lookup"><span data-stu-id="3c1bf-125">Fill in the fields as described as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

    > [!NOTE]  
    >  <span data-ttu-id="3c1bf-126">Sie können Kostenarten im Fenster **Kostenartkarte** oder im Fenster **Kostenartenplan** einrichten und verwalten.</span><span class="sxs-lookup"><span data-stu-id="3c1bf-126">You can set up and maintain cost types in either the **Cost Type Card** window or in the **Chart of Cost Types** window.</span></span> <span data-ttu-id="3c1bf-127">So richten Sie im Fenster **Liquiditätskontenplan** neue Liquiditätskonten ein.</span><span class="sxs-lookup"><span data-stu-id="3c1bf-127">In this procedure, you set up cost types in the **Chart of Cost Types** window.</span></span>

3.  <span data-ttu-id="3c1bf-128">Nachdem Sie alle Kostenarten erstellt haben, wählen Sie die Aktion **Kostenarten einrücken** aus.</span><span class="sxs-lookup"><span data-stu-id="3c1bf-128">After you have created all cost types, choose the **Indent Cost Types** action.</span></span> <span data-ttu-id="3c1bf-129">Klicken Sie im Dialogfeld auf die Schaltfläche **Ja**.</span><span class="sxs-lookup"><span data-stu-id="3c1bf-129">In the dialog box, choose the **Yes** button.</span></span>  
4.  <span data-ttu-id="3c1bf-130">Verknüpfen Sie die neue Kostenart mit dem entsprechenden Sachkonto.</span><span class="sxs-lookup"><span data-stu-id="3c1bf-130">Link the new cost type to the corresponding general ledger account.</span></span>  

    > [!IMPORTANT]  
    >  <span data-ttu-id="3c1bf-131">Wenn Sie in den Feldern **Zusammenzählung** Definitionen für die Zeilenart **Bis-Summe** eingetragen haben, bevor Sie die Funktion **Kostenarten einrücken** ausgeführt haben, müssen Sie diese Eintragungen wiederholen, da die Funktion die Werte in allen **Bis-Summe**-Feldern überschreibt.</span><span class="sxs-lookup"><span data-stu-id="3c1bf-131">If you have entered definitions in the **Totaling** fields for the line type of **End-Total** before you run the **Indent Cost Types** function, then you must enter the definitions again because the function overwrites the values in all **End-Total** fields.</span></span>  

## <a name="to-update-cost-types"></a><span data-ttu-id="3c1bf-132">So aktualisieren Sie Kostenarten</span><span class="sxs-lookup"><span data-stu-id="3c1bf-132">To update cost types</span></span>  
1.  <span data-ttu-id="3c1bf-133">Im Fenster **Kostenrechnung einrichten**  wählen Sie aus, ob der Kostenartenplan automatisch aktualisiert werden soll, wenn der Kontenplan geändert wird.</span><span class="sxs-lookup"><span data-stu-id="3c1bf-133">In the **Cost Accounting Setup** window, select if you want the chart of cost types to be automatically updated when the chart of accounts is changed.</span></span>  
2.  <span data-ttu-id="3c1bf-134">Die folgenden Optionen stehen im Feld **Sachkonto ausrichten** zur Auswahl.</span><span class="sxs-lookup"><span data-stu-id="3c1bf-134">In the **Align G/L Account** field, you can choose from the following options.</span></span>  

- <span data-ttu-id="3c1bf-135">**Keine Ausrichtung** - Es gibt keine entsprechende Änderung im Kostenartenplan, wenn Sie den Kontenplan ändern.</span><span class="sxs-lookup"><span data-stu-id="3c1bf-135">**No Alignment** - There is no corresponding change in the chart of cost types when you change the chart of accounts.</span></span>  
- <span data-ttu-id="3c1bf-136">**Automatisch** - Es gibt eine entsprechende Änderung im Kostenartenplan, wenn Sie den Kontenplan ändern.</span><span class="sxs-lookup"><span data-stu-id="3c1bf-136">**Automatic** - A corresponding change is made in the chart of cost types when you change the chart of accounts.</span></span>  
- <span data-ttu-id="3c1bf-137">**Eingabeaufforderung** - Eine Meldung wird mit der Frage angezeigt, ob Sie die entsprechende Änderung auch im Kostenartenplan vornehmen möchten, wenn Sie den Kontenplan ändern.</span><span class="sxs-lookup"><span data-stu-id="3c1bf-137">**Prompt** - A message is displayed asking if you want to make a corresponding change in the chart of cost types when you change the chart of accounts.</span></span>  

## <a name="see-also"></a><span data-ttu-id="3c1bf-138">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="3c1bf-138">See Also</span></span>  
[<span data-ttu-id="3c1bf-139">Kostenrechnung</span><span class="sxs-lookup"><span data-stu-id="3c1bf-139">Accounting for Costs</span></span>](finance-manage-cost-accounting.md)  
<span data-ttu-id="3c1bf-140">[Definieren der Beziehung zwischen Kostenarten und Sachkonten](finance-defining-the-relationship-between-cost-types-and-general-ledger-accounts.md) </span><span class="sxs-lookup"><span data-stu-id="3c1bf-140">[Defining the Relationship Between Cost Types and General Ledger Accounts](finance-defining-the-relationship-between-cost-types-and-general-ledger-accounts.md) </span></span>  
<span data-ttu-id="3c1bf-141">[Definieren von Kostenstellen und Kostenträgern für Kontenpläne](finance-defining-cost-centers-and-cost-objects-for-chart-of-accounts.md) </span><span class="sxs-lookup"><span data-stu-id="3c1bf-141">[Defining Cost Centers and Cost Objects for Chart of Accounts](finance-defining-cost-centers-and-cost-objects-for-chart-of-accounts.md) </span></span>  
<span data-ttu-id="3c1bf-142">[Salden zwischen Kostenart, Kostenstelle und Kostenträger](finance-balances-between-cost-type-cost-center-and-cost-object.md) </span><span class="sxs-lookup"><span data-stu-id="3c1bf-142">[Balances Between Cost Type, Cost Center, and Cost Object](finance-balances-between-cost-type-cost-center-and-cost-object.md) </span></span>  
<span data-ttu-id="3c1bf-143">[Einrichten der Kostenrechnung](finance-set-up-cost-accounting.md) </span><span class="sxs-lookup"><span data-stu-id="3c1bf-143">[Setting Up Cost Accounting](finance-set-up-cost-accounting.md) </span></span>  
<span data-ttu-id="3c1bf-144">[Terminologie der Kostenrechnung](finance-terminology-in-cost-accounting.md) </span><span class="sxs-lookup"><span data-stu-id="3c1bf-144">[Terminology in Cost Accounting](finance-terminology-in-cost-accounting.md) </span></span>  
[<span data-ttu-id="3c1bf-145">Informationen zur Kostenrechnung</span><span class="sxs-lookup"><span data-stu-id="3c1bf-145">About Cost Accounting</span></span>](finance-about-cost-accounting.md)  
<span data-ttu-id="3c1bf-146">[Arbeiten mit [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="3c1bf-146">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
