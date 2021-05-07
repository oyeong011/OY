개요
====

모로가도 이것만 보면 너도 ***MARKDOWN GOSU!***
# 1) 제목
>제목을 만들려면 #을 사용하여서 만들수 있음

> ### ex)
```
Markdown	                  HTML	
# Heading level 1	    <h1>Heading level 1</h1>	

## Heading level 2	    <h2>Heading level 2</h2>	

### Heading level 3	    <h3>Heading level 3</h3>	

#### Heading level 4	<h4>Heading level 4</h4>	

##### Heading level 5	<h5>Heading level 5</h5>	

###### Heading level 6	<h6>Heading level 6</h6>	


```
# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

#### #의 개수에 따라서 제목크기가 커짐 +++#을 붙여서 사용하면 크기추가가 안됨! 샵은 띄워쓰기
#### 또한 =와 -를 제목을 적고 그밑에 배치를 함으로써 제목크기 변형 가능 
```
Markdown	                HTML	
Heading level 1       <h1>Heading level 1</h1>
===============		

Heading level 2       <h2>Heading level 2</h2>
---------------		

```
Heading level 1      
===============
Heading level 2    
---------------

# 2) 단락
단락을 만들려면 빈 줄을 사용하여 하나 이상의 텍스트 줄을 분리합니다.또는 *p*를 이용해서 나눌 수 있음
> ### ex)
```
Markdown	                                     
I really like using Markdown.

I think I'll use it to format all of my documents from now on.	



HTML
<p>I really like using Markdown.</p>
<p>I think I'll use it to format all of my documents from now on.</p>	
```
I really like using Markdown.

I think I'll use it to format all of my documents from now on.


### 글쓰고 엔터 두번 다시 글쓰기


# 3) 줄 끊기
선 나누기()를 만들려면 ***두 개 이상의 공백***으로 선을 끝내고 반환을 입력합니다 

### backspace 2번 또는 ***br을 이용***

> ### ex)
```
Markdown		
This is the first line.  
And this is the second line.	

HTML

<p>This is the first line.<br>
And this is the second line.</p>	

```
This is the first line.  
And this is the second line.
# 4) 강조


## 1)) BOLD
BOLD를 하고 싶으면 하고싶은 양쪽에 **별표** 두개 혹은 __밑줄__ 두개를 치면 됨
### ** 또는 __
#### 1))) 어지간하면 별표사용
> ### EX)
```
Markdown	                                    HTML

I just love **bold text**.	  I just love <strong>bold text</strong>.	

I just love __bold text__.	  I just love <strong>bold text</strong>.	

Love**is**bold	Love                <strong>is</strong>bold	
```

## 2)) 이태릭체
텍스트 하나에 별표하나 또는 밑줄하나 추가하기
### 어지간하면 별표사용
### EX)

```

Markdown	                                               HTML

Italicized text is the *cat's meow*.	Italicized text is the <em>cat's meow</em>.	

Italicized text is the _cat's meow_.	Italicized text is the <em>cat's meow</em>.	

A*cat*meow	                                        A<em>cat</em>meow	
```

## 3))  BOLD and 이태릭
BOLD와 이태릭체를 하고싶으면 ***별표 세개*** 하기
# ***
### EX)
```
            Markdown	                                          HTML

This text is ***really important***.	This text is <strong><em>really important</em></strong>.	

This text is ___really important___.	This text is <strong><em>really important</em></strong>.	

This text is __*really important*__.	This text is <strong><em>really important</em></strong>.	.

This text is **_really important_**.	This text is <strong><em>really important</em></strong>.	

This is really***very***important text.	This is really<strong><em>very</em></strong>important text.	
```

# 5) 블록 따옴표
블록따옴표를 만들려면 단락 앞에 블록을 추가. 
# >
### EX)

```
> Dorothy followed her through many of the beautiful rooms in her castle.
```
> Dorothy followed her through many of the beautiful rooms in her castle.

## 1)) 여러 단락의 차단
블록 따옴표에는 여러 단락이 포함될 수 있습니다. 단락 사이에 빈 줄에 추가합니다.
### ex)
```
> Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.
```
> Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.


## 2)) 중첩 된 블록 따옴표
블록 따옴표를 중첩 할 수 있습니다. 중첩할 단락 앞에 추가합니다.
### >>
### EX)
```
> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.
```
> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.
## 3)) 다른 요소와 블록 따옴표
블록 따옴표는 다른 요소들 #같은 *같은 것들이랑 같이 쓸수있음
### EX)
```
> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
>  *Everything* is going according to **plan**.
```
> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
>  *Everything* is going according to **plan**.

# 6) 목록
항목을 정렬된 목록과 주문되지 않은 목록으로 구성할 수 있습니다.

* ## order list
숫자와 함께 줄 항목과 마침표뒤에 추가 숫자는 숫자 순서로 있을 필요는 없지만   
목록은 숫자 ***1***로 시작해야함.
### EX)
```
1. Markdown	

1. First item
2. Second item
3. Third item
4. Fourth item	

1. HTML

<ol>
  <li>First item</li>
  <li>Second item</li>
  <li>Third item</li>
  <li>Fourth item</li>
</ol>

2. Markdown	

1. First item
1. Second item
1. Third item
1. Fourth item	

2. HTML

<ol>
  <li>First item</li>
  <li>Second item</li>
  <li>Third item</li>
  <li>Fourth item</li>
</ol>

3. Markdown

1. First item
8. Second item
3. Third item
5. Fourth item	

3. HTML

<ol>
  <li>First item</li>
  <li>Second item</li>
  <li>Third item</li>
  <li>Fourth item</li>
</ol>

4. Markdown

1. First item
2. Second item
3. Third item
    1. Indented item
    2. Indented item
4. Fourth item

4. HTML

<ol>
  <li>First item</li>
  <li>Second item</li>
  <li>Third item
<ol>
  <li>Indented item</li>
  <li>Indented item</li>
</ol>
</li>
  <li>Fourth item</li>
</ol>
```
> 실행결과 동일

1. First item
2. Second item
3. Third item
4. Fourth item

* ## disorder list
정렬되지 않은 목록을 만들려면 광고 항목 앞에 대시(대시), 별표(또는 표지판)를 추가합니다. 중첩된 목록을 만들 수 있는 하나 이상의 항목을 들여쓰기합니다.
1. # - 
1. # *
1. # +

### EX)
```
1. Markdown

- First item
- Second item
- Third item
- Fourth item	

1. HTML	

<ul>
  <li>First item</li>
  <li>Second item</li>
  <li>Third item</li>
  <li>Fourth item</li>
</ul>

2. Markdown

* First item
* Second item
* Third item
* Fourth item	

2. HTML

<ul>
  <li>First item</li>
  <li>Second item</li>
  <li>Third item</li>
  <li>Fourth item</li>
</ul>	

3. Markdown

+ First item
+ Second item
+ Third item
+ Fourth item	

3. HTML

<ul>
  <li>First item</li>
  <li>Second item</li>
  <li>Third item</li>
  <li>Fourth item</li>
</ul>

4. Markdown

- First item
- Second item
- Third item
    - Indented item
    - Indented item
- Fourth item	

4. HTML

<ul>
  <li>First item</li>
  <li>Second item</li>
  <li>Third item
<ul>
  <li>Indented item</li>
  <li>Indented item</li>
</ul>
</li>
  <li>Fourth item</li>
</ul>
```
* ##  목록에 요소 추가
목록에 다른 요소를 추가 하고싶으면 탭이나 띄어쓰기 네번

### 엔터 또는 띄어쓰기 네번

# 7) 코드
단어 나 구를 코드로 나타내려면 백틱에 동봉하십시오.`
> ## '
### EX)
```
Markdown

At the command prompt, type `nano`.	

HTML	

At the command prompt, type <code>nano</code>.
```

Markdown	Html	렌더링된 출력
At the command prompt, type `nano`.	At the command prompt, type <code>nano</code>.	명령 프롬프트에서 .nano
* ## 백틱 탈출
코드로 나타내려는 단어 나 문구에 하나 이상의 백틱이 포함되어 있는 경우 단어 또는 구를 이중 백틱()으로 둘러싸서 탈출할 수 있습니다.
> ## ``

### EX)
```
Markdown

``Use `code` in your Markdown file.``	

HTML

<code>Use `code` in your Markdown file.</code>
```

* ## 코드 블록
코드 블록을 만들려면 블록의 모든 줄을 적어도 4개의 공백 또는 하나의 탭으로 들여쓰기합니다.

### EX)
```
    <html>
      <head>
      </head>
    </html>
```
 참고: 라인을 들여쓰지 않고 코드 블록을 만들려면 울타리가 있는 코드 블록을사용합니다.

# 8) horizontal rules
수평 규칙을 만들려면 선에 3개 이상의 별표(), 대시(또는 밑줄)를 사용
### EX)
```
***

---

_________________
```

# 9) 링크
링크를 만들려면 링크 텍스트를 괄호(예:)로 둘러본 다음 괄호안에 있는 URL(예:)으로 바로 따르십시오.[링크 제목](https://google.com)
> ##### [하이퍼링크]+(사이트주소)
### EX)
```
My favorite search engine is [Duck Duck Go](https://duckduckgo.com).
```
* ## 타이틀 추가
>[]을 이용해서 하이퍼링크 제목을 정할수있음
### EX)
```
My favorite search engine is [Duck Duck Go](https://duckduckgo.com "The best search engine for privacy").
```

* ## URL 및 이메일 주소
>URL 또는 이메일 주소를 링크로 빠르게 바꾸려면 <링크> 사용
> ## <>
### EX)
```
<https://www.markdownguide.org>
<fake@example.com>
```

