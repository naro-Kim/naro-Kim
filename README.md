# 김아현

 미디어 도메인에서 업로드, 결제, 재생같은 사용자 여정을 안정적인 웹 구조로 전환해 왔습니다. 
 문제 발견과 기술 제안부터 구현, QA, 장애 분석, 운영까지 end-to-end로 책임을 다합니다. 대용량 미디어 스트리밍 최적화 및 공통 인프라(디자인 시스템, 패키지) 구축에 특화되어 있습니다.

- **HLS 미디어 최적화**: 2시간 이상 대용량 비디오의 멀티트랙 재생 및 싱크 오차(Audio/Video Sync) 누적 문제를 디버깅하여 미디어 재생 신뢰성 확보
- **성능 및 아키텍처**: Next.js App Router 점진적 마이그레이션을 주도하여 번들 사이즈 64% 감소 및 사용자 체류 시간 20% 향상 기여
- **생산성 고도화**: 사내 디자인 시스템(Coretone) 및 DesignOps 구축으로 전사적인 생산성 향상에 기여. 디자인-개발 협업 리소스 53.6%에서 6.5%로 대폭 절감

[Email](mailto:gracias9022@gmail.com) · [Blog](https://velog.io/@naro-kim) · [Resume](https://github.com/user-attachments/files/30964813/default.pdf) · [Portfolio](https://github.com/user-attachments/files/31049385/Portfolio.pdf)


## What I build   

- **Reliable media experiences**  
  장시간 HLS 재생, 멀티트랙 제어, Audio/Video Sync, 미디어 파일 검증
- **Resilient user journeys**  
  업로드와 결제 Funnel의 상태 경계, 실패 복구, 관측 가능성
- **Scalable web architecture**  
  Next.js Server/Client 성능을 고려한 최적의 렌더링, 번들 최적화
- **Reusable product infrastructure**  
  디자인 토큰, 공통 컴포넌트, 사내 패키지 배포와 변경 관리

## Experience

### Gaudio Lab | `2024.03–2026.06 · Frontend Engineer` 

#### Gaudio Studio Pro

*AI 영상 콘텐츠 현지화 플랫폼*

`TypeScript` `Next.js` `HLS.js` `wavesurfer.js` `Zustand` `Playwright`

> - HLS readiness와 buffer event를 control gate에 연결해 실제 재생 준비가 끝난 뒤 조작이 시작되도록 구성했습니다.
> - 트랙별 MediaElement lifecycle은 독립적으로 유지하면서 play, pause, seek는 하나의 Controller에서 조율했습니다.
> - 권한별 UI 조합과 playback 로직을 분리해 Customer와 Agent 애플리케이션이 같은 Player package를 사용하도록 만들었습니다.

#### Coretone

*Design System & Internal Package Platform*

`React` `TypeScript` `Tailwind CSS` `shadcn/ui` `Storybook` `Figma Plugin` `Changesets` `AWS CodeArtifact`

> - Primitive와 Semantic token을 나누고 라이트/다크 alias 구조를 설계했습니다.
> - Figma의 collection, mode, alias를 코드 자산으로 바꾸는 플러그인을 구현해 디자인과 코드의 기준점을 하나로 맞췄습니다.
> - Storybook 리뷰, Changesets 버전 관리, CodeArtifact 배포, 사용 제품 업데이트로 이어지는 흐름을 정리했습니다.

#### Gaudio Studio

*AI 오디오 편집 SaaS*

`TypeScript` `Next.js App Router` `Zustand` `TanStack Query` `next-intl` `Paddle` `Sentry`

> - 정적 UI는 Server Component로 옮기고 상호작용이 필요한 영역만 Client Component로 남겼습니다.
> - Parallel Route와 persistent store로 업로드 단계를 나누고, 단계 진입과 이탈 시 검증 및 초기화 규칙을 명확히 했습니다.
> - 결제 완료 확인, credit query 갱신, orderId 로깅, Paddle callback 정리로 결제 상태의 일관성과 추적 가능성을 높였습니다.
> - 파일 헤더와 메타데이터를 브라우저에서 먼저 확인해 지원하지 않는 미디어가 비용이 큰 AI 워크플로에 들어가기 전에 차단했습니다.

## Tech

**Frontend**  
> TypeScript, React, Next.js, Zustand, TanStack Query, Tailwind CSS

**Platform & Quality**  
> Storybook, Playwright, Sentry, Changesets, AWS CodeArtifact, Figma Plugin

## How I work

- 화면에 드러난 오류를 UI 문제로만 보지 않고 lifecycle, 데이터, 미디어 소스의 경계까지 추적합니다.
- 재현 가능한 로그와 수치로 가설을 좁히고 다른 직군과 같은 근거를 보며 해결합니다.
- 어디까지 공통으로 관리해야 변경 비용이 줄어드는지 살핍니다. 사용하는 팀이 안전하게 업데이트할 수 있도록 배포 흐름도 함께 설계합니다.
   

AWARD
-
- 2023 항해플러스 코딩 육상 대회 최우수상
- 2022 한국관광공사 x 카카오 관광데이터 활용 공모전 장려상
- 2022 홍익대학교 경영대학 창업 아이디어 경진대회 1위
- 2021 IF Design Talented Award Winner
- 2020 티릴리 아이디어 해커톤 우수상
- 2016 한양대 Art&3D프린팅 어워드 장려상
- 2016 창의융합디자인교육캠프 장려상 

ETC
-
- 2025.07~2026.01 대한조선학회 조선용어사전, Web Front-End, 기획-운영 전반 참여
- 2023 알파코 X GDSC 연합 해커톤 '나무톤' Design, Web Front-End
- 2023 기업형 IT 연합동아리 YAPP 22nd - Web Front-End
- 2022 홍익대학교 교내 IT 연합동아리 멋쟁이사자처럼 10기 - Web Front-End
- 2021 Hongik Univ. Industrial Design Degree Graudation Exhibition Lead Committee - Web Team Leader 
