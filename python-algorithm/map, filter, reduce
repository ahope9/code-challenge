##  map()
각 요소에 공통된 작업 수행
반환값의 자료형을 변환해야 함
items = [1, 2, 3, 4, 5]
squared = list(map(lambda x: x**2, items))

squared = [x**2 for x in items]



## filter() 
조건을 걸러냄
number_list = range(-5, 5)
less_than_zero = list(filter(lambda x: x < 0, number_list))

less_than_zero = [x for x in number_list if x <0]

## reduce()
모든 요소에 접근하여 한차원 낮은 결과를 내기 위해 사용
sum_value = reduce((lambda x,y : x+y), [x for x in range(1,101)])
리스트[1 ~ 100] 모두 더하기
