# 제목1
## 제목2
### 제목3
#### 제목4
##### 제목5
###### 리액트 앱 실행
- 개발서버 실행
  1. `npm run dev`
###### 리액트 앱 설치
- npm 모듈 설치
  1. `npm i`
---
#### 깃으로 관리하기
1. 프로젝트에서 깃 시스템 초기화(최초1회)
   1. `git init`
2. 관리할 파일을 스테이지로 등록
   1. `git add 파일명`,
   2. `.`: 변경이력이 있는 파일만 선택
   3. `*`: 모든 파일 선택

3. 커밋메시지와 함께 커밋

echo "# react-test" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/diwony/react-test.git
git push -u origin main

---
##### 깃 명령(한 줄씩 설명)
- `echo "# react-test" >> README.md`: `README.md` 파일 끝에 `# react-test` 텍스트를 추가합니다. 파일이 없으면 새로 생성됩니다.
- `git init`: 현재 디렉터리를 새 Git 저장소로 초기화합니다(`.git` 디렉터리 생성).
- `git add README.md`: `README.md` 파일을 스테이징 영역에 추가하여 다음 커밋에 포함되게 합니다.
- `git commit -m "first commit"`: 스테이징된 변경을 `"first commit"` 메시지로 커밋합니다.
- `git branch -M main`: 현재 브랜치를 `main`으로 이름 변경합니다.(`-M`은 강제 이동/이름 변경 옵션)
- `git remote add origin https://github.com/diwony/react-test.git`: 원격 저장소 이름을 `origin`으로 추가하고 해당 GitHub URL을 연결합니다.
- `git push -u origin main`: 로컬 `main` 브랜치를 `origin`으로 푸시하고, `-u` 옵션으로 업스트림(추적) 브랜치를 설정합니다.