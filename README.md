# git의 기초

1. 일반 디렉토리를 git이 버전 관리할 수 있도록 한다.
```bash
git init
```
디렉토리별로 딱 한 번 한다.

2. git의 3요소
    - working directory : 작업 공간(=분장실)
    - staging area : 대기 공간(=무대 위)
    - repository : 버전이 기록되는 공간 , 사진 찍은 목록(=사진 촬영)
3. 3요소를 넘나들기 위해 쓰는 git 명령어
    - working directory --> staging area
    ```bash
    git add 파일명
    ```
    - staging area --> repository
    ```bash
    git commit -m '버전을 기록하는 이유'
    ```
4. 상태 & 기록을 확인하기 위한 명령어
    - 파일 상태 확인
    ```
    git status
    ```
    - 버전 기록을 보기 위한 명령어
    ```
    git log #육하원칙에 따라 뭉텅이로 다 알려줌
    ``` 
    ```
    git log --one line #좀 더 단순하게 볼 수 있음 
    ```