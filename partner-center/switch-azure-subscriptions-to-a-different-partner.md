---
title: "Azure 구독을 다른 파트너로 전환 | 파트너 센터"
description: "고객은 Microsoft Azure 서비스에 사용할 클라우드 솔루션 공급자 프로그램의 파트너를 변경할 수 있습니다. 그러나 이 작업은 파트너와 고객 모두의 조치가 필요한 수동 프로세스입니다."
ms.assetid: 42D1D9AB-613D-4FC1-A846-EE769923E699
author: MaggiePucciEvans
translationtype: Human Translation
ms.sourcegitcommit: cb3523dffbd017aa5c40e6899e1cb37be1f2a726
ms.openlocfilehash: ec227dac6f8b0625120bf4b5d1bc76fbeaaae635

---

# Azure 구독을 다른 파트너로 전환

**적용 대상**

-  파트너 센터

고객은 Microsoft Azure 서비스에 사용할 클라우드 솔루션 공급자 프로그램의 파트너를 변경할 수 있습니다. 그러나 이 작업은 파트너와 고객 모두의 조치가 필요한 수동 프로세스입니다.

**참고** 현재 Azure 고객이 EA, 오픈 또는 기타 라이선싱 프로그램에서 CSP로 전환하는 자동 프로세스는 없습니다. 이 작업은 파트너와 고객의 조치가 필요한 수동 프로세스입니다. 또한 Office 365, Enterprise Mobility Suite 또는 Microsoft Dynamics CRM 구독에 대한 클라우드 솔루션 공급자 구독의 파트너는 현재 변경할 수 없습니다.

 

**Azure 구독에 대한 파트너 전환**

1.  Azure 구독을 새 파트너로 이전하려면 고객이 프로세스를 시작하고 현재 POR(Partner of Record) CSP 파트너에 서면으로 연락해야 합니다.

2.  구독의 CSP는 다음 작업을 수행해야 합니다.

    파트너 센터에서 구독 이전을 요청하는 Azure 서비스 티켓을 만듭니다.

    -   파트너 센터 대시보드 메뉴에서 **고객**을 선택하고 목록에서 해당 고객을 선택한 다음 **서비스 관리**를 선택합니다. **지원 티켓** 섹션에서 **새 티켓** 드롭다운을 선택하고 **Microsoft Azure**를 선택합니다.

    -   Azure Portal에서 **새 지원 요청**을 선택합니다.

        1단계에서 **구독 관리**를 문제 유형으로 선택하고 이전하려는 구독 ID를 지정한 다음 **클라우드 솔루션 공급자**를 지원 계획으로 선택합니다.

        2단계에서 **C–Minimal impact**(C - 최소 영향)를 선택하고 문제 유형으로 **Other General Questions**(기타 일반 질문)를 선택합니다.

        [CSP 구독 이전 양식](https://assets.windowsphone.com/5222c408-e546-4e01-b72a-2ec7d4c43d57/CSP_Subscription_Transfer_Form_Azure_InvariantCulture_Default.zip)을 다운로드합니다.

3.  구독의 현재 CSP 파트너: [CSP 구독 이전 양식](https://assets.windowsphone.com/5222c408-e546-4e01-b72a-2ec7d4c43d57/CSP_Subscription_Transfer_Form_Azure_InvariantCulture_Default.zip)을 작성하고 서명한 다음 고객에게 보냅니다. 양식을 작성하려면 다음 정보가 필요합니다.

    -   현재 파트너의 연락처 정보 및 Microsoft ID. 파트너 센터 메뉴에서 **계정 설정** &gt; **조직 프로필**을 선택하고 나열된 **Microsoft ID**, **조직 이름** 및 **주소**를 사용합니다.

    -   고객의 Microsoft ID. 파트너 센터 메뉴에서 **고객**을 선택하고 고객 목록을 확장하여 **Microsoft ID**를 확인합니다.

    -   이전할 구독 ID. 확장된 고객 목록에서 **구독 보기**를 선택한 다음 선택한 구독을 확장하여 **구독 ID**를 확인합니다.

4.  고객 및 구독의 새 CSP:

    양식을 검토하고 새 파트너에 대한 정보를 입력한 다음 서명합니다. 새 고객에게 계약 협약서가 있는지 확인합니다. 현재 POR(Partner of Record)에게 양식을 다시 보냅니다.

    *중요*: 새 CSP 파트너가 고객과의 재판매인 관계가 없으면 구독을 이전하기 전에 재판매인 관계를 설정해야 합니다. [여기서 이 작업을 수행하는 방법에 대한 자세한 내용을 확인할 수 있습니다](https://int.msdn.microsoft.com/en-us/library/partnercenter/mt750320.aspx).

5.  현재 CSP 파트너:

    양식에 두 파트너 관리자의 연락처 정보가 포함되어 있는지 확인합니다. Microsoft 지원 센터에서 두 관리자에게 연락하여 이전을 확인합니다. 세 개의 서명이 모두 있는지 확인한 다음 **파일 업로드** 옵션을 사용하여 완성된 양식을 기존 서비스 요청에 첨부합니다. Microsoft 지원 엔지니어가 업무 시간으로 8시간 내에 연락하여 수신 및 완료를 확인합니다.

6.  새 CSP 파트너:

    Azure 구독 설정을 업데이트하여 계정에서 이전 파트너를 제거합니다. 프로비전된 역할 할당을 보려면 두 개의 Powershell Commandlet을 실행합니다.

    -   새 파트너를 계정의 재판매인으로 추가:

        **PS C:\\&gt; Add-AzureRMAccount -tenant "CustomerDomainName"**

        customerDomainName을 찾으려면 파트너 센터 메뉴에서 **고객**을 선택합니다. 고객 목록에서 고객을 선택합니다. 고객 메뉴에서 **계정**을 선택하고 **도메인 이름**을 사용합니다.

    -   이전 CSP 파트너를 포함하여 계정의 역할 보기:

        **PS C:\\&gt; Get-AzureRMRoleAssignment**

    Azure 포털에서 구독을 관리하여 구독 및 리소스에 대한 오래된 액세스 권한을 제거합니다. 파트너 센터 메뉴에서 **고객**을 선택합니다. 고객 목록을 확장하고 **구독 보기**를 선택합니다. 고객 메뉴에서 **서비스 관리**를 선택합니다. **Microsoft Azure** 아래에서 **Microsoft Azure 관리 포털**로 이동하는 링크를 클릭합니다.

 

 






<!--HONumber=Jan17_HO2-->

