### 안녕하세요! 👋

<!--
**YUSEONGMIN/YUSEONGMIN** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

# 협업을 위한 규칙
- [Git branch & naming](#git-branch--naming)
- [Commit Convention](#commit-convention)
- [코드 스타일 가이드 PEP8](#코드-스타일-가이드-pep8)
- [보일러플레이트](#보일러플레이트)

## Git branch & naming
<details><summary>
깃 브랜치 전략이란?
</summary>

브랜치 전략: 브랜치 생성에 규칙을 만들어 협업을 유연하게 하는 방법

### 브랜치의 종류
Main branch
  - `master`: 제품으로 출시될 수 있는 브랜치
  - `develop`: 다음 출시 버전을 개발하는 브랜치

Supporting branches
  - `feature`: 기능을 개발하는 브랜치
  - `release`: 이번 출시 버전을 준비하는 브랜치
  - `hotfix`: 출시 버전에서 발생한 버그를 수정하는 브랜치

### 브랜치 네이밍 규칙
1. `master`와 `develop` 브랜치는 이름 그대로 사용 (일반적)
2. `feature`는 어떤 이름도 가능 (feature/기능요약 추천)  
   ex) feature/login, feature/{issue-number}-{feature-name}
3. `release`는 release-... 형식 추천 ex) release-1.7
4. `hotfix`는 hotfix-... 형식 추천 ex) hotfix-1.4.1
</details>

## Commit Convention
<details><summary>
Commit Convention 란?
</summary>

정해진 규칙에 따라 커밋 메시지를 기재함으로써  
프로젝트를 효율적이고 안정적으로 관리할 수 있음

### 커밋 메시지 구조
```
type: subject

body

footer
```
type: 변경 사항의 유형
 - `feat`: 새로운 기능 추가
 - `fix`: 버그 수정
 - `docs`: 문서 수정
 - `style`: 스타일 수정
 - `refactor`: 코드 리팩토링
 - `test`: 테스트 코드 수정
 - `chore`: 기타 작업

subject: 변경 작업의 제목이나 간단한 요약
- 50자 이내로 간결하게
- 영문인 경우 대문자 시작 및 동사원형
- 마침표 및 특수기호 생략

body: 작업 내용이 복잡하거나 상세한 내용을 남겨야 하는 경우 작성
- 여러 줄로 작성 가능하며, 한 줄당 72자 이내
- 최대한 상세히 작성
- 어떻게(How) 보다 무엇(What)을 또는 왜(Why) 변경했는지 설명

footer: 코드 작업과 관련된 이슈 번호 또는 참조 링크 등 추가
- `유형: #이슈 번호(작업 번호)` 형식으로 작성
- `Fixes`: 이슈 수정 중
- `Resolves`: 이슈를 해결 했을 때
- `Ref`: 참고할 이슈가 있을 때
- `Related to`: 해당 커밋에 관련된 이슈 번호
- ex) `Fixes: #45 Related to: #34, #23`

### 커밋 메시지 자동화 툴: [Commitlint](https://commitlint.js.org/#/), [Husky](https://typicode.github.io/husky/#/)
</details>

## 코드 스타일 가이드 PEP8
<details><summary>
PEP8 이란?
</summary>

[PEP8 전체 가이드](https://peps.python.org/pep-0008/)

- 파이썬 코드를 어떻게 구상할 지 알려주는 스타일 가이드
- 원활한 협업을 위해선 공통된 스타일 공유가 필요하다.
- 일관성 있는 스타일은 가독성과 유지 보수성을 높일 수 있다.
</details>

## 보일러플레이트
보일러플레이트 코드: 최소한의 변경으로 여러 곳에서 재사용되는 코드
- 변경의 횟수를 최소화하고 반복적인 일을 줄여 개발 소요 시간을 줄일 수 있다.
