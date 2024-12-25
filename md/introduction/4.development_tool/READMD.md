# 개발자 도구

# Contents

- [Chrome](#Chrome)
- [Firefox, Edge 및 기타 브라우저](#Firefox,-Edge-및-기타-브라우저)
- [Safari](Safari)

## 개발자 도구란?

- 브라우저엔 '개발자 도구'라는 것이 내장되어 있다.
  - 이 도구를 이용하면 예외를 확인할 수 있다.
  - 이 도구는 개발자가 웹 개발을 하는 것을 돕기 위한 도구이다.

## Chrome

- [bug.html](./refer/bug.html)을 연다.

- 페이지 내 스크립트에 예외가 존재한다.
  - 일단적인 사용자 눈에는 이 예외가 보이지 않아, 개발자 도구를 열어 예외를 확인해야 한다.
- `key:F12`를 입력 한다.
  - Mac 사용자라면, `key:Cmd+Opt+J`를 입력 한다.
- 개발자 도구가 열린 화면
  - ![chrome](./refer/chrome.png)
- 붉은 예외 메시지가 보인다.
  - 'lalala'가 정의되지 않았다(not defined)라는 메시지이다.
- 예외 메시지 우측에 링크 `bug.html:12`가 있다.
  - bug.html은 해당 예외가 발생한 파일, 12는 예외가 발생한 줄을 나타냅니다.
- 예외 메세지 아래에 파란색 기호 `>`가 있는 데, 이 기호가 있는 곳엔 자바스크립트 명령어(command)를 입력할 수 있다.
  - 이를 '커맨드 라인(command line)'이라 부른다.
  - 커맨드 라인에 명령어(command)를 입력한 후 `key:Enter`를 누르면 해당 명령어가 실행 된다.

## Firefox, Edge 및 기타 브라우저

- `key:F12`를 누르면 대부분의 브라우저에서 개발자 도구를 열 수 있다.

## Safari

- Mac 전용 브라우저인 Safari에서 개발자 도구를 사용하려면 '개발자 메뉴(Develop menu)'를 명시적으로 활성화해주어야 한다.

- 환경설정(Preferences)의 고급(Advanced) 패널을 클릭한 후 메뉴 막대에서 '개발자용 메뉴 보기' 체크 박스를 체크해 개발자 도구를 활성화 한다.
  - ![safari](./refer/safari.png)

- `key:Cmd+Opt+C`를 눌러 개발자 콘솔을 실행할 수 있게 되었다.
