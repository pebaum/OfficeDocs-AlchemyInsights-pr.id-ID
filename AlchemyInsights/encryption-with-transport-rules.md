---
title: Enkripsi dengan aturan transportasi
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002635"
- "5154"
ms.openlocfilehash: 3f16c7e7be99a50cd57f47ea2801b3022c4aec95
ms.sourcegitcommit: 07725fcaf073f0ac145f98653b989afdb34c5ad0
ms.translationtype: HT
ms.contentlocale: id-ID
ms.lasthandoff: 04/28/2020
ms.locfileid: "43915176"
---
# <a name="encryption-with-transport-rules"></a>Enkripsi dengan aturan transportasi

Di [Pusat Admin Exchange](https://go.microsoft.com/fwlink/p/?linkid=834822) (EAC), Anda dapat menggunakan kemampuan Enkripsi Pesan Office (OME) di aturan aliran email untuk memicu enkripsi pesan. Pilih opsi **Terapkan Enkripsi Pesan dan perlindungan hak Office 365** pada kondisi Aturan Transportasi.

- Untuk informasi selengkapnya, lihat [Menentukan Aturan aliran email untuk mengenkripsi](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email).

- Di PowerShell, gunakan cmdlet [New-TransportRule](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email?view=o365-worldwide#use-exchange-online-powershell-to-create-a-mail-flow-rule-for-encrypting-email-messages-without-the-new-ome-capabilities) dan atur parameter *ApplyOME* ke $true.
