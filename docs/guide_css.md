# CSS 컨벤션 가이드
<br>

## 1. 기본 원칙
+ CSS3 표준 속성 우선
+ 불필요한 중복 스타일 제거
+ 공통 CSS 사용\
<br>

## 2. 들여쓰기 및 코드 구조
+ 들여쓰기 : *스페이스 2칸*
+ 코드 구조
```
.selector {
  property: value; /* 콜론 뒤 한 칸 띄움 */
}
```
<br>

## 3. 네이밍 규칙
+ 케밥 케이스(Kebab-case) 사용 : *띄어쓰기를 하이픈(-)로 표현*
+ 접두사 활용
<br>

## 4. 단위 및 수치
+ 기본 단위 : *폰트 및 여백은 px 단위를 기본으로 함*
  + base font unit : *16px*
  + base row unit : *27px*
  + base col unit : *24px* 
+ 색상 : *HEX 또는 RGBA를 사용*
+ 레이아웃 : *컨테이너 최대 너비는 1272px로 제한*
<br>

## 5. 주석 규칙
```
/* selector */
selector { ... }
```
