---
title: DLP tidak bekerja seperti yang diharapkan
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1241"
- "3200001"
ms.assetid: f6fcf5ad-55a1-4f25-af27-1f7c1ce06409
ms.openlocfilehash: e96904e2f0da2fe1fafb3f8722465eaf22681b71
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: id-ID
ms.lasthandoff: 06/02/2020
ms.locfileid: "44507481"
---
# <a name="dlp-not-working-as-expected"></a>DLP tidak bekerja seperti yang diharapkan

**Penting**: Selama masa-masa yang berat ini, kami mengambil langkah untuk memastikan bahwa SharePoint Online dan layanan OneDrive tetap memiliki ketersediaan yang tinggi. Silakan kunjungi [Penyesuaian Fitur Sementara SharePoint Online](https://aka.ms/ODSPAdjustments) untuk informasi selengkapnya.

 **Menyiapkan DLP**

Apakah Anda mengalami masalah dengan **pencegahan kehilangan data (DLP)** di Office 365 tidak bekerja seperti yang diharapkan? Jika demikian, pastikan bahwa Anda **DLP kebijakan** diatur dengan benar, dan bahwa data Anda berisi apa **kebijakan DLP** sedang mencari ketika sedang dievaluasi.
  
Kebijakan DLP memungkinkan Anda mengidentifikasi dan melindungi informasi sensitif di organisasi Anda. Untuk setup DLP kebijakan, gunakan informasi [di sini](https://docs.microsoft.com/office365/securitycompliance/prevent-data-loss#set-up-dlp).
  
 **Apa yang dicari oleh kebijakan DLP**
  
Bila menggunakan **jenis informasi sensitif internal** di pusat keamanan dan kepatuhan, kebijakan DLP akan mencari pola dan elemen tertentu saat mendeteksi jenis sensitif ini.
  
- **Jenis informasi sensitif internal**

    Untuk informasi tentang jenis sensitif internal dan apa yang dicari oleh kebijakan DLP saat mendeteksi jenis sensitif, lihat: [apa jenis informasi sensitif Cari](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions).

- **Jenis informasi sensitif khusus**

    Jika Anda mencoba untuk membuat jenis informasi sensitif kustom, gunakan artikel berikut ini untuk informasi tentang cara membuat jenis sensitif kustom: [membuat jenis informasi sensitif kustom](https://docs.microsoft.com/microsoft-365/compliance/create-a-custom-sensitive-information-type).

**Menguji kebijakan DLP**

Untuk menguji data Anda dengan jenis informasi sensitif internal atau kustom, gunakan opsi **jenis uji** di bawah **klasifikasi**  >  **jenis Info sensitif**. Untuk informasi selengkapnya, lihat [menguji jenis informasi sensitif kustom](https://docs.microsoft.com/microsoft-365/compliance/create-a-custom-sensitive-information-type#create-custom-sensitive-information-types-in-the-security--compliance-center).

 **Laporan**
  
- Dapatkan wawasan data sensitif dengan [laporan DLP.](https://docs.microsoft.com/microsoft-365/compliance/data-loss-prevention-policies#dlp-reports)

- Lihat detail spesifik acara dengan [laporan insiden](https://docs.microsoft.com/microsoft-365/compliance/data-loss-prevention-policies#incident-reports).
