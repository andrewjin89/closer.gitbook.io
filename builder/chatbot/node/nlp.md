# 자연어 처리 노드 👩🏻‍🔬

### **자연어 처리 노드**   <a id="nlp-node"></a>

![&#xC790;&#xC5F0;&#xC5B4; &#xCC98;&#xB9AC; &#xB178;&#xB4DC; &#xC608;&#xC2DC;](../../../.gitbook/assets/guide_%20%2811%29.png)

* 사용자의 입력에 따라 인공지능 기반 대화를 구현하기 위해 사용하는 노드입니다.
* CLOSER는 자체 인공지능 엔진은 제공하지 않지만 외부 자연어 서비스를 연동할 수 있습니다.
* 자동응답, 의도 및 개체 식별 기능을 제공합니다.
* API.ai\(Dialogue Flow\), Watson Conversation 과 연동 가능합니다.
* 반환 값은 아래와 같이 nlp 파라미터 안에 저장됩니다.

| 파라미터 | 자료형 | 설명 |
| :--- | :--- | :--- |
| nlp.intent | string | 의도 |
| nlp.entities | \[{entity: string, value: string, score: number}\] | 개체 |
| nlp.answer | string | 자동응답 답변 |
| nlp.score | number | 자동응답 정확도 |

