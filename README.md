# js-problem-Solving
[date : 19-nov-21] <br>
let's start problem solving ---
 ### 1. check whatever the number is prime or not ?

```
function prime(n){
    for(var i=2; i<n;i++)
{
    if(n%i==0){
        return "this is not a prime number !";
       
    }
    return "this is prime n"
}
}
console.log(prime(43))
```
2.Calculate Factorial of a number using for loop(iterative)
```
function asdf(x) {
    let count = 1;
    for (let i = 1; i <= x; i++) {
        count*=i;
    }
    return count;
}
const factorial = asdf(10);
console.log(factorial); 
```
3.Calculate Factorial of a number using a while loop(iterative)
```
function asdf(x) {
    let count = 1;
    let i=1;
   while (i <= x) {
        count*=i;
        i++;
    }
    return count;
}
const factorial = asdf(10);
console.log(factorial); 
```
4.Calculate Factorial in a Recursive function
```
function asdf(x) {
  if(x==0)
  {
      return 1;
  }
  else{
      return x*asdf(x-1);
  }
}
const factorial = asdf(10);
console.log(factorial); 
```
5.Create a Fibonacci Series using a for loop
```function fibo(n) {
    var fibo = [0, 1];
    // fibo[n]=fibo[n-1]+fibo[n-2]
    for (var i = 2; i <= n; i++) {
        fibo[i] = fibo[i - 1] + fibo[i - 2]
        console.log(fibo[i], fibo[i - 1], fibo[i - 2]);
    }
    return fibo;
}
console.log(fibo(10))
```
6.Fibonacci Element in a Recursive Way
```
function fibo(n) {
    if(n === 0) return 0;
    if(n === 1) return 1;
    else{
        return fibo(n - 1)+fibo(n - 2)
    }
}
console.log(fibo(10))
```
7.Create Fibonacci series in a recursive way
```function fibo(n){
    if(n === 0) return [0];
    if(n === 1) return [0,1];
    else{
        // calculate array nth element 
        var fiboo= fibo(n - 1);
        var nextFiboo=fiboo[n-1]+fiboo[n-2];
        fiboo.push(nextFiboo);
        return fiboo;
    }
}
console.log(fibo(10))
```
8.
