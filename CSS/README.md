# CSS

- 생활코딩 홈페이지 HTML 페이지 : <https://opentutorials.org/course/2418>

- 생활코딩 유투브 HTML 재생목록 : <https://www.youtube.com/playlist?list=PLuHgQVnccGMDaVaBmkX0qfB45R_bYrV62>

<br>

## 강의 미리보기

1. CSS 소개
> 초기에 정보만을 담고 있던 html에 점차 정보와 디자인이 함께 저장되기 시작<br>
  새로운 문법의 css의 등장으로 인해 html은 "정보"에 더욱 전념할 수 있게 되었고, css로 더욱 효율적으로 "디자인"이 가능해짐<br>

2. 실습환경

3. HTML과 CSS가 만나는 법
> HTML에 CSS를 적용시키기 위한 두 가지 방식<br>
  inline 방식으로 태그 안에 style 속성을 추가해 css를 작성하는 방법과 \<style\> 태그 사이에 css를 작성하는 방법이 존재

4. 선택자와 선언
> 선택자(Selector), 선언(Declaration), 속성(Property), 속성값(Value), 구분자(Value-Property Separator, Declaration Separator)

5. 선택자의 종류 : 아이디 선택자
> id 선택자를 통해 선택하기 위해서는 #id 를 이용

6. 선택자의 종류 : 클래스 선택자
> class 선택자를 통해 선택하기 위해서는 .class 를 이용

7. 부모 자식 선택자
> 선택자를 이용해 자손 관계 선택, 자식 관계 선택, 복수 선택

8. 선택자 공부팁

9. 가상클래스 선택자
> element의 상태에 따라 선택을 하는 선택자. 방문하지 않은 링크, 방문한 링크, 마우스를 올린 상태, 클릭한 상태, focusing된 상태

10. 다양한 선택자들 1

11. 다양한 선택자들 2

12. 다양한 선택자들 3

13. 다양한 선택자들 4

14. 속성을 공부하는 방법
> [속성에 대한 통계](https://developer.microsoft.com/en-us/microsoft-edge/platform/usage/)

15. 타이포그래피 : font-size
> 고정된 폰트 사이즈를 지정할 때 사용하는 px, 사용자가 페이지의 폰트 사이즈를 가변적으로 변경할 수 있도록 할 때 사용하는 em, rem

16. 타이포그래피 : color
> 폰트 색상을 표현하는 세가지 방법 color name, hex, rgb<br>
  http://www.w3schools.com/css/css_colors.asp

17. 타이포그래피 : text-align
> 왼쪽 정렬, 오른쪽 정렬, 가운데 정렬, 균등 정렬

18. 타이포그래피 : font
> font-family(글꼴), font-weight(폰트 두께), line-height(행간), 축약해서 나타내는 font

19. 타이포그래프 : 웹폰트
> 서버에서 사용자의 웹브라우저가 다운로드해서 사용할 수 있도록 제공하는 기법<br>
  [google fonts](https://fonts.google.com/?authuser=1)

20. 상속
> 부모에서 설정된 css 속성값이 자식 요소에 적용. 일부 css 속성만 상속됨

21. stylish

22. 캐스케이딩 소개

23. 캐스케이딩 실습
> 중첩되어 적용된 css의 우선순위 : style 속성 > id 선택자 > class 선택자 > 태그 선택자

24. bracket

25. inline block
> 자신의 크기만을 사용하는 inline element와 한 줄 전체를 사용하는 block element

26. box model
> border, padding, margin, width, height / inline element는 width, height 적용 불가능

27. box-sizing
> 기본적으로 box의 크기는 content-box로 결정, border-box로 했을 때 border를 기준으로 크기를 결정

28. 마진 겹침 1
> 인접한 두 오브젝트 사이에서 마진이 큰 값만 적용

29. 마진 겹침 2
> 부모 태그가 시각적으로 아무런 효과가 없는 상태가 되었을 때 부모 태그와 자식 태그의 마진값이 겹치게 됨

30. 마진 겹침 3
> 시각적으로 아무런 효과가 없는 태그의 마진값은 더 큰 값으로 결정(margin top과 bottom, left와 right)

31. 포지션 1 : ralative VS static
> 기본적으로 position은 static / relative를 사용해 원래 있어야 할 위치를 기준으로 자신의 위치 조절

32. 포지션 2 : absolute
> position의 속성값이 absoulute가 되면 position이 static이 아닌 부모를 기준으로 offset으로 위치 결정 / 없다면 html 기준, 즉 화면을 기준으로 결정

33. 포지션 3 : fixed
> position의 속성값이 fixed가 되면 화면에 고정된 위치를 부여해 스크롤과 무관하게 표현

34. flex 1 : intro

35. flex 2 : basic
> display: flex 로 설정 / flex-direction을 통해 flex 방향 설정

36. flex 3 : basis & grow & shrink
> flex-basis 로 기본 크기 설정 / flex-grow 로 나눠가질 영역 비율 설정 / flex-shrink 로 컨테이너의 공간이 부족해질 때 줄어들 영역 비율 설정 

37. flex 4 : holy grail layout

38. flex 5 : 기타 속성들

39. Multi column
> column-count 로 컬럼 최대 수 결정 / column-width 로 최소 컬럼의 폭 결정 / column-rule 로 컬럼 구분에 대한 설정 / column-gap 으로 컬럼 여백 설정 / column-span 으로 컬럼 구분에 구애받지 않도록 설정

40. mediaquery 1 - 기본
> 화면의 종류와 크기에 따라 디자인을 달리 줄 수 있는 기능

41. mediaquery 2 - 응용

42. float 1
> 주로 이미지를 삽입할 때 자연스럽게 삽입 또는 레이아웃을 잡을 때 사용 / float을 무시하기 위해 clear 속성

43. float 2 : holy grail layout

44. 배경
> background-color 로 배경 색상 결정 / background-image 로 배경 이미지 결정 / background-repeat 으로 배경 이미지 반복 설정 / background-attachment 로 화면 이동에 따른 배경 이미지 표현 결정 / background-size 로 배경 이미지 크기 결정 / background-position 으로 배경 이미지 위치 결정

45. filter
> 포토샵과 같은 디자인툴에서 사용하는 필터 효과를 코드를 통해 구현

46. blend 1 : 소개
> 하나의 이미지에 효과를 주는 filter와 달리 두 가지 이미지를 혼합해 효과를 주는 기능

47. blend 2 : background-blend-mode

48. blend 3 : mix-blend-mode

49. transform 1 : 소개
> 요소의 표시 위치 또는 크기 등을 변경시키는 태그

50. transform 2

51. transition 1
> 요소가 변경될 때 전환에 대하여 자세히 결정하는 태그

52. transition 2

53. link & import
> 똑같은 css를 적용해야 하는 페이지가 많아졌을 때 모두 수정하는 것이 아닌 외부의 파일로 빼는 방법

54. 코드 경량화 (minify)
> css의 크기가 커졌을 때 컨텐츠의 생산자 소비자 모두 손해이기 때문에 코드의 크기를 줄이는 minify 도구 존재

55. CSS 뛰어넘기, preprocesser 1 - 소개

56. CSS 뛰어넘기, preprocesser 2 - 에디터의 확장기능

57. CSS 뛰어넘기, preprocesser 3- 명령어로 컴파일하기

58. Fontello 1 - 소개

59. Fontello 2 - 사용법

60. Fontello 3 - 원리

61. Fontello 4 - 폰트만들기
