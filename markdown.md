# 헤더 크기 (h1)
## 헤더 크기 (h2)
### 헤더 크기 (h3)
#### 헤더 크기 (h4)
##### 헤더 크기 (h5)
###### 해더 크기 (h6)

### 리스트
Unordered
* Item 1
* Item 2
  * Item 2a
  * Item 2b
  
Ordered
1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b

### 이미지
첫번째 방법  
![Github logo](/images/markdown_logo.jpg)  
Format: ![이미지 alt명](url 링크)

두번째 방법  
<a href="#"><img src="https://github.com/..각자절대경로../images/markdown_syntax.jpg" width="400px" alt="sample image"></a>   
Format: img 태그 사용 - 이미지경로는 상대경로 or 절대경로   
   
### 하이퍼 링크
[GitHub](http://github.com "깃허브")

### 코드블록
```javascript
function test() {
 console.log("hello world!");
}
```

### 인용상자
As Grace Hopper said:

> I’ve always been more interested.  
> in the future than in the past.

### 강조
*This text will be italic*  
_This will also be italic_  

**This text will be bold**  
__This will also be bold__  

*You **can** combine them*  

### 테이블
First Header | Second Header
------------ | -------------
Content cell 1 | Content cell 2
Content column 1 | Content column 2

### 체크박스
- [x] this is a complete item  
- [ ] this is an incomplete item  
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported  
- [x] list syntax required (any unordered or ordered list supported) 

### 인라인 코드
문단 중간에 `Code`를 넣을 수 있습니다.  
예를 들어 `printf("hello world!");` 이런 식으로 들어갑니다.

### 수평선
---
***
___

### 탈출문자
\*literal asterisks\*  
*literal asterisks*  
__\*\*Text\*\*__  
_\_Tom\__ 

### 이모지
GitHub supports emoji!  
:+1: :sparkles: :camel: :tada:  
:rocket: :metal: :octocat:

### 배지
작성 예시
<img src="https://img.shields.io/badge/license-mit-green.svg">
https://img.shields.io/badge/<LABEL>-<MESSAGE>-<COLOR>.svg

APM:		/apm/l/:packageName.svg
AUR license:	/aur/license/:packageName.svg
