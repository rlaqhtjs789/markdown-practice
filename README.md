# 제목(Header)

# 제목 1
## 제목 2
### 제목 3




# 문장(Paragraph)
띄어쓰기 두번하면 줄바꿈  
동해물과 백두산이 마르고 닳도록   
하느님이 보우하사 우리나라 만세  

# 줄바꿈(Line Breakds)
동해물과 백두산이 마르고 닳도록  
동해물과 백두산이 마르고 닳도록  
동해물과 백두산이 마르고 닳도록<br />
동해물과 백두산이 마르고 닳도록  


# 강조(Emphasis)

_이텔릭_

**두껍게**  
**_이텔릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</U> 그닥 권장은 안함


# 목록(List)
**ol태그**
1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록

(들여쓰기 두번)
1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록
1. 순서가 필요한 목록

**li태그**
- 순서가 필요없는 목록
- 순서가 필요없는 목록
    - 순서가 필요없는 목록
    - 순서가 필요없는 목록
    - 순서가 필요없는 목록
- 순서가 필요없는 목록
- 순서가 필요없는 목록


# 링크(Links//a태그)

<a href = "https://google.com">Goggle</a>

[Goggle](https://google.com)

<a href = "https://google.com" title ="구글로 이동">Goggle</a>

[Goggle](https://google.com "구글로이동")

<a href = "https://google.com" title ="구글로 이동" target='_blank'>Goggle</a>



# 이미지(img)

![HEROPY](https://www.louisvuitton.com/images/M41487_PM2_Front%20view.jpg)  

느낌표만 추가하면됨 // a태그 표기법과 다른점.

[![HEROPY](https://www.louisvuitton.com/images/M41487_PM2_Front%20view.jpg)](https://google.com)  

이미지에 링크를 넣고 싶을때는 [이미지표기법](링크) 


# 인용문(BlockQuote)
인용문은 > 문장  
인용문 중첩시 > 개수를 늘린다

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> (네이버 국어 사전)
>> 네이버
>>>네이버
>>>>네이버
  

# 인라인(inline)코드 강조
CSS에서 `background` 혹은  
`background-image` 속성으로 요소에 배경  
이미지를 삽입할 수 있습니다.  

▶︎ 맥북에서 백틱은 옵션키 + ₩ 키같이
▶︎ 윈도우는 백스페이스키 밑에 있음



# 블록(Block)코드 강조

```html
<a href = "https://google.com" title ="구글로 이동" target='_blank'>Goggle</a>
```  

```javascript
function func(){
    var a = 'aaaa';
    return a;
}
```

```bash
$ git commit -m 'study'
```

```plaintext
   동해물과 백두산이 마르고 닳고록  
   하느님이 보우하사 우리나라 만세
```


코드를 그대로 출력할시 위의 표현처럼 하면 가능.  
(javascript, html, bash/터미널, plaintext/그냥글 등..)



# 표(table)

position 속성

값 | 의미 | 기본값  
--|:--:|--:
static | 기준 없음 | O  
relative | 요소 자신 | X  
absolute | 위치 상 부모요소 | X  
fixed | 뷰포트 | X  



# 원시 HTML(Raw HTML)

동해물과 <sapn style="text-decoration: underline;">백두산</sapn>이 마르고 닳고록 <br/>
하느님이 보우하사 우리나라 만세

<a href = "https://google.com" title ="구글로 이동" target='_blank'>Goggle</a>

<img style="width: 70px;" src="https://www.louisvuitton.com/images/M41487_PM2_Front%20view.jpg">


# 수평선(Horizontal Rule)

--- 

***

___