# spread-operator

const sum = (function () {
  return function (...args){
  //const args = [x, y, z];
  return args.reduce((a,b) => a + b, 0)
  }
})();
sum(1, 2, 3);
