# 오늘배운 내용 - UIView
 - view Tagging - 아울렛 없이 태그로 뷰에 접근
 - 만약 서브뷰량 루트뷰랑 태그값이 같으면 뷰 순서가 빠른거 대로 작동함
 - opaque 옵션 - 뷰가 겹쳐있는데 알파값이 있어서 색상이 합쳐져야할 때 활용하면 성능향상에 도움이됨
   알파가 1일때 opaque 옵션 해제 권장, 알파가 1 이하일때 opaque 옵션 체크 권장
 - Clears Graphics Context - 이전 내용을 지우고 다시그리기 옵션?
   성능에 문제가 없다면 그냥 사용권장. 
