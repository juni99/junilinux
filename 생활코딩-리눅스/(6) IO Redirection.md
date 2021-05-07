# IO Redirection (리다이렉션)

## Redirecion
- 보통 기본적으로 출력은 **모니터**로 되지만 출력을 파일로 바꾸는 것을 **리다이렉션**이라고 한다.

![화면 캡처 2021-05-04 233505](https://user-images.githubusercontent.com/63636275/117112065-78180480-adc3-11eb-8193-4380dfa5c60c.jpg)
- ls -l 만 쓰면 명령의 출력이 모니터로 나간 것인데 **ls -l > reslit.txt** 명령어는 > 화살표를 이용하여 모니터로 출력될 것을 파일로 출력하게 한다. 흔하게 저장한다고 할 수 있다.

![화면 캡처 2021-05-05 170643](https://user-images.githubusercontent.com/63636275/117112621-4bb0b800-adc4-11eb-98b9-0439985f00e4.jpg)
- ls -l /error 명령은 파일명이 error인 디렉터리가 없기 때문에 에러가 출력됨.
- ls -l /error > error.txt 명령은 ls -l /error 명령의 출력이 error.txt라는 파일에 리다이렉션이 되어야하는데 에러가 발생하였다.
- **>** 는 standard output을 리다이렉션 한 것이지 standard error를 리다이렉션한 것이 아니기 때문에.
- **2>** 는 standard error를 리다이렉션한 것이다.

![화면 캡처 2021-05-05 170834](https://user-images.githubusercontent.com/63636275/117113420-68012480-adc5-11eb-92b5-db050735d40d.jpg)

![화면 캡처 2021-05-05 171336](https://user-images.githubusercontent.com/63636275/117113450-72232300-adc5-11eb-9344-6ec423cc80e5.jpg)
- ls -l > test.txt = ls -l 1> test.txt 는 같은 명령어이다. **>** 앞에 1을 생략할 수 있다.

## Input

![화면 캡처 2021-05-07 181445](https://user-images.githubusercontent.com/63636275/117427696-42f4e900-af60-11eb-932b-85bf7820cd43.jpg)
- **응용**: cat hello.txt error.txt 파일 두개를 동시에 출력이 가능하다.
- cat 만 입력했을 경우 대기상태가 되어 키보드로 입력한 것을 standard input으로 받고 있는 것이다.
- [Ctrl] + [d] 를 누르면 종료됨.

![화면 캡처 2021-05-07 181828](https://user-images.githubusercontent.com/63636275/117428056-a5e68000-af60-11eb-9eda-1d49b586c57f.jpg)
- cat은 키보드로 입력을 받아 출력을 하지만 **<** 를 이용하여 리다이렉션하면 파일의 내용을 입력을 받아 출력을 하게 되는 것이다.

![화면 캡처 2021-05-07 182305](https://user-images.githubusercontent.com/63636275/117428742-4f2d7600-af61-11eb-8f36-afcee04f894c.jpg)
- head -n1 은 파일의 첫번째줄만 출력을 하게하고 head -n2은 파일의 두번째줄만 출력하게하듯이 -n 뒤에 숫자에 따라 몇번째줄까지 출력하게 하는지 정하는 것이다.

## Append

![화면 캡처 2021-05-07 183700](https://user-images.githubusercontent.com/63636275/117430615-3f169600-af63-11eb-8e42-f244994cf138.jpg)
- ls > ls.txt를 두번 연달아 입력하면 결과를 **덮어쓰기**를 한다.

![화면 캡처 2021-05-07 183825](https://user-images.githubusercontent.com/63636275/117430791-6c634400-af63-11eb-9843-851fe9038822.jpg)
- ls >> ls.txt를 입력하면 결과를 **덮어쓰지않고 추가**하여 저장을 한다. 