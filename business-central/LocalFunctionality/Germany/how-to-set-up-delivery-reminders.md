---
title: 'Gewusst wie: Einrichten von Lieferbenachrichtigungen'
description: In Business Central können Sie Lieferbenachrichtigungen nutzen, um Verkäufer über verspätete Lieferungen zu mahnen.
author: SorenGP
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: ''
ms.date: 04/01/2020
ms.author: sgroespe
ms.openlocfilehash: 23bcc95f24d19281577f8563e4c1b4f1b17e6a50
ms.sourcegitcommit: 88e4b30eaf6fa32af0c1452ce2f85ff1111c75e2
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 04/01/2020
ms.locfileid: "3181156"
---
# <a name="set-up-delivery-reminders"></a><span data-ttu-id="5d12c-103">Gewusst wie: Einrichten von Lieferbenachrichtigungen</span><span class="sxs-lookup"><span data-stu-id="5d12c-103">Set Up Delivery Reminders</span></span>
<span data-ttu-id="5d12c-104">In [!INCLUDE[d365fin](../../includes/d365fin_md.md)] können Sie Lieferbenachrichtigungen nutzen, um Verkäufer über verspätete Lieferungen zu mahnen.</span><span class="sxs-lookup"><span data-stu-id="5d12c-104">In [!INCLUDE[d365fin](../../includes/d365fin_md.md)], you can use purchase delivery reminders to remind vendors about overdue deliveries.</span></span> <span data-ttu-id="5d12c-105">Um Lieferanmahnungen für Kreditoren zu erstellen, müssen Sie die Stammdaten für die Erstellung von Lieferanmahnungen sowie die Nummernserien für die Lieferanmahnungen auf der Seite Fenster **Kreditoren & Einkauf einrichten** einrichten.</span><span class="sxs-lookup"><span data-stu-id="5d12c-105">To create delivery reminders for vendors, you must set up base data for delivery reminder creation and number series for the delivery reminders on the **Purchases & Payables Setup** page.</span></span>  

## <a name="to-set-up-delivery-reminders"></a><span data-ttu-id="5d12c-106">Gewusst wie: Einrichten von Lieferbenachrichtigungen</span><span class="sxs-lookup"><span data-stu-id="5d12c-106">To set up delivery reminders</span></span>  

1.  <span data-ttu-id="5d12c-107">Wählen Sie das Symbol ![Suche nach Seite oder Bericht](../../media/ui-search/search_small.png "Symbol „Suche nach Seite oder Bericht“") aus, geben Sie **Einkäufe und Verbindlichkeiten – Einrichtung** ein und wählen Sie dann den entsprechenden Link.</span><span class="sxs-lookup"><span data-stu-id="5d12c-107">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Purchases & Payables Setup**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="5d12c-108">Wählen Sie im Inforegister **Allgemein** im Feld **Standard ENTF. Abbau, AfA**, geben Sie eine der folgenden Optionen an, wie in der folgenden Tabelle beschrieben.</span><span class="sxs-lookup"><span data-stu-id="5d12c-108">On the **General** FastTab, in the **Default Del. Rem. Date Field** field, specify one of the following options as described in the following table.</span></span>  

    |<span data-ttu-id="5d12c-109">Option</span><span class="sxs-lookup"><span data-stu-id="5d12c-109">Option</span></span>|<span data-ttu-id="5d12c-110">Description</span><span class="sxs-lookup"><span data-stu-id="5d12c-110">Description</span></span>|  
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="5d12c-111">**Gewünschtes Wareneingangsdatum**</span><span class="sxs-lookup"><span data-stu-id="5d12c-111">**Requested Receipt Date**</span></span>|<span data-ttu-id="5d12c-112">Um anzugeben, dass der Datumswert im Feld **Gewünschtes Wareneingangsdatum** in der Bestellzeile als Standarddatum für die Erstellung von Lieferanmahnungen verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="5d12c-112">To specify that the date value in the **Requested Receipt Date** field on the purchase order line will be used as the default date for creating delivery reminders.</span></span>|  
    |<span data-ttu-id="5d12c-113">**Zugesagtes Wareneingangsdatum**</span><span class="sxs-lookup"><span data-stu-id="5d12c-113">**Promised Receipt Date**</span></span>|<span data-ttu-id="5d12c-114">Um anzugeben, dass der Datumswert im Feld **Gewünschtes Wareneingangsdatum** in der Bestellzeile als Standarddatum für die Erstellung von Lieferanmahnungen verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="5d12c-114">To specify that the date value in the **Promised Receipt Date** field on the purchase order line will be used as the default date for creating delivery reminders.</span></span>|  
    |<span data-ttu-id="5d12c-115">**Erwartetes Wareneingangsdatum**</span><span class="sxs-lookup"><span data-stu-id="5d12c-115">**Expected Receipt Date**</span></span>|<span data-ttu-id="5d12c-116">Um anzugeben, dass der Datumswert im Feld **Erwartetes Wareneingangsdatum** in der Bestellzeile als Standarddatum für die Erstellung von Lieferanmahnungen verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="5d12c-116">To specify that the date value in the **Expected Receipt Date** field on the purchase order line will be used as the default date for creating delivery reminders.</span></span>|  

3.  <span data-ttu-id="5d12c-117">Füllen Sie im Inforegister **Nummerierung** die Felder gemäß der Beschreibung in der folgenden Tabelle aus.</span><span class="sxs-lookup"><span data-stu-id="5d12c-117">On the **Numbering** FastTab, fill in the fields as described in the following table.</span></span>  

    |<span data-ttu-id="5d12c-118">Feld</span><span class="sxs-lookup"><span data-stu-id="5d12c-118">Field</span></span>|<span data-ttu-id="5d12c-119">Description</span><span class="sxs-lookup"><span data-stu-id="5d12c-119">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="5d12c-120">**Lieferbenachrichtigungsnummern**</span><span class="sxs-lookup"><span data-stu-id="5d12c-120">**Delivery Reminder Nos.**</span></span>|<span data-ttu-id="5d12c-121">Der Nummernseriencode für Lieferanmahnungen.</span><span class="sxs-lookup"><span data-stu-id="5d12c-121">The number series code for delivery reminders.</span></span>|  
    |<span data-ttu-id="5d12c-122">**Reg. Lieferbenachrichtigungsnummern**</span><span class="sxs-lookup"><span data-stu-id="5d12c-122">**Issued Delivery Reminder Nos.**</span></span>|<span data-ttu-id="5d12c-123">Der Nummernseriencode für ausgegebene Lieferanmahnungen.</span><span class="sxs-lookup"><span data-stu-id="5d12c-123">The number series code for issued delivery reminders.</span></span>|  

4.  <span data-ttu-id="5d12c-124">Wählen Sie die Schaltfläche **OK** aus.</span><span class="sxs-lookup"><span data-stu-id="5d12c-124">Choose the **OK** button.</span></span>  

## <a name="see-also"></a><span data-ttu-id="5d12c-125">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="5d12c-125">See Also</span></span>  
 <span data-ttu-id="5d12c-126">[Lieferbenachrichtigungen](delivery-reminders.md) </span><span class="sxs-lookup"><span data-stu-id="5d12c-126">[Delivery Reminders](delivery-reminders.md) </span></span>  
 <span data-ttu-id="5d12c-127">[Einrichten von Lieferbenachrichtigungsbestimmungen, Stufen und Text](how-to-set-up-delivery-reminder-terms-levels-and-text.md) </span><span class="sxs-lookup"><span data-stu-id="5d12c-127">[Set Up Delivery Reminder Terms, Levels, and Text](how-to-set-up-delivery-reminder-terms-levels-and-text.md) </span></span>  
 <span data-ttu-id="5d12c-128">[So werden Lieferbenachrichtigungscodes zu Kreditoren zugewiesen](how-to-assign-delivery-reminder-codes-to-vendors.md) </span><span class="sxs-lookup"><span data-stu-id="5d12c-128">[Assign Delivery Reminder Codes to Vendors](how-to-assign-delivery-reminder-codes-to-vendors.md) </span></span>  
 [<span data-ttu-id="5d12c-129">So erstellen Sie Lieferanmahnungen manuell</span><span class="sxs-lookup"><span data-stu-id="5d12c-129">Create Delivery Reminders Manually</span></span>](how-to-create-delivery-reminders-manually.md)
