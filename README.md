
Well Well Well how the turntables.
=======

## Bubble Sort in Javascript
```javascript
function bubbleSort(arr){
   
  var i, j;
  var len = arr.length;
   
  var isSwapped = false;
   
  for(i =0; i < len; i++){
     
    isSwapped = false;
     
    for(j = 0; j < len; j++){
        if(arr[j] > arr[j + 1]){
          var temp = arr[j]
          arr[j] = arr[j+1];
          arr[j+1] = temp;
          isSwapped = true;
        }
    }
     
    // IF no two elements were swapped by inner loop, then break
     
    if(!isSwapped){
      break;
    }
  }
   
  // Print the array
  console.log(arr)
}
 
 
var arr = [243, 45, 23, 356, 3, 5346, 35, 5];
 
// calling the bubbleSort Function
bubbleSort(arr)


```




## Rust program for Fibonacci Sequence

``` rust
fn fibonacci(n: u32) -> u32 {
    match n {
        0 => 1,
        1 => 1,
        _ => fibonacci(n - 1) + fibonacci(n - 2),
    }
}

fn main() {
    println!("Fibonacci generator");
    println!("{}", fibonacci(1));
    println!("{}", fibonacci(3));
    println!("{}", fibonacci(5));
}

```

## Square root of number in GO

``` go
package main
 
import (
    "fmt"
    "math"
)
 
func main() {
    var x float64 = 9
    result := math.Sqrt(x)
    fmt.Println("Square root of 9 is :", result)
}

```

## Merge two dictionary in python

``` python
dict_1 = {1: 'a', 2: 'b'}
dict_2 = {2: 'c', 4: 'd'}

dict_3 = dict_2.copy()
dict_3.update(dict_1)

print(dict_3)
```
