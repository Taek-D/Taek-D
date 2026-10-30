# 이성택 · 풀스택 개발자

Next.js·TypeScript와 Supabase(PostgreSQL)로 기획부터 배포·운영까지 만드는 개발자입니다.
데이터 분석에서 출발해, 지금은 실제 사용자가 쓰는 웹 서비스를 만들고 운영합니다.

## 기술

| 구분 | 사용 기술 |
|---|---|
| 프런트엔드 | TypeScript, React, Next.js(App Router), Tailwind CSS, Zustand |
| 백엔드·DB | Supabase(PostgreSQL, Auth, RLS), FastAPI, Java·Spring(전자정부 표준프레임워크) |
| 테스트·배포 | Vitest, Playwright, GitHub Actions, Docker, Vercel |

## 계약 프로젝트

**B2B 예치금 폐쇄몰** · 2026.04 ~ 운영 중 · 소스 비공개(계약)

- 승인된 구매자의 예치금 결제, 재고 적립, 배송대행 엑셀 업로드, 관리자 검토·승인까지 구현했습니다.
- 사용자 그룹별 권한을 라우트 가드, 메뉴 필터, 서버 액션 세 곳에서 막습니다.
- Next.js 16 + Supabase, 단위 테스트(Vitest)와 E2E 테스트(Playwright), 커밋 346개.

## 프로젝트

| 프로젝트 | 내용 | 스택 | 링크 |
|---|---|---|---|
| [focus-valley](https://github.com/Taek-D/focus-valley) | 집중하면 식물이 자라는 뽀모도로 타이머. 충돌 해소를 포함한 클라우드 동기화, 오프라인 PWA, 3개 언어 | React 19, Supabase, Web Worker, Playwright | [라이브](https://focus-valley.vercel.app) |
| [plugin-advisor](https://github.com/Taek-D/plugin-advisor) | PRD·README를 넣으면 Claude Code 플러그인 조합을 추천하고 점수화. 제안 접수와 관리자 검토 흐름 | Next.js 14, Supabase, Vitest | [라이브](https://plugin-advisor.vercel.app) |
| [Funnel & Retention Explorer](https://github.com/Taek-D/funnel-retention-explorer) | CSV를 올리면 퍼널·코호트 리텐션·세그먼트를 분석하는 대시보드. 회원 인증과 클라우드 저장 | React 19, Supabase, Recharts | [라이브](https://fre-analytics.vercel.app) |
| [CMS_Demo](https://github.com/Taek-D/CMS_Demo) | 어린이집 수납 CRM 데모. 학부모용 모바일 웹과 관리자 CRM을 나누고, 자동이체 배치 출금·미납 관리·거래명세표 엑셀을 구현. 계좌번호는 AES-256으로 암호화 | Next.js 16, Supabase(RLS), Vitest, Playwright | 저장소 |
| [egov-asset-mgmt](https://github.com/Taek-D/egov-asset-mgmt) | 공공기관형 비품·자산 관리. 신청 → 승인 → 지급 결재 흐름과 행 잠금 기반 동시 처리 | Java 17, Spring 6, MyBatis, MySQL, Docker | 저장소 |
| [datalens](https://github.com/Taek-D/datalens) | CSV·JSON을 올리면 분포·상관관계·이상값을 자동 탐색. 프런트와 백엔드 분리, PR마다 CI | React 19, FastAPI, pandas, GitHub Actions | [라이브](https://datalens-tau.vercel.app) |

## 오픈소스 기여

- [eGovFramework/egovframe-common-components #1388](https://github.com/eGovFramework/egovframe-common-components/pull/1388): MySQL 초기화 스크립트의 문자셋을 utf8mb4로 고정해 한글 이중 인코딩과 로그인 collation 충돌을 수정 (2026-10 병합)

## 연락

atef21422@gmail.com
