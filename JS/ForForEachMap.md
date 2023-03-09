# for, forEach, map 차이
<br>
1. for()

초기값부터 시작해서 증가 혹은 감소하면서 순회</br>
중간에 break문 만나면 순회 중지</br>

2.forEach()

callback함수 </br>
return값이 없음</br>
순회를 멈출 수 없음

    let array =[1,2];
    array.forEach(item=>{
        console.log(item);
    });
    // [콘솔 출력 결과]
    // 1
    // 2

</br>
3. map()

callback함수</br>
return값이 있으며 새로운 배열 생성</br>
순회를 멈출 수 없음</br>    

    let array =[1,2];
    array.forEach(item=>{
        console.log(item);
    });
    // [콘솔 출력 결과]
    // 1
    // 2
    //[undefined, undefined]