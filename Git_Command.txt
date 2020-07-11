C:\GitFolder\
git clone {~~~.git}				: Rep 불러오기

C:\GitFolder\{프로젝트 폴더}
git add .
git commit -m "변경내역"
git push

	git status					: 변경 사항
	git reset {파일}				: commit 취소
	git add {파일}				: 하나의 파일만 서버로
	git pull					: 로컬 <- 서버
	
	git checkout -- {파일}		: 마지막 버전 복원
	git log						: 버전 기록
	git log --graph				: branch-merge 기록
	git reset --hard {hash}		: 로컬 <- 서버
	git push -f					: 서버 <- 로컬
	git commit --amend			: 수정 vim
	
	git checkout -b {branch}	: 만들고 이동
	git branch					: 조회
	git branch {branch}			: 생성
	git checkout {branch}		: 이동
	git merge {branch}			: 병합
	git branch -d {branch}		: 삭제
	git push {name} {branch}	: git에 생성
	
	git remote						: 조회
	git remote -v
	git remote show {name}			: 정보 확인
	git remote add {name} {link}		: 추가
	git remote rename {from} {to}	: 이름변경
	git remote rm {name}				: 제거