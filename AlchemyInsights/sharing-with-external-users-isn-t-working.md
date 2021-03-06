---
title: Berbagi dengan pengguna eksternal tidak berfungsi
ms.author: mikeplum
author: MikePlumleyMSFT
manager: scotv
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: d3d0b69b-214e-4859-8957-621fd6306b30
ms.openlocfilehash: 37da77c73b3abbdcf9cb2b9c4c43f31eea3c0a49
ms.sourcegitcommit: 286000b588adef1bbbb28337a9d9e087ec783fa2
ms.translationtype: MT
ms.contentlocale: id-ID
ms.lasthandoff: 04/27/2020
ms.locfileid: "43913005"
---
# <a name="fix-problems-sharing-sharepoint-content-with-external-users"></a>Memperbaiki masalah saat berbagi konten SharePoint dengan pengguna eksternal

Pastikan berbagi eksternal diaktifkan untuk organisasi Anda:
  
1. Buka [Halaman Add- &amp; in layanan di pusat admin Microsoft 365](https://portal.office.com/adminportal/home#/Settings/ServicesAndAddIns), dan klik **situs**.
    
2. Pastikan setelan diubah menjadi "aktif". Jika "hanya ada pengguna eksternal" dipilih, pastikan pengguna eksternal tercantum di pusat admin Microsoft 365.
    
Pastikan berbagi eksternal diaktifkan untuk situs. Untuk koleksi situs klasik:
  
1. Di pusat admin SharePoint baru, di sebelah kiri, klik **situs**.
    
2. Pilih situs atau situs, dan pada pita, klik **berbagi**.
    
Untuk situs tim yang dimiliki oleh grup 365 Microsoft, atau situs komunikasi:
  
- Jenis situs baru ini memiliki setelan berbagi yang sama dengan setelan di seluruh organisasi, kecuali jika setelan di seluruh organisasi memungkinkan berbagi file menggunakan tautan yang tidak memerlukan masuk. Dalam hal ini, situs memungkinkan berbagi dengan pengguna eksternal baru dan yang ada yang masuk. Untuk mengubah pengaturan untuk situs tertentu, gunakan Pusat admin SharePoint baru atau PowerShell. [Pelajari selengkapnya](https://go.microsoft.com/fwlink/?linkid=871863).
    
> [!NOTE]
> Setelan berbagi eksternal untuk situs mana pun dapat lebih ketat daripada setelan di seluruh organisasi, tetapi tidak lebih permisif daripada setelan di seluruh organisasi. 
  

