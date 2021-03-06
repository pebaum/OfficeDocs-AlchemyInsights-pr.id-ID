---
title: Mengidentifikasi penerusan email eksternal di kotak pesan dalam log audit
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1369"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: 592eb92e4b0fe0f9da2fa20bb93ffa4fbbb76662
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: id-ID
ms.lasthandoff: 06/02/2020
ms.locfileid: "44508955"
---
# <a name="identify-when-external-email-forwarding-is-configured-on-mailboxes"></a>Mengidentifikasi saat penerusan email eksternal dikonfigurasi pada kotak pesan

Ketika pengguna 365 Microsoft mengkonfigurasi penerusan email eksternal di kotak surat, aktivitas diaudit sebagai bagian dari cmdlet **Set-Mailbox** . Anda dapat melihat aktivitas menggunakan pencarian log audit di pusat kepatuhan & keamanan.

1. Masuk ke [Microsoft 365 keamanan & Compliance Center](https://protection.office.com/).

2. Buka halaman penelusuran **Search**  >  **log audit** penelusuran.

3. Pilih rentang tanggal di kolom tanggal **mulai** dan **tanggal akhir** . Anda tidak perlu menentukan nama pengguna. Verifikasi bidang **aktivitas** diatur untuk **Menampilkan hasil untuk semua aktivitas**.

4. Klik **Cari**.

Di hasil, klik **filter hasil** dan ketik **set-kotak surat** di kotak filter aktivitas. Pilih catatan audit di hasil. Di Flyout **rincian** , klik **informasi lebih lanjut**. Anda harus melihat rincian setiap catatan audit untuk menentukan apakah aktivitas terkait dengan penerusan email.

- **ObjectID**: nilai alias kotak surat yang telah diubah.

- **Parameter**: _forwardingsmtpaddress_ menunjukkan alamat email target.

- **Userid**: pengguna yang dikonfigurasi penerusan email di kotak surat di kolom **ObjectID** .

Untuk selengkapnya, lihat [menentukan siapa yang mengatur penerusan email untuk kotak pesan](https://docs.microsoft.com/microsoft-365/compliance/auditing-troubleshooting-scenarios#determine-who-set-up-email-forwarding-for-a-mailbox).
