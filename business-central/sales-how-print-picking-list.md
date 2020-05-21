---
title: So drucken Sie eine Lager-Kommissionierliste aus einem Verkaufsauftrag
description: Sie können eine Lager-Kommissionierliste direkt aus einem Verkaufsauftrag, Verkaufsbeleg, Rechnungsbeleg und anderen ausgehenden Verkaufsauftragsbelegen drucken.
author: SorenGP
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: ''
ms.date: 04/27/2020
ms.author: sgroespe
ms.openlocfilehash: d5eaad5279445375ec00fdf42dd48bffa5d03645
ms.sourcegitcommit: 7d54d8abe52e0546378cf760f5082f46e8441b90
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 04/30/2020
ms.locfileid: "3324467"
---
# <a name="print-the-picking-list"></a><span data-ttu-id="45aca-103">Kommissionierliste drucken</span><span class="sxs-lookup"><span data-stu-id="45aca-103">Print the Picking List</span></span>
<span data-ttu-id="45aca-104">Sie können eine Lager-Kommissionierliste direkt aus einem Verkaufsauftragsbeleg, Verkaufsbeleg, Rechnungsbeleg und anderen ausgehenden Verkaufsauftragsbelegen drucken.</span><span class="sxs-lookup"><span data-stu-id="45aca-104">You can print an inventory picking list directly from a sales order, a sales invoice, or any other document that initiates shipment of items.</span></span>

<span data-ttu-id="45aca-105">Dieser Bericht wird normalerweise in Unternehmen ohne dedizierte Funktionen für die Lagerverwaltung verwendet, sodass ein Lagerarbeiter die Kommissionierliste einfach über den zugehörigen Verkaufsbeleg aufrufen oder drucken kann.</span><span class="sxs-lookup"><span data-stu-id="45aca-105">This report is typically used in companies without dedicated functionality for warehouse management, so that an inventory worker can simply view or print the picking list from the related sales document.</span></span> <span data-ttu-id="45aca-106">In Unternehmen mit höherem Volumen oder komplexeren Prozessen wird die Kommissionierung in dedizierten Lagerdokumenten geplant und durchgeführt.</span><span class="sxs-lookup"><span data-stu-id="45aca-106">In companies with higher volume or more complex processes, picking is planned and performed in dedicated warehouse documents.</span></span> <span data-ttu-id="45aca-107">Weitere Informationen finden Sie unter [Artikel kommissionieren](warehouse-pick-items.md).</span><span class="sxs-lookup"><span data-stu-id="45aca-107">For more information, see [Pick Items](warehouse-pick-items.md).</span></span>

## <a name="to-print-a-picking-list-from-a-sales-order"></a><span data-ttu-id="45aca-108">So drucken Sie eine Kommissionierliste aus einem Verkaufsauftrag</span><span class="sxs-lookup"><span data-stu-id="45aca-108">To print a picking list from a sales order</span></span>  
<span data-ttu-id="45aca-109">Das folgende Verfahren basiert auf einer Auftragsabwicklung.</span><span class="sxs-lookup"><span data-stu-id="45aca-109">The following procedure is based on a sales order.</span></span> <span data-ttu-id="45aca-110">Die Schritte sind für alle Verkaufsbelege ähnlich, mit denen der Versand von Artikeln eingeleitet werden kann.</span><span class="sxs-lookup"><span data-stu-id="45aca-110">The steps are similar for all sales documents that can be used to initiate shipment of items.</span></span>

1. <span data-ttu-id="45aca-111">Wählen Sie das Symbol ![Nach Seite oder Bericht suchen](media/ui-search/search_small.png "Nach dem Symbol für „Seite“ oder „Bericht“ suchen") aus, geben Sie **Verkaufsaufträge** ein, und wählen Sie dann den entsprechenden Link aus.</span><span class="sxs-lookup"><span data-stu-id="45aca-111">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Sales Orders**, and then choose the related link.</span></span>  
2. <span data-ttu-id="45aca-112">Öffnen Sie den Verkaufsauftrag, für den Sie Artikel auswählen möchten.</span><span class="sxs-lookup"><span data-stu-id="45aca-112">Open the sales order that you want to pick items for.</span></span>  
3. <span data-ttu-id="45aca-113">Wählen Sie die Aktion **Bericht** und dann die Aktion **Kommissionierliste nach Bestellung** aus.</span><span class="sxs-lookup"><span data-stu-id="45aca-113">Choose the **Report** action, and then choose the **Picking List by Order** action.</span></span>  
4. <span data-ttu-id="45aca-114">Wählen Sie die Schaltfläche **Drucken** aus, um die Kommissionierliste zu drucken, oder die Schaltfläche **Vorschau**, um sie auf dem Bildschirm anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="45aca-114">Choose the **Print** button to print the picking list or choose the **Preview** button to view it on the screen.</span></span>

<span data-ttu-id="45aca-115">Sie können die Kommissionierliste auch als Dokument speichern, um sie beispielsweise an jemanden zu senden oder dem Verkaufsauftrag als Anhang hinzuzufügen.</span><span class="sxs-lookup"><span data-stu-id="45aca-115">You can also save the picking list as a document, for example, to send to someone or to add as an attachment to the sales order.</span></span> <span data-ttu-id="45aca-116">Weitere Informationen finden Sie unter [Verwalten von Anhängen, Links und Notizen zu Karten und Dokumenten](ui-how-add-link-to-record.md).</span><span class="sxs-lookup"><span data-stu-id="45aca-116">For more information, see [Manage Attachments, Links, and Notes on Cards and Documents](ui-how-add-link-to-record.md).</span></span>

> [!NOTE]
> <span data-ttu-id="45aca-117">Wenn Sie die Funktion **Stückliste explodieren** auf dem Verkaufsauftrag verwendet haben, werden im Bericht nur die Komponenten des zugehörigen Montageartikels angezeigt.</span><span class="sxs-lookup"><span data-stu-id="45aca-117">If you used the **Explode BOM** function on the sales order, then only the components of the related assembly item are shown in the report.</span></span> <span data-ttu-id="45aca-118">Weitere Informationen finden Sie unter [Mit Stücklisten arbeiten](inventory-how-work-BOMs.md).</span><span class="sxs-lookup"><span data-stu-id="45aca-118">For more information, see [Work with Bills of Material](inventory-how-work-BOMs.md).</span></span>

## <a name="see-also"></a><span data-ttu-id="45aca-119">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="45aca-119">See Also</span></span>  
[<span data-ttu-id="45aca-120">Lagerbestand</span><span class="sxs-lookup"><span data-stu-id="45aca-120">Inventory</span></span>](inventory-manage-inventory.md)  
[<span data-ttu-id="45aca-121">Entnahme von Artikeln</span><span class="sxs-lookup"><span data-stu-id="45aca-121">Pick Items</span></span>](warehouse-pick-items.md)  
<span data-ttu-id="45aca-122">[Arbeiten mit [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="45aca-122">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>   