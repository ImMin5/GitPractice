# GitPractice
Tips for Git

## git 저장소 다시 연결하기
```
git remote remove origin
git remote add origin '깃주소.git'
git remote -v 로 확인
```

## 원격 브랜치 가져오기
```
git checkout -t origin/feature/openapi
```
## git ignore 적용 안될때 
```
 git rm -r --cached .
```

##  ! [rejected]        master -> master (non-fast-forward) 해결 
```
 git init 
 git remote add origin <url>
 git push origin master
 만약 다지우고 README.md 파일을 추가 시킨경우( 본인의 경우였음)
 git push origin +master 
```
