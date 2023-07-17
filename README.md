### 7. 하이퍼링크
[수업카페](https://cafe.daum.net/pcwk)


### 6. 가로선
화면 전체를 가로지르는 가로선
---
***
---
***


### 5. 목록
#### 무순서 목록
- 목록 이름
+ 목록 이름
* 목록 이름
  * 목록
    * 목록
      * 목록

#### 순서있는 목록
1. 목록 이름
2. 목록 이름
3. 목록 이름
1. 목록 이름
1. 목록 이름
1. 목록 이름
   1. 목록
      1. 목록
         1. 목록


### 4. 코드블럭
```python
def main():

    count = int(input("구매 상품 수를 입력하세요"))
    totalPrice = 0 #총금액

    for num in range(1, count+1):
        price = 1000
        print("2+1 상품입니다.")

        if(num % 3 == 0):
            pass
        else:
            totalPrice += price

    print('총 가격은 {}원입니다.'.format(totalPrice))

    # 구매 상품 수를 입력하세요3
    # 2+1 상품입니다.
    # 2+1 상품입니다.
    # 2+1 상품입니다.
    # 총 가격은 2000원입니다.

    # 구매 상품 수를 입력하세요6
    # 2+1 상품입니다.
    # 2+1 상품입니다.
    # 2+1 상품입니다.
    # 2+1 상품입니다.
    # 2+1 상품입니다.
    # 2+1 상품입니다.
    # 총 가격은 4000원입니다.

main()
```


### 3. 인용상자
> 여기에 인용할 내용을 넣으면 됨  
> 빈 줄이 없으면 자동으로 인용 상자에 포함됨  
이건 포함됨  

이건 포함 안 됨  


### 2. 헤더
#을 1개부터 6개까지 6단계로 사용할 수 있음
# Java
## Html
### CSS
#### Javascript
##### JSP
###### Spring


### 1. 문단 구분을 위한 개행
여름 공원을 걸어보아요.  
(개행 : space 2번)  
여름을 만끽하세요.
