# 구글 스프레드 시트 노드 👩🏻‍🔬

### **구글 스프레드시트 노드**   <a id="google-sp-node"></a>

* 사용자가 입력한 정보를 구글 스프레드 시트에 기록하고 저장하기 위해 사용하는 노드 입니다.
* [프로필 설정 &gt; 연결된 계정 관리 ](../../../platform/settings/integration.md)메뉴에서 구글 계정을 연동한 경우에 사용 가능합니다.
* 시트명, 컬럼명, 값을 입력해두면 사용자가 입력한 값이 시트에 실시간으로 입력됩니다.
* 일치하는 시트명\(sheetName\)이 없으면 새로운 시트를 생성합니다.
* 새로운 시트를 생성할때는 Columns 항목의 이름을 첫 행에 입력합니다.
* 이미 존재하는 sheet에 입력할 경우에는 column 명칭에 상관 없이 빈 행부터 차례로 값을 채웁니다.
* spreadsheetId는 스프레스 시트 URL에서 아래 표시된 부분 입니다.

![](../../../.gitbook/assets/guide_google-spreadsheet-id.png)

* 아래는 사용자가 입력한 메시지를 파라미터로 저장하여 시트에 입력받는 예시 입니다. 아래와 같이 입력할 경우 사용자가 입력한 이름 값은  파라미터에 저장되어 이름 열에, 전화번호 값은  파라미터에 저장되어 전화번호 열에 기록됩니다.

![&#xAD6C;&#xAE00; &#xC2A4;&#xD504;&#xB808;&#xB4DC;&#xC2DC;&#xD2B8; &#xB178;&#xB4DC; &#xC0AC;&#xC6A9; &#xC608;&#xC2DC;](../../../.gitbook/assets/guide_google-spreadsheet.png)

![&#xAD6C;&#xAE00; &#xACC4;&#xC815; &#xC5F0;&#xACB0; &#xC608;&#xC2DC;](../../../.gitbook/assets/integrations.png)

{% page-ref page="../../../platform/settings/integration.md" %}



### \*\*\*\* <a id="agent-call-node"></a>

