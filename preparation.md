# 사전 준비

## 1. 저장소(Repository) 준비

* 저장소 준비 전, `git-cli` [설치](https://git-scm.com/)와 자신의 github 계정으로 로그인 과정이 필요합니다.

1. 저장소를 포크(fork) 해주세요.

<img src="./image/fork.png" alt="저장소 포크하기" style="zoom:60%;" />



* 잠시만 기다리시면 로그인한 계정으로 저장소가 포크됩니다.

<img src="./image/forking.png" alt="포크 중" style="zoom:60%;" />

  

2. 포크된 자신의 저장소 주소를 확인합니다.

<img src="./image/check_address.png" alt="주소 확인" style="zoom:60%;" />



3. 명령 프롬프트 등의 터미널을 실행한 뒤, 저장소를 복사할 디렉토리로 이동해주세요.
   * `Shift + 우클릭` -> `여기에 명령창 실행` 을 사용하시면 편리합니다.



4. 아래 명령어를 순서대로 입력해주세요. 
   * (`<주소>`는 알맞은 주소를 입력하신 뒤, 주석 부분은 제외하고 입력해주세요.)
   * 예시: `git clone https://github.com/계정명/......`

```powershell
git clone <주소> 				# 복사(clone) 명령
```



## 2. 작업 전 issue 생성

* 중복 작업과 충돌(conflict) 방지를 위해 이슈를 생성하고, `assignee`를 자신으로 설정해주세요.
* 이슈는 원래의 저장소인 [pyconkr의 script 저장소](https://github.com/pythonkr/pyconkr-script)에 생성해주시면 됩니다.



1. `pycon/pycon-script` 저장소에서 새로운 이슈를 생성합니다.

<img src="./image/new-issue.png" alt="이슈 생성" style="zoom:60%;" />

2. `assign yourself`를 클릭하시면 자신을 `assignee`로 추가할 수 있습니다.

<img src="./image/assign-yourself.png" alt="assignee 할당" style="zoom:60%;" />

3. 제목 등 필요한 내용을 기입하신 뒤 `Submit new issue`를 눌러주세요.

<img src="./image/example-complete.png" alt="예제" style="zoom:60%;" />





기여를 위한 사전작업이 완료되었습니다. 컴퓨터에 생성된 `*.md` 파일을 수정해주시면 됩니다.

커밋 후 PR(Pull Request)를 보내주시면 빠르게 반영하겠습니다.

PR과 관련된 내용은 [링크](./pr-guide.md)에서 확인하실 수 있습니다.

