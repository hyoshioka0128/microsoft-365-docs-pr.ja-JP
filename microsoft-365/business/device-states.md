---
title: デバイス状態
ms.author: sirkkuw
author: Sirkkuw
manager: scotv
ms.audience: Admin
ms.topic: overview
ms.service: o365-administration
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- Adm_O365
- Core_O365Admin_Migration
- MiniMaven
- MSB365
search.appverid:
- BCS160
- MET150
- MOE150
ms.assetid: c3ac23c5-d4b4-4b1b-b7ce-ea759521bf8c
description: Microsoft 365 のビジネスでのデバイスの状態について説明します。
ms.openlocfilehash: bd6f1ad7f7671d9616fd14d477dfcfb164ff6bd0
ms.sourcegitcommit: eb1a77e4cc4e8f564a1c78d2ef53d7245fe4517a
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 11/28/2018
ms.locfileid: "26869227"
---
# <a name="device-states"></a>デバイス状態

## <a name="device-states"></a>デバイス状態

[ **デバイス アクション**] ([管理者のホーム] \> [ **デバイス アクション**]) の一覧にあるデバイスは、次のいずれかの状態になります。
  
![In the Device actions list, you can see the Devices states.](media/a621c47e-45d9-4e1a-beb9-c03254d40c1d.png)
  
|**状態**|**説明**|
|:-----|:-----|
|Intune で管理  <br/> |Microsoft 365 Business で管理されています。  <br/> |
|インベントリからの削除待ち  <br/> |Microsoft 365 Business はデバイスから会社データを削除する準備をしています。  <br/> |
|回収を実行中です  <br/> |現在、Microsoft 365 Business はデバイスから会社データを削除しています。  <br/> |
|インベントリからの削除失敗  <br/> | 会社データの削除アクションが失敗しました。  <br/> |
|インベントリからの削除がキャンセルされました  <br/> |インベントリからの削除がキャンセルされました。  <br/> |
|ワイプの保留中  <br/> |出荷時のリセットを開始するのを待っています。  <br/> |
|ワイプを実行中です  <br/> |出荷時のリセットが発行されました。  <br/> |
|ワイプ失敗  <br/> |出荷時の設定へのリセットを実行できませんでした。  <br/> |
|ワイプがキャンセルされました  <br/> |出荷時のワイプがキャンセルされました。  <br/> |
|異常  <br/> |アクションは保留中 (または進行中) ですが、デバイスは 30 日以上チェックインされていないことを意味します。  <br/> |
|削除の保留中  <br/> |削除アクションが保留中です。  <br/> |
|検出  <br/> |Microsoft 365 Business はデバイスを検出しました。  <br/> |
   