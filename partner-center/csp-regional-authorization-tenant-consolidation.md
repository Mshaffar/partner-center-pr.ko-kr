---
title: "CSP 지역 권한 설정 테넌트 통합 | 파트너 센터"
description: "다양한 국가/지역에 대한 테넌트를 통합하려면 다음 지침을 사용하세요."
ms.assetid: 749B4C6A-26BE-4942-BDA8-F08C40DF048A
author: MaggiePucciEvans
translationtype: Human Translation
ms.sourcegitcommit: 1d29dad279cacb63b59822efe407f26263c1a25b
ms.openlocfilehash: cc87659cd0412876a29a2f8fe48d005a84026509

---

# CSP 지역 권한 설정 테넌트 통합

**적용 대상**

-  파트너 센터
-  Microsoft 클라우드 독일 파트너 센터

\[일부 정보는 상업용으로 출시되기 전에 상당 부분 수정될 수 있는 시험판 제품과 관련이 있습니다. Microsoft는 여기에 제공된 정보에 대해 명시적 또는 묵시적 보증을 하지 않습니다.\]

다양한 국가/지역에 대한 테넌트를 통합하려면 다음 지침을 사용하세요.

**참고** 고객이 전환 계정에서 프로비전한 모든 구독 및 실제 사용자 수를 알고 있어야 합니다. 파트너는 마이그레이션 프로세스의 일부로 새 중앙 CSP 계정에서 같은 실제 사용자 수가 포함된 정확히 같은 구독을 다시 프로비전합니다. 목록 내보내기 기능을 사용하여 중앙 집중식 테넌트로 이동할 고객의 목록을 만드세요. 파트너가 테넌트를 통합하도록 선택합니다. 통합이 완료되면 파트너는 이전 상태로 되돌릴 수 없습니다. 고객 작업도 필요합니다.

 

## 마이그레이션 준비


-   전환(기존) 계정으로 <https://partnercenter.microsoft.com>에 로그온하고 모든 고객 및 해당 고객에 대해 프로비전된 모든 서비스를 기록해 둡니다.

![지역 고객 목록](images/regionalcustomer1.png)

## 고객 계정 마이그레이션


1.  전환(새) 계정으로 <https://partnercenter.microsoft.com>에 로그온하고 파트너 센터 대시보드에서 고객 목록으로 이동합니다.

2.  고객을 선택합니다.

3.  **재판매인 관계 요청**을 클릭합니다. 고객에게 제공할 기본 메일 메시지가 표시됩니다. 이 메시지는 새 파트너 센터 계정에 고유한 조직 ID가 포함된 URL을 포함합니다.

4.  **고객 작업:** 마이그레이션할 각 활성 고객이 이 URL을 방문하도록 합니다. URL을 열면 고객에게 Office 365 포털에 로그인하라는 메시지가 표시됩니다. 고객은 Azure 및 Office 365 관리 포털에 액세스하는 데 사용하는 것과 같은 조직 ID를 사용하여 로그인합니다.

5.  로그인한 후 고객 계정의 전역 관리자에게 새 CSP 계정에 위임된 관리 권한을 부여하는 것에 대한 동의를 제출하라는 메시지가 표시됩니다. 동의하는 경우 고객은 확인란을 선택하고 관계에 권한을 부여하는 것에 동의합니다.

고객이 동의를 제출하고 나면 고객이 하나씩 파트너의 고객 목록에 나타납니다.

## Office 365 및 비 Azure 사용량 기준 구독 마이그레이션


1.  고객이 계약에 서명하고 나면, 중앙 집중식 파트너 테넌트에서 해당 구독을 다시 만들 수 있습니다.

2.  파트너 센터 대시보드의 왼쪽 탐색에서 **고객**을 클릭합니다.

3.  마이그레이션할 고객의 회사 이름을 엽니다.

4.  **구독 추가**를 클릭합니다.

5.  카탈로그에서 올바른 구독 및 실제 사용자 수를 추가합니다. **전환 원본** 파트너 계정에 제공된 정보로 확인합니다.

    ![고객 목록의 스크린샷](images/regionalcustomer2.png)

6.  **제출**을 클릭합니다.

이제 서비스가 **전환 대상** 파트너 계정의 고객에게 제공됩니다.

모든 추가 고객에 대해 구독을 마이그레이션하려면 이러한 단계를 반복합니다.

다음 섹션을 계속하기 전에 **전환 원본** 파트너 계정 아래에 있는 모든 고객 구독이 **전환 대상** 파트너 계정 아래에 다시 프로비전되었는지 확인합니다.

**참고** 파트너는 파트너 센터에서 **전환 대상** 파트너 테넌트 계정 아래에 구독이 전환 및 설정되는 날과 같은 날에 파트너 센터의 **전환 원본** 파트너 테넌트 계정에서 해당 구독을 일시 중단하여 이중 청구가 발생하지 않도록 해야 합니다. **전환 원본** 구독을 사용 안 함으로 올바르게 설정하지 않아 발생하는 청구의 겹침으로 인해 크레딧에 대한 지원 요청이 거부됩니다.

 

## 전환 원본 파트너 계정에서 Office 365 구독을 사용하지 않도록 설정


**전환 원본** 파트너 계정에서 CSP 구독을 사용하지 않도록 설정하면 이후 청구가 중지됩니다. Azure 구독은 마이그레이션 프로세스 동안 자동으로 사용하지 않도록 설정되므로 수동으로 Azure 구독을 사용하지 않도록 설정할 필요가 없습니다.

1.  **전환 원본** CSP 계정으로 <https://partnercenter.microsoft.com>에 로그온하고 고객 목록으로 이동합니다.

2.  사용하지 않도록 설정할 구독이 포함된 고객을 연 다음 사용하지 않도록 설정할 첫 번째 제품을 선택합니다.
3.  구독을 **일시 중단됨**으로 설정한 다음 **제출**을 클릭합니다.

    **참고** 구독을 일시 중단하면 이중 청구가 발생하지 않습니다.

     

    구독이 구독 목록에서 **일시 중단됨**으로 표시됩니다.

4.  고객의 모든 구독에 대해 이러한 단계를 반복합니다. 모든 구독이 **일시 중단됨**으로 표시되는지 확인합니다.

5.  목록에서 다음 고객을 선택하고 모든 구독을 사용하지 않도록 설정하는 프로세스를 반복합니다.

## Azure 사용량 기준 구독 마이그레이션


Office 365 CSP 구독의 경우와 마찬가지로 Azure 사용량 기준 CSP 구독은 수동으로 마이그레이션할 필요가 없습니다. Microsoft Azure 지원에서는 **전환 원본** CSP 재판매인 계정의 모든 배포된 서비스 또는 리소스뿐만 아니라 Azure 구독을 **전환 대상** CSP 재판매인 계정으로 마이그레이션할 수 있습니다. 이 전환 동안 고객에게 서비스 중단이 발생하지 않습니다.

1.  Azure 구독을 마이그레이션해야 하는 고객 계정이 새 **전환 대상** CSP 계정과 연결하기 위한 계약에 동의했는지 확인합니다.
2.  파트너는 Microsoft에 Azure 구독을 마이그레이션할 준비가 된 고객 계정을 알리고 해당 고객의 회사 이름을 제공합니다.
3.  Microsoft는 Azure 사용량 기준 구독을 마이그레이션하고 마이그레이션이 완료되면 파트너에게 알립니다.
4.  파트너는 **전환 원본** CSP 재판매인 계정의 Azure 구독이 이제 파트너 센터의 고객 구독 섹션에서 일시 중단됨으로 표시되는지 확인합니다.
5.  파트너는 **전환 대상** CSP 재판매인 계정의 Azure 구독이 이제 파트너 센터의 고객 구독 섹션에서 **활성** 상태로 표시되는지 확인합니다.

    **참고** 고객의 구독을 사용하지 않도록 설정해도 고객 목록에서 고객의 모양이 변경되지는 않습니다. 현재 목록에서 고객을 제거하는 옵션은 없습니다. 파트너는 나중에 **전환 원본** 계정에서 이러한 고객에 구독을 다시 추가하지 않아야 합니다.

     

6.  모든 고객의 모든 구독에 대해 이러한 단계를 반복하여 이후 **전환 원본** 계정에 요금이 청구되지 않도록 합니다. 파트너는 취소일과 청구 기간의 마지막 날 사이에 사용되지 않은 일수에 대한 크레딧이 포함된 최종 송장을 하나 받게 됩니다. 해당 최종 청구 기간 이후 더는 송장이 생성되지 않습니다.

### 참고

-   **전환 원본** CSP 계정의 구독을 사용하지 않도록 설정해도, 이렇게 사용하지 않도록 설정하기 전에 서비스가 **전환 대상** CSP 계정에서 프로비전된 경우 최종 고객의 서비스에는 영향을 주지 않습니다.

-   고객은 구독을 사용할 수 없으며 구독이 일시 중단되거나 취소된 경우 청구 요금이 발생하지 않습니다.

-   현재 고객 목록에서 고객을 완전히 제거하는 방법은 없습니다.

-   **참고** 파트너는 파트너 센터에서 **전환 대상** 파트너 테넌트 계정 아래에 구독이 전환 및 설정되는 날과 같은 날에 파트너 센터의 **전환 원본** 파트너 테넌트 계정에서 해당 구독을 일시 중단하여 이중 청구가 발생하지 않도록 해야 합니다. Microsoft는 **전환 원본** 구독을 일시 중단됨으로 올바르게 설정하지 않아 발생하는 청구의 겹침으로 인한 크레딧에 대한 요청은 지원하지 않습니다.

     

### 내보내기를 사용하여 마이그레이션 간소화

**내보내기 기능**을 사용하여 새 통합 구조에서 사용해야 하는 구독을 캡처할 수 있습니다.

1.  대시보드에서 **고객**을 클릭하여 기존 구조에서 고객 목록을 표시합니다.

2.  원하는 고객 이름을 엽니다.

3.  **구독** 페이지에서 **구독 내보내기**를 클릭하여 구독 세부 정보를 Excel 파일로 내보냅니다.

4.  이 목록을 사용하여 새 통합 테넌트에서 구독을 다시 만듭니다.

### API 등록

API 등록에 대한 자세한 내용은 [이 페이지를 참조](https://msdn.microsoft.com/en-us/library/partnercenter/mt267552.aspx)하세요.

## 파트너 센터 활동 로그


활동 로그를 사용하여 파트너는 해당 테넌트에서 수행된, 고객에게 영향을 미치는 모든 변경 내용 레코드를 볼 수 있습니다. 이 기능을 통해 파트너는 고객 테넌트의 변경 내용을 추적할 수 있습니다.

**활동 로그 보기**

1.  파트너 센터 대시보드에서 **활동 로그** 링크를 클릭합니다.
2.  **활동 로그** 페이지에서 고객 계정에 수행된 변경 내용을 확인합니다. 날짜를 기준으로 활동 로그를 필터링하려면 **시작일** 및 **종료일**을 선택하여 로그에서 선택되는 레코드 범위를 좁힙니다. **활동 로그**에서 고객을 기준으로 필터링하려면 검색 상자를 사용합니다.

**활동 로그 내보내기**

-   **로그 내보내기**를 클릭하여 활동 로그 데이터를 CSV 파일로 내보냅니다.

    고객 목록 및 단일 고객의 구독 목록을 내보낼 수도 있습니다(고객의 구독 페이지에서).

 

 






<!--HONumber=Jan17_HO2-->

