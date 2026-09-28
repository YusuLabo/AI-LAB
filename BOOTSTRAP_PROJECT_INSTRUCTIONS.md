# ChatGPT 프로젝트 지침에 넣을 Bootstrap 문안

> 이 내용은 `CORE.md` 내부가 아닌, **해당 ChatGPT 프로젝트의 지침**에 붙여 넣는다. `REPOSITORY`는 실제 접근 권한이 있는 GitHub 저장소로 교체한다.

```text
이 프로젝트의 기억은 GitHub 저장소 REPOSITORY에 보관한다.
프로젝트 관련 작업을 시작할 때 GitHub 연결로 REPOSITORY의 /CORE.md를 먼저 읽는다.
CORE의 Work / Skill / System Registry에서 현재 요청과 관련 있는 파일만 선택적으로 읽는다.
Work가 INDEX.md로 연결된 경우에만 해당 INDEX를 먼저 읽고 필요한 세부 파일을 연다.
읽기만 할 때는 memory-policy.md를 불필요하게 열지 않는다. 기억 추가·갱신·삭제를 수행할 때는 system/memory-policy.md를 확인한다.
CORE에 기재된 실제 파일이 없거나 GitHub 권한 부족으로 열 수 없으면 추측해서 진행하지 말고 무엇을 읽지 못했는지 알려준다.
사용자가 GitHub 저장을 요청하면 최신 파일을 읽고 변경 사항과 정책을 확인한 다음, 실제로 허용된 쓰기 기능으로만 반영한다. GitHub의 응답을 통해 성공이 확인되기 전에는 저장 완료라고 말하지 않는다.
```

## 설치 전에 채워야 할 값

- GitHub 저장소: `owner/repository` (현재 미정)
- CORE 경로: `/CORE.md`
- 연결 GitHub 계정의 읽기·쓰기 권한: 확인 전
- 공개/비공개 저장소 범위와 개인정보·비밀정보 정책: 운영 전 확인

## 실제 동작 검증 항목

- 새 채팅에서 프로젝트 작업 요청 시 `/CORE.md`를 실제로 읽는가?
- CORE가 가리키는 작은 Work 하나 및 큰 Work의 `INDEX.md` 하나를 올바르게 여는가?
- 실패 시 임의 내용을 만들어내지 않고 오류를 보고하는가?
- 저장 요청 시 최신 SHA를 확인하고 수정 결과/commit SHA를 보고하는가?

> ChatGPT 프로젝트 지침을 추가했다고 외부 GitHub의 자동 읽기·쓰기가 검증된 것은 아니다. 연결 권한 및 실제 환경에서 시험해야 한다.
