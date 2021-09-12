# 오늘배운 내용 - UIView
- UIView 는 화면에 필요한 내용을 그리는데 사용된다
- 모든 뷰는 고유한 영역의 Frame 을 가지고 있다.
- On-demand Drawing Model - 새로운 내용은 없고 단순히 크기나 위치가 바뀌는경우 캐시를 재사용
- 뷰는 프레임 내에서 생성되는 터치이벤트를 처리한다.
- 뷰의 계층구조 : SuperView -> SubView SuperView 는 항상하나다.
- SubView 는 배열구조로 저장된다. 배열의 가장마지막은 가장 마지막에 생성된 서브뷰
- 뷰의 좌표체계 : 왼쪽상단이 원점
- 윈도우와 뷰는 고유의 지역좌표를 가지고 있다.
- 뷰가 컨텐트를 표시할 때에는 뷰의 지역좌표를 사용한다
- 뷰의 위치와 크기를 지정할때에는 슈퍼뷰의 지역좌표를 사용한다.
- 
- Frame : CGRect : Superview 의 지역좌표에서 뷰의 크기나 위치를 저장
- Bound : CGRect : 현재 뷰의 지역좌표에서 뷰의 크기만 저장 - origin에는 0이 저장되있고 사이즈는 Frame 과 똑같다.
![image](https://user-images.githubusercontent.com/42457589/132979651-d6fd1001-01ee-417c-836c-1b2ce0c19407.png)

