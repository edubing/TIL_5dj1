# Git

1. 저장소(repository) 만들기 - git이 관리하는 폴더(directory)

   이미 init한 repo에서 또 init하지 않는다!

   ```shell
   $ git init
   ```

2. 파일을 스테이징하기

   ```shell
   $ git add 파일명
   ```

3. 파일을 커밋하기

   ```shell
   $ git commit -m '커밋 메세지 내용(변경사항을 요약해서 적음)'
   ```

- 상태 확인하기

  ```shell
  $ git status
  ```

- 내가 누군지 정보 입력하기

  ```shell
  $ git config --global user.name 유저이름
  ```

  ```shell
  $ git config --global user.email 유저이메일
  ```

- 커밋 기록 확인하기

  ```shell
  $ git log --oneline(옵션)
  ```

## 원격(remote) 저장소

- github - 무료,개인 ms -> github 얼마주고? 8조원
- gitlab(SSAFY) - 유료, 회사, 조직

폴더(repository)단위로 관리됨!

내 컴퓨터의 저장소 -> github의 내가 만든 원격 저장소



원격 저장소를 지정 : origin이라고 하겠다 그 주소는 https://github.com/edubing/TIL_5dj1.git

```shell
$ git remote add origin https://github.com/edubing/TIL_5dj1.git
```



```shell
$ git push origin master
```







