# GiftMacroBrowser
해피머니 상품권을 자동으로 입력하는 프로그램입니다.

<p>
현재 버전 : v0.1
제작자 : RichardBang
First Release Date : 2020.09.17
</p>


## 사용방법
브라우저를 실행하면 고정으로 해피머니의 홈페이지가 나옵니다.

<ol>
  <li>본인의 계정으로 로그인을 합니다</li>
  <li>상단 입력-상품권코드입력 에서 상품권 입력코드를 기입합니다</li>
  <li>입력-실행하기 버튼을 누르면 자동으로 기입을 완료합니다</li> 
 </ol>

## 알아둘 점

현재 해피머니의 인식하는 문자열 패턴은 다음과 같습니다.
   <ul>
  <li>xxxx-xxxx-xxxx-xxxx_yyyyMMdd
  </ul>

## ChangeLog
* v0.1 (Alpha)
  - 최초 개발 릴리즈 배포
  - 해피머니 상품권 자동화 입력 
  - 상품권 입력 수량에 상관없이 자동으로 충전을 수행 
    * 5개 이상일 경우 10개의 창으로 변경시킴
    * 10개 이상일 경우 10개의 충전을 완료 후 나머지 충전을 반복함.
    
 ## 주의사항
 본 프로그램을 이용하여 충전을 진행하는 중에는 컴퓨터의 다른 동작을 수행하지 말고 기다리십시오.<br>
 자동충전을 수행하는 중에 다른 작업을 할 경우 충전이 올바르게 이루어지지 않을 수 있습니다.<br>
 해피머니의 경우 10개 이상을 한번에 충전 입력하였을 경우에 해당 충전 결과를 확인하지 못하고 넘어갈 수 있습니다.<br>
 충전 시작전 현재의 충전금액을 확인하여 실 충전 금액을 확인토록 하십시오.<br>
 
##앞으로의 계획
코드입력의 인식패턴의 추가
해피머니 이외의 상품권 충전가능한 사이트 확대
추가 되었으면 하는 내용이 있으면 메일을 주시면 추가 검토 하겠습니다.
다른 contributor들도 환영합니다.

<a href="mailto:richard.bang83@gmail.com">메일보내기<a>
    
  


