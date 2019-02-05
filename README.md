### d4
---
https://github.com/heavysixer/d4

```
bower install d4
npm install d4
```

```js
var data = [
  { x : '2010', y : 5 },
  { x : '2011', y : 15 },
  { x : '2012', y : 20 }
];
var columnChart = d4.charts.column();

d3.select('someDomElement')
  .daum(data)
  .call(columnChart);

var data = [
  { x : '2010', y : 5},
  { x : '2011', y : 15 },
  { x : '2012', y : 20 }
];
var columnChart = d4.charts.column()
.mixout('yAxis')
.mixin({ 'name' : 'grid', 'feature' : d4.features.grid, 'index' : 0 })
d3.select('someDomElement')
  .datum(data)
  .call(columnChart);  
```

```html
```

