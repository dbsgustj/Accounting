# Accounting
valueOfSupply는 공급가액이고 vatRate는 부가세입니다.
getVat은 공급가액 * 부가세를 반환합니다
getTotal은 공급가액 + (공급가액 * 부가세) 반환합니다.

# 첫 번째 코드
![화면 캡처 2023-03-15 153102](https://user-images.githubusercontent.com/126844596/225225936-a131ee3b-e0a6-40a4-bc1c-859c849218b1.png)

계산하고자 하는 공급가액의 수가 늘어날때마다 코드의 길이가 늘어납니다.
# 두 번째 코드
![화면 캡처 2023-03-15 153037](https://user-images.githubusercontent.com/126844596/225225949-ab3a7796-f1c4-4ce1-8d5a-4c7990449f56.png)

공급가액의 수가 늘어나더라도 valueOfSupply의 값을 바꿀 필요 없이 새로운 인스턴스를 생성하여 그 인스턴스의 valueOfSupply에 공급가액을 넣으면 되므로 코드의 길이가 줄어듭니다.
# 세 번째 코드
![화면 캡처 2023-03-15 153017](https://user-images.githubusercontent.com/126844596/225225956-8a0722e5-dc26-4df7-8d0b-ff56235f2a33.png)

이 코드는 class에 생성자 메소드를 만들어 인스턴스를 생성할 때 인수를 받아 class의 valueOfSupply에 바로 초기화 시킵니다.
this.valueOfSupply는 클래스의 필드에 있는 valueOfSupply를 뜻하고 valueOfSupply는 생성자 메소드에 있는 매개변수를 의미합니다.
# 출력 후
위 3개의 코드를 출력시키면 값은 동일하게 나옵니다.

![화면 캡처 2023-03-16 090327](https://user-images.githubusercontent.com/126844596/225472796-ad8f25f2-f500-4623-98f1-3ab3e3e12ebd.png)
