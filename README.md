>`task 1`
``` js
function count(number){
    let cnt=0
    for(let i=number; i>0; i=Math.floor(i/10)){
        if((i%10)%2==0){
            cnt++
        }
    }
    return cnt
}
console.log(count(123456));
```
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



>`task 4`
``` js
function sumCubes(number){
    let result=0;
    for(let i=1; i<=number; i++){
        result+=i ** 3
    }
    return result
}
console.log(sumCubes(7));
```


>`task 5`
``` js
function isSymetrical(number){
    let reverse=''
    for(let i=number; i>0; i=Math.floor(i/10)){
        reverse+=i%10
    }
    return number==reverse
}
console.log(isSymetrical(444444));
```

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


>`task 7`
``` js
function fib(number){
    let fib0=0;
    let fib1=1;
    let fibN=0
    for(let i=1; i<number; i++){
        fibN=fib0+fib1;
        fib0=fib1;
        fib1=fibN;
    }
    return fibN;
}
console.log(fib(3));
```


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


>`task 10`
``` js
function factorial(number){
    let result=1;
    for(let i=1; i<=number; i++){
        result*=i
    }
    return result
}
console.log(factorial(5));
```