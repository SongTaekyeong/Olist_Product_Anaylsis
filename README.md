# Olist E-commerce: Product Analytics Portfolio

> 브라질 이커머스 마켓플레이스 데이터(2016-2018, 약 10만 주문)를 활용한
> Product Data Analyst 포트폴리오 — Funnel · Cohort · Retention · LTV · A/B Test

## 🎯 한 줄 요약
재구매율 5% 이커머스에서 **"누가, 왜, 언제 이탈하는가"** 를 정량화하고,
이를 끌어올리기 위한 **2개의 A/B 테스트 가설**을 설계했습니다.

## 📌 핵심 결과 (TL;DR)
- **Funnel**: 주문 생성 → 배송완료까지 OOO% 전환, 가장 큰 leakage는 OO 단계 (lead time OO일)
- **Retention**: M1 리텐션 OO%, 6개월 시점 OO%로 수렴 — 카테고리별 최대 OOpp 격차
- **RFM × LTV**: 상위 20% 고객이 전체 매출의 OO% 기여, 평균 LTV는 일반 고객의 OO배
- **Churn Signal**: 재구매 간격 87일 초과 시 복귀율 OO% 미만, LightGBM AUC OO
- **A/B 제안**: ① 첫 구매 후 30-60일 재참여 캠페인 ② 카테고리 크로스셀 추천

## 🛠 Stack
BigQuery (SQL) · Python (pandas, scikit-learn, lightgbm, lifetimes, shap) · Plotly

## 📂 Repository Structure
[아래 0.3 참조]

## 🔗 Quick Links
- [📊 Full Analysis Report](./reports/final_report.md)
- [📓 Notebooks](./notebooks/)
- [🗄 SQL Queries](./sql/)
