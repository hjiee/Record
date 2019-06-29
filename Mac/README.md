Editing

Alt + mouse left key click , Ctrl + g , Ctrl + Cmd + g : Multi-Selection, 여러줄 동시 편집  

Alt + Space : 기본 코드 완성(커스텀 단축키이다. 맥의 spotlight와 단축키가 겹치기 때문에 변경했다.)

Ctrl + Shift + Space : 스마트 코드 완성(예상되는 타입의 메소드또는 변수명 )

F1 , Control + j : 빠른 문서 보기 Quick Document

Shift + F1 : 외부 문서보기(http://developer.android.com/reference로 이동)

Control + mouse over code : 간단한 설명.

Cmd + N : Generate code( Getters, Setters, Constructors, hashCode/equals, toString )

Cmd + Shift + N : 파일 java, package 등등 새로 만들기

Alt + Shift + Insert  or Alt + LeftMouseDrag : 블럭 단위 선택 및 편집

Control + O : Override methods

Control + I : Implement methods

Cmd + Alt + T : Surround with… (if..else, try..catch, for, synchronized, etc.)

Cmd + / : 한줄주석

Command + Alt + / : 블럭주석

Alt + Upper Arrow : 연속적인 코드블럭 선택

Alt + Enter : 빠른수정.

Cmd + Alt + L : Reformat code    코드 자동정렬





Ctrl + Alt + O : Optimize imports 임포트 자동정렬

Ctrl + Alt + I : Auto-indent line(s)

Ctrl + Shift + V : 이전에 클립보드에 복사한 히스토리 열기.

Cmd + D : 라인복제 또는 선택블록 복제

Cmd + Delete : 라인삭제

Ctrl + Shift + J : 라인합치기(Smart line join)

Ctrl + Enter : 라인분리(Smart line split)

Cmd + Shift + U : 대소문자 변환

Cmd + Alt + ] / [ : 코드블럭 처음또는 끝까지 선택

Alt + Delete : 단어끝까지 삭제

Alt + Fn + Delete : 단어처음까지 삭제 

Search/Replace

 

Double Shift : 모든곳에서 찾기.

Cmd + F : 찾기

//* 찾은 상태에서

Cmd + G : 다음찾기

Cmd + Shift + G : 이전찾기

//*/

Cmd + R : 바꾸기

Cmd + Shift + F : 경로에서 단어 찾기Find in path)
Cmd + Shift + R : 경로에서 바꾸기(Replace in path)

 

 

 

Usage Search

 

Alt + F7 / Cmd + F7 : 사용내용 전체찾기 / 파일에서 사용한것 찾기
Cmd + Shift + F7 : 현재파일에서 하이라이트
Cmd + Alt + F7 : 사용된것 새창으로 보여줌.

 

 

 

Compile and Run

 

Ctrl + Alt + R : Run

Ctrl + Alt + D : Debug 

 

 

Debugging


F8 : Step over

Alt + Shift + F8 : Force Step over
F7 : Step into

Alt + Shift + F7 : Force Step into
Shift + F7 : Smart step into
Shift + F8 : Step out
Alt + F9 : Run to cursor
Alt + F8 : Evaluate expression
F9 : Resume program
Cmd + F8 : Toggle breakpoint
Cmd + Shift + F8 : View breakpoints

 

 

 

Navigation

Cmd + 1 : Project 탭 메뉴 가기, (이 상태에서 Cmd + Shift + 좌우 화살표 :  창 넓이 조절.)

Cmd + 7 : Structure 탭 메뉴 가기

ESC : Go to editor 다른 메뉴나 툴바로 이동했을 때 마지막 에디터 있던 위치로 이동한다. (from tool window)


Shift + Esc : 마지막에 사용한 도구창 닫기
Ctrl + G : 줄번호로 이동.
Cmd + E : 이전에 열었던파일 목록창 열기, 최근 수정한 탭 열기
Cmd + B or Cmd + Click or F4 : Go to declaration, 메소드 or 클래스 선언 부로 이동
Cmd + Alt + B : Go to implementation(s)
Cmd + y or Alt + spacebar : Open quick definition lookup 정의부 빠르게 보기. 팝업 윈도우에서 정의된 부분 확인
Cmd + U : super-method/super-class 이동.

Ctrl + H : 상속 구조 확인

Ctrl + Alt + H : caller Hierarchy 호출하는 곳 확인

Cmd + F7 : Find Usage . 메소드를 호출하는 곳 확인.

Ctrl + ] / [ :  코드블럭 처음/끝 이동
Cmd + F12 : 파일 구조보기 , quick outline

F2 / Shift + F2 : 다음/이전 하이라이트된 에러로 이동.

Shift + Cmd + Arrow Left / Right : Select Next Tab 열려진 파일 탭 간 이동

Alt + Shift + Arrow Left / Right : xml 리소스 파일 디자인 / 에디터 간 전환키

Ctrl + Alt + Arrow Left / Right : back / forword 키. 소스 이동간에 유용한 키

Ctrl + Alt + HOME or upper Arrow : 메인액티비티 / 메인레이아웃 파일 간 전환

Cmd + P : 메소드 매개변수 확인 parameter 

 

Refactoring

Ctrl + T : 리팩토링 팝업 창

Alt + Cmd + P : 매개변수 추출

Alt + Cmd + M : Method 추출 기능

Cmd + Alt + L : 지역변수 추출

Cmd + Alt + M : 멤버변수 추출

F5 : 복사
F6 : 이동
Alt + Delete : 안전하게 삭제(지우기전에 사용된곳 확인 가능)

Shift + F6 : 이름바꾸기

 
 

Live Templates


Ctrl + Alt + J : Surround with Live Template
Ctrl + J : Insert Live Template
iter : Iteration according to Java SDK 1.5 style
inst : Check object type with instanceof and downcast it
itco : Iterate elements of java.util.Collection
itit : Iterate elements of java.util.Iterator
itli : Iterate elements of java.util.List
psf : public static final
thr : throw new

control + cmd + 화살표 상 : java파일과 레이아웃 xml파일 간의 전환토글키
control + Shift + 화살표 좌, 우 : 레이아웃 xml파일의 Text/Design 탭간의 전환 토글키.
alt + enter : 코드 자동 삽입, 수정
cmd + n : Generate 컨텍스트 메뉴 키.
alt + Shift + 화살표 상,하 : 코드 통째로 위아래로 이동.
cmd + [ , ] : 이전 , 이후 소스 코드로 이동.
cmd + F12 : 클래스 안의 메소드 선택 이동 가능(편리함)



출처: https://devfalledinmac.tistory.com/25 [MAC 빠진 개발자]
