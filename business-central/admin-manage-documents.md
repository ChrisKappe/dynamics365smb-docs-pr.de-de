---
title: "Verwalten, löschen oder komprimieren von Belegen | Microsoft Docs"
description: "Speichern Sie die historischen Daten oder löschen Sie sie."
author: edupont04
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/01/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: d7fb34e1c9428a64c71ff47be8bcff174649c00d
ms.openlocfilehash: 292231a907970de2821daeba87003eca7bf54cdc
ms.contentlocale: de-de
ms.lasthandoff: 03/22/2018

---
# <a name="manage-documents"></a><span data-ttu-id="df433-103">Verwalten von Belegen</span><span class="sxs-lookup"><span data-stu-id="df433-103">Manage Documents</span></span>
<span data-ttu-id="df433-104">Ein Benutzer mit einer zentralen Rolle, z. B. der Anwendungsadministrator, muss sich regelmäßig um die angesammelten historischen Belege kümmern, indem er diese löscht oder komprimiert.</span><span class="sxs-lookup"><span data-stu-id="df433-104">A central role, such as the application administrator, must regularly deal with accumulating historic documents by deleting or compressing them.</span></span>  

## <a name="delete-documents"></a><span data-ttu-id="df433-105">Belege löschen</span><span class="sxs-lookup"><span data-stu-id="df433-105">Delete Documents</span></span>
<span data-ttu-id="df433-106">Es kann gelegentlich erforderlich sein, erledigte Einkaufsbestellungen zu löschen, die noch nicht gelöscht wurden.</span><span class="sxs-lookup"><span data-stu-id="df433-106">In certain situations, you may need to delete invoiced purchase orders that have not been deleted.</span></span> [!INCLUDE[d365fin](includes/d365fin_md.md)]<span data-ttu-id="df433-107"> überprüft, ob Sie die gelöschten Bestellungen vollständig fakturiert haben.</span><span class="sxs-lookup"><span data-stu-id="df433-107"> checks that you have fully invoiced the deleted purchase orders.</span></span> <span data-ttu-id="df433-108">Sie können keine Bestellungen löschen, die noch nicht vollständig geliefert und fakturiert wurden.</span><span class="sxs-lookup"><span data-stu-id="df433-108">You cannot delete orders that you have not fully invoiced and received.</span></span>  

<span data-ttu-id="df433-109">Reklamationen werden üblicherweise gelöscht, nachdem sie fakturiert wurden.</span><span class="sxs-lookup"><span data-stu-id="df433-109">Return orders are usually deleted after they are invoiced.</span></span> <span data-ttu-id="df433-110">Wenn Sie eine Rechnung buchen, wird sie in das Fenster **Geb. Einkaufsgutschrift** übertragen.</span><span class="sxs-lookup"><span data-stu-id="df433-110">When you post an invoice, it is transferred to the **Posted Purchase Credit Memo** window.</span></span> <span data-ttu-id="df433-111">Ist das Kontrollkästchen **Rücklieferung bei Gutschrift** im Fenster **Kreditoren & Einkauf Einr.** aktiviert, wird sie auch in das Fenster **Gebuchte Rücklieferung** übertragen.</span><span class="sxs-lookup"><span data-stu-id="df433-111">If you selected the **Return Shipment on Credit Memo** check box in the **Purchases & Payable Setup** window, then the invoice is transferred to the **Posted Return Shipment** window.</span></span> <span data-ttu-id="df433-112">Sie können die Belege mithilfe der Stapelverarbeitung **Erledigte Eink.-Rekl. löschen** löschen.</span><span class="sxs-lookup"><span data-stu-id="df433-112">You can delete the documents using the **Delete Invd Purch. Ret. Orders** batch job.</span></span> <span data-ttu-id="df433-113">Vor dem Löschen prüft die Stapelverarbeitung, ob die Einkaufsreklamationen vollständig geliefert und fakturiert wurden.</span><span class="sxs-lookup"><span data-stu-id="df433-113">Before deleting, the batch job checks if the purchase return orders are fully shipped and invoiced.</span></span>  

<span data-ttu-id="df433-114">Rahmenbestellungen werden nicht gelöscht, nachdem Sie alle zugehörigen Bestellungen verarbeitet und fakturiert haben.</span><span class="sxs-lookup"><span data-stu-id="df433-114">Blanket purchase orders are not deleted after you have processed and invoiced all the related purchase orders.</span></span> <span data-ttu-id="df433-115">Sie können erledigte Rahmenbestellungen mit Hilfe der Stapelverarbeitung **Erledigte Rahmenbestellungen löschen** löschen.</span><span class="sxs-lookup"><span data-stu-id="df433-115">You can delete blanket orders with the **Delete Invoiced Blanket Purchase Orders** batch job.</span></span>  

<span data-ttu-id="df433-116">Verrechnete Serviceaufträge werden automatisch gelöscht, nachdem diese vollständig fakturiert wurden.</span><span class="sxs-lookup"><span data-stu-id="df433-116">Invoiced service orders are usually deleted automatically after having been fully invoiced.</span></span> <span data-ttu-id="df433-117">Beim Buchen einer Rechnung wird ein entsprechender Posten im Fenster **Gebuchte Servicerechnungen** erstellt.</span><span class="sxs-lookup"><span data-stu-id="df433-117">When an invoice is posted, a corresponding entry is created in the **Posted Service Invoices** window.</span></span> <span data-ttu-id="df433-118">Der gebuchte Beleg kann im Fenster **Gebuchte Servicerechnung** angezeigt werden.</span><span class="sxs-lookup"><span data-stu-id="df433-118">The posted document can be viewed in the **Posted Service Invoice** window.</span></span>  

<span data-ttu-id="df433-119">Serviceaufträge werden aber nicht automatisch gelöscht, wenn die Gesamtmenge des Auftrags nicht aus dem eigentlichen Serviceauftrag, sondern im Fenster **Servicerechnung** gebucht wurde.</span><span class="sxs-lookup"><span data-stu-id="df433-119">Service orders are not deleted automatically, however, if the total quantity on the order has been posted not from the service order itself, but from the **Service Invoice** window.</span></span> <span data-ttu-id="df433-120">In diesem Fall müssen Sie fakturierte Aufträge, die nicht gelöscht wurden, manuell löschen.</span><span class="sxs-lookup"><span data-stu-id="df433-120">Then you may need to delete invoiced orders that were not deleted.</span></span> <span data-ttu-id="df433-121">Dazu führen Sie die Stapelverarbeitung **Fakturierte Serviceaufträge löschen** aus.</span><span class="sxs-lookup"><span data-stu-id="df433-121">You can do this by running the **Delete Invoiced Service Orders** batch job.</span></span>  

## <a name="see-also"></a><span data-ttu-id="df433-122">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="df433-122">See Also</span></span>  
[<span data-ttu-id="df433-123">Einrichtung und Verwaltung in Business Central</span><span class="sxs-lookup"><span data-stu-id="df433-123">Setup and Administration in Business Central</span></span>](admin-setup-and-administration.md)  
