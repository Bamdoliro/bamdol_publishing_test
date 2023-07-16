## 0️⃣ 과제 안내

> 학교 소개 메인 페이지 퍼블리싱

### 사용 기술

- HTML
- CSS

<br>

## 1️⃣ 제출 방법

1. 이 레포지토리를 포크합니다
2. 본인의 이름으로 브랜치를 만듭니다. (예시: seokjin)
3. 퍼블리싱을 진행하며 커밋해주세요. (밑 커밋 메시지 규칙 참고)
4. 모두 완료한 후 Pull Request를 보내주세요.

> **포크, 브랜치, Pull Request가 뭔지 모르겠다면?** <br>  
> 다음 글을 참고하면서 진행해주세요!<br>  
> 꼭 이 글이 아니더라도, 다른 글들을 참고하면서 해도 괜찮습니다.<br>  
> [Git을 이용한 협업: Fork 부터 Pull Request 까지](https://seungwubaek.github.io/tools/git/contributing_using_pull_request/)

<br>

## 2️⃣ 커밋 메시지 규칙

### 형식

```
Type :: Title

Body
```

### 상세 규칙

- 헤더는 type을 지정해 주고, title을 명령문으로 작성한다.
- 헤더는 너무 길지 않도록 한다.
- Body에는 해당 커밋에서 무엇을 왜 하였는지 구체적으로 서술한다.
- 원활한 소통을 위해 한글로 작성한다.

### Header Type

| type     | description      |
| -------- | ---------------- |
| ADD      | 새로운 기능      |
| FIX      | 버그 수정        |
| REFACTOR | 코드 리팩토링    |
| TEST     | 테스트 코드 작성 |
| SET      | 프로젝트 세팅    |
| CHORE    | 자잘한 일        |
| DOCS     | 문서 추가        |
| DELETE   | 삭제             |

### 명령어 예시

```bash
git commit -m "ADD :: 원서 객체
- ~~ 구체적인 설먕
"
```
