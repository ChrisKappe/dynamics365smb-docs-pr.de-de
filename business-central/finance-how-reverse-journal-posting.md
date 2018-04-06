---
title: "Rückgängigmachen einer Buchung durch Buchung einer Rückbuchung | Microsoft Docs"
description: "Wenn Sie fehlerhafte Buchungen im Fibu Buch.-Blatt vorgenommen haben, können Sie die Funktion verwenden, um die korrekte Buchung mit einem Protokoll zu stornieren."
services: project-madeira
documentationcenter: 
author: SorenGP
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: reimbursement
ms.date: 08/03/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: d7fb34e1c9428a64c71ff47be8bcff174649c00d
ms.openlocfilehash: 9a4a7001ab5a752bf2e2acdd273d2a584a1e0b8a
ms.contentlocale: de-de
ms.lasthandoff: 03/22/2018

---
# <a name="reverse-postings"></a><span data-ttu-id="87019-103">Buchungen stornieren</span><span class="sxs-lookup"><span data-stu-id="87019-103">Reverse Postings</span></span>
<span data-ttu-id="87019-104">Zum Stornieren (Rückgängig machen) fehlerhafter Buch.-Blattbuchungen wählen Sie einen Posten und erstellen einen Korrekturposten (ein Posten, die mit dem ursprünglichen Posten identisch ist, jedoch im Betragsfeld ein umgekehrtes Vorzeichen aufweist) mit derselben Belegnummer und demselben Belegdatum wie der ursprüngliche Posten.</span><span class="sxs-lookup"><span data-stu-id="87019-104">To undo an erroneous journal posting, you select the entry and create a reverse entry (entries identical to the original entry but with opposite sign in the amount field) with the same document number and posting date as the original entry.</span></span> <span data-ttu-id="87019-105">Nachdem Sie einen Posten storniert haben, müssen Sie den Korrekturposten erstellen.</span><span class="sxs-lookup"><span data-stu-id="87019-105">After reversing an entry, you must make the correct entry.</span></span>

<span data-ttu-id="87019-106">Storniert werden können nur Posten, die in eine Zeile eines Fibu Buch.-Blattes gebucht wurden.</span><span class="sxs-lookup"><span data-stu-id="87019-106">You can only reverse entries that are posted from a general journal line.</span></span> <span data-ttu-id="87019-107">Ein Posten kann nur einmal storniert werden.</span><span class="sxs-lookup"><span data-stu-id="87019-107">An entry can only be reversed once.</span></span>

<span data-ttu-id="87019-108">Weitere Informationen zum Buchen eines Fibu Buch.-Blatt, siehe [Transaktionen direkt in die Finanzbuchhaltung buchen](finance-how-post-transactions-directly.md).</span><span class="sxs-lookup"><span data-stu-id="87019-108">For more information about posting from a general journal, see [Post Transactions Directly to the General Ledger](finance-how-post-transactions-directly.md).</span></span>

<span data-ttu-id="87019-109">Wenn Sie eine inkorrekte negative Mengenbuchung durchgeführt haben, das heißt, wenn Sie eine Einkaufsbestellung mit der falschen Artikelmenge erstellt und als Wareneingang gebucht (aber nicht fakturiert) haben, können Sie die Buchung umkehren.</span><span class="sxs-lookup"><span data-stu-id="87019-109">If you have made an incorrect negative quantity posting, such as a purchase order with the wrong number of items and posted it as received but not invoiced, then you can undo the posting.</span></span>

<span data-ttu-id="87019-110">Wenn Sie eine inkorrekte positive Mengenbuchung durchgeführt haben, das heißt, wenn Sie einen Rückgabeauftrag mit der falschen Artikelmenge erstellt und als Warenausgang gebucht (aber nicht fakturiert) haben, können Sie die Buchung umkehren.</span><span class="sxs-lookup"><span data-stu-id="87019-110">If you have made an incorrect positive quantity posting, such as a purchase return order with the wrong number of items and posted it as shipped but not invoiced, then you can undo the posting.</span></span>   

## <a name="to-reverse-the-journal-posting-of-a-general-ledger-entry"></a><span data-ttu-id="87019-111">Um die Buch.-Blatt-Buchung eines Sachpostens zu stornieren</span><span class="sxs-lookup"><span data-stu-id="87019-111">To reverse the journal posting of a general ledger entry</span></span>
<span data-ttu-id="87019-112">Posten können in allen **Posten** storniert werden.</span><span class="sxs-lookup"><span data-stu-id="87019-112">You can reverse entries from all **Ledger Entries** windows.</span></span> <span data-ttu-id="87019-113">Das folgende Verfahren basiert auf dem **Sachposten** Fenster.</span><span class="sxs-lookup"><span data-stu-id="87019-113">The following procedure is based on the **General Ledger Entries** window.</span></span>
1. <span data-ttu-id="87019-114">Wählen Sie in der rechten oberen Ecke das Symbol ![Nach Seite oder Bericht suchen](media/ui-search/search_small.png "Nach Seite oder Bericht suchen") und geben die **Finanzbuchhaltung einrichten** ein. Wählen Sie dann den zugehörigen Link aus.</span><span class="sxs-lookup"><span data-stu-id="87019-114">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **General Ledger Entries**, and then choose the related link.</span></span>
2. <span data-ttu-id="87019-115">Wählen Sie den Posten, den Sie stornieren möchten, und wählen die **Transaktion stornieren** Aktion aus.</span><span class="sxs-lookup"><span data-stu-id="87019-115">Select the entry that you want to reverse, and then choose the **Reverse Transaction** action.</span></span> <span data-ttu-id="87019-116">Beachten Sie, das sie aus einer Buch.-Blatt-Buchung stammen muss.</span><span class="sxs-lookup"><span data-stu-id="87019-116">Note that is must originate from a journal posting.</span></span>
3. <span data-ttu-id="87019-117">Im Fenster **Transaktionsposten stornieren** wählen Sie den entsprechenden Posten, und wählen die **Stornieren** Aktion aus.</span><span class="sxs-lookup"><span data-stu-id="87019-117">In the **Reverse Transaction Entries** window, select the relevant entry, and then choose the **Reverse** action.</span></span>
4. <span data-ttu-id="87019-118">Klicken Sie auf die Schaltfläche **Ja** auf der Bestätigungsnachricht.</span><span class="sxs-lookup"><span data-stu-id="87019-118">Choose the **Yes** button on the confirmation message.</span></span>

## <a name="to-undo-a-quantity-posting-on-a-posted-purchase-receipt"></a><span data-ttu-id="87019-119">So stornieren Sie eine Mengenbuchung einer gebuchten Einkaufslieferzeile</span><span class="sxs-lookup"><span data-stu-id="87019-119">To undo a quantity posting on a posted purchase receipt</span></span>  

1.  <span data-ttu-id="87019-120">Wählen Sie das Symbol ![Nach Seite oder Bericht suchen](media/ui-search/search_small.png "Symbol Nach Seite oder Bericht suchen"), geben **Geb. Einkaufslieferungen** ein und wählen dann den zugehörigen Link aus.</span><span class="sxs-lookup"><span data-stu-id="87019-120">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Posted Purchase Receipts**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="87019-121">Öffnen Sie die gebuchte Lieferung, den Sie rückgängig machen möchten.</span><span class="sxs-lookup"><span data-stu-id="87019-121">Open the posted receipt that you want to undo.</span></span>  
3.  <span data-ttu-id="87019-122">Wählen Sie die Zeile oder Zeilen aus, die Sie rückgängig machen möchten.</span><span class="sxs-lookup"><span data-stu-id="87019-122">Select the line or lines that you want to undo.</span></span>  
4.  <span data-ttu-id="87019-123">Wählen Sie die Aktion **Wareneingang stornieren** aus.</span><span class="sxs-lookup"><span data-stu-id="87019-123">Choose **Undo Receipt** action.</span></span>

    <span data-ttu-id="87019-124">Eine Korrekturzeile wird unter der ausgewählten Lieferzeile eingefügt.</span><span class="sxs-lookup"><span data-stu-id="87019-124">A corrective line is inserted under the selected receipt line.</span></span>  

    <span data-ttu-id="87019-125">Wenn die Menge in einem Wareneingang eingegangen ist, wird eine Korrekturzeile in den gebuchten Wareneingang eingefügt.</span><span class="sxs-lookup"><span data-stu-id="87019-125">If the quantity was received in a warehouse receipt, then a corrective line is inserted in the posted warehouse receipt.</span></span>  

    <span data-ttu-id="87019-126">Die Felder **Bereits gelief. Menge** und **Lief. nicht fakt. Menge** auf der zugehörigen Bestellung werden auf Null gesetzt.</span><span class="sxs-lookup"><span data-stu-id="87019-126">The **Quantity Received** and **Qty. Rcd. Not Invoiced** fields on the related purchase order are set to zero.</span></span>

## <a name="to-undo-and-then-redo-a-quantity-posting-on-a-posted-return-shipment"></a><span data-ttu-id="87019-127">Eine Mengenbuchung einer gebuchter Rücklieferungen stornieren und wiederholen</span><span class="sxs-lookup"><span data-stu-id="87019-127">To undo and then redo a quantity posting on a posted return shipment</span></span>

1.  <span data-ttu-id="87019-128">Wählen Sie das Symbol ![Nach Seite oder Bericht suchen](media/ui-search/search_small.png "Symbol Nach Seite oder Bericht suchen"), geben **Gebuchte Rücklieferungen** ein und wählen dann den zugehörigen Link aus.</span><span class="sxs-lookup"><span data-stu-id="87019-128">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Posted Return Shipments**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="87019-129">Öffnen Sie die gebuchte Rücklieferung, den Sie rückgängig machen möchten.</span><span class="sxs-lookup"><span data-stu-id="87019-129">Open the posted return shipment that you want to undo.</span></span>
3. <span data-ttu-id="87019-130">Wählen Sie die Zeile oder Zeilen aus, die Sie rückgängig machen möchten.</span><span class="sxs-lookup"><span data-stu-id="87019-130">Select the line or lines you want to undo.</span></span>  

4.  <span data-ttu-id="87019-131">Wählen Sie die Aktion **Rücklieferung stornieren**.</span><span class="sxs-lookup"><span data-stu-id="87019-131">Choose the **Undo Return Shipment** action.</span></span>  

    <span data-ttu-id="87019-132">Eine Korrekturzeile wird in den gebuchten Beleg eingefügt, und die Mengen, die in der Reklamation in den Feldern **Rücklieferungsmenge geliefert** und **Lief. n. fakt. Rückl.-Betrag** enthalten sind, werden auf Null gesetzt.</span><span class="sxs-lookup"><span data-stu-id="87019-132">A corrective line is inserted in the posted document, and the **Return Qty. Shipped** and **Return Shpd. Not Invd.** fields on the return order are set to zero.</span></span>  

    <span data-ttu-id="87019-133">Gehen Sie jetzt zurück zu der Einkaufsreklamation, um die Buchung erneut durchzuführen.</span><span class="sxs-lookup"><span data-stu-id="87019-133">Now go back to the purchase return order to redo the posting.</span></span>  

5.  <span data-ttu-id="87019-134">Beachten Sie im Fenster **Gebuchte Rücklieferung** die Nummer im Feld **Reklamationsnr.**.</span><span class="sxs-lookup"><span data-stu-id="87019-134">In the **Posted Return Shipment** window, take a note of the number in the **Return Order No.**</span></span> <span data-ttu-id="87019-135">Feld</span><span class="sxs-lookup"><span data-stu-id="87019-135">field.</span></span>  
6.  <span data-ttu-id="87019-136">Wählen Sie das Symbol ![Nach Seite oder Bericht suchen](media/ui-search/search_small.png "Symbol Nach Seite oder Bericht suchen"), geben **Einkaufsreklamationen** ein und wählen dann den zugehörigen Link aus.</span><span class="sxs-lookup"><span data-stu-id="87019-136">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Purchase Return Orders**, and then select the related link.</span></span>  
7.  <span data-ttu-id="87019-137">Öffnen Sie die betreffende Rücklieferung und wählen Sie die Aktion **Erneut öffnen**.</span><span class="sxs-lookup"><span data-stu-id="87019-137">Open the return order in question, and then choose the **Reopen** action.</span></span>  
8.  <span data-ttu-id="87019-138">Korrigieren Sie den Eintrag im Feld **Menge** und buchen Sie die Rücklieferung erneut.</span><span class="sxs-lookup"><span data-stu-id="87019-138">Correct the entry in the **Quantity** field and post the purchase return order again.</span></span>  

## <a name="to-post-a-negative-entry"></a><span data-ttu-id="87019-139">So buchen Sie einen negativen Posten</span><span class="sxs-lookup"><span data-stu-id="87019-139">To post a negative entry</span></span>  
<span data-ttu-id="87019-140">Im Feld **Storno** kann ein negativer Soll- anstelle eines Habenbetrags oder ein negativer Haben- anstelle eines Sollbetrags in einem Konto gebucht werden.</span><span class="sxs-lookup"><span data-stu-id="87019-140">You can use the **Correction** field to post a negative debit instead of a credit, or to post a negative credit instead of a debit on an account.</span></span> <span data-ttu-id="87019-141">Zur Einhaltung gesetzlicher Vorschriften wird das Feld standardmäßig in allen Buch.-Blättern angezeigt.</span><span class="sxs-lookup"><span data-stu-id="87019-141">To meet legal requirements, this field is visible by default in all journals.</span></span> <span data-ttu-id="87019-142">Die Felder **Sollbetrag** und **Habenbetrag** enthalten jeweils den ursprünglichen und den stornierten Posten.</span><span class="sxs-lookup"><span data-stu-id="87019-142">The **Debit Amount** and **Credit Amount** fields include both the original entry, and the corrected entry.</span></span> <span data-ttu-id="87019-143">Diese Felder haben keinen Einfluss auf den Kontensaldo.</span><span class="sxs-lookup"><span data-stu-id="87019-143">These fields have no effect on the account balance.</span></span>  

1.  <span data-ttu-id="87019-144">Wählen Sie das Symbol ![Nach Seite oder Bericht suchen](media/ui-search/search_small.png "Nach Seite oder Bericht suchen") und geben **Fibu Buch.-Blatt** ein. Wählen Sie dann den zugehörigen Link aus.</span><span class="sxs-lookup"><span data-stu-id="87019-144">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **General Journals**, and then choose the related link</span></span>  
2.  <span data-ttu-id="87019-145">Wählen Sie im Feld **Buch.-Blattname** den erforderlichen Buch.-Blattnamen aus.</span><span class="sxs-lookup"><span data-stu-id="87019-145">In the **Batch Name** field, select the required batch name.</span></span>  
3.  <span data-ttu-id="87019-146">Geben Sie die Informationen in die entsprechenden Felder ein.</span><span class="sxs-lookup"><span data-stu-id="87019-146">Enter information into the relevant fields.</span></span>  
4.  <span data-ttu-id="87019-147">Aktivieren Sie in der Buch.-Blattzeile, die Sie für negative Posten aktivieren möchten, das Kontrollkästchen **Storno**.</span><span class="sxs-lookup"><span data-stu-id="87019-147">In the journal line that you want to activate for negative entries, select the **Correction** check box.</span></span>  
5.  <span data-ttu-id="87019-148">Prüfen Sie die erstellten Posten und wählen Sie dann die Aktion **Buchen**  und dann **Ja**aus.</span><span class="sxs-lookup"><span data-stu-id="87019-148">To post the journal, choose the **Post** action, and then choose the **Yes** button.</span></span>

## <a name="see-also"></a><span data-ttu-id="87019-149">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="87019-149">See Also</span></span>
[<span data-ttu-id="87019-150">Buchen von Transaktionen direkt in der Finanzbuchhaltung</span><span class="sxs-lookup"><span data-stu-id="87019-150">Post Transactions Directly to the General Ledger</span></span>](finance-how-post-transactions-directly.md)  
[<span data-ttu-id="87019-151">Arbeiten mit Fibu Buch.-Blättern</span><span class="sxs-lookup"><span data-stu-id="87019-151">Working with General Journals</span></span>](ui-work-general-journals.md)  
[<span data-ttu-id="87019-152">Finanzen</span><span class="sxs-lookup"><span data-stu-id="87019-152">Finance</span></span>](finance.md)  
<span data-ttu-id="87019-153">[Arbeiten mit [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="87019-153">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>  
