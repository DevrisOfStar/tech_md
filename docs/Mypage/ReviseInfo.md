# 개인정보 수정 : 사용자의 개인정보를 수정한다.

![MypageSetting](/docs/image/Mypage_info.png)

**[page address]** : /mypage/setting

<br/>

**[condition]**

&nbsp;&ndash; 로그인된 상태

<br/>

**[Function Flow]**

1\) [개인정보 불러오기](/docs/Mypage/LoadInfo.md)를 통해 모든 칸을 불러온다.

2\) 수정이 필요한 부분을 수정한다.

3\) 수정버튼을 누른다.


&ndash; **[비밀번호가 틀린 경우]**

&nbsp;&nbsp;&nbsp;4\) "비밀번호가 틀립니다." 를 보여주고, 비밀번호 확인칸을 초기화한다.

<br/>

&ndash; **[기존에 있던 정보랑 동일한 경우]**

&nbsp;&nbsp;&nbsp;4\) 수정 버튼을 비활성화한다.

<br/>

&ndash; **[정상적으로 작동되는 경우]**

&nbsp;&nbsp;&nbsp;4\) 서버 데이터를 수정하고 [Mypage](/docs/Mypage.md)로 이동한다.

<br/>

[**← 뒤로**](/docs/MypageSetting.md)