#position을 알아보자
##공통사항
1(position:relative,absolute,fixed)에서만 left,right,top,bottom이 적용된다.
2.모든 레이어는 떠오르는 순간 위치값(left,...)을 지정하지 않으면 제자리에 레이어가 된다.

##position:absolute
1.떠오르는 순간 문서의 기준점을 찾는다.**기준점은 그때그때 달라요**
-기준점은 부모중 가장 가까운 레이어가 된 (position;absolute,fixed)부모를 기분으로 한다.

##position:relative
1.레이어가 되지만, 크기나 위치가 변하지 않는다.그래서 기준점이 되기 위해 주로 적용한다.