---
title: "Power BI를 위한 파트너 센터 분석 앱 | 파트너 센터"
description: "Power BI용 파트너 센터 분석 앱을 사용하세요(CSP의 직접 파트너용)."
fwlink: https://go.microsoft.com/fwlink/?linkid=852581
author: labrenne
ms.openlocfilehash: 3eadf41093f6d3d2ad42fecae856384800676b1a
ms.sourcegitcommit: 9183f596e81595496ae49375c116ea0f772babac
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 08/23/2017
---
# <a name="view-your-business-data-with-the-partner-center-analytics-app-for-microsoft-power-bi"></a>Microsoft Power BI용 파트너 센터 분석 앱으로 비즈니스 데이터 보기

**적용 대상**

-   파트너 센터

## <a name="view-your-business-data"></a>비즈니스 데이터 보기

Power BI용 파트너 센터 분석 앱으로 다음을 포함한 비즈니스 데이터를 시각적으로 볼 수 있습니다.

- 고객 기반, 구독 및 라이선스의 증가

- Office 365, Microsoft Dynamics 및 Microsoft Azure 제품의 사용 현황

- 최근 60일간 각 Azure 구독에서 소비된 일일 유료 리소스 사용량

- 최신 요율표에 따른 예상 비용

- 데이터 집합을 내보내고 사용자 지정 보고서를 작성하는 기능(고객별 보고서 포함) 

### <a name="about-the-partner-center-analytics-app-preview-release"></a>파트너 센터 분석 앱 미리 보기 릴리스 정보

 - 이 앱은 클라우드 솔루션 공급자 프로그램의 직접 파트너 전용입니다. CSP의 다른 파트너(예: 간접 재판매인)은 로그인할 수 없습니다.

- 모든 예상 비용은 세전 청구 / 송장 데이터이며 법적 구속력이 없습니다. 예상 비용은 데이터에 대한 정보를 얻기 위한 용도로만 사용됩니다.

- 고객 정보는 구독으로 기반으로 합니다. 최근 계정을 생성했지만 아직 구독이 없는 고객은 이 수에 포함되지 않습니다. 

- 예상 비용은 CSP 가격을 기반으로 하는 최신 요율표를 기반으로 합니다. 

- 날짜는 달력 날짜입니다. 


### <a name="business-insights-report"></a>비즈니스 인사이트 보고서

-  **고객 테넌트**: 구독을 구입한 고객의 개별 Azure AD 테넌트의 수

-  **신규(지난 30일)**: 지난 30일 동안 하나 이상의 구독을 구입한 신규 고객

-  **변동(지난 30일)**: “활성”, “유예” 또는 “사용할 수 없는” 구독이 없는 고객

- **신규(지난 24시간)**: 지난 24시간 동안 하나 이상의 구독을 구입한 신규 고객

- **지난 12개월 동안의 예상 월 비용**: 지난 12개월 동안 월별로 집계된 예상 세전 송장 달러 금액의 월별 추세

- **지난 12개월 동안의 제품별 예상 비용**: 지난 12개월 동안 월별로 집계된 예상 세전 송장 달러 금액별로 정렬된 판매된 제품. 이는 가장 많은 수익을 창출하는 최상위 제품을 나타냅니다.

- **지난 12개월 동안의 고객**: 지난 12개월 동안 월별로 집계된 신규 고객 및 변동 고객의 월별 추세

- **지난 12개월 동안의 고객별 예상 비용**: 지난 12개월 동안 월별로 집계된 예상 세전 송장 달러 금액별로 정렬된 고객. 이는 가장 많은 수익을 창출하는 최상위 고객을 나타냅니다.

- **제품별 고객 수**: 관련 고객별로 정렬된 판매된 제품. 이는 대부분의 고객에게 판매된 최상위 제품을 나타냅니다. 


### <a name="subscription-insights-report"></a>구독 정보 보고서 

- **구독 상태**:

    - 활성: "활성" 또는 "유예" 상태에 속한 구독

    - 일시 중단: “사용하지 않음" 상태에 포함된 구독

    - 프로비전 해제됨: “프로비전 해제" 또는 "만료" 상태에 속한 구독

- **만료 상태**:

    - 만료됨: 이미 만료된 구독(구독 종료 날짜가 과거임)

    - 30일 후 만료: 30일 후에 만료되는 구독(구독 종료 날짜가 30일 이후임)

    - 30일 이내에 만료: 30일 이내에 만료되는 구독(구독 종료 날짜가 오늘과 다음 30일 사이에 있음)

-  **총 구독**: “활성", "유예" 또는 "사용하지 않음" 상태의 구독

- **신규(지난 30일)**: 지난 30일 이내에 고객이 구입한 신규 구독

- **신규(지난 24시간)**: 지난 24시간 이내에 고객이 구입한 신규 구독

- **30일 이내에 만료**: 30일 이내에 만료되는 구독

- **변동(지난 30일)**: 지난 30일 이내에 프로비전 해제되거나 일시 중단된(사용하지 않음) 구독

- **구독 유형별 분포**: 라이선스 기반 및 사용량 기반 구독 유형별 총 구독의 분포 %

- **제품별 활성 구독 수**: 활성 구독 수를 기준으로 정렬된 판매된 제품

- **지난 12개월 동안의 구독**: 지난 12개월 동안 월별로 집계된 신규 구독 및 변동 구독의 월별 추세

- **고객 구독 세부 정보**: 고객, 구독 및 제품에 대한 세부적인 보기 


### <a name="license-insights-report"></a>라이선스 인사이트 보고서:

- **총 라이선스**: 모든 라이선스 기반 구독에 대해 집계된 라이선스의 총 수

- **신규(지난 30일)**: 지난 30일 이내의 라이선스 추가

- **변동(지난 30일)**: 지난 30일 이내의 라이선스 감소

- **신규(지난 24시간)**: 지난 24시간 이내의 라이선스 추가

- **지난 90일 동안의 라이선스**: 지난 90일 동안 월별로 집계된 라이선스 추가 및 감소의 월별 추세

- **제품별 활성 라이선스 수**: 활성 라이선스 수별로 정렬된 판매된 제품

- **고객별 활성 라이선스 수**: 활성 라이선스 수별로 정렬된 고객

- **지난 90일 동안의 고객 라이선스 이벤트 세부 정보**: 이벤트 날짜, 이벤트 이름, 수량 및 수량 변경을 포함한 고객, 구독 및 구독 이벤트에 대한 세부적인 보기.


### <a name="licenses-usage-report"></a>라이선스 사용 보고서:

- **제품별 할당된 라이선스**: 라이선스 할당 수별로 정렬된 판매된 제품

- **제품별 사용 중인 라이선스**: 라이선스 사용 수별로 정렬된 판매된 제품

- **할당된 라이선스의 고객 분포**: 라이선스 할당별로 20% 범위의 버킷으로 나뉜 총 고객의 분포 %

- **사용 중인 라이선스의 고객 분포**: 라이선스 사용 %별로 20% 범위의 버킷으로 나뉜 총 고객의 분포 %

- **고객별 할당된 라이선스**: 고객 및 제품별로 판매된 라이선스 및 할당된 라이선스의 세부적인 보기

- **고객별 사용 중인 라이선스**: 고객 및 제품별로 판매된 라이선스 및 사용 중인 라이선스의 세부적인 보기


### <a name="azure-insights-report"></a>Azure 인사이트 보고서:

- **지난 12개월 동안의 사용량 기반 고객**: 지난 12개월 동안 월별로 집계된 신규 사용량 기반 고객 및 변동 사용량 기반 고객의 월별 추세

- **지난 12개월 동안의 사용량 기반 구독**: 지난 12개월 동안 월별로 집계된 신규 사용량 기반 구독 및 변동 사용량 기반 구독의 월별 추세

- **지난 60일 동안의 고객별 예상 사용 비용**: 지난 60일 동안 집계된 예상 세전 송장 달러 금액별로 정렬된 사용량 기반 고객. 이는 가장 많은 수익을 창출하는 최상위 사용량 기반 고객을 나타냅니다.

- **지난 60일 동안의 범주별 예상 사용 비용**: 지난 60일 동안 집계된 예상 세전 송장 달러 금액별로 정렬된 사용량 기반 구독의 측정 범주.

- **지난 60일 동안의 구독별 예상 사용 비용**: 지난 60일 동안 집계된 예상 세전 송장 달러 금액별 사용량 기반 구독.

- **지출 예산별 고객 예상 사용량 비용**: 임계치(100%)를 초과하는 현재 사용량 지출 예산의 비율별로 정렬된 고객.


### <a name="azure-resource-usage-report"></a>Azure 리소스 사용량 보고서:

- **선택한 기간에 대한 일별 Azure 리소스 사용량**: 지난 60일 이내의 선택한 기간에 대해 각 사용량 기반 구독에서 측정되는 각 리소스에 대한 일일 소비 단위.

- **선택한 기간에 대한 일별 Azure 리소스 예상 사용량 비용**: 지난 60일 이내의 선택한 기간에 대해 각 사용량 기반 구독에서 측정되는 각 리소스에 대한 최신 요율표 기반의 예상 비용. 

## <a name="see-also"></a>참고 항목

[Power BI를 위한 파트너 센터 분석 앱 개요](power-bi-app-for-direct-partners.md)


[Microsoft Power BI용 파트너 센터 분석 앱 설치 및 미리 보기](power-bi-app-for-direct-partners-install.md)