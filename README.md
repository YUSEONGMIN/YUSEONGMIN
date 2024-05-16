### 😄 안녕하세요!

### 1. 이런 프로그램을 다룰 수 있습니다.

```
Back-end: Linux, Django, Flask, SpringBoot
 DevOps : AWS(CodePipeline), Docker
  Infra : AWS(EC2, S3, Lambda, RDS, EMR), ELK Stack

   Data : AirFlow, Hadoop, Kafka, Pandas, Scikit-Learn, Spark
   DB   : MySQL

Language: Java, Python, R, SAS, SPSS
 협업툴 : Git, Notion, Slack
```

### 2. 이런 경험을 해봤습니다.
1. 

### 3. 이런 일을 하고 싶습니다.

###




## 기술 질문 정리


- **앱 개발자 기술 질문**
- 
    - [ ]  Q1. PNG와 JPG의 차이점은?
    - [ ]  Q2. Dynamic Programming이란?
    - [ ]  Q3. Virtual Memory란?
    - [ ]  Q4. Garbage Collection이란?
    - [ ]  Q5. Cache란?
    - [ ]  Q6. Database Index 추가의 장단점은?
    - [ ]  Q7. 비대칭 암호화란?
    - [ ]  Q8. HDD, SSD, DRAM 각각의 성능은?
    - [ ]  Q9. GIT의 장점은?
- **Android 개발자 기술 질문**
    - [ ]  Q1. DIP란?
    - [ ]  Q2. ConstraintLayout의 장점은?
    - [ ]  Q3. Activity 생명주기는?
    - [ ]  Q4. WeakReference란?
    - [ ]  Q5. Parcelable이란?
    - [ ]  Q6. 고해상도 이미지의 로딩 방법은?
    - [ ]  Q7. Looper란?
    - [ ]  Q8. MultiDex란?
    - [ ]  Q9. Proguard의 원리는?
- **iOS 개발자 기술 질문**
    - [ ]  Q1. Auto Layout의 장단점은?
    - [ ]  Q2. MVC 패턴이란?
    - [ ]  Q3. KVC와 KVO란?
    - [ ]  Q4. Swift의 특징은?
    - [ ]  Q5. Higher Order Function이란?
    - [ ]  Q6. Method Swizzling이란?
    - [ ]  Q7. HTTP/2의 특징은?
    - [ ]  Q8. Memory Leak의 대처방법은?
    - [ ]  Q9. 이미지 리스트의 성능 향상법은?
- **Vrew 데스크탑 앱 개발자 기술 질문**
    - [ ]  Q1. UTF-8 이란?
    - [ ]  Q2. React 란?
    - [ ]  Q3. Web Browser 의 프로세싱 중 Reflow 란?
    - [ ]  Q4. 함수형 프로그래밍 패러다임이란?
    - [ ]  Q5. Callback hell 이란?
    - [ ]  Q6. async I/O 란?
    - [ ]  Q7. 프로세스 간 통신(IPC) 이란?
    - [ ]  Q8. C++ 에서 다형성이란?
    - [ ]  Q9. 그래픽카드를 이용한 하드웨어 가속이란?
- **딥러닝 모델 개발자 기술 질문**
    - [ ]  Gradient Descent란?
    - [ ]  Loss Surface란?
    - [ ]  Attention이란?
    - [ ]  Transformer란?
    - [ ]  Collaborative filtering이란?
    - [ ]  Few-Shot Learning이란?
    - [ ]  Federated Learning이란?
    - [ ]  SVD란?
    - [ ]  중심극한정리란?
- **백엔드 개발자 기술 질문**
    - [ ]  Q1. Base64 인코딩이란?
    - [ ]  Q2. 사용자 패스워드를 전송/보관하는 방법은?
    - [ ]  Q3. system call이란?
    - [ ]  Q4. .so와 .a 파일의 차이는?
    - [ ]  Q5. MySQL과 MongoDB의 차이점은?
    - [ ]  Q6. HTTP/2의 특징은?
    - [ ]  Q7. Firewall의 동작 원리는?
    - [ ]  Q8. Docker와 Virtual Machine의 차이점은?
    - [ ]  Q9. AMD와 Intel CPU의 차이점은?
    - [ ]  Q10. CRDT란?
    - [ ]  Q11. CORS란?
    - [ ]  Q12. CI/CD란?
    - [ ]  Q13. 동시 사용자 1만명을 지원하는 채팅 서버를 어떻게 만들겠는가?
    - [ ]  Q14. 최근 사회적 이슈가 된 보안 관련 사고 몇가지의 원인과 대책은?
    - [ ]  Q15. 대용량 로그 시스템을 구축한다면 어떻게 하겠는가?
 

    
### 협업을 위한 규칙

디자인패턴

<details><summary>
Git branch & naming
</summary>

Git 브랜치 전략: 브랜치 생성에 규칙을 만들어 협업을 유연하게 하는 방법

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

<details><summary>
Commit Convention
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

<details><summary>
코드 스타일 가이드 PEP8
</summary>

[PEP8 전체 가이드](https://peps.python.org/pep-0008/)

- 파이썬 코드를 어떻게 구상할 지 알려주는 스타일 가이드
- 원활한 협업을 위해선 공통된 스타일 공유가 필요하다.
- 일관성 있는 스타일은 가독성과 유지 보수성을 높일 수 있다.
</details>

<details><summary>
보일러플레이트
 </summary>

보일러플레이트 코드: 최소한의 변경으로 여러 곳에서 재사용되는 코드
- 변경의 횟수를 최소화하고 반복적인 일을 줄여 개발 소요 시간을 줄일 수 있다.
</details>






