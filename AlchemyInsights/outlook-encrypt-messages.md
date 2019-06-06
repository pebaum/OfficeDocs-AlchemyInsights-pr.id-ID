---
title: S/MIME di Outlook di web
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.date: 5/1/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: 9000329
ms.openlocfilehash: 16454927730d49ba1ec64380145b0fde1294850b
ms.sourcegitcommit: 6d341637dbb14e90726a1ce1d68f077ace9bb765
ms.translationtype: MT
ms.contentlocale: id-ID
ms.lasthandoff: 06/04/2019
ms.locfileid: "34720220"
---
# <a name="encrypt-email-messages-in-outlook"></a><span data-ttu-id="e076a-102">Mengenkripsi pesan email di Outlook</span><span class="sxs-lookup"><span data-stu-id="e076a-102">Encrypt email messages in Outlook</span></span>

<p><span data-ttu-id="e076a-103"><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif;">Kantor 365 pesan enkripsi dibangun di Microsoft Azure Rights Management (Azure RMS) yang merupakan bagian dari perlindungan informasi Azure. Jika Anda berlangganan termasuk manajemen hak Azure atau Azure perlindungan informasi, <strong style="mso-bidi-font-weight: normal;">Anda tidak perlu untuk mengambil tindakan untuk secara manual mengaktifkan atau mengaktifkan</strong> Layanan manajemen hak.</span></span><span class="sxs-lookup"><span data-stu-id="e076a-103"><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif;">Office 365 Message Encryption is built on Microsoft Azure Rights Management (Azure RMS) which is part of Azure Information Protection. If your subscription includes Azure Rights Management or Azure Information Protection, <strong style="mso-bidi-font-weight: normal;">you do not need to take any actions to manually enable or activate</strong> the Rights Management Service.</span></span></span></p> <p><span data-ttu-id="e076a-104"><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif;">Berdasarkan umpan balik pelanggan, kita akan tidak lagi memungkinkan asing mail aliran aturan untuk secara otomatis mengenkripsi outbound email yang berisi informasi sensitif di penyewa Anda jenis tertentu secara default. &nbsp; Sebagai gantinya, kami menyediakan petunjuk rinci pada bagaimana Anda dapat melakukannya sendiri. &nbsp;Untuk rincian tambahan tentang cara membuat aturan transport untuk mengenkripsi informasi sensitif, lihat <a href="https://aka.ms/OmeEtr">artikel</a>ini.</span><u></u><span style="text-decoration: line-through;"></span></span><span class="sxs-lookup"><span data-stu-id="e076a-104"><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif;">Based on customer feedback, we will no longer be enabling Exchange mail flow rules to automatically encrypt outbound email containing certain type of sensitive information in your tenant by default.&nbsp; Instead, we are providing detailed instructions on how you can do so yourselves. &nbsp;For additional details on how to create a transport rule to encrypt sensitive information, see this <a href="https://aka.ms/OmeEtr">article</a>.</span><u></u><span style="text-decoration: line-through;"></span></span></span></p> <ul> <li style="text-indent: -.25in; mso-list: l0 level1 lfo1;"><span data-ttu-id="e076a-105"><span style="font-size: 10.5pt; font-family: Symbol; mso-fareast-font-family: Symbol; mso-bidi-font-family: Symbol;"><span style="mso-list: Ignore;">&nbsp;&nbsp; &nbsp; &nbsp; </span> </span> <span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif;">Jika menggunakan Outlook di Web (formerly <strong style="mso-bidi-font-weight: normal;">OWA</strong>): Ketika menyusun pesan email, cukup klik <strong>melindungi</strong> dalam OWA. Hal ini akan berlaku secara default &lsquo;tidak maju&rsquo; izin. Klik <strong>perubahan izin</strong> dan memilih <strong>mengenkripsi</strong> hanya mengenkripsi pesan.</span></span><span class="sxs-lookup"><span data-stu-id="e076a-105"><span style="font-size: 10.5pt; font-family: Symbol; mso-fareast-font-family: Symbol; mso-bidi-font-family: Symbol;"><span style="mso-list: Ignore;">&nbsp; &nbsp; &nbsp;&nbsp; </span></span><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif;">If using Outlook on the Web (formerly <strong style="mso-bidi-font-weight: normal;">OWA</strong>): When composing an email message, simply click <strong>Protect</strong> in OWA. This will apply by default &lsquo;Do not forward&rsquo; permission. Click <strong>Change permission</strong> and choose <strong>Encrypt</strong> to only encrypt the message.</span></span></span></li> <li style="text-indent: -.25in; mso-list: l0 level1 lfo1;"><span data-ttu-id="e076a-106"><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif;">&nbsp;&nbsp; &nbsp; Jika menggunakan <strong style="mso-bidi-font-weight: normal;">Outlook client</strong>: untuk mengirim pesan yang dienkripsi dari Outlook 2013 atau 2016, atau Outlook 2016 untuk Mac, pilih opsi &agrave; izin, kemudian pilih opsi perlindungan yang Anda butuhkan.</span></span><span class="sxs-lookup"><span data-stu-id="e076a-106"><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif;">&nbsp; &nbsp;&nbsp; If using <strong style="mso-bidi-font-weight: normal;">Outlook client</strong>: To send an encrypted message from Outlook 2013 or 2016, or Outlook 2016 for Mac, select Options &agrave; Permissions, then select the protection option you need.</span></span></span></li> <li style="text-indent: -.25in; mso-list: l0 level1 lfo1;"><span data-ttu-id="e076a-107"><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif;">&nbsp;&nbsp; Untuk <strong style="mso-bidi-font-weight: normal;">secara otomatis mengenkripsi semua email</strong> dikirim ke penerima atau organisasi mitra eksternal tertentu, Anda perlu membuat aturan transport aliran e-mail di asing Admin Center. Petunjuk rinci disediakan di ini <span style="color: black;"><a href="https://docs.microsoft.com/en-us/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email#create-a-mail-flow-rule-to-encrypt-email-messages-with-the-new-ome-capabilities">mendukung artikel</a></span></span></span><span class="sxs-lookup"><span data-stu-id="e076a-107"><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif;">&nbsp; &nbsp; To <strong style="mso-bidi-font-weight: normal;">automatically encrypt all email</strong> sent to certain recipients or external partner organizations, you need to create a mail flow transport rule in the Exchange Admin Center. Detailed instructions are provided in this <span style="color: black;"><a href="https://docs.microsoft.com/en-us/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email#create-a-mail-flow-rule-to-encrypt-email-messages-with-the-new-ome-capabilities">support article</a></span></span></span></span></li> </ul>
