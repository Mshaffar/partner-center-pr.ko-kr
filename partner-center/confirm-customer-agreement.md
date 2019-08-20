---
title: Microsoft 고객 계약의 고객 승인 확인 | 파트너 센터
ms.topic: article
ms.date: 04/16/2019
Description: 파트너는 해당 고객에 대 한 Microsoft 제품 및 서비스를 주문 하기 전에 고객이 Microsoft 고객 계약에 동의 해야 합니다. 파트너가 규정 준수 요구 사항을 충족 하는 데 도움이 되도록 Microsoft는 계약에 동의한 사용자에 대 한 특정 세부 정보를 제공 하 여 파트너에 게 동의를 확인 하도록 요청 합니다.
author: LauraBrenner
ms.author: labrenne
keywords: 고객, 고객, 동의, MCA, Microsoft 클라우드 계약, Microsoft 고객 계약, 고객 계약 템플릿
ms.localizationpriority: medium
ms.openlocfilehash: 6ca8eb3acdee0114f01dbd5952e9c092859147a2
ms.sourcegitcommit: ee722dc2b9d82557d273738b64cec6d8cb435084
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/31/2019
ms.locfileid: "68681759"
---
# <a name="confirm-customer-acceptance-of-the-microsoft-customer-agreement-preview"></a>Microsoft 고객 계약 (미리 보기)의 고객 승인 확인

현재는 CSP 파트너가 고객을 대신 하 여 주문할 수 있기 전에 해당 하는 **Microsoft 클라우드 계약**에 동의 하 고 서명 해야 합니다. 그러면 파트너가 Microsoft에 서명자에 대 한 정보를 제공 하 여 고객의 동의를 확인 해야 합니다. 고객이 Microsoft 클라우드 계약에 대 한 동의를 확인 하지 않는 경우:
- 이 고객에 대해 새로운 주문을 생성할 수 없습니다.
- 이 고객에 대해 기존의 사용자 수 기준 구독의 사용자 수를 변경할 수 없습니다.

파트너 센터 대시보드 또는 API를 사용 하 여 고객의 Microsoft 클라우드 계약에 대 한 동의를 확인 하는 방법에 대 한 자세한 내용은 [Microsoft 클라우드 계약에 대 한 고객 승인 확인](confirm-consent.md)을 참조 하세요.

2019 년 10 월 1 일부 터 Microsoft는 CSP 프로그램에 **Microsoft 고객 계약** 을 도입 하 여 Microsoft 클라우드 계약을 대체 합니다. 파트너의 새 계약 마이그레이션을 용이 하 게 하기 위해 2019 년 1 월 31 일까 지 CSP 프로그램에서 현재 Microsoft 클라우드 계약이 지원 됩니다. 자세한 타임 라인 정보는 다음 표를 참조 하세요.

| Date | 마일스 톤 | 설명 |
|------------|------------|--------------------------------|
|2019 년 8 월 01 일|샌드박스에서 사용할 수 있는 UX 미리 보기|파트너는 CSP 샌드박스 환경에서 파트너 센터 대시보드를 사용 하 여 Microsoft 고객 계약에 대 한 고객의 동의를 확인할 수 있습니다. CSP 샌드박스 환경에 액세스할 수 있는 파트너는 사용자 환경 변경을 미리 봅니다. 샌드박스 액세스 권한이 없는 파트너는이 항목의 변경 내용에 대해 알아볼 수 있습니다.|
|2019 년 9 월 02 일|API 미리 보기는 샌드박스에서 사용할 수 있습니다.|파트너는 CSP 샌드박스 환경에서 파트너 센터 API를 사용 하 여 Microsoft 고객 계약에 대 한 고객의 동의를 확인할 수 있습니다. API 파트너는이 기회를 사용 하 여 API 변경을 미리 보고 API 통합 작업을 시작 하 여 새 규약을 지원할 수 있습니다.|
|2019 년 10 월 01 일|프로덕션 환경에서 사용할 수 있는 Microsoft 고객 계약|Microsoft는 CSP 프로그램에 Microsoft 고객 계약을 도입 하 여 Microsoft 클라우드 규약을 대체 합니다. 파트너는 프로덕션 환경에서 파트너 센터 대시보드 및 API를 사용 하 여 Microsoft 고객 계약에 대 한 고객의 동의를 확인할 수 있습니다. Microsoft 클라우드 계약은 CSP 파트너 프로그램 내에서 계속 지원 됩니다. 그러나 파트너는 Microsoft 고객 계약으로 마이그레이션을 시작 하는 것이 좋습니다. 기존 구독에 대 한 새로운 구매 및 사용자 수 변경에는 Microsoft 고객 계약 또는 Microsoft 클라우드 계약의 파트너 확인이 필요 합니다. 특정 새 제품 (예: 새 Azure 요금제)은 Microsoft 고객 계약을 확인 해야 합니다.|
|2019 년 1 월 31 일|프로덕션에서 제거 되는 Microsoft 클라우드 계약|Microsoft 클라우드 계약은 CSP 파트너 프로그램 내에서 더 이상 허용 되지 않습니다. 기존 구독에 대 한 새로운 구매 및 사용자 수를 변경 하려면 파트너가 Microsoft 고객 계약에 대 한 확인을 제공 해야 합니다. 이 요구 사항은 새 고객과 이전에 Microsoft 클라우드 계약에 동의 했을 수 있는 기존 고객에 게 적용 됩니다.|


## <a name="confirm-customer-acceptance-for-new-customers"></a>새 고객에 대 한 고객 승인 확인

파트너 센터에서 새 고객 테 넌 트를 만들 때 다음 단계를 사용 하 여 고객이 Microsoft 고객 계약에 동의 하는지 확인 합니다. 이러한 단계를 수행 하려면 관리 에이전트 또는 판매 에이전트 여야 합니다.

1. **고객**을 선택한 다음 **신규 고객**을 선택합니다.

2. **계정 정보**아래에서 회사 및 기본 연락처에 대 한 정보를 입력 합니다.

3. **Microsoft 계약**에서 **microsoft 고객 계약**을 선택 합니다.

4. **계약 동의 날짜**에 해당 날짜를 입력합니다. 이 날짜는 미래의 날짜로 설정할 수 없습니다.

5. 표시 된 기본 사용자 연락처 정보가 올바른지 확인 합니다. 정확 하지 않은 경우 **업데이트** 를 선택 하 고 규약을 수락한 사용자의 **이름**, **성**, **전자 메일 주소**및 **전화 번호** (선택 사항)를 입력 합니다.

6. 고객 테넌트를 생성하기 위한 나머지 단계들을 계속하려면 **다음**을 선택합니다.

![새 고객](images/mcua1.png)

## <a name="confirm-customer-acceptance-for-existing-customers"></a>기존 고객에 대 한 고객 승인 확인

이 작업을 수행 하려면 관리 에이전트 또는 판매 에이전트 여야 합니다.

1. **고객**을 선택 합니다. 고객을 찾아 선택 합니다.

2. **계정 정보**를 선택 합니다.

3. **Microsoft 고객 계약**에서 **업데이트**를 선택 합니다.

4. 규약을 수락한 사용자의 **이름**, **성**, **전자 메일 주소**및 **전화 번호** (선택 사항)를 입력 합니다. **계약 동의 날짜**에 해당 날짜를 입력합니다. 이 날짜는 미래의 날짜로 설정할 수 없습니다.

5. **저장** 및 계속을 선택 합니다.

![기존 고객](images/mcua2.png)

## <a name="retrieve-confirmation-of-customer-acceptance"></a>고객 승인 확인 검색

다음 단계를 사용 하 여 기존 고객이 Microsoft 고객 계약에 동의한 확인을 검색할 수 있습니다. 관리자 에이전트 또는 판매 에이전트만 이러한 확인이 가능합니다.

1. **고객**을 선택한 다음, 확인하려는 고객을 찾아서 선택합니다.

2. **계정 정보**를 선택 합니다.

3. **Microsoft 클라우드 계약**에서이 고객이 확인을 제공 했는지 여부를 확인 합니다.

