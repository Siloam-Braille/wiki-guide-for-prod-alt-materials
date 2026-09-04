# 형식 검사

{% hint style="info" %}
엑셀 검사 도구 활용

(파일 링크 추가?)
{% endhint %}



{% stepper %}
{% step %}
### 레벨 및 페이지

* 차례(목차)와 본문의 레벨/페이지 일치 여부
* 부제목 처리
* 코드 위·아래 빈줄 (없어야 함)

{% tabs %}
{% tab title="코드 앞 빈줄 찾기" %}
```
^n^n@@
```
{% endtab %}

{% tab title="코드 뒤 빈줄 찾기" %}
```
@@[^ ]+^n^n
```
{% endtab %}
{% endtabs %}
{% endstep %}

{% step %}
### 시각자료

* 시작/끝
* 코드
  * `@@t` 개수 = `t@@` 개수
  * `@@i` 개수 = \[파일]-\[문서 정보]-\[그림 정보]의 그림 개수
* 본문 언급과 명칭 일치 여부
{% endstep %}

{% step %}
### 유니코드

* 사용할 수 없는 유니코드
* 의미상 적절한 유니코드

{% tabs %}
{% tab title="줄 처음 빈칸 찾기" %}
```
^n\b+
```
{% endtab %}

{% tab title="줄 끝 빈칸 찾기" %}
```
\b+^n
```
{% endtab %}
{% endtabs %}

{% tabs %}
{% tab title="마침표 앞 빈칸 찾기" %}
마침표(.), 물음표(?), 느낌표(!)

```
\b+[\.?!]+
```
{% endtab %}

{% tab title="단어 앞·사이 마침표 찾기" %}
마침표(.), 물음표(?), 느낌표(!)

```
\w?[\.?!]+\w
```
{% endtab %}
{% endtabs %}

{% tabs %}
{% tab title="특수기호 찾기" %}
제외 범위

* ASCII: 띄어쓰기(U+0020)부터 물결표(U+007E)까지
* 한글: ‘가’(U+AC00)부터 ‘힣’(U+D7A3)까지

```
[^ -~가-힣]+
```
{% endtab %}

{% tab title="기타 조판 부호 찾기" %}
탭(t), 줄바꿈(l), 고정폭 빈칸(s), 묶음 빈칸(r)

```
[^t^l^s^r]+
```
{% endtab %}

{% tab title="비방향성 따옴표 찾기" %}
```
['"]+
```
{% endtab %}

{% tab title="모든 한자 찾기" %}
```
[一-龥㐀-䶵豈-龎]+
```
{% endtab %}
{% endtabs %}
{% endstep %}

{% step %}
### 묶음표




{% endstep %}
{% endstepper %}

