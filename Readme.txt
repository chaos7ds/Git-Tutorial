C:\GitFolder\
git clone {~~~.git}

C:\GitFolder\{프로젝트 폴더}
git add .
git commit -m "변경내역"
git push
	git status
	git reset {파일}
	git add {파일}
	git checkout -- {파일}	: 마지막 버전 복원
	git pull
	git log
	git reset --hard {hash 값}
	git push -f				: 서버 롤백
	git commit --amend		: 수정 vim
	git checkout -b {branch 이름}