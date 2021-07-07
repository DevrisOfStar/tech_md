# 비밀번호 변경 : 사용자의 비밀번호를 변경한다.

![MypageSetting](/docs/image/Mypage_info.png)

**[page address]** : /mypage/setting

<br/>

**[condition]**

&nbsp;&ndash; 로그인되어있고, \[Change Password\] 버튼을 누른 상태

<br/>

**[Function Flow]**

1\) Change Password 창을 오른쪽에 띄운다.

2\) 현재 비밀번호, 바꿀 비밀번호, 바꿀 비밀번호 확인을 입력한다.
  - 각 비밀번호는 유효성(8자이상) 검사를 한다.


&ndash; **[현재 비밀번호가 틀린 경우]**

&nbsp;&nbsp;&nbsp;3\) "비밀번호가 틀립니다." 를 보여주고, 비밀번호 칸을 초기화한다.

<br/>

&ndash; **[바꿀 비밀번호와 바꿀비밀번호가 다른 경우]**

&nbsp;&nbsp;&nbsp;3\) "바꿀 비밀번호가 다릅니다." 를 보여주고, 바꿀 비밀번호 확인 칸을 초기화한다.

<br/>

&ndash; **[정상적으로 작동되는 경우]**

&nbsp;&nbsp;&nbsp;3\) "비밀번호가 변경되었습니다."를 알린다.

<br/>

[**← 뒤로**](/docs/MypageSetting.md)