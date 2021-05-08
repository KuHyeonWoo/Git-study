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

## 5. 인용구
단락 앞에 >를 추가하십시오

    > Dorothy followed her through many of the beautiful rooms in her castle.

출력 결과는 다음과 같습니다.

> Dorothy followed her through many of the beautiful rooms in her castle.

### 여러 단락이 있는 인용구
인용구는 여러 단락을 포함 할 수 있습니다. 단락 사이의 빈 줄에 >를 추가합니다.

    > Dorothy followed her through many of the beautiful rooms in her castle.
    >
    > The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

출력 결과는 다음과 같습니다.

> Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

### 중첩 인용구
인용구는 중첩 될 수 있습니다. 중첩하려는 단락 앞에 >>를 추가하십시오.

    > Dorothy followed her through many of the beautiful rooms in her castle.
    >
    >> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.
    end

출력 결과는 다음과 같습니다.

> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

### 다른 요소와 인용구
인용구는 다른 마크 다운 형식의 요소를 포함 할 수 있습니다. 모든 요소를 ​​사용할 수 있는 것은 아닙니다. 어떤 요소가 작동하는지 확인하기 위해 실험해야합니다.

    > #### The quarterly results look great!  
    >  
    > - Revenue was off the chart.  
    > - Profits were higher than ever.  
    >  
    >  *Everything* is going according to **plan**.

출력결과는 다음과 같습니다.

> #### The quarterly results look great!  
>  
> - Revenue was off the chart.  
> - Profits were higher than ever.  
>  
>  *Everything* is going according to **plan**.

___

## 6. 목록
항목을 순서있는 또는 순서없는 목록으로 구성할 수 있습니다.

### 순서있는 목록
숫자 뒤에 마침표가 있는 항목을 추가합니다. 숫자는 숫자 순서일 필요는 없지만 목록은 숫자 1로 시작해야합니다.

    1. First item
    2. Second item
    8. Third item
    4. Fourth item
    
>1. First item
>2. Second item
>3. Third item
>4. Fourth item

    1. First item
    2. Second item
    3. Third item
        1. Indented item
        2. Indented item
    4. Fourth item

>1. First item
>2. Second item
>3. Third item
>    1. Indented item
>    2. Indented item
>4. Fourth item

### 순서없는 목록
항목 앞에 대시(-), 별표(*) 또는 더하기 기호(+)를 추가합니다. 중첩된 목록을 만들려면 하나 이상의 항목을 들여 씁니다.

    * First item
    * Second item
    * Third item
    * Fourth item
    
>* First item
>* Second item
>* Third item
>* Fourth item

    - First item
    - Second item
    - Third item
        - Indented item
        - Indented item
    - Fourth item

>- First item
>- Second item
>- Third item
>    - Indented item
>    - Indented item
>- Fourth item



### 목록에 요소 추가
목록의 연속성을 유지하면서 목록에 다른 요소를 추가하려면 다음 예와 같이 요소를 공백 4개 또는 탭 1개로 들여 쓰십시오.

#### a. 단락
    *   This is the first list item.
    *   Here's the second list item.

        I need to add another paragraph below the second list item.

    *   And here's the third list item.

>*   This is the first list item.
>*   Here's the second list item.
>
>   I need to add another paragraph below the second list item.
>
>*   And here's the third list item.

#### b. 인용구
    *   This is the first list item.
    *   Here's the second list item.

        > A blockquote would look great below the second list item.

    *   And here's the third list item.

>*   This is the first list item.
>*   Here's the second list item.
>
>    > A blockquote would look great below the second list item.
>
>*   And here's the third list item.

#### c. 코드 블록
코드 블록은 일반적으로 공백 4개 또는 탭 1개로 들여 쓰기됩니다. 목록에 있으면 공백 8개 또는 탭 2개를 들여 씁니다.

    1.  Open the file.
    2.  Find the following code block on line 21:

            <html>
              <head>
                <title>Test</title>
              </head>

    3.  Update the title to match the name of your website.

출력 결과는 다음과 같습니다.

1.  Open the file.
2.  Find the following code block on line 21:

        <html>
            <head>
            <title>Test</title>
            </head>

3.  Update the title to match the name of your website.

#### d. 이미지
    1.  Open the file containing the Linux mascot.
    2.  Marvel at its beauty.

        ![Tux, the Linux mascot](/assets/images/tux.png)

    3.  Close the file.

>1.  Open the file containing the Linux mascot.
>2.  Marvel at its beauty.
>
>    ![Tux, the Linux mascot](/assets/images/tux.png)
>
>3.  Close the file.

#### e. 목록
순서없는 목록을 순서있는 목록에 중첩하거나 그 반대로 할 수 있습니다.

    1. First item
    2. Second item
    3. Third item
        - Indented item
        - Indented item
    4. Fourth item

>1. First item
>2. Second item
>3. Third item
>    - Indented item
>    - Indented item
>4. Fourth item

___

## 7. 코드
단어나 구를 코드로 표시하려면 백틱(\`)으로 묶습니다.

    At the command prompt, type `nano`.


>At the command prompt, type `nano`.

### 백틱탈출
코드로 표시하려는 단어나 구에 하나 이상의 백틱이 포함되어있는 경우 단어나 구를 이중 백틱(\``)으로 묶어 이스케이프 할 수 있습니다.

    ``Use `code` in your Markdown file.``

>``Use `code` in your Markdown file.``

### 코드 블록
코드 블록을 만들려면 블록의 모든 줄을 최소 4개의 공백 또는 1개의 탭으로 들여 쓰십시오.

        <html>
          <head>
          </head>
        </html>

출력 결과는 다음과 같습니다.

    <html>
      <head>
      </head>
    </html>
___

## 8. 수평선
수평선을 만들려면 3개 이상의 별표(***), 대시(---) 또는 밑줄(___)을 한 줄에 단독으로 사용하십시오. 호환성을 위해 수평선 앞뒤에 빈 줄을 넣으십시오.

    ***

    ---

    ________

세 가지 모두의 렌더링된 출력은 동일하게 보입니다.

___

## 9. 링크
링크를 만들려면 링크 텍스트를 대괄호로 묶은 다음(예 : [Duck Duck Go]) 바로 뒤에 URL을 괄호로 묶습니다 (예 : (https://duckduckgo.com)). 마크 다운 애플리케이션은 URL 중간에 공백을 처리하는 방법에 동의하지 않습니다. 호환성을 위해 공백대신 %20을 씁니다.

    My favorite search engine is [Duck Duck Go](https://duckduckgo.com).

>My favorite search engine is [Duck Duck Go](https://duckduckgo.com).  

### 제목 추가
선택적으로 링크 제목을 추가 할 수 있습니다. 사용자가 링크 위로 마우스를 가져 가면 도구 설명(tooltip)으로 표시됩니다. 제목을 추가하려면 괄호 안 URL 뒤에 넣습니다.

    My favorite search engine is [Duck Duck Go](https://duckduckgo.com "The best search engine for privacy").

>My favorite search engine is [Duck Duck Go](https://duckduckgo.com "The best search engine for privacy").

### URL 및 이메일 주소
URL 또는 이메일 주소를 링크로 빠르게 전환하려면 꺾쇠 괄호로 묶습니다.

    <https://www.markdownguide.org>
    <fake@example.com>

><https://www.markdownguide.org>  
><fake@example.com>

### 링크 서식 지정
링크를 강조하려면 괄호와 괄호 앞뒤에 별표를 추가하십시오. 링크를 코드로 표시하려면 괄호 안에 백틱을 추가하세요.

    I love supporting the **[EFF](https://eff.org)**.
    This is the *[Markdown Guide](https://www.markdownguide.org)*.
    See the section on [`code`](#code).

>I love supporting the **[EFF](https://eff.org)**.  
>This is the *[Markdown Guide](https://www.markdownguide.org)*.  
>See the section on [`code`](#code).

### 참조 스타일 링크
참조 스타일 링크는 두 부분으로 구성됩니다. 텍스트를 인라인으로 두는 부분과 텍스트를 쉽게 읽을 수 있도록 파일의 다른 곳에 저장하는 부분입니다.

#### a. 링크의 첫 번째 부분 서식 지정
참조 스타일 링크의 첫 번째 부분은 두 세트의 대괄호로 이루어집니다. 첫 번째 대괄호 세트에는 링크된 것으로 표시되어야하는 텍스트가 들어갑니다. 두 번째 대괄호 세트는 (문서의 다른 곳에 저장되는 링크를 가리키는) 레이블을 표시합니다.

필수는 아니지만 첫 번째와 두 번째 대괄호 세트 사이에 공백을 포함할 수 있습니다. 두 번째 대괄호 세트의 레이블은 대소 문자를 구분하지 않으며 문자, 숫자, 공백 또는 구두점을 포함 할 수 있습니다.

    [hobbit-hole][1]
    [hobbit-hole] [1]

#### b. 링크의 두 번째 부분 서식 지정
참조 스타일 링크의 두 번째 부분은 다음 세 파트로 구성됩니다.

1. 괄호로 묶인 레이블. 바로 뒤에 콜론과 하나 이상의 공백이옵니다(예: [label]: ).
2. 링크의 URL. 선택적으로 꺾쇠 괄호로 묶을 수 있습니다.
3. 링크의 선택적 제목. 큰따옴표, 작은따옴표 또는 괄호로 묶습니다.

이 링크의 두 번째 부분은 마크 다운 문서의 아무 곳에나 배치할 수 있습니다. (예: 미주 또는 각주).

    [1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle
    [1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle 'Hobbit lifestyles'
    [1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle (Hobbit lifestyles)
    [1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> 'Hobbit lifestyles'
    [1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> (Hobbit lifestyles)

___

## 10. 이미지
이미지를 추가하려면 느낌표(!), 대괄호로 둘러싸인 대체 텍스트, 괄호로 둘러싸인 이미지의 경로 또는 URL을 추가합니다. 선택적으로 URL 뒤에 괄호로 둘러싸인 제목을 추가할 수 있습니다.

    ![Philadelphia's Magic Gardens. This place was so cool!](/assets/images/philly-magic-gardens.jpg "Philadelphia's Magic Gardens")

출력 결과는 다음과 같습니다.

![Philadelphia's Magic Gardens. This place was so cool!](philly-magic-garden.jpg "Philadelphia's Magic Gardens")

### 이미지 연결
이미지에 링크를 추가하려면 이미지의 마크다운을 대괄호로 묶은 다음 링크를 괄호로 추가합니다.

    [![Philadelphia's Magic Gardens. This place was so cool!](philly-magic-garden.jpg "Philadelphia's Magic Gardens")](https://www.flickr.com/photos/beaurogers/31833779864/in/photolist-Qv3rFw-34mt9F-a9Cmfy-5Ha3Zi-9msKdv-o3hgjr-hWpUte-4WMsJ1-KUQ8N-deshUb-vssBD-6CQci6-8AFCiD-zsJWT-nNfsgB-dPDwZJ-bn9JGn-5HtSXY-6CUhAL-a4UTXB-ugPum-KUPSo-fBLNm-6CUmpy-4WMsc9-8a7D3T-83KJev-6CQ2bK-nNusHJ-a78rQH-nw3NvT-7aq2qf-8wwBso-3nNceh-ugSKP-4mh4kh-bbeeqH-a7biME-q3PtTf-brFpgb-cg38zw-bXMZc-nJPELD-f58Lmo-bXMYG-bz8AAi-bxNtNT-bXMYi-bXMY6-bXMYv)

출력 결과는 다음과 같습니다.

[![Philadelphia's Magic Gardens. This place was so cool!](philly-magic-garden.jpg "Philadelphia's Magic Gardens")](https://www.flickr.com/photos/beaurogers/31833779864/in/photolist-Qv3rFw-34mt9F-a9Cmfy-5Ha3Zi-9msKdv-o3hgjr-hWpUte-4WMsJ1-KUQ8N-deshUb-vssBD-6CQci6-8AFCiD-zsJWT-nNfsgB-dPDwZJ-bn9JGn-5HtSXY-6CUhAL-a4UTXB-ugPum-KUPSo-fBLNm-6CUmpy-4WMsc9-8a7D3T-83KJev-6CQ2bK-nNusHJ-a78rQH-nw3NvT-7aq2qf-8wwBso-3nNceh-ugSKP-4mh4kh-bbeeqH-a7biME-q3PtTf-brFpgb-cg38zw-bXMZc-nJPELD-f58Lmo-bXMYG-bz8AAi-bxNtNT-bXMYi-bXMY6-bXMYv)
___

## 11. 이스케이프 문자

### 이스케이프 할 수 있는 문자

백슬래시를 사용하여 다음 문자를 이스케이프 할 수 있습니다.

    \   백슬래시
    `   백틱
    *   별표
    _   밑줄
    {}  중괄호
    []  대괄호
    <>  꺾쇠 괄호
    ()  괄호
    #   샵
    +   더하기 기호
    -   빼기 기호
    .   마침표
    !   느낌표
    |   파이프

___

## 12. HTML

## 13. 확장 구문 링크
<https://github.com/KuHyeonWoo/GFM-study/blob/main/README.md>