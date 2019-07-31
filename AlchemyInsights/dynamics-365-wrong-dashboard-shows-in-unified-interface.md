---
title: Dynamics 365 - salah Dashboard menunjukkan dalam antarmuka yang bersatu Dynamics 365
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1484"
- "6200024"
ms.openlocfilehash: 6edf6fbae0174f3fa4d635c7a99e7daae1243b60
ms.sourcegitcommit: a413a0e27ef4ab8c484fa9fccff8bbef381c8b96
ms.translationtype: MT
ms.contentlocale: id-ID
ms.lasthandoff: 07/16/2019
ms.locfileid: "35747919"
---
# <a name="wrong-dashboard-shows-in-dynamics-365-unified-interface"></a><span data-ttu-id="fd88b-102">Salah dashboard menunjukkan dalam antarmuka yang bersatu Dynamics 365</span><span class="sxs-lookup"><span data-stu-id="fd88b-102">Wrong dashboard shows in Dynamics 365 unified interface</span></span>

<span data-ttu-id="fd88b-103">Ada beberapa alasan mengapa Anda mungkin melihat sebuah dashboard yang berbeda daripada yang Anda harapkan:</span><span class="sxs-lookup"><span data-stu-id="fd88b-103">There are several reasons why you may see a different dashboard than the one you expect:</span></span>

## <a name="the-user-has-set-a-user-default-dashboard"></a><span data-ttu-id="fd88b-104">Pengguna telah menetapkan pengguna default dashboard</span><span class="sxs-lookup"><span data-stu-id="fd88b-104">The user has set a user default dashboard</span></span> 

<span data-ttu-id="fd88b-105">Biasanya Anda dapat mengidentifikasi pengguna default dashboard diatur jika tombol **Set sebagai Default** tidak menunjukkan di bilah perintah dashboard.</span><span class="sxs-lookup"><span data-stu-id="fd88b-105">Typically you can identify a user default dashboard is set if the **Set As Default** button does not show in the dashboard command bar.</span></span> <span data-ttu-id="fd88b-106">Pengguna default dashboard akan menimpa semua default dashboard, bahkan jika pengguna default dasbor tidak di app saat ini.</span><span class="sxs-lookup"><span data-stu-id="fd88b-106">The user default dashboard will override all other default dashboards, even if the user's default dashboard is not in the current app.</span></span>

<span data-ttu-id="fd88b-107">Menggunakan solusi berikut untuk unset dashboard default mereka.</span><span class="sxs-lookup"><span data-stu-id="fd88b-107">Use the following workaround to unset their default dashboard.</span></span>

1. <span data-ttu-id="fd88b-108">Membuat dashboard pribadi baru.</span><span class="sxs-lookup"><span data-stu-id="fd88b-108">Create a new personal dashboard.</span></span>

2. <span data-ttu-id="fd88b-109">Menetapkan dashboard yang baru sebagai default pengguna.</span><span class="sxs-lookup"><span data-stu-id="fd88b-109">Set that new dashboard as the user default.</span></span>

3. <span data-ttu-id="fd88b-110">Menghapus dashboard itu.</span><span class="sxs-lookup"><span data-stu-id="fd88b-110">Delete that dashboard.</span></span>

## <a name="the-dashboard-is-set-in-the-sitemap"></a><span data-ttu-id="fd88b-111">Dashboard terletak di sitemap</span><span class="sxs-lookup"><span data-stu-id="fd88b-111">The dashboard is set in the sitemap</span></span>

<span data-ttu-id="fd88b-112">Anda dapat menetapkan dashboard default organisasi dengan memilih sebuah dashboard dan memilih 'Set sebagai Default' di bawah 'Menyesuaikan sistem'.</span><span class="sxs-lookup"><span data-stu-id="fd88b-112">You may have set an organization default dashboard by selecting a dashboard and choosing 'Set As Default' under 'Customize The System'.</span></span> <span data-ttu-id="fd88b-113">Tapi dashboard didefinisikan dalam desain sitemap akan mengambil alih dashboard ini, jika pengguna memiliki akses ke sana.</span><span class="sxs-lookup"><span data-stu-id="fd88b-113">But the dashboard defined in the sitemap designer will take precedence over this dashboard, if the user has access to it.</span></span>

<span data-ttu-id="fd88b-114">Agar pengguna melihat dashboard Anda tetapkan sebagai default organisasi, Anda dapat:</span><span class="sxs-lookup"><span data-stu-id="fd88b-114">To have users see the dashboard you've set as the organization default, you can either:</span></span>

* <span data-ttu-id="fd88b-115">Menetapkan bahwa dashboard dalam sitemap</span><span class="sxs-lookup"><span data-stu-id="fd88b-115">Set that dashboard in the sitemap</span></span>

* <span data-ttu-id="fd88b-116">Menghapus akses ke dashboard sitemap yang ditetapkan bagi para pengguna</span><span class="sxs-lookup"><span data-stu-id="fd88b-116">Remove access to the sitemap defined dashboard for those users</span></span>