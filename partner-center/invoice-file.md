---
title: 청구 청구서의 필드 이해
ms.topic: article
ms.date: 05/18/2020
description: 파트너 센터 요금 청구를 위한 청구서 파일의 필드를 이해 합니다.
ms.assetid: ''
author: LauraBrenner
ms.author: labrenne
keywords: 청구, 송장
ms.localizationpriority: medium
ms.custom: SEOMAY.20
ms.openlocfilehash: f546174ee80c90695ec11f09e9cd1d5fdd4c4e46
ms.sourcegitcommit: 2a980b50cf177753c15ebfd7770e14cf6d486cf7
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/22/2020
ms.locfileid: "83794859"
---
# <a name="partner-center-billing-invoices---learn-how-to-read-the-billing-and-one-time-charge-fields"></a>파트너 센터 청구 송장-청구 및 일회성 요금 필드를 읽는 방법을 알아봅니다.

**적절한 역할**

- 글로벌 관리자
- 사용자 관리자
- 청구 관리자
- 기술 지원팀 상담원

다음 표를 사용 하 여 파트너 센터 청구서 파일의 필드를 이해할 수 있습니다.

## <a name="invoice-file-fields"></a>송장 파일 필드

청구서 파일에 다음 필드가 표시 됩니다.

| 필드 | 정의 |
| ----- | ---------- |
| US FEIN | 사용자의 연방 고용주 Id 번호 (FEIN) 미국 연방 세금 id 번호입니다. |
| 고객 번호 | 고객 번호입니다. |
| 청구지 | 청구서를 보낼 주소입니다. 파트너 센터 청구 프로필에서 회사 이름 및/또는 주소를 변경할 수 있습니다. |
| 라이선스 기반 요금 | 구매한 사용 기반 라이선스에 대 한 월별 월별 또는 연간 요금으로, 서비스를 미리 청구 합니다. 이 숫자는 라이선스 기반 조정 파일의 **부분합** 열 (열 **T**)에 있는 모든 요금 합계입니다. |
| 사용량 기반 요금 | Azure 사용량입니다. 여기에는 청구 기간 동안 사용 및 사용 되는 새 서비스 또는 응용 프로그램이 포함 됩니다. 이 수는 사용량 기반 조정 파일의 **PretaxCharges** 열 (열 **Z**)에 있는 모든 요금 합계입니다. |
| 할인 | 고객이 구독의 일반 가격에서 받는 할인입니다. 이 숫자는 단가 또는 라이선스 당 가격이 아니라 *평평한 양만큼*표시 됩니다. |
| 크레딧 | 구독에 대 한 변경 내용에 대 한 크레딧 또는 조정 (예: 사용자의 늘어나거나 감소). |
| 소계 | 세금 및 세금-배타 요금 및 크레딧 전 합계 |
| 세금 | 청구서의 2 페이지에서 시작 하는 **세부 정보** 섹션에서 요약 된 현재 요금에 대 한 총 세금입니다. 이 숫자는 사용 빈도 기반 조정 파일의 **taxationitem.taxamount** 열 (열 **AA**)에 있는 모든 요금 합계와 라이선스 기반 조정 파일의 **세금** 열 (열 **U**)입니다. |
| 기타 크레딧 | 세금-제외 크레딧입니다. |
| 현재 총 요금 | 청구 기간에 대 한 청구 통화로 인 한 금액입니다. 이러한 요금은 지불 기한 기한입니다. |
| 지불 관련 지침 | 지역을 기준으로 청구서를 지불 하는 방법에 대 한 설명입니다. *지불 시 청구서 번호를 반드시 포함 해야 합니다.* |
| 청구서 번호 | 청구서의 번호입니다. |
| 청구 기간 | 매월 청구서 날짜로 계산 되는 기간입니다. 사용 빈도 기반 서비스가 사용 되는 기간으로, 라이선스 기반 서비스는 크레딧 조정 또는 라이선스 수 변화에 맞게 조정 됩니다. |
| 청구서 날짜 | 송장이 매월 생성 되는 청구 날짜 또는 기념일입니다. |
| 지급 조건 | 지불 조건입니다. 일회성 구매의 경우 항상 60 일로 청구 됩니다. |
| 결제 기한 | 지불을 받아야 하는 날짜입니다. |
| 고객 PO | 구매 번호 주문입니다. |
| 고객 서비스 | 고객 서비스에 액세스할 수 있는 웹 사이트 주소입니다. |
| 서비스 받는 사람 | 서비스를 사용 하는 주소입니다. (회사 심사와 연결 된 법적 회사 주소입니다.) |

## <a name="one-time-charges-fields"></a>일회성 요금 필드

다음 필드는 파트너 센터에서 **일회성 요금** 에만 적용 됩니다.

| 필드 | 정의 |
| ----- | ---------- |
| Date | 구매한 날짜입니다. |
| Description | 제품 이름입니다. |
| 수량 | 구매한 제품 (예: 예약)의 수입니다. |
| 단가 | 제품별 가격 (예: 예약). |
| 할인 | 모든 해당 할인 |
| 세 전 금액 | 세금 전 구매의 하위 합계입니다. |
| 판매 세금 | 세액 |
| 합계 | 총 지불 금액입니다. |
