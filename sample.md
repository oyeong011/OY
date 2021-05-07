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

* ## 링크 서식 지정
> 링크 강조를 원하면 <> 양쪽에 별표를 쳐서 강조나 BOLD만들기
### EX)
```
I love supporting the **[EFF](https://eff.org)**.
This is the *[Markdown Guide](https://www.markdownguide.org)*.
See the section on [`code`](#code).
```

* ## 참조 스타일 링크
참조 스타일 링크는 마크다운에서 URL을 쉽게 표시하고 읽을 수 있는 특별한 종류의 링크입니다. 참조 스타일 링크는 텍스트와 인라인으로 유지하는 부분과 파일을 다른 곳에 저장하는 부분으로 텍스트를 읽기 쉽게 유지할 수 있습니다.

   ### 1)))) 링크의 첫 번째 부분 서식 지정
  참조 스타일 링크의 첫 번째 부분은 []로 서식합니다. 괄호의 첫 번째 집합은 연결된 것처럼 보이는 텍스트를 둘러싸고 있습니다. 두 번째 괄호 세트에는 문서의 다른 곳에 저장하는 링크를 가리키는 데 사용되는 레이블이 표시됩니다.

> ### [][]
### EX)
```
[hobbit-hole][1]
[hobbit-hole] [1]
```
필요는 없지만 첫 번째 와 두 번째 괄호 집합 사이에 공백을 포함할 수 있습니다. 두 번째 괄호 세트의 레이블은 대/소문자, 숫자, 공백 또는 문장 부호를 포함할 수 있습니다.
  ### 2)))) 링크의 두 번째 부분 서식

대괄호로 라벨이 곧바로 이어지며, 그 다음에는 결장과 하나 이상의 공간(예:)이 뒤따랐다.
> ### [label]:
링크의 URL은 선택적으로 <>에 동봉할 수 있습니다.
이중 따옴표, 단일 따옴표 또는 괄호에 동봉할 수 있는 링크의 선택적 제목입니다.
즉, 다음 예제 형식은 모두 링크의 두 번째 부분에 대해 거의 동일합니다.

> ### [번호] : (<)링크(>) {" , ' , ( 중하나} 제목 {", ' , ( 중 하나}
### EX)
```
[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle
[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit lifestyles"
[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle 'Hobbit lifestyles'
[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle (Hobbit lifestyles)
[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"
[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> 'Hobbit lifestyles'
[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> (Hobbit lifestyles)
```
* ## 부품을 함께 넣는 예
URL을 단락에 표준 URL 링크로 추가하면 Markdown에서 다음과 같다.

### EX)
```
In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends
of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to
eat: it was a [hobbit-hole][1], and that means comfort.

[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"
```

# 10) 이미지
이미지를 추가하려면 느낌표(), 괄호에 alt 텍스트, 괄호의 이미지 자산에 경로 또는 URL을 추가합니다. 괄호 안에 URL 이후에 선택적으로 제목을 추가할 수 있습니다.
> #### ![제목](사진이 있는 링크)

### EX)
```
![Philadelphia's Magic Gardens. This place was so cool!](/assets/images/philly-magic-gardens.jpg "Philadelphia's Magic Gardens")
```
![Philadelphia's Magic Gardens. This place was so cool!](/assets/images/philly-magic-gardens.jpg "Philadelphia's Magic Gardens")
## 1)) 이미지 연결
이미지에 링크를 추가하려면 괄호안에 있는 이미지의 Markdown을 둘러친 다음 괄호안에 링크를 추가합니다.
> #### ![제목](사진이 있는 링크)
```
![Philadelphia's Magic Gardens. This place was so cool!](/assets/images/philly-magic-gardens.jpg "Philadelphia's Magic Gardens")
```
![Philadelphia's Magic Gardens. This place was so cool!](philly-magic-garden.jpg "Philadelphia's Magic Gardens")
### EX)
```
[![An old rock in the desert](shiprock.jpg "Shiprock, New Mexico by Beau Rogers")](https://www.flickr.com/photos/beaurogers/31833779864/in/photolist-Qv3rFw-34mt9F-a9Cmfy-5Ha3Zi-9msKdv-o3hgjr-hWpUte-4WMsJ1-KUQ8N-deshUb-vssBD-6CQci6-8AFCiD-zsJWT-nNfsgB-dPDwZJ-bn9JGn-5HtSXY-6CUhAL-a4UTXB-ugPum-KUPSo-fBLNm-6CUmpy-4WMsc9-8a7D3T-83KJev-6CQ2bK-nNusHJ-a78rQH-nw3NvT-7aq2qf-8wwBso-3nNceh-ugSKP-4mh4kh-bbeeqH-a7biME-q3PtTf-brFpgb-cg38zw-bXMZc-nJPELD-f58Lmo-bXMYG-bz8AAi-bxNtNT-bXMYi-bXMY6-bXMYv)
```
[![An old rock in the desert](shiprock.jpg "Shiprock, New Mexico by Beau Rogers")](https://www.flickr.com/photos/beaurogers/31833779864/in/photolist-Qv3rFw-34mt9F-a9Cmfy-5Ha3Zi-9msKdv-o3hgjr-hWpUte-4WMsJ1-KUQ8N-deshUb-vssBD-6CQci6-8AFCiD-zsJWT-nNfsgB-dPDwZJ-bn9JGn-5HtSXY-6CUhAL-a4UTXB-ugPum-KUPSo-fBLNm-6CUmpy-4WMsc9-8a7D3T-83KJev-6CQ2bK-nNusHJ-a78rQH-nw3NvT-7aq2qf-8wwBso-3nNceh-ugSKP-4mh4kh-bbeeqH-a7biME-q3PtTf-brFpgb-cg38zw-bXMZc-nJPELD-f58Lmo-bXMYG-bz8AAi-bxNtNT-bXMYi-bXMY6-bXMYv)
# 11) 캐릭터 탈출
Markdown 문서에서 텍스트를 포맷하는 데 ***사용할 문자를 표시***하려면 문자 앞에 백슬래시(백슬래시)를 추가합니다.\
> ## \

탈출할 수 있는 캐릭터
* \	
* `	백틱(코드에서 백틱을 벗어나는 것 참조))
* \*
* _	
* { }
* [ ]
* < >
* ( )
* \#
* \+
* \-
* .	
* !	
* |

### EX)
```
\* Without the backslash, this would be a bullet in an unordered list.
```


https://github.com/oyeong011/SE-TASK