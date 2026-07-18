# Open Source SW — 실습 (2022 Fall)

2022년 2학기 오픈소스소프트웨어 수업 실습 저장소. 셸 스크립트 기초와 마크다운 문법을 다뤘다.

## 셸 스크립트 실습 (`src/`)

| 스크립트 | 내용 |
|---|---|
| [ex3-0.sh](src/ex3-0.sh) | 변수와 `echo` 기본 출력 |
| [ex3-1.sh](src/ex3-1.sh) | `for` + `seq` — 인자로 받은 횟수만큼 반복 출력 |
| [ex3-2.sh](src/ex3-2.sh) | `case` 분기 — 커맨드라인 인자로 사칙연산 계산기 |
| [ex3-3.sh](src/ex3-3.sh) | BMI 계산 후 `if/elif` 조건 분기로 체중 판정 |
| [ex3-4.sh](src/ex3-4.sh) | `read`로 입력받아 `case` 패턴 매칭 (y/n 응답) |
| [ex3-5.sh](src/ex3-5.sh) | 셸 함수 정의와 호출, `eval` 사용 |
| [ex3-6.sh](src/ex3-6.sh) | 디렉토리 존재 검사(`-d`) 후 생성 |
| [ex3-7.sh](src/ex3-7.sh) | 반복문으로 디렉토리·파일 일괄 생성 |
| [ex3-8.sh](src/ex3-8.sh) | 파일 읽기 처리 |
| [ex3-9.sh](src/ex3-9.sh) | 종합 연습 |
| [hello.py](src/hello.py) | 파이썬 첫 실행 확인 |

## 문서 (`doc/`)

- [markdown-practice.md](doc/markdown-practice.md) — 마크다운 문법 연습 (코드블럭, 인용, 목록, 구분선 등)
- 과제 제출 문서 (docx)

## 실행 방법

```bash
sh src/ex3-0.sh
sh src/ex3-1.sh 5        # 5회 반복 출력
sh src/ex3-2.sh 3 + 4    # 7
```
