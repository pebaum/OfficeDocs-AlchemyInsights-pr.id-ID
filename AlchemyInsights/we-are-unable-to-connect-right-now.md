---
title: Masalah aktivasi-kami tidak dapat terhubung saat ini
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3408"
- "9001423"
ms.openlocfilehash: 56accf68f2cf41dbe6119281b74e2cb56b702789
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: id-ID
ms.lasthandoff: 04/22/2020
ms.locfileid: "43716175"
---
# <a name="fixing-the-office-apps-we-are-unable-to-connect-right-now-message"></a>Memperbaiki aplikasi Office "kami tidak dapat terhubung sekarang" pesan

Jika Anda menerima pesan ini, cobalah berikut ini:

1. Periksa firewall, perangkat lunak antivirus, dan pengaturan proxy untuk mengonfirmasi bahwa mereka tidak memblokir akses internet ke aplikasi Office. Lihat [Microsoft URL dan kisaran alamat IP](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges).

2. Pergi ke **mulai** > **menjalankan**, dan kemudian ketik **Services. MSC**. Pastikan bahwa layanan berikut ini berjalan:
    - Jaringan tersambung perangkat Auto-setup
    - Layanan daftar jaringan
    - Kesadaran lokasi jaringan
    - Log peristiwa Windows

Jika salah satu layanan ini tidak berjalan, cobalah untuk memulainya. Jika Anda memiliki masalah memulai layanan, jalankan perintah berikut ini dengan membuka prompt perintah dengan izin yang ditinggikan:

**SFC/SCANNOW**

Setelah perintah ini selesai, mulai ulang komputer.

Untuk informasi terperinci, lihat ["Maaf, kami tidak dapat tersambung ke akun Anda. Silakan coba lagi nanti "galat saat Anda mengaktifkan Office dari Microsoft 365](https://docs.microsoft.com/office/troubleshoot/activation-installation/issue-when-activate-office-from-office-365).