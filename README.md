# 마크다운 Markdown

## 1. 헤더 

# 헤더 크기(h1)
## 헤더 크기(h2)
### 헤더 크기(h3)
#### 헤더 크기(h4)
##### 헤더 크기(h5)
###### 헤더 크기(h6)

## 2. Unordered
* Item 1
* Item 2
  * Item 2a
  * Item 2b
  
## 3. Ordered
1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b

## 4. 문단 구분
문장을 작성한다.(공백 없음)
빈 줄이 없으면 자동으로 앞의 문장 뒤에 붙는다.(Space Bar를 두 번 이상 눌러 띄어쓰기 함)  
위 문장에서 두 칸의 공백을 두어 강제 개행한다.

## 5. 이미지 삽입
* 방법1  
느낌표[이미지 alt명](url 링크) 사용: **상대경로** 또는 **절대경로** 가능  
![Github logo](/images/frog.jpg)  

* 방법2  
img 태그 사용: **상대경로** 또는 **절대경로** 가능
<img src="/images/deerdog.jpg" width="300px" height="300px" title="px지정" alt="deerdog">  

## 6. 하이퍼링크
* [Github](http://github.com"깃허브")  
* 외부링크: <http://example.com/>  
* 이메일링크: address@example.com

## 7. 코드블록
```
public class BootSpringBootApplication {  
 public static void main(String[] args){  
  System.out.println("Hello World");  
 }  
}  
```

## 8. 인용상자
As Grace Hopper said:

> I've always been more interested.  
> in the future than in the past.  

> 눈 뜨면 좋은 생각을 할 것  
>> 시작하기 전에 걱정하지 말 것  
>>> 나에게도 남에게도  
>>>> 예쁜 말을 많이 해줄 것

## 9. 강조
*This text will be italic*  
_This text will be italic_  

**This text will be bold**  
__This will also be bold__  

*You **can** combine them*  

## 10. 테이블
First Header | Second Header  
-------------- | ----------------  
Content cell 1 | Content cell 2  
Content column1 | Content colimn2  

## 11. 체크박스
- [x] this is a acomplete item  
- [ ] this is an incomplete item
- [x] @emntions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)

## 12. 인라인 
문단 중간에 `Code`를 넣을 수 있다.  
예를 들어 `printf("hello world");` 이런 식으로 들어간다.

## 13. 수평선
---  
***  
___  

## 14. 탈출문자
\*literal asterisks\*  
*literal asterisks*  
__\*\*Text\*\*__  
_\_Tom\__

## 15. 이모지
* 이모지 참고 사이트 : [http://emoji-cheat-sheet.com](http://emoji-cheat-sheet.com)  
GitHub supports emoji!  
:+1: :sparkles: :camel: :tada:
:rocket: :metal: :octocat: :clap:

## 16. 배지 만들기
* 사이트 : [https://shields.io/](https://shields.io/)  
* 직접 만든 나의 배지 <img src="https://img.shields.io/badge/license-esks-yellow">

