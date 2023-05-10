# 模糊查询

## 应用场景
电影院中的搜索功能，输入关键字，然后给出相关联的结果
可以使用es5中的过滤filter函数来进行过滤。
JavaScript中，filter()函数是一个数组方法，它可以用来筛选数组中符合条件的元素，并返回一个新的数组，原数组不会被修改

filter 的实例
var numbers = [1, 2, 3, 4, 5, 6];
var evenNumbers = numbers.filter(function(number) {
  return number % 2 == 0;
});
console.log(evenNumbers); // [2, 4, 6]

### 方法1
使用filter进行过滤。创建一个新数据和一个老数据。变动新数据，让老数据不变
如果想使用includes函数的话，得确保数组里面的是字符串
### 方法2
函数表达式方案
在遍历数组那里，