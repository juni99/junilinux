# ls, pwd, mkdir, cd, rm 
## ls 
- 현재 디렉토리의 파일 목록을 출력하는 명령어

## pwd
- 현재 위치하고 있는 디렉토리를 알려주는 명령어

## mkdir
- 디렉토리를 생성하는 명령어

## cd
- 디렉토리로 이동하는 명령어

## rm
- 파일 또는 (-r)디렉토리 삭제 명령어

## help
- 명령어 뒤에 --help를 붙이면 그 명령어의 사용설명서를 출력


![화면 캡처 2021-04-11 174618](https://user-images.githubusercontent.com/63636275/114298404-357b4900-9af1-11eb-910c-811141f256b9.jpg)
- **ls** 명령어를 통해 현재 디렉토리 파일 목록을 출력.
- **ls -l** 명령어를 통해 접근권한, 파일 생성 날짜 등의 자세한 정보 출력.
- **pwd** 명령어를 통해 현재 위치 출력.
- **mkdir hello_linux** 명령어를 통해 hello_linux 파일이 생성되어있는 것을 확인.

![화면 캡처 2021-04-11 174715](https://user-images.githubusercontent.com/63636275/114298509-bd615300-9af1-11eb-9128-c5fbd6fd8fae.jpg)
- 실제 파일 위치로 들어가보면 생성되어있는 것을 확인.

![화면 캡처 2021-04-11 175809](https://user-images.githubusercontent.com/63636275/114298545-dc5fe500-9af1-11eb-826c-211e4180dbe2.jpg)
- **cd hello_linux** 명령어를 통해 hello_linux 디렉토리로 이동.
- **pwd** 명령어를 통해 현재 위치를 확인.

![화면 캡처 2021-04-11 180154](https://user-images.githubusercontent.com/63636275/114298581-1204ce00-9af2-11eb-8aff-371d8b7f146e.jpg)
- **cd /home/junehee** 명령어를 이용해 이동하고싶은 디렉토리를 지정해 이동할 수 있지만 **cd ..** 명령어를 통해 부모 디렉토리로 바로 이동 가능.
- **/ 는 최상위 디렉토리.**

![화면 캡처 2021-04-11 180631](https://user-images.githubusercontent.com/63636275/114298675-90617000-9af2-11eb-85e0-bb1cbf823b93.jpg)
- **rm -r hello_linux** 명령어를 통해 hello_linux 디렉토리를 삭제.
- **ls** 명령어를 통해 삭제된 것을 확인.

![화면 캡처 2021-04-11 180659](https://user-images.githubusercontent.com/63636275/114298732-ba1a9700-9af2-11eb-83b6-757f37cd57bf.jpg)
- **ls --help** 명령어를 통해 ls 명령어의 사용설명서 확인.