# Usage

## #File
 - `:e` : 새로운 파일 열기 
 - `:r` : 해당 파일 내용 읽어오기
 - `:{N}r` : N번째 줄에 `:r` 실행
 - `:r !{Command}` : Command의 결과 읽어오기
 - `:w` : 저장하기
 - `:q` : 나가기
 - `:q!` : `!` = force
 - `:x` : = `:wq`
 - `:new` : new file

<br><br><hr><br><br><br>

## #Shell
 - `:sh` : 쉘로 잠시 빠져나가기
 - `Ctrl + D` : back to the vim
 - `:!` : 쉘로 빠져나가지 않고 명령어만 실행

<br><br><hr><br><br><br>

## #Visual
 - `set nu` : 줄번호 보이기
 - `set nonu` : 줄번호 가리기

<br><br><hr><br><br><br>
## #Edit

### - Basic
 - `h`,`j`,`k`,`l`
 - `u` : undo
 - `Ctrl + r` : redo
 - `:시작행,끝행s/변경전/변경후/g` : no ask
 - `:시작행,끝행s/변경전/변경후/c` : ask
 - `:reg` : register

### - `insert mode` will be ON
 - `i` : 커서 위치에서
 - `I` : 맨 앞 줄에서
 - `a` : 커서 다음 위치에서
 - `A` : 맨 뒷 줄에서
 - `o` : 커서 아랫줄에서
 - `O` : 커서 윗줄에서
 - `s` : 커서 위치 첫글자 수정으로 시작
 - `C` : 커서 위치부터 줄 끝까지 수정으로 시작
 - `S` + `cc`: 커서 위치의 줄 모두 지우고 시작

### - Movement
 - `w` : 단어 단위로 뒷줄 방향으로 이동
 - `W` : 단어 공백 단위로 뒷줄 방향으로 이동 
 - `b` : 단어 단위로 앞줄 방향으로 이동
 - `B` : 단어 공백 단위로 앞줄 방향으로 이동
 - `e` : `w`에서 마지막 글자 기준
 - `E` : `W`에서 마지막 글자 기준
 - `gg` + `H` + `{` : 문서 맨 앞으로/화면 상단
 - `G` + `L` : 문서 맨 뒤로/화면 하단
 - `^` + `0` : 문장 맨 앞으로 이동/줄 맨 앞으로 이동
 - `$` : 문장 맨 뒤로 이동
 - `줄번호 + Shift + g` : 해당 줄번호로 이동
 - `Ctrl + f` + `Ctrl + d` : 다음 페이지 단위로 이동/반페이지 단위
 - `Ctrl + b` + `Ctrl + u` : 이전 페이지 단위로 이동/반페이지 단위

### - Searching
 - `/` : 단어 검색(아래쪽으로) with `n` + `N`
 - `?` : 단어 검색(위쪽으로) with `n` + `N`
 - `*` : 현재 단어를 포워드 방향
 - `#` : 현재 단어를 백워드 방향

<br><br><hr><br><br><br>

## #Reference

https://stricky.tistory.com/135
https://blog.jiniworld.me/115
