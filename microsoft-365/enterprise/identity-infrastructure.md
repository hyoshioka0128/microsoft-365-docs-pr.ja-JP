---
title: 'フェーズ 2: ID'
ms.author: josephd
author: JoeDavies-MSFT
manager: laurawi
ms.date: 04/16/2019
ms.audience: ITPro
ms.topic: article
ms.service: o365-solutions
localization_priority: Priority
ms.collection:
- M365-identity-device-management
- Strat_O365_Enterprise
ms.custom: ''
description: Microsoft 365 Enterprise の ID インフラストラクチャを展開する手順。
ms.openlocfilehash: 932b6fb2cfeb86edcf708bdfdea55cdd8b580838
ms.sourcegitcommit: 81273a9df49647286235b187fa2213c5ec7e8b62
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/23/2019
ms.locfileid: "32288740"
---
# <a name="phase-2-identity"></a>フェーズ 2: ID

![](./media/deploy-foundation-infrastructure/identity_icon.png)

Microsoft 365 enterprise では、ID インフラストラクチャを入念に計画および実施することで、セキュリティを強化し、認証されたユーザーとデバイスだけが生産性ワークロードとそのデータにアクセスできるようにする準備が整います。

>[!Note]
>既に ID インフラストラクチャを展開している場合は、[ID インフラストラクチャの終了条件](identity-exit-criteria.md)を参照し、Microsoft 365 Enterprise の必須条件とオプションの条件を満たしていることを確認してください。
>

## <a name="plan-and-deploy-your-microsoft-365-enterprise-identity-infrastructure"></a>Microsoft 365 Enterprise の ID インフラストラクチャを計画および展開する 

開始する前に、Microsoft 365 の ID モデルと認証の概要についてこのビデオをご覧ください。

> [!VIDEO https://www.microsoft.com/videoplayer/embed/RE2Pjwu]

クラウドで新しい ID インフラストラクチャを計画および展開するには、次の手順を使用します。また、これらの手順を使用して既存のオンプレミスまたはハイブリッド ID インフラストラクチャを導入し、Microsoft 365 Enterprise と連携することができます。 

|||
|:-------|:-----|
|![](./media/stepnumbers/Step1.png)| [ユーザーおよびグループを計画する](identity-plan-users-groups.md) |
|![](./media/stepnumbers/Step2.png)| [特権 ID をセキュリティで保護する](identity-designate-protect-admin-accounts.md) |
|![](./media/stepnumbers/Step3.png)| [ハイブリッド ID の構成](identity-azure-ad-connect.md) |
|![](./media/stepnumbers/Step4.png)| [セキュリティで保護されたユーザー認証を構成する](identity-multi-factor-authentication.md) |
|![](./media/stepnumbers/Step5.png)| [ユーザーのアクセスを簡素化する](identity-password-reset.md) |
|![](./media/stepnumbers/Step6.png)| [管理を容易にするためのグループの使用](identity-self-service-group-management.md) |

上記の手順が完了したら、このフェーズの[終了条件](identity-exit-criteria.md)を参照し、Microsoft 365 Enterprise の必須条件とオプションの条件を満たしていることを確認します。

## <a name="identity-and-device-access-recommendations"></a>ID とデバイスのアクセスに関する推奨事項

Microsoft では、セキュアで生産性の高い要員を確保するために [ID とデバイスのアクセス](microsoft-365-policies-configurations.md)に関する一連の推奨事項を提供しています。たとえば、このフェーズの手順で、以下の記事に記されている推奨事項と設定を使用してください。

- [前提条件](identity-access-prerequisites.md)
- [共通 ID とデバイスのアクセス ポリシー](identity-access-policies.md)

## <a name="how-microsoft-does-microsoft-365-enterprise"></a>Microsoft での Microsoft 365 Enterprise の活用方法

以下のリソースで、Microsoft の IT 担当者による Microsoft 365 Enterprise の ID 機能の計画方法および展開方法を確認することができます。

- [Microsoft でのユーザー ID の管理とアクセスの保護](https://www.microsoft.com/itshowcase/Article/Content/931/Managing-user-identities-and-secure-access-at-Microsoft)
- [アクセス許可を昇格するために、Azure AD Privileged Identity Management を使用する](https://www.microsoft.com/itshowcase/Article/Content/887/Using-Azure-AD-Privileged-Identity-Management-for-elevated-access)

## <a name="how-contoso-did-microsoft-365-enterprise"></a>Contoso 社での Microsoft 365 Enterprise の活用方法

架空の典型的な多国籍企業である Contoso Corporation が、Microsoft 365 のクラウド サービス向けに[ハイブリッド ID インフラストラクチャを展開](contoso-identity.md)した方法をご紹介します。

![](./media/contoso-overview/contoso-icon.png)


## <a name="next-step"></a>次の手順

|||
|:-------|:-----|
|![](./media/stepnumbers/Step1.png)| [ユーザーおよびグループを計画する](identity-plan-users-groups.md) |
