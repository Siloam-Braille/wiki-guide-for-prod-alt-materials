# 기본 서지 및 제작 정보

{% stepper %}
{% step %}
### [국립중앙도서관](https://www.nl.go.kr/)에서 ISBN 검색

서명, 저자, 발행처, 발행일 등 서지정보 확인

{% hint style="warning" %}
e-book 자료를 참조하지 않도록 주의
{% endhint %}
{% endstep %}

{% step %}
### 필수 항목 유무 및 위치 확인

* 서명, 저자, 발행처
* 표지
* (앞날개, 표지 이면)
* 판권지
  * 해당 페이지의 페이지코드 직후
  * 판권지가 뒤표지에 있다면 판권지 내용 전체를 `@@[뒤표지` 앞으로 당겨오기
* (뒤표지 이면, 뒷날개)
* 뒤표지

{% hint style="info" %}
조건식 `^@@\[(서명)|(저자)|(발행처)|(뒤?표지( 이면)?)|([앞뒷]날개)|(판권지)`로 검색
{% endhint %}


{% endstep %}
{% endstepper %}

{% content-ref url="https://app.gitbook.com/s/0gRJ8Rz7jMKq9PZaOXvc/2/5" %}
[제5조(서지 및 제작 정보)](https://app.gitbook.com/s/0gRJ8Rz7jMKq9PZaOXvc/2/5)
{% endcontent-ref %}
