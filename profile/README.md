# 프라이스잇 (PriceIt) — 개발 조직

> 교육 → 유통 → 금융 → AI 비서

식품 위탁판매 셀러를 위한 B2B 플랫폼을 만듭니다.

---

## 핵심 서비스 (매출/수익 직결)

| 레포 | 설명 | 기술 스택 | 상태 |
|------|------|-----------|------|
| **b2b-order-system** | 비투비허브 — 셀러↔공급사 발주/정산 플랫폼 (팜허브 후속) | Next.js · Prisma · Supabase | 가오픈 테스트 중 |
| **priceit-starter-codex** | Sky Scanner — 공급사 가격비교 서비스 | Python · FastAPI · Next.js · Railway | v3 운영 중 |
| **priceflow** | PriceFlow — 공급가 변동 → 판매가 반영 자동화 | Next.js 15 · Supabase · Vercel | Phase 0 운영 중 |
| **cs-ai-assistant** | CS AI 비서 — 식품 CS 전문 자동 응답 (채널톡 ALF 대체) | Python · Claude API · FastAPI | 기획 완료, 개발 대기 |

## 데이터 수집/분석

| 레포 | 설명 | 기술 스택 |
|------|------|-----------|
| **openclo-collector** | 어드민플러스/GSheet/카카오 가격 데이터 수집기 | Python |
| **priceit-price-scanner** | 판매채널(쿠팡/네이버 등) 가격 모니터링 | Python |
| **price-change** | 공급가 변동 예측 모형 | Python · ML |
| **biz-datahub** | 전사 ETL 파이프라인 | Python |

## 마케팅/교육

| 레포 | 설명 | 기술 스택 |
|------|------|-----------|
| **classhub-video-analyst** | Zoom 강의 녹화 분석 + 결제 퍼널 최적화 | Python · Zoom API |
| **growth-engine** | 코치 후보 리드 수집 (SNS 크롤링) | Python · Apify |
| **classhub-freebook** | 클래스허브 무료 교재 | — |

## 인프라/품질

| 레포 | 설명 | 기술 스택 |
|------|------|-----------|
| **qa-hub** | QA 컨트롤 타워 — 전사 E2E 테스트/매뉴얼 중앙 관리 | Next.js |
| **priceit-design-system** | 디자인 시스템 (Figma ↔ 코드) | TypeScript |
| **farmhub-cs-orchestrator** | 팜허브 CS 오케스트레이터 | Python |

## 보조/레거시

| 레포 | 설명 | 비고 |
|------|------|------|
| **priceit-starter** | 스캐너 원본 | → priceit-starter-codex로 분리 |
| **kakaotalk-autobot** | 카카오톡 CS 봇 | → cs-ai-assistant로 통합 예정 |
| **priceflow-qa** | PriceFlow QA 가이드 문서 | 문서 전용 |
| **growth-diary-bot** | — | — |

---

## 별도 관리

| 레포 | 위치 | 설명 |
|------|------|------|
| **po-agent** | `shlee-creator/po-agent` | PO 에이전트 — 전사 기획/전략 컨트롤 타워 (대표 전용) |

---

## 주요 배포 URL

| 서비스 | URL |
|--------|-----|
| 비투비허브 | b2b-order-system.vercel.app |
| PriceFlow | pf-farmhub.vercel.app |
| 스캐너 Web | web-shlee-1687s-projects.vercel.app |
| 스캐너 API | priceit-starter-codex-production.up.railway.app |
| CS AI 비서 | cs-ai-assistant-production.up.railway.app |
| QA Hub | qa-hub-shlee-1687s-projects.vercel.app |
