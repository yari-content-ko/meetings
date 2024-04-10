## MDN yari-content-ko 회의 2024-03-24

[yari-content-ko 회의 일정 캘린더](https://calendar.google.com/calendar/u/0/embed?src=e43bb879372391269af4ee800723136b5df9a7c01bba63f6f3798504ba6b94e7@group.calendar.google.com&ctz=Asia/Seoul)에서 회의 참여 URL을 확인해주세요.

### 안건 소개 및 개요

- 다음 회의에 이야기할 내용을 `팀 업데이트 사항`과 `질문 및 토론`에 작성해주세요.

### 팀 업데이트

팀 업데이트 사항

- [Github `yari-content-ko` Origanization 생성](https://github.com/yari-content-ko) (@hochan222)
  - `yari-content-ko` origanization 초대 메일 확인
  - `yari-content-ko` google calendar 초대 메일 확인
- [오픈소스 컨트리뷰션 아카데미 멘토 신청](https://www.oss.kr/notice/show/d277cc91-3e51-494c-b8cd-b04626196d7e) (@swimjiy)
  - 결과 발표: 4월 5일
- 현재 상철님 할당 PR에 대해 팀원 할당되어 리뷰 같이 진행 중 입니다. 진행중에 궁금한 사항이나 고민되는 사항 있을까요? (@1ilsang)
- [JavaScript - Reference - Global Object - Error: 번역률 100%](https://github.com/mdn/translated-content/pull/18809) (@wisedog)
- [2024 개인 기여 활동](https://docs.google.com/document/d/1vxfpQ5OLTT1Ycnw_Ub68Igb5fcGUhuj66CbbGNbVfBQ/edit) (@hochan222)
  - 하고 싶은 것 1~2가지 다시 계획 및 다음 회의록에 작성
- 장기 지연 PR 목록 ([지난 회의록](https://docs.google.com/document/d/1sGWtB_C3phqR_SpbfNMMaMItK16_MHBpQZubLz57fbA/edit?usp=sharing)) (@hochan222)
  - sunhpark42
    - https://github.com/mdn/translated-content/pull/18124
  - wisedog
    - https://github.com/mdn/translated-content/pull/15297
  - jho2301
    - https://github.com/mdn/translated-content/pull/15294

### 질문 및 토론

질문 및 논의할 사항

- [Exploring Guidelines for Line Length and Newline in Markdown Documentation.](https://github.com/orgs/mdn/discussions/655) (@1ilsang)
- [`http://localhost:3000/<locale>/_flaws locale page error`](https://github.com/mdn/yari/issues/10653) (@hochan222)
  - 해결 방법: `git clone` => `nvm use` => `yarn` => create `.env` file (for CONTENT_TRANSLATED_ROOT, CONTENT_ROOT) => `yarn start` => `http://localhost:3000/ko/_flaws` => `yarn build --locale ko` => `yarn start`
- ["Iterate"를 순회로 번역하는 이유](https://github.com/mdn/translated-content/issues/14044) (@hochan222)
