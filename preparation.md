# 사전 준비

## 1. 저장소(Repository) 준비

* 저장소 준비 전, `git-cli` [설치](https://git-scm.com/)와 자신의 github 계정으로 로그인 과정이 필요합니다.

1. 저장소를 포크(fork) 해주세요.

  

  <img src="./image/fork.png" alt="저장소 포크하기" style="zoom:60%;" />

  <img src="./image/forking.png" alt="포크 중" style="zoom:60%;" />

  

2. 포크 된 자신의 저장소 주소를 확인합니다.

<img src="./image/check_address.png" alt="주소 확인" style="zoom:60%;" />



3. 저장소를 복사할 디렉토리로 이동한 뒤, 아래 명령어를 순서대로 입력해주세요. 
   * (`<주소>`는 알맞은 주소를 입력하신 뒤, 주석 부분은 제외하고 입력해주세요.)

```powershell
git clone <주소> 				# 복사(clone) 명령
```



## 2. 작업 전 issue 생성

* 중복작업과 충돌(conflict) 방지를 위해 이슈를 생성하고, `assignee`를 자신으로 설정해주세요.
* 이슈는 원래의 저장소인 [pyconkr의 script 저장소](https://github.com/pythonkr/pyconkr-script)에 생성해주시면 됩니다.



1. `pycon/pycon-script` 저장소에서 새로운 이슈을 생성합니다.

<img src="./image/new-issue.png" alt="이슈 생성" style="zoom:60%;" />

2. `assign yourself`를 클릭하시면 자신을 `assignee`로 추가할 수 있습니다.

<img src="./image/assign-yourself.png" alt="assignee 할당" style="zoom:60%;" />

3. (템플릿 작성 예시 추가 예정)



### 작성예정 (?)

* 포크를 하면 branch를 별도로 만들어야 할까? 하는 생각이 들어서 일단은 해당부분 제외하고 만들어봤습니다.
* 이미지는 논의 후에 더 깔끔하게 만들어 볼게요.

 (cli 명령어 / fork, git clone 등) - [참고](https://github.com/pythonkr/pyconkr#getting-started)

  branch 세팅

  - branch 명 형식, branch 를 forked project 에 생성