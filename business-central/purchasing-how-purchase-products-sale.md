---
title: "Einkaufs-Artikel für einen Verkauf durch das Erstellen von Einkaufsrechnungen | Microsoft Docs"
description: "Von einer Verkaufsrechnung um Produkte einzukaufen, können Sie eine Einkaufsrechnung für einen Kreditor oder Lieferanten einen erstellen."
author: SorenGP
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: supply planning, sales demand, replenish
ms.date: 01/25/2018
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: e7dcdc0935a8793ae226dfc2f9709b5b8f487a62
ms.openlocfilehash: d5ae63043a6f296de22f71c401a5686f970ad3a0
ms.contentlocale: de-de
ms.lasthandoff: 03/22/2018

---
# <a name="purchase-items-for-a-sale"></a><span data-ttu-id="83edd-103">Einkauf von Produkten für einen Verkauf</span><span class="sxs-lookup"><span data-stu-id="83edd-103">Purchase Items for a Sale</span></span>
<span data-ttu-id="83edd-104">Bei Verkaufsaufträgen aus der Verkaufsrechnungen können Sie Funktionen verwenden, um für Einkaufsbelege Mengen des fehlenden Stücks schneller zu erstellen, die im Verkauf benötigt werden.</span><span class="sxs-lookup"><span data-stu-id="83edd-104">From sales orders and sales invoices, you can use functions to quickly create purchase documents for missing item quantities that are required by the sale.</span></span> <span data-ttu-id="83edd-105">Sie können zwei verschiedene Funktionen nutzen, abhängig von der Belegart, die verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="83edd-105">You can use two different functions depending on the document type.</span></span>
|<span data-ttu-id="83edd-106">Funktion</span><span class="sxs-lookup"><span data-stu-id="83edd-106">Function</span></span>|<span data-ttu-id="83edd-107">Description</span><span class="sxs-lookup"><span data-stu-id="83edd-107">Description</span></span>|
|--------|-----------|
|<span data-ttu-id="83edd-108">**Einkaufsbestellungen erstellen**</span><span class="sxs-lookup"><span data-stu-id="83edd-108">**Create Purchase Orders**</span></span>|<span data-ttu-id="83edd-109">Bei einem Verkaufsauftrag erstellt diese Funktion eine Einkaufsbestellung für jeden Kreditor aus Artikeln des Verkaufsauftrags.</span><span class="sxs-lookup"><span data-stu-id="83edd-109">From a sales order, this function creates a purchase order for each vendor of items on the sales order.</span></span> <span data-ttu-id="83edd-110">Sie können die Abnahmemenge bearbeiten, bevor Sie die Bestellungen erstellen.</span><span class="sxs-lookup"><span data-stu-id="83edd-110">You can edit the purchase quantity before you create the purchase orders.</span></span> <span data-ttu-id="83edd-111">Nur nicht verfügbare Verkaufsmengen werden vorgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="83edd-111">Only unavailable sales quantities are suggested.</span></span>
|<span data-ttu-id="83edd-112">**Einkaufsrechnung erstellen**</span><span class="sxs-lookup"><span data-stu-id="83edd-112">**Create Purchase Invoice**</span></span>|<span data-ttu-id="83edd-113">Bei einem Verkaufsauftrag und einer Verkaufsrechnung, erstellt diese Funktion eine Einkaufsrechnung für einen ausgewählten Kreditor für alle Zeilen oder nur ausgewählte Zeilen des Verkaufsbelegs.</span><span class="sxs-lookup"><span data-stu-id="83edd-113">From a sales order and from a sales invoice, this function creates a purchase invoice for a selected vendor for all lines or selected lines on the sales document.</span></span> <span data-ttu-id="83edd-114">Die verfügbare Verkaufsmenge wird vorgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="83edd-114">The full sales quantity is suggested.</span></span>|

## <a name="to-create-one-or-more-purchase-orders-from-a-sales-order"></a><span data-ttu-id="83edd-115">Um eine oder mehrere Einkaufsbestellungen aus Verkaufsaufträgen zu erstellen</span><span class="sxs-lookup"><span data-stu-id="83edd-115">To create one or more purchase orders from a sales order</span></span>
<span data-ttu-id="83edd-116">Um eine Bestellung für jede Artikelmenge von nichtverfügbaren Artikeln im Verkaufsauftrag zu erstellen, verwenden Sie die Funktion **Einkaufsbestellungen**.</span><span class="sxs-lookup"><span data-stu-id="83edd-116">To create a purchase order for each unavailable item quantity on the sales order, you use the **Create Purchase Orders** function.</span></span>

1. <span data-ttu-id="83edd-117">Wählen Sie das Symbol ![Nach Seite oder Bericht suchen](media/ui-search/search_small.png "Nach Seite oder Bericht suchen") und geben **Verkaufsauftrag** ein, und wählen Sie dann den zugehörigen Link aus.</span><span class="sxs-lookup"><span data-stu-id="83edd-117">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Sales Orders**, and then choose the related link.</span></span>
2. <span data-ttu-id="83edd-118">Öffnen Sie einen Verkaufsauftrag für Artikel, die Sie kaufen möchten.</span><span class="sxs-lookup"><span data-stu-id="83edd-118">Open a sales order that you want to purchase items for.</span></span>
3. <span data-ttu-id="83edd-119">Wählen Sie die Aktion **Einkaufsbestellung erstellen**.</span><span class="sxs-lookup"><span data-stu-id="83edd-119">Choose the **Create Purchase Orders** action.</span></span>

    <span data-ttu-id="83edd-120">Das Fenster **Einkaufsbestellungen** wird geöffnet und zeigt eine Zeile für jeden anderen Artikel im Verkaufsauftrag.</span><span class="sxs-lookup"><span data-stu-id="83edd-120">The **Create Purchase Orders** window opens showing a line for each different item on the sales order.</span></span> <span data-ttu-id="83edd-121">Zeilen für verfügbare und nicht verfügbare (abgeblendet) Verkaufsmengen werden standardmäßig angezeigt.</span><span class="sxs-lookup"><span data-stu-id="83edd-121">Lines for both fully available sales quantities and unavailable sales quantities (grayed) are shown by default.</span></span> <span data-ttu-id="83edd-122">Sie können die Funktionen **Anzeigen nicht verfügbar** Aktion auswählen, um Zeilen für nicht verfügbare Verkaufsmengen nur anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="83edd-122">You can choose the **Show Unavailable** action to only see lines for unavailable sales quantities.</span></span>

    <span data-ttu-id="83edd-123">Das Feld **Einzukaufen Menge** enthält standardmäßig die nichtverfügbare Verkaufsmenge.</span><span class="sxs-lookup"><span data-stu-id="83edd-123">The **Quantity to Purchase** field contains the unavailable sales quantity by default.</span></span>
4. <span data-ttu-id="83edd-124">Um eine andere Menge als die nichtverfügbare Verkaufsmenge einzukaufen, ändern Sie den Wert im Feld **Einzukaufende Menge**.</span><span class="sxs-lookup"><span data-stu-id="83edd-124">To purchase another quantity than the unavailable sales quantity, edit the value in the **Quantity to Purchase** field.</span></span>

    > [!NOTE]  
    >   <span data-ttu-id="83edd-125">Sie können das Feld **Einzukaufen Menge** in abgeblendeten Zeilen auch ändern, obwohl sie vollständig verfügbare Verkaufsmengen darstellen.</span><span class="sxs-lookup"><span data-stu-id="83edd-125">You can also change the **Quantity to Purchase** field on grayed lines even though they represent fully available sales quantities.</span></span>
5. <span data-ttu-id="83edd-126">Wählen Sie die Schaltfläche **OK** aus.</span><span class="sxs-lookup"><span data-stu-id="83edd-126">Choose the **OK** button.</span></span>

    <span data-ttu-id="83edd-127">Eine Bestellung ist für jeden Kreditor der Artikel im Verkaufsauftrag, einschließlich alle Mengenänderungen erstellt, die Sie im **Einkaufsbestellungen** durchgeführt haben.</span><span class="sxs-lookup"><span data-stu-id="83edd-127">A purchase order is created for each vendor of items on the sales order, including any quantity changes that you made in the **Create Purchase Orders** window.</span></span>
7. <span data-ttu-id="83edd-128">Fahren Sie fort, die Einkaufsbestellungen zu verarbeiten, indem Sie beispielsweise Einkaufsbestellungszeilen bearbeiten oder hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="83edd-128">Proceed to process the purchase order or orders, for example, by editing or adding purchase order lines.</span></span> <span data-ttu-id="83edd-129">Weitere Informationen finden Sie unter [Erfassen eines Einkaufs](purchasing-how-record-purchases.md).</span><span class="sxs-lookup"><span data-stu-id="83edd-129">For more information, see [Record Purchases](purchasing-how-record-purchases.md).</span></span>


## <a name="to-create-a-purchase-invoice-from-a-sales-order-or-sales-invoice"></a><span data-ttu-id="83edd-130">Eine Einkaufsrechnung aus einer Verkaufsbestellung erstellen</span><span class="sxs-lookup"><span data-stu-id="83edd-130">To create a purchase invoice from a sales order or sales invoice</span></span>
<span data-ttu-id="83edd-131">Eine einzelne Einkaufsrechnung für eine oder mehrere Zeilen in einem Verkaufsbeleg erstellen, indem Sie zuerst auswählen, von welchem Kreditor Sie die Funktion **Einkaufsr""echnung erstellen** verwenden.</span><span class="sxs-lookup"><span data-stu-id="83edd-131">To create a single purchase invoice for one or more lines on a sales document by first selecting which vendor to buy from, you use the **Create Purchase Invoice** function.</span></span>

> [!NOTE]  
>   <span data-ttu-id="83edd-132">Diese Funktion erstellt eine Einkaufsrechnung für die exakte Artikelmenge audf dem ausgewählten Verkaufsbeleg.</span><span class="sxs-lookup"><span data-stu-id="83edd-132">This function creates a purchase invoice for the exact item quantity on the selected sales document.</span></span> <span data-ttu-id="83edd-133">Um die Abnahmemenge zu ändern, müssen Sie die Einkaufsrechnung bearbeiten nachdem sie erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="83edd-133">To change the purchase quantity, you must edit the purchase invoice after it is created.</span></span>  

1. <span data-ttu-id="83edd-134">Wählen Sie das Symbol ![Nach Seite oder Bericht suchen](media/ui-search/search_small.png "Nach Seite oder Bericht suchen") und geben **Verkaufsauftrag** ein, und wählen Sie dann den zugehörigen Link aus.</span><span class="sxs-lookup"><span data-stu-id="83edd-134">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Sales Orders**, and then choose the related link.</span></span>
2. <span data-ttu-id="83edd-135">Öffnen Sie einen Verkaufsrechnunung für Artikel, die Sie kaufen möchten.</span><span class="sxs-lookup"><span data-stu-id="83edd-135">Open a sales invoice that you want to purchase items for.</span></span>
3. <span data-ttu-id="83edd-136">Wählen Sie eine oder mehrere Rechnungszeilen aus, die Sie auf der Einkaufsrechnung verwenden möchten.</span><span class="sxs-lookup"><span data-stu-id="83edd-136">Select one or more sales invoice lines that you want to use on the purchase invoice.</span></span> <span data-ttu-id="83edd-137">Um alle Verkaufsrechnungszeilen zu verwenden, wählen Sie entweder alle oder keine Zeilen aus.</span><span class="sxs-lookup"><span data-stu-id="83edd-137">To use all the sales invoice lines, select either all of them or do not select any lines.</span></span>
4. <span data-ttu-id="83edd-138">Wählen Sie die Aktion **Einkaufsrechnung erstellen**.</span><span class="sxs-lookup"><span data-stu-id="83edd-138">Choose the **Create Purchase Invoice** action.</span></span>
5. <span data-ttu-id="83edd-139">Wählen Sie entweder **Alle Posten** oder **Ausgewählte Posten**, und wählen Sie die **OK**-Schaltfläche.</span><span class="sxs-lookup"><span data-stu-id="83edd-139">Select either **All Lines** or **Selected Lines**, and then choose the **OK** button.</span></span>  
6. <span data-ttu-id="83edd-140">In der Kreditorenliste, die erscheint, wählen Sie den Kreditor, der die Artikel oder Dienstleistung liefert, und wählen Sie die Schaltfläche **OK**.</span><span class="sxs-lookup"><span data-stu-id="83edd-140">In the list of vendors that appears, select the vendor that you want to buy all the items from, and then choose the **OK** button.</span></span>

    <span data-ttu-id="83edd-141">Eine Einkaufsrechnung wird erstellt, die eine, mehrere oder alle Zeilen auf der Verkaufsrechnung enthält.</span><span class="sxs-lookup"><span data-stu-id="83edd-141">A purchase invoice is created that contains one, more, or all the lines on the sales invoice.</span></span>
7. <span data-ttu-id="83edd-142">Fahren Sie fort, die Einkaufsrechnung zu verarbeiten, indem Sie beispielsweise Einkaufsrechnungszeilen bearbeiten oder hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="83edd-142">Proceed to process the purchase invoice, for example, by editing or adding purchase invoice lines.</span></span> <span data-ttu-id="83edd-143">Weitere Informationen finden Sie unter [Erfassen eines Einkaufs](purchasing-how-record-purchases.md).</span><span class="sxs-lookup"><span data-stu-id="83edd-143">For more information, see [Record Purchases](purchasing-how-record-purchases.md).</span></span>

## <a name="see-also"></a><span data-ttu-id="83edd-144">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="83edd-144">See Also</span></span>
[<span data-ttu-id="83edd-145">Einkauf</span><span class="sxs-lookup"><span data-stu-id="83edd-145">Purchasing</span></span>](purchasing-manage-purchasing.md)  
[<span data-ttu-id="83edd-146">Erfassen eines Einkaufs</span><span class="sxs-lookup"><span data-stu-id="83edd-146">Record Purchases</span></span>](purchasing-how-record-purchases.md)  
[<span data-ttu-id="83edd-147">Verkaufsrechnung</span><span class="sxs-lookup"><span data-stu-id="83edd-147">Invoice Sales</span></span>](sales-how-invoice-sales.md)  
[<span data-ttu-id="83edd-148">Registriert einen neuen Kreditor</span><span class="sxs-lookup"><span data-stu-id="83edd-148">Register New Vendors</span></span>](purchasing-how-register-new-vendors.md)  
<span data-ttu-id="83edd-149">[Arbeiten mit [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="83edd-149">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
