# 노트 작성 : 노트를 열어서 내용을 작성한다.

![CreateNote](/docs/image/Note_Create.png)

**[page address]** : -

<br/>

**[condition]**

&nbsp;&ndash; 로그인한 상태

<br/>

**[Function Flow]**

1\) 쿠키로부터 노트 데이터를 불러온다. (쿠키가 없으면 새 노트)

2\) Markdown으로 내용을 작성한다. (노트 작성이 활성화된 순간부터 5초 간격으로 자동저장된다.)

</br>

&ndash; **[노트 작성 위치에서 나간 경우 (창 종료 등)]**

&nbsp;&nbsp;&nbsp;3\) 서버에 메모를 전달하여 저장한다.

<br/>

&ndash; **["+" 버튼을 누른 경우]**

&nbsp;&nbsp;&nbsp;3\) 서버에 메모를 전달하여 저장하고, 쿠키를 삭제한다.

&nbsp;&nbsp;&nbsp;4\) 노트를 새로 연다.

<br/>

[**← 뒤로**](/docs/GNB/Note/Main.md)