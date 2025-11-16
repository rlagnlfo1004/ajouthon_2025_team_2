# 제 2회 아주톤 최우수상 수상

## 🗂 프로젝트 개요
- **주제**: 학교 생활 불편함 해소 또는 서비스 개선
- **기간**: 24시간 해커톤

<br/><br/>

### 프로젝트 동기
학교 프로그램 중 특정 모임 활동을 인정받기 위해서는, 지금까지의 활동 기록을 증빙하는 보고서를 제출해야 하는 프로그램들이 많이 존재한다.
하지만, 이러한 보고서를 작성시에, 이전의 활동 기록을 관리하기 위해선 여러 플랫폼이 사용되고 (카톡, Drive, Notion) 이를 보고서로 작성시에, 자료를 보고서 형식에 맞춰 정리하는 불편함을 해소하고자 한다.

<img width="1336" height="765" alt="Image" src="https://github.com/user-attachments/assets/24cc52a6-30a3-4dfa-ae52-7e63c4f4de32" />
보고서 양식 예시

<br/><br/>

<img width="1242" height="723" alt="Image" src="https://github.com/user-attachments/assets/fa45db95-341e-41d6-a686-106636f27521" />
기존의 불편함 존재 (여러 플랫폼 사용 필요)

<br/><br/>

### 해결 방안 (서비스 기능)
1. 활동 그룹을 생성합니다.
2. 그룹원은 초대코드 발급을 통해 초대할 수 있습니다.
3. 활동 게시물 업로드 합니다. 이때, 활동에 참가한 그룹원들을 태그할 수 있습니다.
4. 업로드한 활동 게시물 중 보고서로 기입을 원하는 게시물들을 선택하면, 이를 보고서 형식의 Word(docx) 문서로 추출할 수 있습니다.

<br/><br/>

### 서비스 사진

<img width="566" height="554" alt="Image" src="https://github.com/user-attachments/assets/04c3bc37-292f-4277-b01b-d926f6df2b64" />
게시물 업로드 (제목, 활동 내용, 증명 사진, 참여한 그룹원 태그)

<br/><br/>

<img width="767" height="498" alt="Image" src="https://github.com/user-attachments/assets/745e53b5-1580-4ae6-b348-1508da6839f4" />
보고서 추출

<br/><br/>

<img width="573" height="745" alt="Image" src="https://github.com/user-attachments/assets/85a48dd3-455b-4d1d-957b-2514e675c720" />
Jinja2 template (아주대학교 2025 운동크루 프로그램 활동 보고서 예시)

<br/><br/>


## ⚙ 기술 스택

### Backend
- Spring Boot
- Python (docx 파일 생성을 위한 스크립트)
- Java → Python 프로세스 실행 방식 사용

### Frontend
- React

### Infra / DevOps
- AWS RDS (PostgreSQL)
- AWS S3 (이미지 업로드용)
- Docker 컨테이너

<br/><br/>


## 🧑‍💻 맡은 역할
- 백엔드 구현
- Word 변환 로직 연결 및 API 구성

<br/><br/>

## 📝 기타
- 해당 저장소는 해커톤 기간 내 빠르게 개발된 코드로, 구조나 네이밍, API 구조에 개선 여지가 있습니다.