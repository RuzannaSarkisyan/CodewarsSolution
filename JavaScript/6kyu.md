### 6 kyu solutions

* [Arrays Similar] (https://www.codewars.com/kata/51e704f2d8dbace389000279)

``` javascript
function arraysSimilar(arr1, arr2) {
 return JSON.stringify(arr1.sort())===JSON.stringify(arr2.sort());
}
```
