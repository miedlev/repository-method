# repository-method

### 대용량 파일을 github에 넣는 과정


##### 1-1. Git Large File Storage (LFS) installation  https://git-lfs.github.com/
##### 1-2. Brew installation https://whitepaek.tistory.com/3

###### -> brew의 경우 순서대로 진행하되, 비밀번호는 최초 컴퓨터를 킬때 비밀번호이다 /
###### -> 1-1번만 진행할 경우, ‘lfs’ is not a git command'라고 뜨며 실행이 안된다. 따라서 1-2를 반드시 진행해줘야 한다.
###### -> 이후 밑의 두개를 적용하면 lfs실행 가능
```
$ brew update
$ brew install git-lfs
```

##### 1-3. git lfs 진행
