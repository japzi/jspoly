# JSPoly

JSPoly is a Javascript translation of the Boost Polygon Library originally written in C++. 

License : Boost Software License - Version 1.0

![screen shot 2017-06-07 at 10 34 03 pm](https://user-images.githubusercontent.com/5238776/26909838-7f1d6caa-4bd1-11e7-80b9-c278c0f9e7ab.png)


## Sample code
```
boundary = [{x: 1, y: 1}, {x: 2, y: 2}, {x: 3, y: 2}, {x: 4, y: 1}];
segments = JSPoly.construct_medial_axis(boundary, []);
```
## Output
for above example, resultant `segments` contains following
```
[{"point0":{"x":3,"y":2,"radius":0},"point1":{"x":2.7928932188134525,"y":1.5,"radius":0.4999999999999998}},{"point0":{"x":1,"y":1,"radius":0},"point1":{"x":2.2071067811865475,"y":1.5,"radius":0.49999999999999994}},{"point0":{"x":2,"y":2,"radius":0},"point1":{"x":2.2071067811865475,"y":1.5,"radius":0.5}},{"point0":{"x":2.2071067811865475,"y":1.5,"radius":0.5},"point1":{"x":2.7928932188134525,"y":1.5,"radius":0.5}},{"point0":{"x":2.7928932188134525,"y":1.5,"radius":0.4999999999999998},"point1":{"x":4,"y":1,"radius":0}}]
```
![screen shot 2017-05-10 at 3 15 26 pm](https://cloud.githubusercontent.com/assets/5238776/25916687/94591ac8-3593-11e7-8326-d82b6d4ce8b2.png)

