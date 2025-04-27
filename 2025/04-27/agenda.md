## MDN yari-content-ko 회의 [insert date]

[yari-content-ko 회의 일정 캘린더](https://calendar.google.com/calendar/u/0/embed?src=e43bb879372391269af4ee800723136b5df9a7c01bba63f6f3798504ba6b94e7@group.calendar.google.com&ctz=Asia/Seoul)에서 회의 참여 URL을 확인해주세요.

### 안건 소개 및 개요

- 다음 회의에 이야기할 내용을 `팀 갱신 사항`과 `질문 및 토론`에 작성해주세요.

### yari-content-ko

- [2025 오픈소스 컨트리뷰션 아카데미](https://www.oss.kr/) “MDN 문서 한글화 프로젝트” 프로젝트는 하반기 체험형 2차 프로젝트로 진행 (@hochan222)
  - “MDN 문서 한글화 프로젝트” 프로젝트는 하반기 체험형 2차 프로젝트로 진행
  - 멘토단 위촉 : 7월 중
  - 멘티 모집 : 8월 중
  - 체험형 2차 진행 : 9월 둘쨋 주 ~ 10월 31일(금)
- `translated-content repo` 변경사항
  - [feat(actions): ko-locale label discord noti webhooks #22297](https://github.com/mdn/translated-content/pull/22297)
  - [yari 로컬 실행 이슈 - Discord](https://discord.com/channels/1009925603572600863/1070064829466939503/1361185757494251551)
    - 5042 포트 번호 실행 안됨 => 3000 포트로 안내.
- `content repo` 변경사항
  - [Migrating interactive examples inline #782](https://github.com/orgs/mdn/discussions/782)
    - [Migrate HTML Interactive Examples #38257](https://github.com/mdn/content/pull/38257)
  - [Remove unreferenced images #39026](https://github.com/mdn/content/pull/39026)

### 질문 및 토론

질문 및 논의할 사항

- @givvemee님, yari-content-ko 멤버의 충원 계획 및 지원 절차 있을지 문의 주심.
- 폴더구조가 변경 되어 slug 가 변경되었습니다[(MR)](https://github.com/mdn/translated-content/pull/25682). [메타데이터가이드](https://github.com/mdn/translated-content/blob/main/docs/ko/guides/meta-data-guide.md)에서 현재 slug만 사용하는 것으로 기재되어있으나, slug가 변경되고 originalSlug가 추가된 것으로 확인 됩니다. MR 머지 여부 및 대응을 어떻게할 지 고민이라 안건으로 작성해둡니다. (@sunhpark42)
  - 폴터 구조 변경 => [Update on the Content Organization Project #776](https://github.com/orgs/mdn/discussions/776)
    - [[PROJECT] Content organisation phase 1 #637](https://github.com/mdn/mdn/issues/637)
    - [[PROJECT] Content organisation Phase 2 #662](https://github.com/mdn/mdn/issues/662)
  - original_slug 추가 => 확인 중
- `translated-content` locale 전체에 영향 있는 변경 사항 공지 방법
  - 문제: 보통 아래 두 군데에 올려주지만, 일관된 공지 채널 없음. `original_slug` 변경 사항 누락.
  - discord `#localization-general`
  - [github discussion](https://github.com/orgs/mdn/discussions)
