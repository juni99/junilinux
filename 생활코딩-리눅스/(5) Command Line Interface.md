# Command Line Interface

## GUI vs CLI

![화면 캡처 2021-05-01 211720](https://user-images.githubusercontent.com/63636275/116782408-dd1de280-aac3-11eb-8c76-ddaa04700632.jpg)
1. why 디렉터리을 생성
2. why 디렉터리로 이동
3. 현재 디렉터리 확인
4. 부모(상위) 디렉터리로 이동
5. why 디렉터리 삭제
6. why 디렉터리 생성 후 이동
7. 현재 디렉터리 확인
- 세미콜론(;)으로 명령을 연달아 실행

**응용**
![화면 캡처 2021-05-01 211908](https://user-images.githubusercontent.com/63636275/116782673-80bbc280-aac5-11eb-9c33-d7d9dd9fd158.jpg)
- test 디렉터리 생성 후 이동 후 하위 디렉터리로 test.txt 생성

![화면 캡처 2021-05-01 212417](https://user-images.githubusercontent.com/63636275/116782712-bc568c80-aac5-11eb-9521-bbbd737402e4.jpg)
- test 디렉터리 생성 후 이동 후 test 이름이라는 파일 생성 후 실행

![화면 캡처 2021-05-01 212437](https://user-images.githubusercontent.com/63636275/116782731-d2644d00-aac5-11eb-92f8-ff14f29b9b9d.jpg)
- hello CLI!!!! 쓰고 저장

![화면 캡처 2021-05-01 212500](https://user-images.githubusercontent.com/63636275/116782745-e3ad5980-aac5-11eb-9a02-63f2410dbafb.jpg)
- cat test -> test 파일 출력

## 파이프 라인
- 컴퓨터 과학에서 파이프라인(영어: pipeline)은 한 데이터 처리 단계의 출력이 다음 단계의 입력으로 이어지는 형태로 연결된 구조를 가리킨다.

![화면 캡처 2021-05-01 215156](https://user-images.githubusercontent.com/63636275/116783355-418f7080-aac9-11eb-8321-04f4a1ce750b.jpg)
- react.txt 파일을 만들고 react 사이트에서 튜토리얼을 복사 후 붙여넣기함

![화면 캡처 2021-05-01 215627](https://user-images.githubusercontent.com/63636275/116783382-65eb4d00-aac9-11eb-8c49-699a52224e60.jpg)
- 현재 디렉터리에 있는 react.txt 파일을 test 디렉터리에 같은 이름으로 복사함

![화면 캡처 2021-05-01 215821](https://user-images.githubusercontent.com/63636275/116783403-8ddab080-aac9-11eb-92d6-85909ec584bb.jpg)
- grep game react.txt -> react.txt 파일에서 game이라는 단어를 포함하는 행 출력.

![화면 캡처 2021-05-01 215834](https://user-images.githubusercontent.com/63636275/116783435-b4005080-aac9-11eb-9da3-bf0cfcf9d46e.jpg)
- game 단어의 행만 출력

![화면 캡처 2021-05-01 220049](https://user-images.githubusercontent.com/63636275/116783443-c1b5d600-aac9-11eb-9963-5e56818494e5.jpg)
- ls --help | grep sort -> ls --help 출력 화면에서 sort 라는 단어를 포함하는 행을 출력

![화면 캡처 2021-05-01 220103](https://user-images.githubusercontent.com/63636275/116783468-e316c200-aac9-11eb-9d9b-c4fd59c7e875.jpg)
- sort 단어의 행만 출력