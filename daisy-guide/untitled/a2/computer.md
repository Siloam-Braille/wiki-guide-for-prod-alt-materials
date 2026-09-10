# 주제 : 컴퓨터 도서

1. 컴퓨터 도서의 코딩 입력은 원본에 나온 기호 외에 다른 기호는 넣지 않는다.



2. 코딩 기호 중 단위(예: kg), 마이너스 기호 등은 유니코드를 사용하지 않고 자판을 사용한다.



3. 코딩 내용 중 나오는 설명들은 컴퓨터 프로그래밍 언어와 주석 형태에 따라 다음과 같이 제작한다.
   1. 주석 기호 앞과 뒤는 한 칸을 띄어 쓰고, 위·아래 빈 줄은 주지 않는다.
   2. 주석 기호에서 `"`와 `'` 기호는 자판에서 영문키로 설정하고 입력한다.
   3. 블록주석의 경우 시작과 끝 기호는 주석내용과 줄바꿈 없이 한 줄에 입력하거나 줄바꿈하여 입력하여도 같은 효력을 가진다.

{% tabs %}
{% tab title="예 1" %}
{% code overflow="wrap" lineNumbers="true" expandable="true" %}
```java
/*
new Float:newpos[MAX_PLAYERS][3];
new Float:oldpos[MAX_PLAYERS][3];
new Text:gText[MAX_PLAYERS];
*/
```
{% endcode %}
{% endtab %}

{% tab title="예 2" %}
{% code overflow="wrap" lineNumbers="true" expandable="true" %}
```java
/* new Float:newpos[MAX_PLAYERS][3];
new Float:oldpos[MAX_PLAYERS][3];
new Text:gText[MAX_PLAYERS]; */
```
{% endcode %}
{% endtab %}
{% endtabs %}



<table data-search="false"><thead><tr><th>프로그래밍 언어</th><th>라인주석*</th><th>블록주석**</th><th width="338">예시</th></tr></thead><tbody><tr><td rowspan="2">JAVA, C, C++, C#</td><td rowspan="2"><code>// 주석내용</code></td><td rowspan="2"><code>/* 주석내용 */</code></td><td><code>GradeBook ( String ) : // GradeBook 클래스의 생성자입니다.</code></td></tr><tr><td><code>/*</code><br><code>new Float:newpos[MAX_PLAYERS][3];</code><br><code>new Float:oldpos[MAX_PLAYERS][3];</code><br><code>new Text:gText[MAX_PLAYERS];</code><br><code>*/</code></td></tr><tr><td rowspan="2">HTML, XML</td><td colspan="2"><code>&#x3C;!-- 주석내용 --\></code></td><td></td></tr><tr><td colspan="2"></td><td></td></tr><tr><td rowspan="2">파이썬(Python)</td><td rowspan="2"><code># 주석내용</code></td><td rowspan="2"><p><code>"""</code></p><p><code>주석내용</code><br><code>"""</code></p></td><td></td></tr><tr><td></td></tr><tr><td rowspan="2">CSS</td><td colspan="2"><code>/* 주석내용 */</code></td><td></td></tr><tr><td colspan="2"></td><td></td></tr><tr><td rowspan="2">비주얼 베이직</td><td colspan="2"><code>' 주석내용</code></td><td></td></tr><tr><td colspan="2"></td><td></td></tr><tr><td rowspan="2">어셈블리</td><td rowspan="2"><code>; 주석내용</code></td><td rowspan="2"><p><code>COMMENT!</code></p><p><code>주석내용</code><br><code>!</code></p></td><td></td></tr><tr><td></td></tr><tr><td rowspan="2">PHP</td><td rowspan="2"><p><code>// 주석내용</code></p><p>또는</p><p><code># 주석내용</code></p></td><td rowspan="2"><code>/* 주석내용 */</code></td><td></td></tr><tr><td></td></tr><tr><td rowspan="2">MS SQL</td><td rowspan="2"><code>-- 주석내용</code></td><td rowspan="2"><code>/* 주석내용 */</code></td><td></td></tr><tr><td></td></tr><tr><td rowspan="2">MySQL</td><td rowspan="2"><code># 주석내용</code></td><td rowspan="2"><code>/* 주석내용 */</code></td><td></td></tr><tr><td></td></tr></tbody></table>

\* 라인주석: 줄바꿈 없이 한 줄

\*\* 블록주석: 줄바꿈이 2줄 이상



(예) 탭1



4. 파이썬, 하스켈, occam과 같은 프로그래밍 언어에서는 C나 자바와 같은 중괄호(‘`{`’, ‘`}`’)를 사용하여 범위를 지정하지 않고 들여쓰기를 사용하여 범위를 지정하므로 다음과 같이 제작한다.
   1. 원본자료에서 들여쓰기 칸수를 제시한 경우에는 원본자료를 따른다.
   2. 들여쓰기 칸수를 제시하지 않은 경우에는 묵자에서 보이는 공백 길이와 상관없이 들여쓰기의 깊이가 1단계일 때는 2칸, 2단계일 때는 4칸, 단계가 증가할수록 2칸씩 증가한다.
   3. 제작자 주를 사용하여 들여쓰기 표시 방법을 고지한다.

> \[예]
>
> {% code overflow="wrap" lineNumbers="true" expandable="true" %}
> ```
> * 제작자 주: 파이썬 언어의 들여쓰기는 @빈칸+숫자@로 표기하였음.
> ```
> {% endcode %}

(예) 탭2



5. 코딩 내용 중 결과값이 표 형태로 출력된 경우에는 다음과 같이 제작한다.
   1. 납본 파일의 경우에는 표 선은 그대로 복사하여 사용하고 셀과 셀 사이는 두 칸 띄어 구분한다.
   2. 스캔 파일의 경우에는 표 선은 생략하고 셀과 셀 사이는 두 칸 띄어 구분한다.
   3. 빈 셀은 붙임표 두 개(`--`)로 표기한다.



(예) 탭1: 방법2 / 탭2
