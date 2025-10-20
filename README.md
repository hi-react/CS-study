# CS-study
_"취업을 위한 데일리 스터디 기록 저장소"_

> 📅 2025.10.17 ~ ing... 

## 🔗 빠른 시작
- 📌 [운영 요약](./Docs/SUMMARY.md) - 스터디 운영 방식 한눈에 보기
- 👉 [시작 가이드](./Docs/GETTING_STARTED.md) - 처음 시작하시는 분들은 여기부터!
- 🍴 [Fork 완벽 가이드](./Docs/FORK_GUIDE.md) - Fork 방식 상세 설명
- ✅ [주간 체크리스트](./Docs/CHECKLIST.md) - 매주 확인할 사항
- 📋 [Issue 템플릿](https://github.com/study-four-career/CS-study/issues/new/choose) - 주간 학습 계획 등록

## 💪 우리의 목표

> **"내 프로젝트를 완벽하게 설명할 수 있는 개발자가 되자!"**

### 🎯 스터디 목표
- 각자의 **포트폴리오 프로젝트**를 기반으로 기술면접을 준비합니다.
- 실제 프로젝트에서 사용한 기술과 개념을 깊이 있게 학습합니다.
- 면접에서 나올 수 있는 질문에 대한 답변을 준비합니다.
- 서로의 학습 내용을 리뷰하며 지식을 확장합니다.

### 스터디 종료 시 우리는...
- ✅ 포트폴리오 프로젝트의 모든 기술 스택을 설명할 수 있다
- ✅ "왜 이 기술을 선택했나요?" 질문에 자신 있게 답변할 수 있다
- ✅ 프로젝트에서 발생한 문제와 해결 과정을 구체적으로 설명할 수 있다
- ✅ 면접관의 꼬리 질문에도 당황하지 않고 대응할 수 있다


## 📚 학습 카테고리
- **자료구조** (Data Structure)
- **알고리즘** (Algorithm)
- **운영체제** (Operating System)
- **네트워크** (Network)
- **데이터베이스** (Database)
- **디자인 패턴** (Design Pattern)
- **웹 개발** (Web)
- **Frontend** (Frontend)
- **기타** (Others)


## 📂 폴더 구조
> [!NOTE]
> 각자의 닉네임 폴더 안에 주차별 폴더를 만들어 관리합니다.
```
/
├── (이름)/
│   ├── week01/
│   │   ├── day01_React의Virtual_DOM.md
│   │   ├── day02_상태관리_라이브러리.md
│   │   ├── day03_웹팩과_번들링.md
│   │   ├── day04_RESTful_API_설계.md
│   │   └── day05_데이터베이스_인덱싱.md
│   └── week02/
│       └── ...
├── (이름)/
│   └── week01/
└── (이름)/
    └── week01/
```


## 💡 진행 방식

### 🔄 주간 사이클 (월~금)

#### **1단계: 주제 선정 (월요일 또는 주말)**
- 각자의 **포트폴리오 프로젝트**에서 5가지 학습 주제 선정
- GitHub **Issue**로 한 주의 학습 계획 등록
- Issue 제목: `[Week N] 이름 - 주간 학습 계획`

**Issue 템플릿 예시:**
```markdown
## 📝 이번 주 학습 주제 (Week 1)

### 포트폴리오 프로젝트
- 프로젝트명: 쇼핑몰 플랫폼
- 사용 기술: React, Node.js, PostgreSQL

### 학습 주제 5가지
1. **Day 1 (월)**: React의 Virtual DOM 동작 원리
2. **Day 2 (화)**: 상태관리 라이브러리 비교 (Redux vs Zustand)
3. **Day 3 (수)**: Webpack과 번들링 최적화
4. **Day 4 (목)**: RESTful API 설계 원칙
5. **Day 5 (금)**: 데이터베이스 인덱싱 전략

### 면접 예상 질문
- Virtual DOM이 일반 DOM보다 빠른 이유는?
- 프로젝트에서 왜 Zustand를 선택했나요?
- 번들 크기를 줄이기 위해 어떤 방법을 사용했나요?
```

#### **2단계: 데일리 학습 & 커밋 (월~금)**
- **매일 1개 주제**씩 공부하고 마크다운으로 정리
- 파일명 규칙: `day0N_주제명.md` (예: `day01_React의Virtual_DOM.md`)
- 학습 후 **즉시 커밋** → `본인브랜치`에 푸시
- 커밋은 매일 쌓아두고, PR은 금요일에 한 번만!

#### **3단계: 주간 PR & 리뷰 (금요일)**
- 금요일에 **한 주의 학습 내용을 모아서 PR 생성**
- 팀원들이 주말 동안 리뷰
- 최소 **1명 이상의 Approve** 후 본인이 Merge


## 🔀 Git 워크플로우 (Fork 방식)

### Fork 전략
- **upstream**: 원본 저장소 (팀 공용)
- **origin**: 개인 Fork 저장소
- `main`: 최종 병합된 학습 자료

[👉🏻 Fork 방식 상세 설명 보러가기](./FORK_GUIDE.md)


## 📝 커밋 컨벤션

```
docs(weekN): day0N - 주제명
fix(weekN): day0N - 수정 내용
update(weekN): day0N - 보완 내용
```

**예시**
```bash
git commit -m "docs(week01): day01 - React Virtual DOM 동작 원리"
git commit -m "fix(week01): day01 - Virtual DOM 설명 오류 수정"
git commit -m "update(week01): day03 - 번들링 코드 예시 추가"
```

> 💡 **주차(weekN)와 요일(day0N)을 명시**하여 어느 시점의 학습인지 명확하게!

<br>

## 🔍 PR (Pull Request) 규칙

### PR 제목 (주간 단위)
```
[Week N] 이름 - 한 주 학습 정리
```
**예시**: `[Week 1] 박창조 - 포트폴리오 기술 스택 정리`

> [!TIP] PR 내용은 템플릿을 참고해주세요.


### PR 프로세스
1. **금요일**: 본인 Fork → 원본 저장소로 PR 생성 
   - Issue 번호를 `study-four-career/CS-study#N` 형식으로 연결
   - 팀원들에게 리뷰 요청
2. **주말**: 팀원들이 리뷰 (최소 **1명 이상** Approve 필요)
3. 본인이 직접 **Merge**
4. **월요일**: upstream 최신 내용 동기화 & 새로운 주차 시작

> 💡 한 주의 학습을 **한 번의 PR**로 올리므로, 데일리 커밋 기록이 모두 보입니다!
> 
> 📌 **Issue 연결 방법**: [상세 가이드 보기](./GETTING_STARTED.md#-issue-연결하기)

## 👀 리뷰 가이드

### 리뷰어가 확인할 내용
- ✅ **기술 정확성**: 개념과 원리가 정확한가?
- ✅ **프로젝트 연관성**: 포트폴리오와 연결이 잘 되어있는가?
- ✅ **면접 대응력**: 실제 면접에서 답변할 수 있을 정도로 정리되었는가?
- ✅ **코드 예시**: 실제 프로젝트 코드가 포함되어 있는가?
- ✅ **추가 질문**: 더 깊이 파고들 수 있는 질문 제시

> 💡 **단순 칭찬보다는 구체적인 피드백**과 추가 학습 방향을 제시해주세요!

<br>

## 📊 진행 현황

| 주차 | 기간 | 박창조 | 박희연 | 이주영 | 이가희 | 변희수 |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Week 1 | 10.20 ~ 10.24 | - | - | - | - | - |
| Week 2 | 10.27 ~ 10.31 | - | - | - | - | - |
| Week 3 | 11.03 ~ 11.07 | - | - | - | - | - |
| Week 4 | 11.10 ~ 11.14 | - | - | - | - | - |
| Week 5 | 11.17 ~ 11.21 | - | - | - | - | - |
| Week 6 | 11.24 ~ 11.28 | - | - | - | - | - |

> ✅ = PR Merged / ⏸️ = 휴식 / ❌ = 불참


## 🏆 스터디 규칙

- **주 5회** (월~금) 데일리 학습 및 커밋 필수
- **금요일**: 한 주의 학습을 PR로 제출
- **주말**: 팀원들의 PR 리뷰 (최소 1개 이상)
- 부득이하게 참여가 어려운 경우 **사전 공지** (카카오톡/Issue)

## 📌 참고 자료

### 기술 면접 대비
- [Interview_Question_for_Beginner](https://github.com/JaeYeopHan/Interview_Question_for_Beginner) - 주니어 개발자 면접 질문
- [tech-interview-for-developer](https://github.com/gyoogle/tech-interview-for-developer) - CS 기술 면접 정리
- [Frontend Interview Handbook](https://www.frontendinterviewhandbook.com/) - 프론트엔드 면접 가이드

## 🧑🏻‍💻 멤버
|  박창조 | 박희연 | 이주영 | 이가희 | 변희수 | 
|:---:|:---:|:---:|:----:|:---:|
| [![](https://github.com/pcjo1202.png?width=150px)](https://github.com/pcjo1202) | [![](https://github.com/hi-react.png?width=150px)](https://github.com/hi-react) | [![](https://github.com/JUST7LING.png?width=150px)](https://github.com/JUST7LING) | [![](https://github.com/2gahee.png?width=150px)](https://github.com/2gahee) |[![](https://github.com/hiheesoo.png?width=150px)](https://github.com/hiheesoo) |