---
title: Terjebak dalam outbox karena lampiran besar
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2713"
- "9000768"
- "9002385"
- "4645"
ms.openlocfilehash: 4f69de167dc51961fa7cf71b4d73ca7ee3ed4d55
ms.sourcegitcommit: 57fb994ddd3854d06faa67680c971b003b06bf83
ms.translationtype: MT
ms.contentlocale: id-ID
ms.lasthandoff: 04/13/2020
ms.locfileid: "43241255"
---
# <a name="fix-messages-that-are-stuck-in-the-outbox"></a>Memperbaiki pesan yang terjebak di kotak keluar

Kami sarankan Anda memulai dengan menjalankan skenario ["saya mengalami masalah mengirim, menerima, atau menemukan pesan email"](https://aka.ms/SaRA-OutlookSendReceive) dari [Microsoft dukungan dan pemulihan asisten](https://diagnostics.office.com/#/) alat.

Saat pesan macet di kotak keluar, kemungkinan penyebabnya adalah lampiran besar atau opsi "Kirim segera saat tersambung" tidak diaktifkan.

**Menghapus lampiran besar**

1. Di Outlook, pilih **kirim/terima** > **bekerja secara offline**. 
2. Di panel navigasi, pilih **kotak keluar**. Dari sini, Anda dapat: 
    - Hapus pesan (pilih dan pilih **Hapus**).
    - Seret pesan ke folder draf, klik dua kali untuk membukanya, dan Hapus lampiran memilihnya lalu pilih **Hapus**).
3. Jika Anda menerima galat yang mengatakan Outlook mencoba untuk mengirimkan pesan, tutup Outlook. Mungkin perlu beberapa saat untuk keluar. Jika Outlook tidak menutup, tekan CTRL + ALT + delete dan pilih **mulai pengelola tugas**. Di Manajer tugas, pilih tab **proses** , gulir ke bawah ke Outlook. exe, dan pilih **Akhiri proses**.
4. Setelah menutup Outlook, mulai ulang dan ulangi langkah 2 dan 3. 
5. Setelah Anda menghapus lampiran, klik **kirim/terima** > **bekerja secara offline** untuk melanjutkan kerja online. 

Pesan juga macet di kotak keluar bila Anda mengklik **kirim**, namun Anda tidak tersambung. Klik **kirim/terima** dan lihat tombol **bekerja offline** . Jika berwarna biru, Anda akan terputus. Klik untuk menghubungkan (tombol berubah putih) dan klik **kirim semua**.
 
**Aktifkan kirim segera ketika terhubung**
 
1. Pada file tab, klik **opsi**.

2. Di kotak dialog Opsi Outlook, klik **lanjut**.

3. Di bagian kirim dan terima, klik untuk mengaktifkan **kirim segera ketika tersambung**. Klik **OK**.
 
Untuk detail selengkapnya, lihat:
- [Video: mengirim atau menghapus email yang macet](https://support.office.com/article/Video-Send-or-delete-an-email-stuck-in-your-outbox-26d5d34a-4e5f-444a-a9e8-44db04a94dec) 
- [Email tetap berada di folder kotak keluar sampai Anda secara manual memulai operasi kirim/terima di Outlook](https://support.microsoft.com/help/2797572/email-stays-in-the-outbox-folder-until-you-manually-initiate-a-send-re)
