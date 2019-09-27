---
title: Kirim pemberitahuan kustom dengan Intune
ms.author: brenduns
author: brenduns
manager: dougeby
ms.date: 07/31/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: 9000679
ms.openlocfilehash: 1244f07fd56cf603280f1710520a04d579224e44
ms.sourcegitcommit: 16f08d051afca3c6d0de32826324f91cf63ab5ba
ms.translationtype: MT
ms.contentlocale: id-ID
ms.lasthandoff: 09/16/2019
ms.locfileid: "36992316"
---
# <a name="how-to-send-custom-notifications-to-the-users-of-managed-ios-and-android-devices"></a><span data-ttu-id="e7dc7-102">Cara mengirim pemberitahuan kustom ke pengguna perangkat iOS dan Android yang dikelola</span><span class="sxs-lookup"><span data-stu-id="e7dc7-102">How to send custom notifications to the users of managed iOS and Android devices</span></span>

<span data-ttu-id="e7dc7-103">Pemberitahuan kustom untuk Intune diproses oleh aplikasi portal perusahaan di perangkat pengguna.</span><span class="sxs-lookup"><span data-stu-id="e7dc7-103">Custom notifications for Intune are processed by the Company Portal app on a user’s device.</span></span> <span data-ttu-id="e7dc7-104">Aplikasi ini kemudian membuat pemberitahuan push pada perangkat tersebut.</span><span class="sxs-lookup"><span data-stu-id="e7dc7-104">The app then creates the push notification on that device.</span></span>

<span data-ttu-id="e7dc7-105">Berikut adalah prasyarat perangkat untuk mendukung penerimaan pemberitahuan kustom, dan untuk aplikasi kemudian membuat pemberitahuan push:</span><span class="sxs-lookup"><span data-stu-id="e7dc7-105">The following are device prerequisites to support receipt of custom notifications, and for the app to then create the push notification:</span></span>

- <span data-ttu-id="e7dc7-106">Perangkat harus memiliki aplikasi portal perusahaan yang diinstal.</span><span class="sxs-lookup"><span data-stu-id="e7dc7-106">The device must have the Company Portal app installed.</span></span>  

- <span data-ttu-id="e7dc7-107">Perangkat harus mengizinkan aplikasi portal perusahaan untuk mengirim pemberitahuan push.</span><span class="sxs-lookup"><span data-stu-id="e7dc7-107">The device must allow the Company Portal app to send push notifications.</span></span> <span data-ttu-id="e7dc7-108">Ketika aplikasi diinstal atau diperbarui, itu akan meminta pengguna untuk mengizinkan pemberitahuan.</span><span class="sxs-lookup"><span data-stu-id="e7dc7-108">When the app is installed or updated, it will prompt the user to permit notifications.</span></span>

- <span data-ttu-id="e7dc7-109">Perangkat Android harus memiliki layanan Google Play terinstal.</span><span class="sxs-lookup"><span data-stu-id="e7dc7-109">Android devices must have Google Play Services installed.</span></span>

- <span data-ttu-id="e7dc7-110">Perangkat harus terdaftar dengan Intune.</span><span class="sxs-lookup"><span data-stu-id="e7dc7-110">The device must be enrolled with Intune.</span></span>

<span data-ttu-id="e7dc7-111">Untuk informasi selengkapnya, termasuk cara mengirim pesan, lihat [dokumentasi fitur](https://docs.microsoft.com/intune/custom-notifications).</span><span class="sxs-lookup"><span data-stu-id="e7dc7-111">For more information including how to send a message, see the [feature documentation](https://docs.microsoft.com/intune/custom-notifications).</span></span>