# 기본 구문

## 0. 목차

1. 제목
2. 단락
3. 줄 바꿈
4. 강조
5. 인용구
6. 목록
7. 코드
8. 수평선
9. 링크
10. 이미지
11. 이스케이프 문자
12. HTML
13. 확장 구문 링크

___

## 1. 제목
단어나 구 앞에 숫자 기호(#)를 추가합니다. 사용하는 숫자 기호의 수는 제목 레벨과 일치해야합니다. 호환성을 위해 항상 숫자 기호(#)와 제목 이름 사이에 공백을 두십시오.

    ### Heading Level 3

>### Heading Level 3

### 대체 구문
텍스트 아래 줄에 ==문자(제목 레벨 1) 또는 --문자(제목 레벨 2)를 원하는만큼 추가합니다.

    Heading Level 2  
    ---------------

> Heading Level 2
> ---------------

___

## 2. 단락
하나 이상의 빈 줄을 사용하여 텍스트를 구분합니다. 단락이 리스트 안에 있지 않는 한, 공백이나 탭으로 들여쓰기 하지 않습니다.

    I really like using Markdown.
    
    I think I'll use it to format all of my documents from now on.

> I really like using Markdown.
>
> I think I'll use it to format all of my documents from now on.
____

## 3. 줄 바꿈
두 개 이상의 공백으로 줄을 끝낸 다음 enter을 입력합니다.

    First line with two spaces after.  
    And the next line.

> First line with two spaces after.  
> And the next line.

### 대체 구문
거의 모든 Markdown 애플리케이션에서 지원하는 또 다른 옵션인 \<br>HTML 태그가 있습니다. 

    First line with the HTML tag after.<br>  
    And the next line.

>First line with the HTML tag after.<br>  
>And the next line.

호환성 문제로 권장하지 않는 두 가지 다른 옵션이 있습니다. CommonMark 및 기타 몇 가지 경량 마크업 언어에서는 줄 끝에 백슬래시(\\)를 입력해 줄바꿈 할 수 있습니다. 그리고 최소한 몇 개의 경량 마크업 언어는 줄 끝에 아무것도 필요하지 않습니다. 그냥 enter을 입력하면 줄 바꿈이 만들어집니다. 

    First line with a backslash after.\
    And the next line.

>First line with a backslash after.\
>And the next line.

___

## 4. 강조
텍스트를 굵게 하거나 기울임꼴로 만들어 강조할 수 있습니다.

### 굵게
단어 또는 구문 앞뒤에 두 개의 별표 또는 밑줄을 추가합니다. 단어 중간을 굵게 표현하려면 문자 주위에 공백없이 별표 두 개를 추가합니다.

    I just love **bold text**.  
    Love**is**bold

>I just love **bold text**.  
>Love**is**bold

### 기울임꼴
단어 또는 구문 앞뒤에 별표 또는 밑줄을 추가합니다. 단어 중간을 기울임 꼴로 표시하려면 문자 주위에 공백없이 별표 하나를 추가하십시오.

    Italicized text is the *cat's meow*.  
    A*cat*meow 

>Italicized text is the *cat's meow*.  
>A*cat*meow 

### 굵은 기울임꼴
단어 또는 구문 앞뒤에 별표 또는 밑줄 세 개를 추가합니다. 단어 중간을 굵은 기울임꼴로 표시하려면 문자 주위에 공백없이 별표 3 개를 추가합니다.

    This text is ***really important***.  
    This is really***very***important text.

>This text is ***really important***.  
>This is really***very***important text.

___