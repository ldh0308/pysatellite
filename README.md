# pysatellite

# 요구사항
- 아래와 예시와 같이 cmd 입력 인자로 발표자 목록을 입력 받음.
- 발표자 목록은 2명 이상.
- 입력 받은 발표자 목록 중 랜덤으로 발표자를 1명 선출하여 출력.
- 오늘 배운 클래스와 메서드 & 상속 코드를 반영하여 작성.
- 완료된 프로젝트는 담당자 이메일로 발송 & 최종 사용자가 사용 가능하도록 설명 문서의 링크를 걸어주세요.( README.md )
- 가능하다면 해당 프로그램의 제약사항을 추가하여 주세요.
```
                       .......,,,,,,     .~       
                  -:---~~~~~~~-.   :$=$@#- =$.    
               .,-,,,,-:::;;;;!!!.;;;::~@=;-, . . 
           .  -~-,,,,~;;;!!!!***;:!;;;::,    .   .
            -~~,,-~:;!!!!****=*=.;!;:,,,   .   ,*.
         .-::::~;;;!!!!*********,!*;....  !@@~.*#-
         , .~;$=$$$$==!*****=$$,,;!!:,,.:-=@$.-##,
                -:;::;!!~..,~:, .-::- ,~,-@@=.~@@,
    !                             .,.--,-~@@-,*$*,
  .*-                           ;##--,---*@@,,#*$,
  ~~-                    =!    -###:----~$@~,-@$$ 
  :.  .             :;~=*:    .!##@;----.,:--*@$=.
        . ,        *=$,=:  .  -$=@@#--- ~~~:*#@#~,
        -.         ,!!*~   ..-:##@$#-~-:;!$$=*;:,.
  *;,                  ..,...,*$=#**~;!==$*:~-,.. 
  ;@@=;.         .~::*=-,,,,,,$$=@@#$=$=;~-,...   
 .,*!:!$#$$$$$$$=!;;#@##:,,,,,$=#@=#=*;~-,..      
 *:=##!...,-:**===*.,=@@#~,,,-##@#@=;~-,..        
.,!==#$##@$*!;;,.~!=:;#@@=--~~#@#$!~-,...         
.,:!*$##$**==$$@*       ,~:!=@@##*-,...           
..,~:!*=$##@@@#==!;;;!!*$$#$$=*;~,..              
 ...,,~:;!*==$$$######$$=*!:~,,...                
     ...,,,--~~:::::::~~-,,....
```

### use

```
$ npm install -g leedonghyuk
$ leedonghyuk

$ awya5 발표자1 발표자2 발표자3

발표자 : 발표자(1~3) 랜덤 출력

```


### dev stack
- WSL > nvm > nodejs v20.11.0. > npm cli

### publish
```
$ npm login
$ npm publish
```
### 제약사항
이 프로그램은 Windows 환경 WSL을 사용하였으므로 MAC OS 환경에서 정상적으로 동작하지 않을 수 있음.
