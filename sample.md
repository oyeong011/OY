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