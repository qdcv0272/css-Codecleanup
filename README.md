# ❗️css-Codecleanup❗️

### CSS 초기화
___
* CSS를 작성할때 초기화를 시킨다.

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/reset-css@5.0.1/reset.min.css">
```

### html에서 꿀팁!!
* hero 라는 클래스를 가지고 있는 div 그 내부에 있는 image 가 32개 다 적기 불편하므로 32개 자동완성
___
```
.hero*32>.image
```

### CSS에서 사용했던 기초 속성들!
___
* display: 요소의 화면 출력 특성
* ```display: flex;``` : 각각 의 요소들이 수평 정렬
* ```flex-wrap: wrap;``` : 줄 바꿈
* ```justify-content: center;``` : 가운데 수평 정렬 
* border: 선-두께, 선-종류, 선-색상
* ```border: 4px solid black;```: 두께는 4px 실선 그리고 색상은 검은색 
