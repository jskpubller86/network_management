



# 환경 변수

셸은 여러가지 환경변수를 갖는다. 환경변수를 확인 하려면  **echo $환경변수이름 ** 형식으로 명령을 실행하면 된다. 

<table>
    <tr>
    	<th>환경 변수</th>
        <th>설명</th>
        <th>환경 변수</th>
        <th>설명</th>
    </tr>
    <tr>
    	<td>HOME</td>
        <td>현재 사용자의 홈 디렉터리</td>
        <td>PATH</td>
        <td>실행 파일을 찾는 디렉터리 경로</td>
    </tr>
    <tr>
    	<td>LANG</td>
        <td>기본 지원되는 언어</td>
        <td>PWD</td>
        <td>사용자의 현재 작업 디렉터리</td>
    </tr>
    <tr>
    	<td>TERM</td>
        <td>로그인 터미널 타입</td>
        <td>SHELL</td>
        <td>로그인해서 사용하는 셸</td>
    </tr>
    <tr>
    	<td>USER</td>
        <td>현재 사용자의 이름</td>
        <td>DISPLAY</td>
        <td>X 디스플레이 이름</td>
    </tr>
    <tr>
    	<td>COLUMNS</td>
        <td>현재 터미널의 컬럼 수</td>
        <td>LINES</td>
        <td>현재 터미널 라인 수</td>
    </tr>
    <tr>
    	<td>PS1</td>
        <td>1차 명령 프롬프트 변수</td>
        <td>PS2</td>
        <td>2차 명령 프롬프트(대개는 '>')</td>
    </tr>
    <tr>
    	<td>BASH</td>
        <td>bash 셸의 경로</td>
        <td>BASH_VERSION</td>
        <td>bash 버전</td>
    </tr>
    <tr>
    	<td>HISTFILE</td>
        <td>히스토리 파일의 경로</td>
        <td>HISTSIZE</td>
        <td>히스토리 파일에 저장되는 개수</td>
    </tr>
    <tr>
    	<td>HOSTNAME</td>
        <td>호스트의 이름</td>
        <td>USERNAME</td>
        <td>현재 사용자 이름</td>
    </tr>
    <tr>
    	<td>LOGNAME</td>
        <td>로그인 이름</td>
        <td>LS_COLORS</td>
        <td>ls 명령의 확장자 색상 옵션</td>
    </tr>
    <tr>
    	<td>MAIL</td>
        <td>메일을 보관하는 경로</td>
        <td>OSTYPE</td>
        <td>운영체제 타입</td>
    </tr>
</table>
환경 변수의 값을 변경하려면 `export 환경변수=값` 형식으로 실행한다. 

~~~export 예시
# export HOME=/    → /root로 되어 있던 홈디렉터리 경로를 /경로로 변경하였다.  
# echo $HOME	   → / 로 변경되었음을 확인할 수 있다.
~~~

환경 변수의 목록을 확인하려면 `printenv` 명령어로 확인할 수 있지만 일부 환경 변수는 나타나지 않을 수 있다. 

~~~~ 
# printenv
~~~~

# 환경변수의 저장 위치









