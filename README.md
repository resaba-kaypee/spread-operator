# spread-operator

const sum = (function () {
  return function (...args){
  //const args = [x, y, z];
  return args.reduce((a,b) => a + b, 0)
  }
})();
sum(1, 2, 3);


const arr1 = [1 ,2 3, 4, 5];
let arr2;

(function () {
arr2 = [...arr1];
})();
console.log(arr2) // [1, 2, 3, 4, 5];
