## Define, Access, and Manipulate Objects

Most common way to create an object:
(const object = {});

Access and set properties on objects using string keys:
(object["key"]);

To get a list of all keys in an object:
 as well as how to get a list of all the keys in an object:
(Object.keys(object)).

Iterating over the properties within an object requires the use of a for...in loop:

```javascript
var planetSpaceShips = {
  mercury: 0,
  venus: 0,
  earth: 13,
  mars: 2,
  jupiter: 42,
  saturn: 3,
  uranus: 70,
  neptune: 1.5
};

for (var planet in planetSpaceShips) {
  var numberOfSpaceShips = planetMoons[planet];
  console.log("Planet: " + planet + ", # of SpaceShips: "+ numberOfSpaceShips);
}
```