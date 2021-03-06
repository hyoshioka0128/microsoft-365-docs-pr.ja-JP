---
title: Microsoft 365 Business CSP サブスクリプションの移行 
description: Microsoft 365 Business CSP サブスクリプションをプレビューから GA に移行する方法を紹介します。 
author: jasongroce
ms.author: jasgro
ms.topic: article 
ms.prod: microsoft-365-business
localization_priority: Normal
audience: microsoft-business 
keywords: Microsoft 365 Business, Microsoft 365, SMB, CSP サブスクリプションの移行
ms.date: 11/01/2017
ms.openlocfilehash: 8109c0b00f06a15c12bbccf89e7f49dc3fa4b34a
ms.sourcegitcommit: 81273a9df49647286235b187fa2213c5ec7e8b62
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/23/2019
ms.locfileid: "32286256"
---
# <a name="transition-a-microsoft-365-business-csp-subscription"></a>Microsoft 365 Business CSP サブスクリプションの移行

Microsoft 365 Business Preview CSP サブスクリプションを利用している場合、既存のプレビュー サブスクリプションを Microsoft 365 Business GA (一般提供) に移行する方法を確認するには、このガイドを参照してください。

**プレビュー サブスクリプションを GA に移行する方法**

1. <a href="https://partnercenter.microsoft.com" target="_blank">パートナー センター</a>にサインインします。
2. ダッシュボードから、**[顧客]** を選び、会社名を選びます。

    会社のサブスクリプションが表示されます。

    ![パートナー センターでの顧客のサブスクリプションの表示](images/pc_customer_subscriptions_1.png)
    
3. 会社の **[サブスクリプション]** ページで、**[サブスクリプションの追加]** を選びます。
4. **[新しいサブスクリプション]** ページで **[小規模ビジネス]** を選び、一覧から **[Microsoft 365 Business]** を選びます。
5. ライセンス数を追加し、**[次へ: レビュー]** を選びます。サブスクリプションを確認して、**[送信]** を選びます。

    ![Microsoft 365 Business の新しいサブスクリプションの確認](images/pc_customer_reviewnewsubscription.png)

    **[ライセンス ベースのサブスクリプション]** には、**[Microsoft 365 Business Preview]** と **[Microsoft 365 Business]** が表示されます。 次に、Preview サブスクリプションを中断する必要があります。

6. **[Microsoft 365 Business Preview]** を選びます。
7. **[Microsoft 365 Business Preview]** ページで、**[中断]** を選んで Preview サブスクリプションを中断します。

    ![Microsoft 365 Business の Preview サブスクリプションの中断](images/pc_customer_m365bpreview_suspend.png)

8. **[送信]** をクリックして確認します。

    **[サブスクリプション]** ページで、**[Microsoft 365 Business Preview]** の状態が **[中断]** と表示されていることを確認します。

    ![Preview サブスクリプションの状態が中断になっていることを確認する](images/pc_customer_m365bpreview_suspend_confirm.png)

9. 必要に応じて、使用許諾契約書を検証することもできます。 これを行うには、次の手順に従います。
    1. 会社の **[サブスクリプション]** ページから **[ユーザーとライセンス]** を選びます。
    2. **[ユーザーとライセンス]** ページで、ユーザーを選択します。
    3. ユーザーのページで、**[ライセンスの割り当て]** セクションを調べて、**[Microsoft 365 Business]** が表示されていることを確認します。

        ![Microsoft 365 Business ライセンスがユーザーに割り当てられていることを確認する](images/pc_customer_userslicenses_m365b_validate.png)

## <a name="impact-to-customers-and-users-during-and-after-transition"></a>移行中および移行後のお客様とユーザーへの影響

移行中や移行後にお客様とユーザーへの影響はありません。

## <a name="impact-to-customers-who-dont-transition"></a>移行されないお客様への影響

次の表は、Microsoft 365 Business Preview サブスクリプションから Microsoft 365 Business サブスクリプションに移行しないお客様への影響をまとめたものです。

|       | T-0 ～ T+30     | T+30 ～ T+60 | T+60 ～ T+120 | T+120 超  |
|-------|-----------------|--------------|---------------|---------------|
| **状態** | 解約猶予期間 | 有効期限切れ      | 無効      | プロビジョニング解除 |
| **サービスへの影響**                                                        |
| **Microsoft 365 Business 管理ポータル** | 機能への影響なし | 機能への影響なし | ユーザーを追加/削除、サブスクリプションを購入できます。</br> ライセンスを割り当て/取り消しできません。 | お客様のサブスクリプションとすべてのデータが削除されます。 管理者は他の有料サブスクリプションを管理できます。 |
| **Office アプリ**                         | エンド ユーザーへの影響なし | エンド ユーザーへの影響なし | Office は機能制限モードになります。</br> ユーザーはファイルを表示することのみできます。 | Office は機能制限モードになります。</br> ユーザーはファイルを表示することのみできます。 |
| **クラウド サービス (SharePoint Online、Exchange Online、Skype、Teams など)** | エンド ユーザーへの影響なし | エンド ユーザーへの影響なし | エンド ユーザーと管理者はクラウドにあるデータにアクセスできません。 | お客様のサブスクリプションとすべてのデータが削除されます。 |
| **EM+S コンポーネント** | 管理者への影響なし</br> エンド ユーザーへの影響なし | 管理者への影響なし</br> エンド ユーザーへの影響なし | 機能が使用できなくなります。</br> 詳細については、「[サブスクリプションの有効期限が切れた場合のモバイル デバイスに対する影響](#mobile-device-impacts-upon-subscription-expiration)」と「[サブスクリプションの有効期限が切れた場合の Windows 10 PC に対する影響](#windows-10-pc-impacts-upon-subscription-expiration)」をご覧ください。 | 機能が使用できなくなります。</br> 詳細については、「[サブスクリプションの有効期限が切れた場合のモバイル デバイスに対する影響](#mobile-device-impacts-upon-subscription-expiration)」と「[サブスクリプションの有効期限が切れた場合の Windows 10 PC に対する影響](#windows-10-pc-impacts-upon-subscription-expiration)」をご覧ください。 |
| **Windows 10 Business** | 管理者への影響なし</br> エンド ユーザーへの影響なし | 管理者への影響なし</br> エンド ユーザーへの影響なし | 機能が使用できなくなります。</br> 詳細については、「[サブスクリプションの有効期限が切れた場合のモバイル デバイスに対する影響](#mobile-device-impacts-upon-subscription-expiration)」と「[サブスクリプションの有効期限が切れた場合の Windows 10 PC に対する影響](#windows-10-pc-impacts-upon-subscription-expiration)」をご覧ください。 | 機能が使用できなくなります。</br> 詳細については、「[サブスクリプションの有効期限が切れた場合のモバイル デバイスに対する影響](#mobile-device-impacts-upon-subscription-expiration)」と「[サブスクリプションの有効期限が切れた場合の Windows 10 PC に対する影響](#windows-10-pc-impacts-upon-subscription-expiration)」をご覧ください。 |
| **Windows 10 PC への Azure AD ログイン** | 管理者への影響なし</br> エンド ユーザーへの影響なし | 管理者への影響なし</br> エンド ユーザーへの影響なし | 管理者への影響なし</br> エンド ユーザーへの影響なし | テナントが削除されると、ユーザーはローカルの資格情報によってのみログインできます。 ローカルの資格情報がない場合は、デバイスにイメージを再作成します。 |

## <a name="mobile-device-impacts-upon-subscription-expiration"></a>サブスクリプションの有効期限が切れた場合のモバイル デバイスに対する影響

次の表は、モバイル デバイスのアプリ管理ポリシーへの影響をまとめたものです。

|                            | 完全なライセンスのエクスペリエンス                      | T+有効期限経過後 60 日          |
|----------------------------|------------------------------------------------|------------------------------------|
| **非アクティブなデバイスから仕事用ファイルを削除する** | 選択した日数後に仕事用ファイルは削除されます。 | 仕事用ファイルはユーザーの個人用デバイスに残ります。 |
| **すべての仕事用ファイルを OneDrive for Business に保存するようユーザーに強制する** | 仕事用ファイルは OneDrive for Business にのみ保存されます。 | 仕事用ファイルは任意の場所に保存できます。 |
| **仕事用ファイルを暗号化する** | 仕事用ファイルは暗号化されます。 | 仕事用ファイルは暗号化されなくなります。</br> セキュリティ ポリシーが削除され、アプリの Office データが削除されます。 |
| **Office アプリへのアクセスに暗証番号 (PIN) または指紋を要求する** | アプリへのアクセスが制限されます。 | アプリ レベルのアクセス制限はありません。 |
| **ログインに失敗したときに PIN をリセットする** | アプリへのアクセスが制限されます。 | アプリ レベルのアクセス制限はありません。 |
| **Office アプリがアイドル状態後、ユーザーに再びサインインを要求する** | サインインが必要です。 | アプリにアクセスするためにサインインは必要ありません。 |
| **脱獄またはルート化されたデバイス上の仕事用ファイルへのアクセスを拒否する** | 脱獄またはルート化されたデバイス上の仕事用ファイルにアクセスできません。 | 脱獄またはルート化されたデバイス上の仕事用ファイルにアクセスできます。 |
| **ユーザーが Office アプリから個人用アプリにコンテンツをコピーすることを許可する** | コピー/貼り付けは、Microsoft 365 Business サブスクリプションの一部として利用可能なアプリに制限されます。 | コピー/貼り付けはすべてのアプリで実行できます。 |

## <a name="windows-10-pc-impacts-upon-subscription-expiration"></a>サブスクリプションの有効期限が切れた場合の Windows 10 PC に対する影響

次の表は、Windows 10 デバイスの構成ポリシーへの影響をまとめたものです。

|                            | 完全なライセンスのエクスペリエンス                      | T+有効期限経過後 60 日          |
|----------------------------|------------------------------------------------|------------------------------------|
| **Windows Defender を使用して脅威から PC を保護する** | オン/オフはユーザー コントロールの範囲外です。 | ユーザーは Windows 10 PC で Windows Defender をオン/オフにすることができます。 |
| **Microsoft Edge で Web ベースの脅威から PC を保護する** | Microsoft Edge での PC の保護 | ユーザーは Microsoft Edge での PC の保護をオン/オフにすることができます。 |
| **アイドル状態のときデバイスの画面をオフにする** | 管理者が画面タイムアウト間隔のポリシーを定義します。 | エンド ユーザーが画面のタイムアウトを構成できます。 |
| **Microsoft Store からアプリをダウンロードすることをユーザーに許可する** | 管理者は、ユーザーが Microsoft Store からアプリをダウンロードできるかどうかを定義します。 | ユーザーはいつでも Microsoft Store からアプリをダウンロードできます。 |
| **Cortana へのアクセスをユーザーに許可する** | 管理者が Cortana へのユーザー アクセスのポリシーを定義します。 | ユーザー デバイスで Cortana をオン/オフにすることができます。 |
| **Microsoft からのヒントとお知らせを受信することをユーザーに許可する** | 管理者はユーザーが Microsoft からヒントやお知らせを受信することについてポリシーを定義します。 | ユーザーが Microsoft からのヒントやお知らせをオン/オフにすることができます。 |
| **ユーザーが Office アプリから個人用アプリにコンテンツをコピーすることを許可する** | 管理者が Windows 10 デバイスを最新の状態に保つポリシーを定義します。 | ユーザーが Windows を更新するタイミングを決定できます。 |




