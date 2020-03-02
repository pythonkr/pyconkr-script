# PR(Pull Request)하는 방법
- 멋진 파이써니스타 여러분! 프로젝트에 기여해주셔서 감사합니다. 파이콘 한국은 파이썬 커뮤니티의 많은 분들의 자발적인 도움으로 만들어가고 있습니다.
- PR을 처음해보신다면 [첫 기여하기](https://github.com/firstcontributions/first-contributions/blob/master/translations/README.ko.md)와 [Github Guide - Creating a pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request)를 참고해보세요 :)
- PR 한 후에 Maintainer가 리뷰한 후 내용 수정을 요청할 수 있습니다. (참고.[PR을 업데이트 하는 방법](https://pandas-docs.github.io/pandas-docs-travis/development/contributing.html#updating-your-pull-request))

## PR 전 확인해주세요 
- [ ] PR 관련한 [issue를 먼저 생성](./preparation.md#2-작업-전-issue-생성)해주세요.
- [ ] 중복된 PR이 없는지 확인해주세요.
- [ ] 작업 파일명은 repository의 파일명과 같게 해주세요.

## 모든 PR은
- PR 내용에는 `#이슈 번호`를 포함해 적어주세요. 
- Maintainer가 수정할 수 있도록 `Allow edits from maintainers` 항목을 체크해주세요. 
<img src="image/pr-check-allow-edits-from-maintainers-option.png" alt="Check Allow edits from maintainers" height="480">

## 자막 스크립트 편집 PR
- 작업할 수 있는 만큼만 편집해주시면 됩니다. **어디서부터 어디까지 편집했는지 꼭 파일에 적어주세요.**
- [참고: 스크립트 편집 기준](https://github.com/pythonkr/pyconkr-script#스크립트-편집)

### 스크립트 일부만 편집했을 때 
- 편집한 스크립트 내용 앞에 줄을 추가해 `(여기부터 검수 시작)`을 적어주시고 검수한 내용 마지막 줄에 `(여기까지 검수 완료)`를 추가해 적어주세요.
- PR 제목은 `[일부수정]파일 경로포함 파일명` 으로 합니다. 
(예. `[일부수정]2019-pyconkr/day2/라이트닝 토크/what is my PyCon - 배권한.txt`)

### 스크립트 전체 편집이 완료되었을 때

- 모든 내용이 검수 완료된 스크립트는 마지막 줄에 `(검수완료)`라고 적어주세요.
- PR 제목은 `[전체 편집]파일 경로포함 파일명`으로 합니다. 
(예. `[전체편집]2019-pyconkr/day2/라이트닝 토크/what is my PyCon - 배권한.txt`)

---
참고. 
- [첫 기여하기 by firstcontributions](https://github.com/firstcontributions/first-contributions/blob/master/translations/README.ko.md)
- [Github Guide - Creating a pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request)
- [pandas - contributing guide](https://pandas-docs.github.io/pandas-docs-travis/development/contributing.html#updating-your-pull-request)

