3. Git 사용법



git = 자신이 작업한 코드를 공유



git config --global user.name "parkilhoon-098"

git config --global user.email ""

```
echo "# note" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/parkilhoon-098/note.git
git push -u origin main
```



git init : 관리할 프로젝트를 정함

git add README. md

1. 저장한 파일을 선택
2. 선택한 파일 저장

올릴 파일이 많다면 git add .



git status = 현재 깃의 상태를 파악



.gitignore = 깃허브에 올리지않을 파일을 선택



git commit -m "first commit" 



git remote add [remote 이름] [repository 주소]

git push [romote 이름] [branch 이름]



git branch -M main= 현재 작업중인 브렌치에서 코드가 겹쳐지지않게 하는것.



git push second main 파일을 업로드