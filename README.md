![task1](./task1)
>`task 1`
``` js
function anisa(a) {
    cnt=0
    for (let i = a; i>0; i=Math.floor(i/10)){
        if((i%10)%2==0){
            cnt++
        }
    }
    return cnt
}
console.log(anisa(123456));

```
![task2](./task2)
>`task 2`
``` js
function sevenBoom(number){
    let cnt=0;
    for(let i=number; i>0; i=Math.floor(i/10)){
        if(i%10==7){
            cnt++
        }
    }
    return cnt>0 ? 'Boom': 'There is no 7 in the arguments'
}
console.log(sevenBoom(9874));
```
![task3](./task3)
>`task 3`
``` js
function addDigit(number){
    let dig1=0;
    let dig2=0;
    let result=0;
    for(let i=number; i>10; i=Math.floor((dig1=i/10)+(dig2=i%10))){
        result=i;
    }    
    return result%10+Math.floor(result/10)
}
console.log(addDigit(929));
```


![task4](./task4)
>`task 4`
``` js
function get(a) {
    cnt=0   
    for (let i=0; i<=a; i++) {
    cnt+=i
    }
    return cnt*cnt
}
console.log(get(7));
```

![task5](./task5)
>`task 5`
``` js
function anisa(a) {
    cnt=""
    for (let i=a; i>0; i=Math.floor(i/10)){
    cnt+=i%10
    }
    return cnt==a
}
console.log(anisa(4444444444444));
```

![task6](./task6)
>`task 6`
``` js
function maxNum(number){
    let max=-Infinity
    for(let i=number; i>0; i=Math.floor(i/10)){
        if(i%10>max){
            max=i%10
        }   
    }
    return max
}
console.log(maxNum(7192));
```

![task7](./task7)
>`task 7`
``` js
function anisa(a) {
    let f0=0
    let f1=1
    let fnum=null
    for (let i = 2; i <=a; i++) {
        fnum=f1+f0
        f0=f1
        f1=fnum
    }
    return f1   
}
console.log(anisa(5));
```

![task8](./task8)
>`task 8`
``` js
function hasDoubleDigit(number){
    let dig=0;
    let result=0;
    for(let i=number; i>0; i=Math.floor(i/10)){
        if(i%10==dig){
            return true
        }
        dig=i%10
    }
    return false
}
console.log(hasDoubleDigit(123789));
```
![task9](./task9)
>`task 9`
``` js
function sumOfEvenDigits(number){
    let sum=0; 
    for(let i=number; i>0; i=Math.floor(i/10)){
        if((i%10)%2==0){
            sum+=i%10;
        }
    }
    return sum;
}
console.log(sumOfEvenDigits(2468642));
```

![task10](./task10)
>`task 10`
``` js
function anisa(a) {
    cnt=1
    for (let i=1; i<=a; i++) {
        cnt*=i
    }
  return cnt
}
console.log(anisa(3));
```

#### hi everyone there i know that in future maybe i'll create something that will make world better and someone will look to my past who am i was and i want to share with all that experiences that i had untill learning maybe i'll fail this exam (i mean this month too in js but i will do everything) 
#### future billionaire and yeah if you are laughing behind  your screen laugh but you will use my brauser in future promise <:)
