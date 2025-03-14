<p>해당 문서는 markdown viewer 확장프로그램을 보유하고 있는 기준으로 작성하였습니다.</p>
<p>HTML에 마크다운으로 하려고 했는데 잘 안돼서요 ㅠㅠ</p>
<p>그냥 보셔도 괜찮지만 키고 보시면 좀 깔끔합니다.</p>
<br/>


# 마크다운 문법

## 개요

마크다운 문법은 2004년에 만들어졌다.  
특수기호와 문자를 이용한 간단한 문법으로 쉽게 읽고 쓸 수 있고 HTML로 변환이 가능하다.  
왜 배우는가에 대해서 알아보았는데, 깃헙에 README.md 파일을 보다 높은 가독성으로 작성하기 위해 사용한다고 한다.

## 장단점

- **장점**: 간결하고 툴이 따로 필요 없으며 형태가 많고, 텍스트라 용량이 적으며 버전 관리도 가능하다.  
- **단점**: 표준이 없어 툴에 따라 다양하며, 복잡한 마크업은 사용할 수 없다.

## 헤더

글머리는 1~6까지만 있다.  
문서 제목을 표기할 때는 하단에 `=`과 `-`를 3개 이상 달아서 큰 제목과 작은 제목을 표시한다.  
`*`와 `-`를 3개 이상 이어서 작성하면 수평선으로 인식하며, 문단 구분을 할 수 있다.  
또한 기호 `>`와 `>>`로 블록 설정을 해줄 수 있고, 이 안에서도 다른 마크다운 요소를 포함할 수 있다.

## 목록 작성하기

 숫자 `1.` `2.` `3.` 이런 식으로 적으면 내림차순으로 작성된다. 주의할 점은 숫자 뒤에 띄어쓰기를 꼭 해줘야 한다.  
 기호 `*`, `+`, `-`를 사용해 점으로도 목록을 작성할 수 있다.
  - 과일
    - 사과
    - 포도  

## 코드



마크다운은 부등호를 씌운 pre와 code를 사용하거나 '''로 코드를 감싸서 동작하지 않게 할 수 있다.  
 간단한 코드로 하이퍼링크도 줄 수 있다.  
 [example] (http://example.com "title") -> [네이버](http://naver.com "네이버")
   
## 강조

 텍스트를 강조하고 싶을 때는 **양옆에** \* **또는** \_를 이용하고,
\~~를 이용하여 텍스트 위에 ~~취소선~~을 그어줄 수 있다.  
 기울이고 싶다면 \* *을* 이용하면 된다.

## 이미지

 이미지는 src와 똑같은 방식으로 구동할 수 있다.
 먼저 !를 쓰고 [대체텍스트] (path/image.jpg) <br/>![메이플](https://scontent-gmp1-1.xx.fbcdn.net/v/t1.6435-9/44237321_1868605799926152_7827503473766694912_n.png?_nc_cat=110&ccb=1-7&_nc_sid=a5f93a&_nc_ohc=Qv4x2E07NC8Q7kNvgE1ZR6o&_nc_oc=AdhVGSg7euCqMkE3hyVm1CN8p0lxd-uzPM7eKOc16anH-sy3ZFTV0dHqa36hYd6aIx4&_nc_zt=23&_nc_ht=scontent-gmp1-1.xx&_nc_gid=A_tA9MVX9Kx7DtYaMicWvRw&oh=00_AYDsPOlSgIX69C2wzY4-KjN7vug7N50SrjjGAFBq5c879w&oe=67D5CB85) <p>그럼 요런식으로 이미지가 표시된다.</p>

## 표

 마크다운으로 간단한 표도 만들 수 있다. <br/>
 우선 |제목|내용|설명| 이렇게 칸을 나눠 준 후<br/>
 |:---|---:|:---:| 요렇게 정렬이 될 곳에 :을 찍어주고 안에 내용을 적어주면 <br/>
 |왼쪽정렬|오른쪽정렬|중앙정렬|<br/>
 |제목|내용|설명|
 |:---|---:|:---:|
 |왼쪽정렬|오른쪽정렬|중앙정렬|<br/>
<p>위와 같이 출력 된다.</p>
