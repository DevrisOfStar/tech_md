# 계정 탈퇴 : 로그인한 사용자계정을 탈퇴한다.

![MypageSetting](/docs/image/Mypage_info.png)

**[page address]** : /mypage/setting

<br/>

**[condition]**

&nbsp;&ndash; 로그인되어있고, \[Delete My Account\] 버튼을 누른 상태

<br/>

**[Function Flow]**

1\) Delete My Account 창을 왼쪽에 띄운다.

2\) 삭제를 위한 비밀번호를 입력한다.


&ndash; **[비밀번호가 틀린 경우]**

&nbsp;&nbsp;&nbsp;3\) "비밀번호가 틀립니다." 를 보여주고, 비밀번호 확인칸을 초기화한다.

<br/>

&ndash; **[정상적으로 작동되는 경우]**

&nbsp;&nbsp;&nbsp;3\) 서버에서 계정정보를 삭제한다.

&nbsp;&nbsp;&nbsp;4\) 페이지에 저장된 유저정보를 모두 지우고, [Main](/docs/Main.md)로 이동한다.

<br/>

[**← 뒤로**](/docs/MypageSetting.md)