# 기본
\다음문자 의미없음<br>
^다음문자 제외<br>
[abc] a혹은b혹은c<br>
a-z a 부터 z까지<br>
| 이거나 <br>
. 모든 문자 <br>

# 수량자
*앞의 것이 조건에 맞지 않을때까지 선택(Greedy)<br>
*? 앞의 것이 조건에 처음 맞을 때까지 선택(Lazy)<br>
{n} 앞의 문자가 n번 일치하는 경우<br>

# 특수문자
[\b] 역스페이스<br>
\d 모든 숫자와 일치. [0-9]와 동일<br>

# 빈출 정규식

패턴 설명 | 정규표현식 패턴
-|-
이메일| "/^[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,4}$/"
휴대폰번호| "/^(010|011|016|017|018|019)-\d{3,4}-\d{4}$/u"
아이디| "/^[a-zA-Z]\w{2,7}$/u"
주민등록번호| "/^\d{2}[0-1]\d[0-3]\d-?[1-6]\d{6}$/u"
