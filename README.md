# Git Practice

## 자기소개
안녕하세요! 동국대학교 컴퓨터AI학부 3학년 성준서입니다. 

## 관심 분야
- Backend (Spring Boot, Supabase, PostgreSQL)
- Infra (Docker, AWS)

## Git 명령어 정리
- git init: 새로운 로컬 Git 저장소를 초기화하고 생성합니다.
- git status: 현재 작업 디렉터리와 스테이징 영역의 상태(변경되거나 추적되지 않는 파일 등)를 확인합니다.
- git add: 변경된 파일을 스테이징 영역(Staging Area)에 추가하여 커밋할 준비를 합니다.
- git commit: 스테이징 영역에 있는 파일들의 변경 사항을 스냅샷으로 기록(저장)합니다.
- git log: 저장소에 기록된 커밋 히스토리(과거 기록)를 조회합니다.
- git branch: 현재 존재하는 브랜치 목록을 확인하거나 새로운 브랜치를 생성합니다.
- git switch 또는 git checkout: 작업 중인 브랜치를 다른 브랜치로 전환합니다. (최신 버전에서는 switch 권장)
- git remote: 로컬 저장소와 연결된 원격 저장소를 관리(조회, 추가, 삭제)합니다.
- git push: 로컬 저장소의 커밋된 변경 사항을 원격 저장소(GitHub 등)로 업로드합니다.

## CLI 실습 기록
- 사용한 명령어 순서: 
  1. mkdir git-practice && cd git-practice
  2. git init -b main
  3. git add README.md
  4. git commit -m [아래에 적어둔 커밋 메시지] (3회 반복)
  5. git switch -c feature/profile
  6. git remote add origin https://github.com/junse02/git-practice.git
  7. git push -u origin feature/profile
- 생성한 브랜치명: feature/profile
- 커밋 메시지 3개:
  1. Docs: README 파일 틀 작성
  2. Docs: 자기소개 및 관심 분야 추가
  3. Docs: Git 명령어 정리 추가
- 어려웠던 점: CLI로 깃을 잘 사용하지 않다가, 다시 사용해보니 헷갈리는 점이 있었고, 버튼 기능을 사용하는게 편리하고 좋았다는 느낌을 받았다.

## PR 실습 기록
- PR 제목: feature/profile 브랜치 내용 main 병합 요청
- PR 링크: https://github.com/junse02/git-practice/pull/1
- PR에서 수정한 내용: 자기소개, 관심 분야, Git 명령어 정리 및 실습 기록
- Merge 여부: 완료 (Merged)
