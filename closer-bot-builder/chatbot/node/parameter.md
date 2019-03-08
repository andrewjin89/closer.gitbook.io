# 파라미터 설정 노드

* 대화하는 도중에 사용자로부터 입력받거나 서버에서 받아온 값을 파라미터로 저장할 수 있는 노드 입니다.
* 사용자가 입력한 값 저장, HTTP 요청으로 서버에서 받아온 값 설정, 현재 상황에 따른 변수 값 변경 등의 목적으로 사용합니다.
* 파라미터 값 설정\(set\), 해제\(clear\)가 가능합니다.
* 파라미터 값은 string으로 저장되며, JSON object값 입력은 현재는 가능하지만 비활성예정입니다.
* 아래는 사용자가 입력한 메시지\(이름\)을 name이라는 파라미터에 저장하는 예시입니다. 이렇게 이름 파라미터를 설정한 후에는  형태로 입력받은 이름을 사용할 수 있습니다. 예\) "님 안녕하세요. 무엇을 도와드릴까요?" 형식으로 파라미터로 저장 되어있는 이름을 사용할 수 있습니다.
* CLOSER Chat에서 노출되는 지정된 파라미터를 "chat:파라미터명"으로 설정할 수 있습니다.

| 파라미터명 | 설명 |
| :--- | :--- |
| chat:displayName | 이름 |
| chat:phoneNumber | 전화번호 |
| chat:email | 이메일 |
| chat:category:0 | 대분류 |
| chat:category:1 | 중분류 |
| chat:category:2 | 소분류 |

![&#xD30C;&#xB77C;&#xBBF8;&#xD130; &#xC124;&#xC815; &#xB178;&#xB4DC; &#xC608;&#xC2DC;](../../../.gitbook/assets/guide_%20%2810%29.png)
