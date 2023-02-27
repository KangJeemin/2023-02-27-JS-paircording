1. div children 3개 만들기
2. 함수들 만들어서 이름 붙이기
pull request test123

setBoxSize(obj, widNum, heiNum) : 박스 크기를 vh or vw 단위로 정하는 함수.
setFlex(obj, justiStr, alignStr) : flex로 설정하고 justiStr, alignStr 를 문자열 변수로 받는 함수. "center"을 입력하면 가운데 정렬이 된다.
setRelative(obj) = position : "relative"

1. makediv(a) = 반목문을 사용하여, root의 자식위치에 a만큼의 div태그를 만들어 줌 

2. setWidthAndHeight(a,width,height) = a는 root태그의 자식인덱스를 의미,
  ex) setWidthAndHeight(2,300,200) => root의 이번째 div태그의 width를 300px, height를 200px로 설정.

3. setBackgroundcolorAndFilter(a,backgroundcolor,filter) = a는 root태그의 자식인덱스를 의미,
  ex) setBackgroundcolorAndFilter(1,red,20) -> root의 일번째 div태그의 backgroundcolor를 red로 변경, filter를 20px로 설정,

4. setMargin = top,left,right,bottom 각자 px를 설정.
5. setopacity = opacity 를 설정.
6. etBorderRadius
7. setOverflowx
