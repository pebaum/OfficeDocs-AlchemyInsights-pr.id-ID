---
title: Kinerja masalah-SharePoint atau OneDrive
ms.author: kirks
author: Techwriter40
ms.date: 1/3/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 9225ec0f-771f-4d7a-8157-e188953107aa
ms.openlocfilehash: 3b04e811b69a1f9d652abbd603c3c09df068480c
ms.sourcegitcommit: 6d341637dbb14e90726a1ce1d68f077ace9bb765
ms.translationtype: MT
ms.contentlocale: id-ID
ms.lasthandoff: 06/04/2019
ms.locfileid: "34719520"
---
# <a name="sharepoint-or-onedrive-slow-inaccessible-or-unavailable-for-multiple-users"></a><span data-ttu-id="6ce53-102">SharePoint atau OneDrive lambat, tidak dapat diakses atau tersedia untuk beberapa pengguna</span><span class="sxs-lookup"><span data-stu-id="6ce53-102">SharePoint or OneDrive Slow, Inaccessible or Unavailable for Multiple Users</span></span>

<span data-ttu-id="6ce53-103">Jika situs OneDrive atau SharePoint tidak tersedia untuk beberapa pengguna yang sebelumnya mempunyai akses, mungkin ada masalah sementara layanan.</span><span class="sxs-lookup"><span data-stu-id="6ce53-103">If a OneDrive or SharePoint site is not available to multiple users who previously had access, there may be a temporary service issue.</span></span> <span data-ttu-id="6ce53-104">[Periksa layanan kesehatan dashboard](https://portal.office.com/adminportal/home#/servicehealth).</span><span class="sxs-lookup"><span data-stu-id="6ce53-104">[Check the service health dashboard](https://portal.office.com/adminportal/home#/servicehealth).</span></span>

## <a name="add-and-license-the-user"></a><span data-ttu-id="6ce53-105">Tambahkan dan lisensi pengguna</span><span class="sxs-lookup"><span data-stu-id="6ce53-105">Add and license the user</span></span>

<span data-ttu-id="6ce53-106">Pastikan bahwa Anda [menetapkan lisensi ke pengguna di Office 365 untuk bisnis](https://docs.microsoft.com/en-us/office365/admin/subscriptions-and-billing/assign-licenses-to-users?view=o365-worldwide&amp;tabs=One).</span><span class="sxs-lookup"><span data-stu-id="6ce53-106">Ensure that you [Assign licenses to users in Office 365 for business](https://docs.microsoft.com/en-us/office365/admin/subscriptions-and-billing/assign-licenses-to-users?view=o365-worldwide&amp;tabs=One).</span></span>


## <a name="assign-permissions"></a><span data-ttu-id="6ce53-107">Memberikan izin</span><span class="sxs-lookup"><span data-stu-id="6ce53-107">Assign Permissions</span></span>

<span data-ttu-id="6ce53-108">Jika pengguna telah ditetapkan lisensi Sharepoint dan masih menerima Akses ditolak pesan, pastikan mereka memiliki [tingkat izin yang sesuai](https://docs.microsoft.com/en-us/sharepoint/understanding-permission-levels) yang ditetapkan.</span><span class="sxs-lookup"><span data-stu-id="6ce53-108">If the user has been assigned a Sharepoint license and is still receiving an access denied message, please ensure they have the [appropriate permission level](https://docs.microsoft.com/en-us/sharepoint/understanding-permission-levels) assigned.</span></span>

## <a name="consider-using-the-access-request-feature"></a><span data-ttu-id="6ce53-109">Pertimbangkan untuk menggunakan fitur permintaan akses</span><span class="sxs-lookup"><span data-stu-id="6ce53-109">Consider using the access request feature</span></span>

<span data-ttu-id="6ce53-110">[Fitur permintaan akses](https://support.office.com/en-us/article/Set-up-and-manage-access-requests-94B26E0B-2822-49D4-929A-8455698654B3) memungkinkan orang untuk meminta akses ke konten yang mereka saat ini tidak memiliki izin untuk melihat.</span><span class="sxs-lookup"><span data-stu-id="6ce53-110">The [access request feature](https://support.office.com/en-us/article/Set-up-and-manage-access-requests-94B26E0B-2822-49D4-929A-8455698654B3) allows people to request access to content that they do not currently have permission to see.</span></span>

## <a name="allow-custom-script-may-cause-access-denied-issues"></a><span data-ttu-id="6ce53-111">Memungkinkan script kustom dapat menyebabkan Akses ditolak masalah</span><span class="sxs-lookup"><span data-stu-id="6ce53-111">Allow custom script may cause access denied issues</span></span>

<span data-ttu-id="6ce53-112">Ada skenario tertentu mana fitur *script kustom Izinkan* mungkin menyajikan Akses ditolak.</span><span class="sxs-lookup"><span data-stu-id="6ce53-112">There are certain scenarios where the *Allow custom script* feature may be presenting an access denied.</span></span> <span data-ttu-id="6ce53-113">Untuk daftar fitur yang terpengaruh, pertimbangan keamanan dan kemampuan untuk menonaktifkan fitur.</span><span class="sxs-lookup"><span data-stu-id="6ce53-113">For a list of features affected, security considerations and the ability to disable the feature.</span></span> <span data-ttu-id="6ce53-114">Silahkan kunjungi [Bolehkan atau mencegah script kustom](https://docs.microsoft.com/en-us/sharepoint/allow-or-prevent-custom-script).</span><span class="sxs-lookup"><span data-stu-id="6ce53-114">Please visit [Allow or prevent custom script](https://docs.microsoft.com/en-us/sharepoint/allow-or-prevent-custom-script).</span></span>
